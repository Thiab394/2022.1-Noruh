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
- US: Histórias de Usuário

## 3. Requisitos Funcionais

&emsp;&emsp; A tabela da pós-ratreabilidade backward-from dos requisitos funcionais podem ser encontrados abaixo:

<!--
| Requisito funcional |                                          Técnica utilizada                                          |                                    Onde encontrar                                    |       Elos        |
| :-----------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: | :---------------: |
|         RF1         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF01**](#ef01) |
|         RF2         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF02**](#ef02) |
|         RF3         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF03**](#ef03) |
|         RF4         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF04**](#ef04) |
|         RF5         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF05**](#ef05) |
|         RF6         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF06**](#ef06) |
|         RF7         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF07**](#ef07) |
|         RF8         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF08**](#ef08) |
|         RF9         | [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/) | [RF09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) | [**EF09**](#ef09) |
|        RF10         |                       [Introspecção](../elicitacao/tecnicas/introspeccao.md)                        |            [RF10](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF10**](#ef10) |
|        RF11         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF11](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF11**](#ef11) |
|        RF12         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF12](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF12**](#ef12) |
|        RF13         |                       [Introspecção](../elicitacao/tecnicas/introspeccao.md)                        |            [RF13](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF13**](#ef13) |
|        RF14         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF14](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF14**](#ef14) |
|        RF15         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF15](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF15**](#ef15) |
|        RF16         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF16](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF16**](#ef16) |
|        RF17         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF17](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF17**](#ef17) |
|        RF18         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF18](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF18**](#ef18) |
|        RF19         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF19](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF19**](#ef19) |
|        RF20         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF20](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF20**](#ef20) |
|        RF21         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF21](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF21**](#ef21) |
|        RF22         |                         [Brainstorm](../elicitacao/tecnicas/observacao.md)                          |            [RF22](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF22**](#ef22) |
|        RF23         |                         [Brainstorm](../elicitacao/tecnicas/Brainstorm.md)                          |            [RF23](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF23**](#ef23) |
|        RF24         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF24](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF24**](#ef24) |
|        RF25         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF25](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF25**](#ef25) |
|        RF26         |                         [Brainstorm](../elicitacao/tecnicas/brainstorm.md)                          |            [RF26](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF26**](#ef26) |
|        RF27         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF27](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF27**](#ef27) |
|        RF28         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF28](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF28**](#ef28) |
|        RF29         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF29](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF29**](#ef29) |
|        RF30         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF30](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF30**](#ef30) |
|        RF31         |                         [Observação](../elicitacao/tecnicas/observacao.md)                          |            [RF31](../../elicitacao/resultados/#21-requisitos-funcionais)             | [**EF31**](#ef31) |
-->

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
Brainstorm [BS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)

**Elos:** </br>
Representação: [RF01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US01](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF02

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:
Brainstorm [BS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Storytelling [ST01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados)

**Elos:** </br>
Representação: [RF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF03

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:
Brainstorm [BS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Análise de Documento [AD1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)

**Elos:** </br>
Representação: [RF03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF04

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I021](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Storytelling [ST02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados)

**Elos:** </br>
Representação: [RF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US04](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF05

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I011](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)

**Elos:** </br>
Representação: [RF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF06

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF07

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Questionário [Q05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos:** </br>
Representação: [RF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US07](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF08

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Análise de Documento [AD5](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)

**Elos:** </br>
Representação: [RF08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US08](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF09

**Categoria**:Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I015](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)

**Elos:** </br>
Representação: [RF09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US09](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF10

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US10](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF11

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US11](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF12

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Observação [OBS03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US12](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF13

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I025](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Questionário [Q03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos:** </br>
Representação: [RF13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US13](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF14

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US14](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF15

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Instrospecção [I026](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Questionário [Q02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)
Storytelling [ST04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/storytelling/#5-resultados)
Análise de Documento[AD2](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)

**Elos:** </br>
Representação: [RF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US15](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF16

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)

**Elos:** </br>
Representação: [RF16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US16](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF17

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US17](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF18

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Questionário [Q07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos:** </br>
Representação: [RF18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US18](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF19

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US19](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF20

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US20](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF21

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)
Análise de Documento [AD3](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)

**Elos:** </br>
Representação: [RF21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US21](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF22

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US22](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF23

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Questionário [Q08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos:** </br>
Representação: [RF23](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US23](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF24

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)

**Elos:** </br>
Representação: [RF24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US24](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF25

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)

**Elos:** </br>
Representação: [RF25](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US25](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF26

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)
Introspecção [I010](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Análise de Documento [AD4](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/)

**Elos:** </br>
Representação: [RF26](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US26](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF27

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I018](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Observação [OBS05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)
Questionário [Q04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos:** </br>
Representação: [RF27](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US27](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF28

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US28](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF29

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:** </br>
Representação: [RF29](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US29](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### RF30

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:**  
Recurso: [RF30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

### RF31

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Introspecção [I023](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/)
Observação [OBS10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos:**  
Recurso: [RF31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

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

Brainstorm [BS22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)
Análise de Documento [AD6](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)

**Elos:**  
Alocado: [RNF01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF02

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS23](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos:**  
Alocado: [RNF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF03

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)
Análise de Documento [AD7](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)
Análise de Documento [AD8](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)

**Elos:**  
Alocado: [RNF03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF04

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS25](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos:**  
Alocado: [RNF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF05

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS27](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos:**  
Alocado: [RNF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF06

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)
Análise do Documento [AD11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)

**Elos:**  
Alocado: [RNF06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF07

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)
Análise de Documento [AD12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/analiseDcoumento/#3-analise-do-documento)

**Elos:**  
Alocado: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)  
Recurso: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)  
Agregação: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) agrega [RF20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) e [RF21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

### RNF08

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS32](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos**:
Alocado: [RNF08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Instrospecção](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/#3-resultados)

### RNF09

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS26](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos**:
Alocado: [RNF09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF10

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS29](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

**Elos**:
Alocado: [RNF10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF11

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos**:
Alocado: [RNF11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

### RNF12

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos**:
Alocado: [RNF12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

### RNF13

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos**:
Alocado: [RNF13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no
Recurso: [RNF13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) depende dos recursos do [RF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) E [RF20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

### RNF14

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Brainstorm [BS31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)
Questionário [Q10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos**:
Alocado: [RNF14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### RNF15

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)
Questionário [Q11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/questionario/#4-resultado)

**Elos**:
Alocado: [RNF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

### RNF16

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

Observação [OBS15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)

**Elos**:
Alocado: [RNF16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) está alocado no [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/#4-resultados)
Recurso: [RNF16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) dependo dos recursos do [RF1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

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
