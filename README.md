# CDV · Base de Regras de Negócio

Ferramenta web colaborativa para documentar, visualizar e gerenciar regras de negócio. Interface profissional com persistência automática no GitHub — sem servidor, sem banco de dados.

🔗 **Acesso:** https://gctobias.github.io/cdv-regras/

---

## Como funciona

O app é um arquivo HTML hospedado no GitHub Pages. As regras ficam salvas em  neste repositório. Toda vez que alguém abre o link, o app busca a versão mais atualizada diretamente do GitHub.

### Visualizar
Qualquer pessoa com o link visualiza todas as regras — sem login, sem instalação.

### Editar (criar, modificar, excluir)
Quem tiver um **Personal Access Token** do GitHub com permissão  pode editar.

1. Abra o app pelo link acima
2. Clique em **🔑 Configurar edição** no canto superior direito
3. Cole o token e salve — ele fica guardado no seu navegador
4. A partir daí crie, edite e exclua regras normalmente

> O token fica salvo apenas no navegador de quem configurou. Nunca é enviado para nenhum servidor além do próprio GitHub.

---

## Estrutura do repositório

\
---

## Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 📋 Visão geral | Tabela com todas as regras, ordenável por coluna |
| 🔍 Busca global | Pesquisa em títulos, resumos, definições e critérios |
| 🗂 Filtro por categoria | Filtre por Onboarding, Alocação, Atendimento, Fee ou Compliance |
| 📑 Abas paralelas | Abra múltiplas regras simultaneamente em abas |
| ✏️ Edição completa | Criar, editar e excluir regras com salvamento automático no GitHub |
| 🔗 Referências entre regras | Cite outras regras na definição com  — vira link clicável com tooltip |
| 📄 Importar YAML dbt | Visualize documentação de modelos dbt diretamente no app |

---

## Como atualizar o app

Para modificar a interface (adicionar campos, botões, etc.):

**Via terminal com Claude Code**
Peça a mudança — o  é editado localmente e enviado ao repositório. O GitHub Pages atualiza em ~1 minuto.

**Direto no GitHub**
Acesse  → clique em  → clique no lápis ✏️ → edite e faça commit.
