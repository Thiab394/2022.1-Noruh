# Introspecção

## 1. Introdução

&emsp;&emsp; A introspecção é uma técnica de elicitação de requisitos que busca o entendimento das funcionalidades que mais agradem os usuários do sistema, onde precisamos nos colocar no lugar dos usuários e dos stakeholders. Para a realização desta instrospecção, iremos realizar uma análise de interface de usuário, que como definido por Wiegers e Beatty, é uma técnica onde a equipe interage com a interface de um sistema interativo para fazer o fluxo de tarefas de um usuário padrão do sistema e identificar requisitos ao longo do caminho.

## 2. Metodologia

&emsp;&emsp; Dessa forma, para que possamos garantir que seguimos os passos dos usuários dentro do sistema, iremos seguir o fluxo de tarefas do app desde a criação de uma conta até a realização de um pedido. Assim, a cada passo iremos levantar os requisitos encontrados.

## 3. Introspecção

### 3.1 - Ao acessar aplicativo

- O usuário deve poder criar uma conta
- O usuário deve poder entrar em uma conta ja existente
- O usuário deve poder entrar sem fazer login
- O usuário deve poder fazer login com google
- O usuário deve poder fazre login com facebook

### 3.2 - Ao entrar em conta

- O usuário deve poder escolher a cidade em que deseja buscar restaurantes
- O usuário deve ter acesso a uma lista de restaurantes disponíveis
- O usuário deve poder filtrar os restaurantes abertos no momento
- O usuário deve poder filtrar os restaurantes por tipo de cozinha
- O usuário deve poder filtrar os restaurantes com descontos
- O usuário deve poder abrir uma comanda por leitura de QRCode

### 3.3 - Ao escolher um restaurante

- O usuário deve ter acesso a uma página do restaurante
- O usuário deve ter acesso aos horários de funcionamento do restaurante
- O usuário deve ter acesso ao endereço do restaurante
- O usuário deve ter acesso ao mapa com a localização do restaurante no google maps
- O usuário deve ter acesso a avaliações de outros usuários
- O usuário deve poder fazer uma avaliação do restaurante

### 3.4 - Ao abrir comanda

- O usuário deve poder entrar na fila de espera
- O usuário deve poder fazer um pedido delivery
- O usuário deve poder realizar um pedido para retirar no balcão
- O usuário deve ter acesso a um cardápio com os itens do resturante
- O usuário deve poder adcionar itens à sua comanda
- O usuário deve poder pesquisar um item pelo nome no cardápio

### 3.5 - Ao acessaar comanda

- O usuário deve ter acesso a uma lista com os itens pedidos
- O usuário deve poder pedir a conta pelo app
- O usuário deve poder pagar sua conta pelo app

## 4. Resultados

&emsp;&emsp; A tabela com os requisitos elicitados durante a introspecção pode ser encontrada abaixo:

|  ID  |                               Requisitos Funcionais                               |
| :--: | :-------------------------------------------------------------------------------: |
| I01  |                       O usuário deve poder criar uma conta                        |
| I02  |               O usuário deve poder entrar em uma conta ja existente               |
| I03  |                    O usuário deve poder entrar sem fazer login                    |
| I04  |                    O usuário deve poder fazer login com google                    |
| I05  |                   O usuário deve poder fazer login com facebook                   |
| I06  |     O usuário deve poder escolher a cidade em que deseja buscar restaurantes      |
| I07  |         O usuário deve ter acesso a uma lista de restaurantes disponíveis         |
| I08  |          O usuário deve poder filtrar os restaurantes abertos no momento          |
| I09  |         O usuário deve poder filtrar os restaurantes por tipo de cozinha          |
| I010 |            O usuário deve poder filtrar os restaurantes com descontos             |
| I011 |           O usuário deve poder abrir uma comanda por leitura de QRCode            |
| I012 |               O usuário deve ter acesso a uma página do restaurante               |
| I013 |      O usuário deve ter acesso aos horários de funcionamento do restaurante       |
| I014 |               O usuário deve ter acesso ao endereço do restaurante                |
| I015 | O usuário deve ter acesso ao mapa com a localização do restaurante no google maps |
| I016 |             O usuário deve ter acesso a avaliações de outros usuários             |
| I017 |              O usuário deve poder fazer uma avaliação do restaurante              |
| I018 |                   O usuário deve poder entrar na fila de espera                   |
| I019 |                   O usuário deve poder fazer um pedido delivery                   |
| I020 |          O usuário deve poder realizar um pedido para retirar no balcão           |
| I021 |        O usuário deve ter acesso a um cardápio com os itens do resturante         |
| I022 |                O usuário deve poder adicionar itens à sua comanda                 |
| I023 |           O usuário deve poder pesquisar um item pelo nome no cardápio            |
| I024 |            O usuário deve ter acesso a uma lista com os itens pedidos             |
| I025 |                    O usuário deve poder pedir a conta pelo app                    |
| I026 |                   O usuário deve poder pagar sua conta pelo app                   |

<figcaption align='center'>
    <b>Tabela 1: Requisitos elicitados</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>

## Histórico de Versão

| Versão |                   Alteração                    |            Responsável            | Revisor | Data  |
| :----: | :--------------------------------------------: | :-------------------------------: | :-----: | :---: |
|  1.0   |                Documento criado                | João Henrique,Bruno, Karla, Lucas | Eurico  | 09/07 |
|  1.1   |               Documento revisado               |               Lucas               |    -    | 04/08 |
|  2.0   | Troca fluxo de tarefas e metodologia utilizada |               Lucas               |  João   | 06/08 |

## Referências

- BARBOSA, Simone; SILVA, Bruno. Interação Humano Computador. Rio de Janeiro. Elsevier Editora Ltda. 2010
- [Wiegers, Beatty. Software requirements, third edition](https://aprender3.unb.br/pluginfile.php/2124454/mod_resource/content/1/Elicitacao%20de%20Req.pdf)
