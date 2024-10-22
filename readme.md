API com Node.js e Express para fins de estudos...

URL DO CURSO GRATUITO: https://www.youtube.com/watch?v=94FonmsT27s

URL INSTRUÇÕES PRISMA: 
Objetivos: https://www.prisma.io/

** Sempre que você atualizar seu esquema Prisma, precisará executar o prisma db pushcomando para criar novos índices e regenerar o Prisma Client.

    $ npx prisma db push

** Para acessar o banco via localhost(http://localhost:5555):

    $ npx prisma studio

1. Criar uma API do zero com Node e Express;
2. Aprender a Criptografar Senhas(bcrypt);
3. Integração com o banco de Dados MongoDB(plataforma Atlas);
4. Aprender a usar Prisma;
5. Utilizar Rotas Públicas e Privadas;
6. Token JWT para Autenticação de usuários;
7. Utilização do Thunder para testar as rotas;

Dowloads necessários:
- Express;
- Prisma;
- BCRYPT;

Código para gerar um JWT secret:
    $ node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"

Códigos importantes:

1. Código para Startar e manter o Servidor Rodando
    $ node --watch server.js

2. Criando o package.json
    $ npm init -y

3. Instalando o Express:
   $ npm install express
