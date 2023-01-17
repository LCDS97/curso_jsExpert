## Criar projeto da NLW e criar documentação
## Integrar com Salesforce API do Habits
### Utilizar meu projeto de Churras
#### Criar um aplicativo pessoal no Salesforce

Utilizando banco de Dados SQLite com Prisma
ORM - Prisma
Configuração com Typescript

UUID - Gerador de Ids para o banco de dados para definir ids unicos para aplicação

Prisma tips:
- npx prisma init --datasource-provider SQLite
    - Para criar banco de dados da aplicação utilizando SQLite
- npx prisma studio
    - Para abrir o cliente do Prisma e verificar pelo navegador banco de dados
- npx prisma migrate dev
    - Para criar uma migração (Versionamento do banco de dados) pelo Prisma

Para conectar o banco do Prisma com o node:
- import { PrismaClient } from '@prisma/client'

Instaciando esse classe já tenho todos os recursos do Prisma com o node

Para utilizar configurar o CORS, podemos utilizar o próprio cors do Fastify com:
- npm i @fastify/cors

Depois para configurar o cors, instancia o mesmo e utilize o método
- app.register(cors)