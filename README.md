# Comandos utilizados para criar e testar o projeto no ambiente de desenvolvimento

npm init -y
npm i typescript -D
npx tsc --init
npm i @types/node tsx -D
npm run dev

## Depedencias 
npm i fastify
npm i drizzle-orm
npm i drizzle-kit
npm i zod
npm install --save-dev --save-exact @biomejs/biome

ctrl+shift+p: preferences: Open Workspace Settings (JSON)
{
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "biomejs.biome"
}

copiar arquivo biome.JSON

instalar extensão do vscode

## Operacoes no banco 
npx drizzle-kit generate

npx drizzle-kit migrate

npx drizzle-kit studio