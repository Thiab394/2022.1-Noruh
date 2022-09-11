# Backward-from

## 1.Introdução

&emsp;&emsp; A pós-rastreabilidade tem como objetivo ligar os artefatos que são criados durante o ciclo de vida de um projeto aos seus devidos requisitos elicitados. Sendo assim, neste documento iremos utilizar a técnica de rastreabilidade backward-from com o intuito de conectar os requisitos a suas respectivas técnicas de elicitação e evidenciar os elos presentes entre eles.

## 2. Metodologia

&emsp;&emsp; Para a análise backward-from dos requisitos iremos utilizar uma tabela dividida nas seguintes colunas:

- Requisito
- Ténica utilizada
- Onde encontrar
- Elos

&emsp;&emsp; Abaixo pode-se encontrar a legenda para as abreviaturas que serão utilizadas:

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- BS: Brainstorm
- I: Introspecção
- OBS: Observação
- Q: Questionário
- ST: Storytelling
- AD: Análise de Documento

## 3. Requisitos Funcionais

&emsp;&emsp; A tabela da pós-ratreabilidade backward-from dos requisitos funcionais podem ser encontrados abaixo:

|  ID  |                                      Descrição                                      |                                                                                                                                                                                                                                                            Técnica utilizada                                                                                                                                                                                                                                                             |
| :--: | :---------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| RF1  |                        O usuário deve poder criar uma conta                         |                                                                                                                                                                      [BS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)                                                                                                                                                                       |
| RF2  |                    O usuário deve poder realizar login na conta                     |                                                                                                            [BS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), </br> [ST01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados)                                                                                                             |
| RF3  |                         O usuário deve poder fazer pedidos                          |                                                                                                                                                                    [BS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [AD1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)                                                                                                                                                                     |
| RF4  |                       O usuário deve poder acessar o cardápio                       |                                                                                                            [BS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I021](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), </br> [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados)                                                                                                            |
| RF5  |        O usuário deve poder abrir uma comanda a partir da leitura do QR Code        |                                                                                                                                                                      [BS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I011](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)                                                                                                                                                                      |
| RF6  |                       O usuário deve poder editar seu perfil                        |                                                                                                                                                                                                                      [BS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF7  |                     O usuário deve poder pesquisar restaurantes                     |                                                                                                             [BS17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), </br> [Q05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                                                              |
| RF8  |                  O usuário deve poder ter acesso aos termos de uso                  |                                                                                                                                                                    [BS19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [AD5](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)                                                                                                                                                                     |
| RF9  | O usuário deve poder ver a localização dos estabelecimentos a partir do google maps |                                                                                                                                                                      [BS20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I015](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)                                                                                                                                                                      |
| RF10 |               O usuário deve conseguir cadastrar múltiplos endereços                |                                                                                                                                                                                                               [OBS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF11 |                        O usuário deve fazer logout do perfil                        |                                                                                                                                                                                                               [OBS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF12 |  O usuário deve poder selecionar a cidade em que deseja buscar restaurantes/bares   |                                                                                                                                                               [I06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), [OBS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                |
| RF13 |         O usuário deve poder solicitar a conta para o pagamento fora do app         |                                                                                                                                                               [I025](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), [Q03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                                                                                                                |
| RF14 |             O usuário deve poder cadastrar seu cartão de crédito/débito             |                                                                                                                                                                                                                      [BS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF15 |                      O usuário deve poder realizar pagamentos                       | [BS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I026](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), </br> [Q02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado), [ST04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados), </br> [AD2](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) |
| RF16 |              O usuário deve poder ver restaurantes abertos no momento               |                                                                                                                                                                      [BS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)                                                                                                                                                                       |
| RF17 |        O usuário deve poder receber notificações sobre o andamento do pedido        |                                                                                                                                                                                                                      [BS16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF18 |                  O usuário deve poder acessar histórico de contas                   |                                                                                                                                                                [BS18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [Q07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                                                                                                                 |
| RF19 |       O usuário deve poder ver uma breve descrição sobre o restaurante ou bar       |                                                                                                                                                                                                                      [BS21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF20 |            O usuário deve poder adicionar multiplas formas de pagamento             |                                                                                                                                                                                                               [OBS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF21 |    O usuário deve poder ter a opção de parcelar seus pagamentos quando possível     |                                                                                                                                                             [OBS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados), [AD3](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)                                                                                                                                                              |
| RF22 |             O usuário deve poder filtrar restaurantes pela localização              |                                                                                                                                                                                                                      [BS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF23 |                  O usuário deve poder avaliar restaurantes e bares                  |                                                                                                                                                                [BS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [Q08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                                                                                                                 |
| RF24 |              O usuário deve poder filtrar restaurantes por categorias               |                                                                                                                                                                      [BS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)                                                                                                                                                                       |
| RF25 |               O usuário deve poder filtrar restaurante por avaliação                |                                                                                                                                                                                                                      [BS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)                                                                                                                                                                                                                       |
| RF26 |               O usuário deve poder ver estabelecimentos com promoções               |                                                                                                                 [BS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/), [I010](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), </br> [AD4](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)                                                                                                                 |
| RF27 |      O usuário deve poder entrar na fila de espera do estabelecimento pelo app      |                                                                                                      [I018](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), [OBS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados),</br> [Q04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                                                       |
| RF28 |       O usuário deve receber notificações sobre o andamento da fila de espera       |                                                                                                                                                                                                               [OBS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF29 |                 O usuário deve receber um tutorial no primeiro uso                  |                                                                                                                                                                                                               [OBS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF30 |                O usuário deve poder criar uma comanda compartilhada                 |                                                                                                                                                                                                               [OBS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                                                                                |
| RF31 |                 O usuário deve poder pesquisar produtos no cardápio                 |                                                                                                                                                               [I023](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/), [OBS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                                                               |

<figcaption align='center'>
    <b>Tabela 1: análise backward-from requisitos funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## Elos Funcionais

### RF01

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:
Brainstorm [BS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

**Elos:** </br>
Agregação: [I01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) agrega [BS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

### RF02

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:
Brainstorm [BS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Storytelling [ST01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>

**Elos:** </br>
Agregação: [BS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) agrega [I02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) e [ST01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>

### RF03

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:
Brainstorm [BS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Análise de Documento [AD1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

**Elos:** </br>
Representação: [BS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [AD1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

### RF04

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I021](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Storytelling [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>

**Elos:** </br>
Representação: [BS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) e [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) representa [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>
Agregação: [BS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) agrega [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>

### RF05

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I011](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

**Elos:** </br>
Representação: [BS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [I011](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF06

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF07

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Questionário [Q05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos:** </br>
Representação: [BS17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) e [Q05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) representa [I07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Agregação: [BS17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) agrega [Q05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

### RF08

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Análise de Documento [AD5](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

**Elos:** </br>
Representação: [BS19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [AD5](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

### RF09

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I015](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

**Elos:** </br>
Representação: [BS20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [I015](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF10

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF11

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF12

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Observação [OBS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>
Representação: [I06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) representa [OBS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

### RF13

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I025](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Questionário [Q03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos:** </br>
Recurso: [Q03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) depende de um recurso de [I025](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF14

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF15

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Instrospecção [I026](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Questionário [Q02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>
Storytelling [ST04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>
Análise de Documento [AD2](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

**Elos:** </br>
Representação: [AD2](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) representa [I026](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Agregação: [BS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) agrega [ST04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados) </br>
Recurso: [Q02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) depende de um recurso de [I026](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF16

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

**Elos:** </br>
Representação: [BS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [I08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF17

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF18

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Questionário [Q07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos:** </br>
Representação: [BS18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [Q07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

### RF19

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF20

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF21

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>
Análise de Documento [AD3](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

**Elos:** </br>
Representação: [AD3](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) representa [OBS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

### RF22

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF23

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Questionário [Q08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos:** </br>
Agregação: [BS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [Q08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

### RF24

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

**Elos:** </br>
Representação: [BS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) representa [I09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF25

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF26

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) </br>
Introspecção [I010](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Análise de Documento [AD4](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) </br>

**Elos:** </br>
Recurso: [BS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) e [AD4](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/) depende de um recurso de [I010](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>

### RF27

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I018](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Observação [OBS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>
Questionário [Q04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos:** </br>
Representação: [I018](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) representa [Q04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>
Agregação: [Q04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) e [I018](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) agrega [OBS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

### RF28

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF29

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:** </br>

- Não existe artefato para moldar o elo </br>

### RF30

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:**

- Não existe artefato para moldar o elo </br>

### RF31

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I023](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) </br>
Observação [OBS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos:**  
Representação: [I023](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) depende dos recursos do [OBS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

# 4. Requisitos Não Funcionais

&emsp;&emsp; A tabela da pós-ratreabilidade backward-from dos requisitos não funcionais podem ser encontrados abaixo:

|  ID   |                                                Descrição                                                 |                                                                                                                                                                           Técnica Utilizada                                                                                                                                                                            |
| :---: | :------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| RNF1  |                            O sistema deve restringir a idade para uso do app                             |                                                                 [BS22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados), [AD6](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)                                                                  |
| RNF2  |                                      O sistema deve ser responsivo                                       |                                                                                                                               [BS23](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF3  |    O sistema deve ser disponível para android versão 5.0 ou superior e IOS versão IOS 11 ou superior     | [BS24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados), [AD7](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento), </br> [AD8](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) |
| RNF4  |                               O sistema deve possuir uma interface gráfica                               |                                                                                                                               [BS25](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF5  |            O sistema deve ter um tempo de comunicação com o servidor de no máximo 10 segundos            |                                                                                                                               [BS27](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF6  |                  O sistema deve garantir a privacidade e segurança dos dados do usuário                  |                                                                 [BS28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados), [AD11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)                                                                 |
| RNF7  |                O sistema deve permitir com que pagamentos sejam realizados com segurança                 |                                                                 [BS30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados), [AD12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)                                                                 |
| RNF8  |                        O sistema deve ter integração com o sistema do restaurante                        |                                                                                                                               [BS32](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF9  |                              sistema deve apresentar um design minimalista                               |                                                                                                                               [BS26](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF10 |                         O sistema não deve ficar fora do ar por mais de 4 horas                          |                                                                                                                               [BS29](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)                                                                                                                               |
| RNF11 |              O sistema deve permitir a navegação pelo app sem a necessidade de um cadastro               |                                                                                                                              [OBS11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                               |
| RNF12 | A navegação pelo cardápio dos restaurantes deve ser de fácil entendimento e mostrar imagens dos produtos |                                                                                                                              [OBS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                               |
| RNF13 |                              O pagamento pelo app deve ser simples e rápido                              |                                                                                                                              [OBS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                               |
| RNF14 |                         O sistema deve fornecer uma interface gráfica intuitiva                          |                                                                         [BS31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados), [Q10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                         |
| RNF15 |                     O sistema deve ter um tempo de resposta de no máximo 2 segundos                      |                                                                        [OBS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados), [Q11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)                                                                         |
| RNF16 |                 O sistema deve ter integração com o google e facebook para criar contas                  |                                                                                                                              [OBS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)                                                                                                                               |

<figcaption align='center'>
    <b>Tabela 2: análise backward-from requisitos não funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## Elos Não-Funcionais

### RNF01

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>
Análise de Documento [AD6](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>

**Elos:**  
Representação: [AD6](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) representa [BS22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

### RNF02

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS23](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos:**  
Alocado: [RNF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

### RNF03

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>
Análise de Documento [AD7](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>
Análise de Documento [AD8](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>

**Elos:**  
Representação: [BS24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) representa [AD7](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) e [AD8](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>

### RNF04

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS25](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos:**

- Não existe artefato para moldar o elo </br>

### RNF05

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS27](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos:**

- Não existe artefato para moldar o elo </br>

### RNF06

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>
Análise do Documento [AD11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>

**Elos:**  
Representação: [AD11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) representa [BS28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

### RNF07

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>
Análise de Documento [AD12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) </br>

**Elos:**  
Representação: [AD12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento) repsenta [BS30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

### RNF08

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS32](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF09

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS26](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF10

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS29](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF11

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF12

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF13

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

### RNF14

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>
Questionário [Q10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos**:
Representação: [Q10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) representa [BS31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados) </br>

### RNF15

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>
Questionário [Q11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) </br>

**Elos**:
Recurso: [Q11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado) depende de um recurso de [OBS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

### RNF16

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados) </br>

**Elos**:

- Não existe artefato para moldar o elo </br>

## Referências

- Sayão e Leite. Rastreabilidade de Requisitos. ISSN 0103-9741
- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 1º/2022. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de versão

| Versão |                       Alteração                        |  Responsável  | Revisor |   Data   |      Hora      |
| :----: | :----------------------------------------------------: | :-----------: | :-----: | :------: | :------------: |
|  1.0   |                           -                            | João Henrique |    -    | 20/08/22 | 08:25 às 09:25 |
|  1.1   | Adicionando Rfs 1 ao 9 e suas representações nos elos  | João Henrique |  Lucas  | 22/08/22 | 12:30 às 13:20 |
|  1.2   |                Atualizando metodologia                 | João Henrique |  Lucas  | 22/08/22 | 16:00 às 16:15 |
|  1.3   |          Atualizando metodologia e introdução          |     Lucas     |    -    | 23/08/22 | 10:00 às 11:00 |
|  1.4   | Adicionando Rfs 9 ao 19 e suas representações nos elos |     Lucas     | Eurico  | 23/08/22 | 20:00 às 20:50 |
|  1.5   |           Adicionando Rfs 20 ao 29 na tabela           |    Eurico     |  João   | 23/08/22 | 22:00 às 20:25 |
|  1.6   |              Elos funcionais Rfs 20 ao 29              |    Eurico     |  João   | 23/08/22 | 22:25 às 20:50 |
|  1.7   |                Adicionando tabela RNFS                 |     Bruno     |    -    | 24/08/22 | 11:30 às 11:45 |
|  1.8   |            Finalizando elos não funcionais             |     Bruno     |    -    | 24/08/22 | 20:10 às 20:45 |
|  2.0   |                 Finalizando documento                  |     Bruno     |  João   | 09/09/22 | 15:00 às 16:45 |
