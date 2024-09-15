# Padrão de Commit para Desenvolvedores Iniciantes

## Objetivo
Este documento estabelece um padrão para a criação de mensagens de commit no GitHub, ajudando a manter a organização e a rastreabilidade das mudanças em um projeto.

## Estrutura da Mensagem de Commit

Cada commit deve seguir o seguinte formato:


- **Tipo**: Define o tipo de alteração (veja a lista de tipos abaixo).
- **Contexto**: Descreve de forma breve e clara o que foi alterado.
- **Descrição adicional** (opcional): Adicione informações extras, se necessário, após uma linha em branco.

## Tipos de Commit

| Tipo           | Descrição                                                                 |
| -------------- | ------------------------------------------------------------------------- |
| `feat`         | Adiciona uma nova funcionalidade ou recurso.                              |
| `fix`          | Corrige um bug ou problema.                                               |
| `refactor`     | Reorganiza ou melhora o código sem alterar o comportamento existente.     |
| `docs`         | Atualizações na documentação (README, Wiki, etc.).                        |
| `test`         | Adiciona ou altera testes (unitários, integração, etc.).                  |
| `style`        | Alterações de formatação ou estilo (espaçamento, indentação, etc.).       |
| `chore`        | Tarefas rotineiras que não alteram o código de produção (configurações).  |
| `perf`         | Melhora o desempenho de uma parte do código.                             |
| `ci`           | Alterações em arquivos de CI (integração contínua) ou scripts de build.   |
| `revert`       | Reverte um commit anterior.                                               |

## Exemplos de Mensagens de Commit

- `feat: adicionar endpoint de criação de usuários`
- `fix: corrigir erro na função de login`
- `refactor: reorganizar funções de autenticação`
- `docs: atualizar seção de instalação no README`
- `test: adicionar testes para o componente de autenticação`
- `style: ajustar indentação no arquivo app.js`
- `chore: atualizar dependências no package.json`
- `perf: otimizar tempo de resposta da API`
- `ci: corrigir falha no pipeline de deploy`

## Boas Práticas

- **Escreva no imperativo**: As mensagens devem ser curtas e objetivas, como "adicionar", "corrigir", "remover".
- **Agrupe commits semelhantes**: Tente agrupar alterações relacionadas em um único 
