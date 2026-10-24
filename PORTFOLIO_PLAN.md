# Plano de portfólio — 23/10/2026

## Alvo e evidência disponível

Foco: vagas de desenvolvimento Java/Spring Boot, C#/.NET, React/Angular e Python/SQL. APIs, bancos de dados, Git, testes e automação são os eixos do portfólio.

Foram inspecionados 45 repositórios. O foco são três fluxos executáveis, com mudanças que possam ser explicadas em entrevista.

| Projeto | Por que manter | Entrega desta rodada |
| --- | --- | --- |
| cadastro-usuario | API Spring já implementada; aderência direta ao backend Java | Validação, 400/404/409, proteção contra sobrescrita por ID, oito testes de regras e CI |
| Projeto-React | Fluxo de tarefas já funcional; demonstra front-end | Busca e filtro, formulário por teclado, nomes acessíveis, testes e CI; atualização de dependências |
| DataScope | Dados reais, SQL e dashboard já existente | Validação compartilhada do CSV, ranking com quantidade variável de países, nove testes e CI |

## Próximos incrementos, em ordem

1. Conectar o gerenciador React a uma API ASP.NET Core com SQL: CRUD persistente, validação, tratamento de falhas e testes de integração. Isso cobre a lacuna real de C#/.NET sem criar mais um repositório vazio.
2. No Spring, adicionar testes HTTP e PostgreSQL com migrações. Demonstrar criação, conflito e exclusão.
3. No DataScope, validar a coleta da API com respostas simuladas e documentar atualização do snapshot.
4. Angular permanece uma lacuna: só declarar implementação quando houver uma tela funcional integrada e testes.

Nenhum dos três destaques atuais comprova ASP.NET Core ou Angular. Blazor não deve ser apresentado como Angular. Não adicionar selos de tecnologias sem implementação.

## Organização

Três pins no perfil e README com escopo de desenvolvimento. Projetos secundários com implementação ficam disponíveis no histórico; vazios e exercícios avulsos são arquivados, de forma reversível. Nenhum repositório é excluído nem o histórico reescrito.
