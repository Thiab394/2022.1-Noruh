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

<figcaption align='center'>
    <b>Tabela 1: análise backward-from requisitos funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## Elos Funcionais

### EF01

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US01](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF02

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF03

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF04

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US04](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF05

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF06

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF07

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US07](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF08

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF08](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US08](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF09

**Categoria**:Desenvolvimento

**Elos:** </br>
Representação: [RF09](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US09](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF10

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US10](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF11

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US11](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF12

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US12](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF13

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US13](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF14

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US14](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF15

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US15](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF16

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US16](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF17

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF17](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US17](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF18

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF18](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US18](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF19

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF19](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US19](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF20

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US20](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF21

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US21](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF22

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF22](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US22](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF23

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF23](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US23](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF24

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF24](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US24](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF25

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF25](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US25](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF26

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF26](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US26](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF27

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF27](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US27](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF28

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF28](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US28](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF29

**Categoria**: Desenvolvimento

**Elos:** </br>
Representação: [RF29](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/) representa [US29](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/) </br>

### EF30

**Categoria**: Desenvolvimento

**Elos:**  
Recurso: [RF30](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

### EF31

**Categoria**: Desenvolvimento

**Elos:**  
Recurso: [RF31](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

# 4. Requisitos Não Funcionais

&emsp;&emsp; A tabela da pós-ratreabilidade backward-from dos requisitos não funcionais podem ser encontrados abaixo:

| Requisito funcional |                                            Técnica utilizada                                            |                                                   Onde encontrar                                                   |        Elos         |
| :-----------------: | :-----------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :-----------------: |
|        RNF1         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF1](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF01**](#ENF01) |
|        RNF2         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF2](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF02**](#ENF02) |
|        RNF3         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF3](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF03**](#ENF03) |
|        RNF4         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF4](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF04**](#ENF04) |
|        RNF5         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF5](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF05**](#ENF05) |
|        RNF6         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF6](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF06**](#ENF06) |
|        RNF7         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF7](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF07**](#ENF07) |
|        RNF8         | [Introspecção](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/introspeccao/) | [RNF8](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF08**](#ENF08) |
|        RNF9         |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF9](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais)  | [**ENF09**](#ENF09) |
|        RNF10        |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF10](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF10**](#ENF10) |
|        RNF11        |   [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/)   | [RNF11](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF11**](#ENF11) |
|        RNF12        |   [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/)   | [RNF12](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF12**](#ENF12) |
|        RNF13        |   [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/)   | [RNF13](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF13**](#ENF13) |
|        RNF14        |   [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/)   | [RNF14](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF14**](#ENF14) |
|        RNF15        |   [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/)   | [RNF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF15**](#ENF15) |
|        RNF16        |   [Observação](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/observacao/)   | [RNF16](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#22-requisitos-nao-funcionais) | [**ENF16**](#ENF16) |

<figcaption align='center'>
    <b>Tabela 1: análise backward-from requisitos não funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## Elos Não-Funcionais

### ENF01

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF01](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF02

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF02](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF03

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF03](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF04

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF04](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF05

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF05](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF06

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF06](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)

### ENF07

**Categoria**: Desenvolvimento

**Elos:**  
Alocado: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) está alocado no [Brainstorm](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/tecnicas/brainstorm/#4-resultados)  
Recurso: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) depende dos recursos do [RF15](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)  
Agregação: [RNF07](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) agrega [RF20](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais) e [RF21](https://requisitos-de-software.github.io/2022.1-Noruh/elicitacao/resultados/#21-requisitos-funcionais)

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
