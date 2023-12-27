# node-postgres [![CI](https://github.com/cl4pper/node-postgres/actions/workflows/integration.yaml/badge.svg)](https://github.com/cl4pper/node-postgres/actions/workflows/integration.yaml)

A Node based boilerplate to help you starting your API development :smiley:

Integrated with **PostgreSQL**.

Code linting (by _prettier_) and testing (by _jest_ and _supertest_) already set.

## Scripts:

- **server:up** - builds and starts container
- **server:down** - stops container
- **lint** - lints project (settings at .prettierrc) - automated by [Husky](https://typicode.github.io/husky/) pre-commit
- **test** - runs tests over modules
- **watch** - keeps tests running over modules


By default: Database running on **PORT 3000** and API on **PORT 3001**.