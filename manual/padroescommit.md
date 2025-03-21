## Tipos de Commits e descrições
O commit possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

- `raw` - Commits do tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parâmetros.

- `cleanup` - Commits do tipo cleanup são utilizados para remover código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando aprimorar sua legibilidade e manutenibilidade.

- `remove` - Commits do tipo remove indicam a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto e mantendo-o mais organizado.

## Padrões de emojis
--------------------------------------------------------------------------------------------

| Tipo do commit                      | Emoji                    | Palavra-chave |
|-------------------------------------|--------------------------|---------------|
| Acessibilidade                      | ♿ `:wheelchair:`         |               |
| Adicionando um teste                | ✅ `:white_check_mark:`  | `test`        |
| Atualizando a versão de um submódulo| ⬆️ `:arrow_up:`          |               |
| Retrocedendo a versão de um submódulo| ⬇️ `:arrow_down:`        |               |
| Alterações de revisão de código     | 👌 `:ok_hand:`            | `style`       |
| Animações e transições              | 💫 `:dizzy:`              |               |
| Bugfix                              | 🐛 `:bug:`                | `fix`         |
| Comentários                         | 💡 `:bulb:`               | `docs`        |
| Commit inicial                      | 🎉 `:tada:`               | `init`        |
| Configuração                        | 🔧 `:wrench:`             | `chore`       |
| Deploy                              | 🚀 `:rocket:`             |               |
| Documentação                        | 📚 `:books:`              | `docs`        |
| Em progresso                        | 🚧 `:construction:`       |               |
| Estilização de interface            | 💄 `:lipstick:`           | `feat`        |
| Infraestrutura                      | 🧱 `:bricks:`             | `ci`          |
| Lista de ideias (tasks)             | 🔜 `:soon:`               |               |
| Mover/Renomear                      | 🚚 `:truck:`              | `chore`       |
| Novo recurso                        | ✨ `:sparkles:`           | `feat`        |
| Package.json em JS                  | 📦 `:package:`            | `build`       |
| Performance                         | ⚡ `:zap:`                | `perf`        |
| Refatoração                         | ♻️ `:recycle:`            | `refactor`    |
| Limpeza de Código                   | 🧹 `:broom:`              | `cleanup`     |
| Removendo um arquivo                | 🗑️ `:wastebasket:`        | `remove`      |
| Adicionando uma dependência         | ➕ `:heavy_plus_sign:`    | `build`       |
| Removendo uma dependência           | ➖ `:heavy_minus_sign:`   | `build`       |
| Responsividade                      | 📱 `:iphone:`              |               |
| Revertendo mudanças                 | 💥 `:boom:`               | `fix`         |
| Segurança                           | 🔒️ `:lock:`               |               |
| SEO                                 | 🔍️ `:mag:`                |               |
| Tag de versão                       | 🔖 `:bookmark:`           |               |
| Teste de aprovação                  | ✔️ `:heavy_check_mark:`   | `test`        |
| Testes                              | 🧪 `:test_tube:`          | `test`        |
| Texto                               | 📝 `:pencil:`             |               |
| Tipagem                             | 🏷️ `:label:`              |               |
| Tratamento de erros                 | 🥅 `:goal_net:`           |               |
| Dados                               | 🗃️ `:card_file_box:`      | `raw`         |

