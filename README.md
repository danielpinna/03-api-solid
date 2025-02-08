# Dependências
-   TSX é um loader que permite rodar código TypeScript no NodeJS, sem um processo de compilação, sem configurações. Fazendo a transpilação de TS para JS em tempo de execução. Ela também possui um módulo de watch, que irá realizar o restart da aplicação a cada alteração de código de forma automática. Ajuda muito em desenvolvimento.

-   TSUP é uma biblioteca para realizar o processo de compilar o código TS para JS de forma muito performática, como em produção queremos usar o NodeJS para rodar nosso código em o uso do TSX, esta lib se torna essencial.

-   VITEST é um framework de teste que nos ajuda a escrever testes automatizados (unitários, e2e), trazendo suporte a código TypeScript de forma mais simples, sem configurações para realizar a transpilação de código. (similar ao Jest).

-   ZOD é uma bilioteca de validação (de objetos, tipos de dados, minx e max, etc) e transformação de dados (ex: UpperCase), através da criação de schemas. 

-   