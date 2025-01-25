## Ambiente de desenvolvimento para Typescript com FastFy e ESLINT

### Instalação de pacotes:

- Tipagem no Node:
```
npm install -D @types/node
```
- Fastfy:
```
npm i fastify
```
- Eslit:
```
npm i eslint @rocketseat/eslint-config -D
```
- Tsx
```
npm i tsx
```

## Package.json
- Configuração do lint
```
"scripts": {
    "dev": "tsx watch src/server.ts",
    "lint": "eslint src --ext .ts --fix"
  },  
```
