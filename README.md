# nodets-canil

 tsc --init
 para criar o arquivo de typescript
 alterações na linha 14 para   
   "target": "es6",  
     "module": "commonjs",                                /* Specify what module code is generated. */
     "rootDir": "./src",                                  /* Specify the root folder within your source files. */
    "moduleResolution": "node",   
 Essas 4 linhas tem que ser modificadas e decomentadas
 Depois vai no 
 install express  mustache-express dotenv
 Depois da um 
 npm install --save-dev @types/express @types/mustache-express @types/nodes
É importante lembrar que vc tem que ter instalada de forma global 
npm install -g nodemon typescript ts-node
Como eu não tenho não preciso repetir

### Pre-requisitos globais
npm install -g nodemon typescript ts-node

### instalação
npm install

## para rodar npm run start-dev

Aqui encerra a primeira aula

Trazido css e images
Configurado o .env e o server.ts e fim da terceira aula
Tomei um erro fácil mas que ficou caro. Acabei fazendo o curso de typescript inteiro, que foi bom
e revi o início do curso se node, claro que o erro não tinha nada a ver com isso, eu só tinha escrito
umas porcarias dentro do sript do package.json e por isso não estava rodando. E muitas coisa não rodou 
em node da última vez, então eu acho que trauma me fez ir longe. Velau. Tudo funcionado

Foi feita as rotas e o server e dois controllers

Agora fizemso a pasta de view com pages e partials, lincamos o css e as imagens. Um pequenino perrengue, por causa
do link do partils no page e a forma certa de usar o mustache e o mais importante não adianta modificar o 
html e dar reload. Ele não faz nada, tem que dar reload em uma ts, ai sim ele atualiza
Fiquei um pouco em dúvida com relação ao endereço raiz, que em php é tão cuidado e da tantos problemas 
aqui não párece até agora que é um problema

Nesse commit já estamos a partir de uma mesma página consumindo o conteúdo da pasta de imagens, tudo muito tranquilo

Nesse commit usamos pela primeira vez o typescript tipando um objeto pet e justificando o uso do typescript finalmente.
Os animais que não vão ser entregues atravéz de um banco de dados formaram um grande array que tem tipo Pet[] e isso garante
a integridade do objeto, acho que a ideia de interface agora faz muito mais sentidoEssa foi a aula 8

E aqui encerramos a contrução de um model sem uso de banco de dados e pela primeira vez tenho uma aula sem o DB e sem peso, porque 
também é bom também saber fazer sem. O uso dos métodos de array me deixaram um pouco confuso mas com o uso eu acho que 
a coisa vai ficar mais clara. Principalmente pra por em prática subir o projeto que é um gap muito maior do que o uso de 
DB

Sem querer eu pulei uma aula onde o Boniek controi um helper que é uma função muito interessante que seleciona o tipo de animal
É uma função tipada que usa os poderes do typesript que deve ser mauseada. Eu acho que chegou a hora de refazer esse projeto muitas
vezes para que de fato os conceitos entrem na cabeça. E depois foi alterado na view e no controller para que recebam na tela os 
animais por seus tipos e todos. Falta agora somente fazer individual. Mas esse é um projeto inchuto e interessante