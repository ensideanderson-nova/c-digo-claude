# ENSIDE SISTEMA - Anderson Enside | Grupo Lider Madeiras

---

## Arquivos Disponiveis

| Arquivo | Versao | Descricao |
|---------|--------|-----------|
| `ENSIDE_DATABASE_v5.html` | v5.0 | **PRINCIPAL** - Sistema completo com Agente IA |
| `ENSIDE_IMPORTADOR_ANDERSON_v4.html` | v4.0 | Importador otimizado para CSVs do Anderson |
| `ENSIDE_IMPORTADOR_UNIVERSAL_v3.html` | v3.0 | Importador generico |
| `index.html` | - | Pagina inicial com links |

---

## Como Usar

### Passo 1: Baixar
Baixe o arquivo `ENSIDE_DATABASE_v5.html` para seu Mac.

### Passo 2: Abrir
Clique 2x no arquivo ou arraste para o Chrome/Safari.

### Passo 3: Importar
1. Clique na area de upload
2. Selecione seu arquivo CSV
3. Clique em "INICIAR TRIAGEM AUTOMATICA"

---

## ENSIDE DATABASE v5 - Funcionalidades

### Abas Disponiveis
- **Importar** - Upload de arquivos CSV/Excel
- **Cadastrar** - Cadastro manual de contatos
- **Clientes** - Lista de clientes com busca
- **Fornecedores** - Lista de fornecedores
- **Motoristas** - Lista de motoristas/fretes
- **Listas** - Listas de transmissao WhatsApp (max 256)
- **Analise** - Dashboard com estatisticas
- **Agente IA** - Chat inteligente com comandos
- **Tarefas** - Gerenciador de tarefas com prioridades
- **Aprendizado** - Base de conhecimento do agente
- **WhatsApp** - Monitoramento de conversas
- **Exportar** - Exportacao CSV/JSON

### Comandos do Agente IA
- `resumo` - Status geral do sistema
- `quantos clientes?` - Contagem por categoria
- `buscar [nome]` - Procurar contato
- `clientes de SP` - Filtrar por estado
- `analise` - Insights e metricas
- `dica` - Sugestoes do agente
- `ajuda` - Lista de comandos

---

## Ordem de Triagem

1. **FRETES/MOTORISTAS** (primeiro)
   - Palavras: frete, motorista, transportadora, caminhao, carreta

2. **FORNECEDORES** (segundo)
   - Palavras: madeireira, serraria, marcenaria, fabrica, industria

3. **CLIENTES** (o que sobrar)

---

## Formato CSV Suportado

O sistema detecta automaticamente:
- Separador `;` (padrao Anderson) ou `,`
- Colunas: des_nome, num_celular, tpo_parceiro, etc.
- Encoding UTF-8

---

## Persistencia

Dados salvos no navegador (localStorage).
Chave: `enside_db_v5`

---

## Localizacao Recomendada no Mac

```
~/Enside_Master/
└── ENSIDE_SISTEMA/
    ├── ENSIDE_DATABASE_v5.html      <- USAR ESTE
    ├── ENSIDE_IMPORTADOR_ANDERSON_v4.html
    ├── ENSIDE_IMPORTADOR_UNIVERSAL_v3.html
    └── README_INSTALACAO.md
```

---

**Versao:** 5.0
**Data:** 2024
**Criado por:** Anderson Enside - Grupo Lider Madeiras
