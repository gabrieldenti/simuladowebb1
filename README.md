# Projeto de API - Simulado B1 de Programação Web

Este é um projeto de API desenvolvido em Node.js e TypeScript.

## Instalar NodeJs

Ter o NodeJs instalado na sua máquina (v.16 ou superior)
## Instalando as dependencias do projeto

Baixe ou clone este repositorio para sua IDE de preferência.

Abra o terminal do projeto da API e execute o comando para baixar todas as dependencias do projeto:
```
npm install
``` 

## Passos Iniciais

Crie um arquivo `.env` na raiz do projeto e adicionar as variaveis necessárias para ajustar a conexão do banco de dados. Você pode usar o arquivo `.env.example` de referência para as variáveis que são necessárias.

## Rodando Projeto

Agora com o projeto configurado e com todas as suas dependencias baixadas no terminal execute o seguinte comando para criar ou atualizar as tabelas do banco de dados:
```
npx prisma migrate dev
```
Para gerar a atualização feita do banco de dados no projeto, execute este comando:
```
npx prisma generate
```

Obs: O banco de dados não está com dados inseridos nele , apenas a criação de tabelas e relações estão criados no schema do prisma, caso precise, popule o banco de dados para testes.

Inicie o projeto com o seguinte comando no terminal:
```
npm run dev ou npm run prod 
```

O projeto estará disponível em http://localhost:3000.




