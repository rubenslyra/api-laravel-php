# api-laravel-php
Repositório dedicado ao desenvolvimento do projeto API Laravel PHP.

## Características de uma API REST?

>**Arquitetura cliente-servidor**: indica uma arquitetura baseada em clientes, servidores e recursos, em que as solicitações são feitas via protocolo HTTP. Essa condição está ligada à independência entre o cliente e o servidor. Ou seja, mudanças feitas pelo usuário na aplicação em seu dispositivo não devem afetar o servidor e sua estrutura de dados. De mesmo modo, alterações feitas pelos desenvolvedores nos bancos de dados da aplicação não devem instantaneamente impactar o dispositivo do usuário.
>
>**Comunicação stateless**: a comunicação feita entre cliente e servidor não deve armazenar nenhuma informação entre as solicitações. Em uma REST API, cada solicitação contém todos os dados necessários para que seja atendida, não dependendo de informações já armazenadas em outras sessões.
Cache: uma API REST deve ser desenvolvida de modo que consiga armazenar dados em cache. Quando uma informação fica armazenada em cache, as solicitações e respostas entre cliente e servidor são otimizadas.
>
>**Interface uniforme**: a interface uniforme é o que permite o desenvolvimento independente da aplicação entre usuário e servidor. Uma REST API deve conter uma interface uniforme pois ela oferece uma comunicação padronizada entre o usuário e o software. A manipulação de recursos através de representações (como JSON ou XML), é uma das condições para o desenvolvimento de uma interface uniforme.
>
>**Sistema de camadas**: cada camada do sistema deve possuir uma funcionalidade específica (como segurança ou carregamento). Assim, cada camada é responsável por uma etapa diferente dos processos de requisição de usuário e de resposta do servidor. Essas camadas são ordenadas hierarquicamente mas, apesar de serem separadas, todas interagem entre si.




Referência:

- ["API Rest", Bruna B. Barro @ Hostinger](https://www.hostinger.com.br/tutoriais/api-restful)
