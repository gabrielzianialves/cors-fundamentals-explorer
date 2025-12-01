# Atividade Prática: Demonstrando o CORS (Recusa e Permissão)

## Sobre o projeto
Este projeto demonstra uma comunicação entre um frontend (porta 3000) e um backend em Node.js (porta 8080) utilizando CORS. O objetivo é mostrar como o navegador bloqueia requisições entre origens diferentes e como habilitar o acesso corretamente usando o middleware cors.

🔹 Vídeo de demonstração: https://youtu.be/abQ4o_1m9Mc


## Rodando o projeto 

Pré-requisitos: 

- Node.js
- Git

Em um ambiente de desenvolvimento, siga os seguintes passos utilizando o terminal:

### Backend

1 - Entre na pasta do backend:
```
cd backend
```
2 - Instale as dependências:
```
npm init -y
npm install express cors
```
3 - Inicie o servidor:
```
node server.js
```
4 - Backend estará rodando em:
```
http://localhost:8080
```

### Frontend

1 - Entre na pasta do frontend:
```
cd frontend
```
2 - Instale as dependências:
```
npm init -y
npm install serve
```
3 - Inicie o projeto:
```
npx serve -l 3000
```
4 - O projeto estará rodando em:
```
http://localhost:3000
```

## Como baixar ou clonar o repositório?

Se você preferir por **clonar** o projeto, pode inserir esse comando no terminal do seu Git instalado:
```bash
git clone https://github.com/gabrielzianialves/cors-fundamentals-explorer.git
```

Agora, se preferir **baixar** o projeto em arquivo ZIP, siga as seguintes instruções:

1. Vá até a página principal do repositório no GitHub;
2. Clique no botão Code;
3. Selecione a opção Download ZIP;
4. Após o download, extraia o arquivo em um diretório de sua escolha.
