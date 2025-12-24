# INSTALACAO ENSIDE SISTEMA

## Anderson Enside | Grupo Lider Madeiras

---

## DOWNLOAD RAPIDO

### Opcao 1: Baixar ZIP
1. Acesse: https://github.com/ensideanderson-nova/claude-code
2. Clique no botao verde "Code"
3. Clique em "Download ZIP"
4. Extraia a pasta `ENSIDE_SISTEMA`

### Opcao 2: Git Clone
```bash
git clone https://github.com/ensideanderson-nova/claude-code.git
cd claude-code/ENSIDE_SISTEMA
```

---

## INSTALACAO NO MAC

### Passo 1: Criar Pasta
Abra o Terminal e execute:
```bash
mkdir -p ~/Enside_Master/ENSIDE_SISTEMA
```

### Passo 2: Mover Arquivos
Mova os arquivos baixados para a pasta:
```bash
mv ~/Downloads/ENSIDE_SISTEMA/* ~/Enside_Master/ENSIDE_SISTEMA/
```

### Passo 3: Abrir Sistema
```bash
open ~/Enside_Master/ENSIDE_SISTEMA/index.html
```

Ou clique 2x no arquivo `index.html` no Finder.

---

## ARQUIVOS DO SISTEMA

| Arquivo | Descricao |
|---------|-----------|
| `index.html` | Pagina inicial com links |
| `ENSIDE_DATABASE_v5.html` | **SISTEMA PRINCIPAL** - Use este! |
| `ENSIDE_IMPORTADOR_ANDERSON_v4.html` | Importador para seus CSVs |
| `ENSIDE_IMPORTADOR_UNIVERSAL_v3.html` | Importador generico |
| `README_INSTALACAO.md` | Documentacao |

---

## PRIMEIRO USO

### 1. Abrir o Sistema
- Abra `ENSIDE_DATABASE_v5.html` no Chrome ou Safari
- Ou use `index.html` e clique em "ENSIDE DATABASE"

### 2. Importar Dados
- Clique na aba "Importar"
- Arraste seu arquivo CSV para a area de upload
- Clique em "INICIAR TRIAGEM AUTOMATICA"

### 3. Verificar Triagem
- Clique nas abas: Clientes, Fornecedores, Motoristas
- O sistema classifica automaticamente!

---

## FORMATO CSV SUPORTADO

O sistema aceita seus arquivos com:
- Separador: `;` (ponto-e-virgula)
- Colunas: des_nome, num_celular, tpo_parceiro, etc.

Exemplo:
```
des_nome;num_celular;tpo_parceiro
Joao Silva;11999998888;C
Madeireira ABC;11888887777;F
```

---

## ORDEM DE TRIAGEM

1. **MOTORISTAS/FRETES** - Detecta: frete, motorista, transportadora, caminhao
2. **FORNECEDORES** - Detecta: madeireira, serraria, marcenaria, fabrica
3. **CLIENTES** - Todo o resto

---

## FUNCIONALIDADES PRINCIPAIS

### Importar
- Upload de CSV/Excel
- Triagem automatica inteligente
- Deteccao de duplicados

### Cadastrar
- Adicionar contatos manualmente
- Selecionar tipo e setor

### Listas de Transmissao
- Criar listas para WhatsApp (max 256 por lista)
- Filtrar por tipo, setor, estado, cidade
- Exportar para CSV

### Agente IA
- Chat inteligente
- Comandos: resumo, buscar, analise, dica
- Sistema de XP e niveis

### Tarefas
- Gerenciar tarefas com prioridades
- Marcar como concluido

### Exportar
- CSV por categoria
- JSON completo (backup)
- Lista WhatsApp

---

## COMANDOS DO AGENTE IA

Digite no chat do Agente:
- `resumo` - Ver status geral
- `quantos clientes?` - Contagem
- `buscar Joao` - Procurar contato
- `clientes de SP` - Filtrar por estado
- `analise` - Ver insights
- `dica` - Receber sugestao
- `ajuda` - Ver comandos

---

## BACKUP DOS DADOS

Os dados sao salvos no navegador (localStorage).

### Fazer Backup
1. Aba "Exportar"
2. Clique em "Tudo JSON"
3. Salve o arquivo `enside_backup.json`

### Restaurar Backup
1. Aba "Importar"
2. Selecione o arquivo JSON
3. Dados restaurados!

---

## SUPORTE

- Criado por: Anderson Enside
- Empresa: Grupo Lider Madeiras
- Versao: 5.0
- Data: 2024

---

## REQUISITOS

- Navegador: Chrome, Safari, Firefox ou Edge
- Sistema: macOS, Windows ou Linux
- Conexao: Nao necessaria (funciona offline)

---

## DICAS

1. Use Chrome para melhor desempenho
2. Faca backup regularmente (Exportar > JSON)
3. O sistema salva automaticamente no navegador
4. Limpe o cache do navegador apenas se necessario (perdera dados!)

---

**Pronto! Seu ENSIDE Sistema esta instalado.**
