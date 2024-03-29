# Forward-from

## 1. Introdução

&emsp;&emsp; A pós-rastreabilidade tem como objetivo ligar os artefatos que são criados durante o ciclo de vida de um projeto aos seus devidos requisitos elicitados. Diante disso, neste documento iremos fazer a rastreabilidade foward-from, que tem como objetivo ligar os requisitos aos artefatos gerados durante o projeto, e também se estes requisitos foram implementados ou não no app.

## 2. Metodologia

&emsp;&emsp; Para realizar a rastreabilidade foward-from dos requisitos funcionais iremos utilizar uma tabela divida pelas seguintes linhas:

- Identificador do requisito
- Épico onde se encontra o requisito no backlog
- Tema onde se encontra o requisito no backlog
- História de usuário correspondente ao requisito
- Artefatos derivados do requisito
- Status da implementação do requisito
- Vídeo da tela onde esta implementada a funcionalidade

&emsp;&emsp; Já para a rastreabilidade foward-from dos requisitos não-funcionais iremos utilizar uma tabela divida pelas seguintes linhas:

- Identificador do requisito
- Artefatos derivados do requisito
- Status da implementação do requisito

## 3. Legenda:

- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- C: cenário
- UC: Caso de uso
- US: História de usuário
- ES: Especificação Suplementar
- NFR: NFR Framework

## 4. Requisitos Funcionais

### RF1

|           RF1           |                   O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder criar uma conta                                                                                      |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                      [Gerenciamento de conta](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                      |
|          Tema           |                                                         [Cadastro e login](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                         |
|           US            |                                                              [US01](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                              |
| Status da implementação |                                                                                                      Requisito totalmente implementado                                                                                                       |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-1-criar-perfil) <br> [Caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso1/#caso-de-uso-1-criar-conta) <br>[iStar](../../modelagem/iStar/#31-conta) |
|     Funcionalidade      |                                                             <img src="../../assets/foward-from/rf1.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                             |

### RF2

|           RF2           |                                                                                                     O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder realizar login na conta                                                                                                      |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                          [Gerenciamento de conta](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                           |
|          Tema           |                                                             [Cadastro e login](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                              |
|           US            |                                                                  [US02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                   |
| Status da implementação |                                                                                                           Requisito totalmente implementado                                                                                                           |
|        Artefatos        | [cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-1-criar-perfil) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso1/#caso-de-uso-2-fazer-login-na-conta) <br> [iStar](../../modelagem/iStar/#31-conta) |
|     Funcionalidade      |                                                                 <img src="../../assets/foward-from/rf2.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                  |

### RF3

|           RF3           |                                                                                                            O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder fazer [pedidos](../../modelagem/lexicos/#lexico-19-pedido)                                                                                                            |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                       [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                                       |
|          Tema           |                                                               [Fazer pedido no restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                               |
|           US            |                                                                    [US03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                    |
| Status da implementação |                                                                                                            Requisito totalmente implementado                                                                                                             |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-9-pedido-no-estabelecimento)<br>[caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br>[iStar](../../modelagem/iStar/#33-pedido) |
|     Funcionalidade      |                                                                   <img src="../../assets/foward-from/rf3.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                   |

### RF4

|           RF4           |                                                                                                          O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder acessar o [cardápio](../../modelagem/lexicos/#lexico-03-cardapio)                                                                                                            |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                        [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                                        |
|          Tema           |                                                                [Fazer pedido no restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                                |
|           US            |                                                                     [US04](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                     |
| Status da implementação |                                                                                                             Requisito totalmente implementado                                                                                                              |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-9-pedido-no-estabelecimento) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) |
|     Funcionalidade      |                                                                    <img src="../../assets/foward-from/rf4.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                    |

### RF5

|           RF5           |                                                                                           O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder abrir uma [comanda](../../modelagem/lexicos/#lexico-05-comanda) a partir da leitura do QR Code                                                                                            |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                        [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                                        |
|          Tema           |                                                                [Fazer pedido no restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                                                                |
|           US            |                                                                     [US05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                     |
| Status da implementação |                                                                                                             Requisito totalmente implementado                                                                                                              |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-9-pedido-no-estabelecimento) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br>[iStar](../../modelagem/iStar/#33-pedido) |
|     Funcionalidade      |                                                                    <img src="../../assets/foward-from/rf5.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                    |

### RF6

|           RF6           |                                                                                                      O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder [editar seu perfil](../../modelagem/lexicos/#lexico-10-editar-perfil)                                                                                                       |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                        [Gerenciamento de conta](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                         |
|          Tema           |                                                            [Edição de conta](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                            |
|           US            |                                                                [US06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                 |
| Status da implementação |                                                                                                         Requisito totalmente implementado                                                                                                         |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-7-edicao-do-perfil) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso1/#caso-de-uso-3-editar-conta)<br>[iStar](../../modelagem/iStar/#31-conta) |
|     Funcionalidade      |                                                               <img src="../../assets/foward-from/rf6.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                |

### RF7

|           RF7           |                                                                                                                  O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder [pesquisar](../../modelagem/lexicos/#lexico-20-pesquisar) restaurantes                                                                                                                  |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                          [Informações sobre estabelecimentos](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                           |
|          Tema           |                                                         [Pesquisas e filtros para visualização](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                         |
|           US            |                                                                              [US07](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                               |
| Status da implementação |                                                                                                                       Requisito totalmente implementado                                                                                                                       |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-9-pedido-no-estabelecimento) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/#caso-de-uso-1-fazer-pesquisa-por-restaurantes) <br>[iStar](../../modelagem/iStar/#32-pesquisa) |
|     Funcionalidade      |                                                                             <img src="../../assets/foward-from/rf7.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                              |

### RF8

|           RF8           |                                                                                              O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ter acesso aos termos de uso                                                                                               |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                      [Gerenciamento de conta](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                      |
|          Tema           |                                                          [Termos de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#41-epico-gerenciamento-de-conta)                                                           |
|           US            |                                                              [US08](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                              |
| Status da implementação |                                                                                                      Requisito totalmente implementado                                                                                                       |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-1-criar-perfil) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso1/#caso-de-uso-1-criar-conta) |
|     Funcionalidade      |                                                             <img src="../../assets/foward-from/rf8.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                             |

### RF9

|           RF9           |                                                                                              O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ver a localização dos [estabelecimentos](../../modelagem/lexicos/#lexico-12-estabelecimento) a partir do google maps                                                                                               |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                           [Informações sobre estabelecimentos](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                           |
|          Tema           |                                                                       [Descrição](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                                        |
|           US            |                                                                               [US09](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                               |
| Status da implementação |                                                                                                                       Requisito totalmente implementado                                                                                                                        |
|        Artefatos        | [Cenario](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br> [caso de uso](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/#caso-de-uso-2-acessar-pagina-do-restaurante) |
|     Funcionalidade      |                                                                              <img src="../../assets/foward-from/rf9.gif" alt="Employee data" width="180" height=auto title="Employee Data title">                                                                              |

### RF10

|          RF10           |                                   O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve conseguir cadastrar múltiplos [endereços](../../modelagem/lexicos/#lexico-11-enderecos)                                    |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                     [Gerenciamento de Conta](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                      |
|          Tema           |                        [Cadastro e login](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                         |
|           US            |                             [US10 ](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                             |
|        Artefatos        |                   [UC02](../../modelagem/Diagramas/CasoDeUso1/#caso-de-uso-2---fazer-login-na-conta) <br>                   |
| Status da implementação |                                              Requisito totalmente implementado                                              |
|     Funcionalidade      | <img src="../../assets/foward-from/RF10.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional"> |

### RF11

|          RF11           |                                                 O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve conseguir fazer logout do perfil                                                  |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                [Gerenciamento de Conta](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                                |
|          Tema           |                                   [Cadastro e login](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                                   |
|           US            |                                        [US11](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                        |
|        Artefatos        | [UC04](../../modelagem/Diagramas/CasoDeUso1/#caso-de-uso-2---fazer-login-na-conta) <br> [C02](../../modelagem/cenarios/#caso-2-logout-no-perfil) <br>[iStar](../../modelagem/iStar/#31-conta) |
| Status da implementação |                                                        Requisito totalmente implementado                                                         |
|     Funcionalidade      |           <img src="../../assets/foward-from/RF11.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">            |

### RF12

|          RF12           |                                           O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder selecionar a [cidade](../../modelagem/lexicos/#lexico-04-cidade) em que deseja buscar restaurantes/bares                                            |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                              [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                               |
|          Tema           |                             [Pesquisas e Filtros para Visulaização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                             |
|           US            |                                                  [US12](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                   |
|        Artefatos        | [UC07](../../modelagem/Diagramas/CasoDeUso3/#caso-de-uso-1-fazer-pesquisa-por-restaurantes) <br> [C05](../../modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) |
| Status da implementação |                                                                  Requisito parcialmente implementado                                                                  |
|     Funcionalidade      |                      <img src="../../assets/foward-from/RF12.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                      |

### RF13

|          RF13           |                                       O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder solicitar a conta para o pagamento fora do app                                       |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                          [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                           |
|          Tema           |                                           [Pagamento](../../modelagem/backlog/#42-epico-restaurante)                                            |
|           US            |                                       [US12](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                        |
|        Artefatos        | [UC05](../../modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br> [C09](../../modelagem/cenarios/#caso-9-pedido-no-estabelecimento) |
| Status da implementação |                                                        Requisito totalmente implementado                                                        |
|     Funcionalidade      |           <img src="../../assets/foward-from/RF13.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">           |

### RF14

|          RF14           |                                            O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder cadastrar seu cartão de crédito/débito                                             |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                            [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                            |
|          Tema           |                                             [Pagamento](../../modelagem/backlog/#42-epico-restaurante)                                             |
|           US            |                                         [US14](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                         |
|        Artefatos        | [UC05](../../modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br> [C04](../../modelagem/cenarios/#caso-4-cadastrar-forma-de-pagamento) |
| Status da implementação |                                                         Requisito totalmente implementado                                                          |
|     Funcionalidade      |            <img src="../../assets/foward-from/RF14.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">             |

### RF15

|          RF15           |                                                                                O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder realizar pagamentos pelo app                                                                                 |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                           [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                                                           |
|          Tema           |                                                                            [Pagamento](../../modelagem/backlog/#42-epico-restaurante)                                                                            |
|           US            |                                                                        [US15](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                        |
|        Artefatos        | [UC05](../../modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br> [C06](../../modelagem/cenarios/#caso-6-formas-de-pagamento) <br> [C09](../../modelagem/cenarios/#caso-9-pedido-no-estabelecimento) <br>[iStar](../../modelagem/iStar/#33-pedido) |
| Status da implementação |                                                                                        Requisito totalmente implementado                                                                                         |
|     Funcionalidade      |                                           <img src="../../assets/foward-from/RF15.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                            |

### RF16

|          RF16           |                                                       O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ver restaurantes abertos no momento                                                        |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                              [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                               |
|          Tema           |                             [Pesquisas e Filtros para Visulaização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                             |
|           US            |                                                  [US16](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                   |
|        Artefatos        | [UC07](../../modelagem/Diagramas/CasoDeUso3/#caso-de-uso-1-fazer-pesquisa-por-restaurantes) <br> [C05](../../modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br>[iStar](../../modelagem/iStar/#32-pesquisa) |
| Status da implementação |                                                                   Requisito totalmente implementado                                                                   |
|     Funcionalidade      |                      <img src="../../assets/foward-from/RF16.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                      |

### RF17

|          RF17           |    O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder receber [notificações](../../modelagem/lexicos/#lexico-18-notificar) sobre o andamento do [pedido](../../modelagem/lexicos/#lexico-19-pedido     |
| :---------------------: | :--------------------------------------------------------------------------: |
|          Épico          |         [Restaurante](../../modelagem/backlog/#42-epico-restaurante)         |
|          Tema           | [Fazer pedido no restaurante](../../modelagem/backlog/#42-epico-restaurante) |
|           US            |      [US17](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)      |
|        Artefatos        |   [UC05](../../modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido)   |
| Status da implementação |                      Requisito totalmente implementado                       |

### RF18

|          RF18           |                                      O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder acessar histórico de contas                                       |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                     [Gerenciamento de Conta](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                      |
|          Tema           |                            [Histórico](../../modelagem/backlog/#41-epico-gerenciamento-de-conta)                            |
|           US            |                             [US18](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                              |
|        Artefatos        |                          [UC03](../../modelagem/Diagramas/CasoDeUso1/#caso-de-uso-3-editar-conta)                           |
| Status da implementação |                                              Requisito totalmente implementado                                              |
|     Funcionalidade      | <img src="../../assets/foward-from/RF18.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional"> |

### RF19

|          RF19           |                                               O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ver uma breve descrição sobre o restaurante ou bar                                               |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                             [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                              |
|          Tema           |                                          [Descrição](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                          |
|           US            |                                                 [US19](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                  |
|        Artefatos        | [UC08](../../modelagem/Diagramas/CasoDeUso3/#caso-de-uso-2-acessar-pagina-do-restaurante) <br> [C05](../../modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) |
| Status da implementação |                                                                  Requisito totalmente implementado                                                                  |
|     Funcionalidade      |                     <img src="../../assets/foward-from/RF19.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                     |

### RF20

|          RF20           |                                                                                       O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder adicionar multiplas [formas de pagamento](../../modelagem/lexicos/#lexico-13-formas-de-pagamento)                                                                                        |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                       [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                                                                        |
|          Tema           |                                                                                        [Pagamento](../../modelagem/backlog/#42-epico-restaurante)                                                                                         |
|           US            |                                                                                    [US20](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                                     |
| Status da implementação |                                                                                                     Requisito totalmente implementado                                                                                                     |
|        Artefatos        | [C06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-6-formas-de-pagamento) <br> [UC02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) |
|     Funcionalidade      |                                                        <img src="../../assets/foward-from/rf20.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                                        |

### RF21

|          RF21           |                                                                               O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ter a opção de parcelar seus pagamentos quando possível                                                                                |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                                       [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                                                                        |
|          Tema           |                                                                                        [Pagamento](../../modelagem/backlog/#42-epico-restaurante)                                                                                         |
|           US            |                                                                                    [US21](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                                     |
| Status da implementação |                                                                                                     Requisito totalmente implementado                                                                                                     |
|        Artefatos        | [C06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-6-formas-de-pagamento) <br> [UC02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) |

### RF22

|          RF22           |                                                                               O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder filtrar restaurantes pela localização                                                                                |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                       [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                        |
|          Tema           |                                                      [Pesquisas e Filtros para Visualização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                      |
|           US            |                                                                           [US22](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                            |
| Status da implementação |                                                                                            Requisito totalmente implementado                                                                                            |
|        Artefatos        | [C05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br> [UC03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/) <br>[iStar](../../modelagem/iStar/#32-pesquisa)|
|     Funcionalidade      |                                               <img src="../../assets/foward-from/rf22.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                               |

### RF23

|          RF23           |                                                                                             O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder [avaliar](../../modelagem/lexicos/#lexico-02-avaliar) restaurantes e bares                                                                                             |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                                [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                                 |
|          Tema           |                                                                             [Avaliação](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                                             |
|           US            |                                                                                    [US23](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                                     |
| Status da implementação |                                                                                                        Requisito não implementado                                                                                                         |
|        Artefatos        | [UC02](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-1-fazer-pedido) <br> [C06](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-6-formas-de-pagamento) |
|Funcionalidade ([Protótipo](../analise/validacao/prototipo.md))   |                                               <img src="../../assets/foward-from/rf23.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                               |

### RF24

|          RF24           |                                                                                O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder filtrar restaurantes por categorias                                                                                 |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                       [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                        |
|          Tema           |                                                      [Pesquisas e Filtros para Visualização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                      |
|           US            |                                                                           [US24](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                            |
| Status da implementação |                                                                                            Requisito totalmente implementado                                                                                            |
|        Artefatos        | [UC03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/) <br> [C05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br>[iStar](../../modelagem/iStar/#32-pesquisa) |
|     Funcionalidade      |                                               <img src="../../assets/foward-from/rf24.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                               |

### RF25

|          RF25           |                                                                                 O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder filtrar restaurante por  [avaliação](../../modelagem/lexicos/#lexico-02-avaliar)                                                                                  |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                       [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                        |
|          Tema           |                                                      [Pesquisas e Filtros para Visualização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                      |
|           US            |                                                                           [US25](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                            |
| Status da implementação |                                                                                            Requisito totalmente implementado                                                                                            |
|        Artefatos        | [UC03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/) <br> [C05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br>[iStar](../../modelagem/iStar/#32-pesquisa)|
|     Funcionalidade      |                                               <img src="../../assets/foward-from/rf25.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                               |

### RF26

|          RF26           |                                                                                 O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder ver estabelecimentos com promoções                                                                                 |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                       [Informações sobre Estabelecimentos](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                        |
|          Tema           |                                                      [Pesquisas e Filtros para Visualização](../../modelagem/backlog/#43-epico-informacoes-sobre-estabelecimentos)                                                      |
|           US            |                                                                           [US26](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                                                            |
| Status da implementação |                                                                                            Requisito totalmente implementado                                                                                            |
|        Artefatos        | [UC03](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso3/) <br> [C05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/cenarios/#caso-5-pesquisa-de-estabelecimentos) <br>[iStar](../../modelagem/iStar/#32-pesquisa) |
|     Funcionalidade      |                                               <img src="../../assets/foward-from/rf26.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">                                               |

### RF27

|          RF27           |                              O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder entrar na fila de espera do [estabelecimento](../../modelagem/lexicos/#lexico-12-estabelecimento) pelo app                              |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                    [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                     |
|          Tema           |                           [Fila de espera do restaurante](../../modelagem/backlog/#42-epico-restaurante)                            |
|           US            |                                 [US27](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                  |
| Status da implementação |                                                  Requisito totalmente implementado                                                  |
|        Artefatos        | [UC2](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-2-entrar-na-fila-de-espera) |
|     Funcionalidade      |     <img src="../../assets/foward-from/rf27.gif" alt="Requisito Funcional" width="180" height=auto title="Requisito Funcional">     |

### RF28

|          RF28           |                               O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve receber [notificações](../../modelagem/lexicos/#lexico-18-notificar) sobre o andamento da fila de espera                               |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                    [Restaurante](../../modelagem/backlog/#42-epico-restaurante)                                     |
|          Tema           |                           [Fila de espera do restaurante](../../modelagem/backlog/#42-epico-restaurante)                            |
|           US            |                                 [US28](../../modelagem/historiasDeUsuario/#3-historias-de-usuario)                                  |
| Status da implementação |                                                  Requisito totalmente implementado                                                  |
|        Artefatos        | [UC2](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/Diagramas/CasoDeUso2/#caso-de-uso-2-entrar-na-fila-de-espera) |

### RF30

|          RF30           |                                           O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder criar uma [comanda](../../modelagem/lexicos/#lexico-05-comanda) compartilhada                                            |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |               [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                |
|          Tema           |       [Fazer pedido no restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)        |
|           US            |            [US05](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/historiasDeUsuario/#3-historias-de-usuario)             |
| Status da implementação |                                                     Requisito totalmente implementado                                                     |
|     Funcionalidade      | <img src="https://user-images.githubusercontent.com/78981063/186289844-6ab8026e-274c-4684-956a-c9c502b2e245.png" width="180" height=auto> |

### RF31

|          RF31           |                                            O [usuário](../../modelagem/lexicos/#lexico-23-usuario) deve poder [pesquisar](../../modelagem/lexicos/#lexico-20-pesquisar) produtos no [cardápio](../../modelagem/lexicos/#lexico-03-cardapio)                                            |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |               [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)                |
|          Tema           |       [Fazer pedido no restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)        |
|           US            |                                                                   US04                                                                    |                                          |
| Status da implementação |                                                     Requisito totalmente implementado                                                     |
|     Funcionalidade      | <img src="https://user-images.githubusercontent.com/78981063/186290795-c83c8254-9e87-4ef9-a686-b4885e86dd15.gif" width="180" height=auto> |

## 5. Requisitos Não-Funcionais

### RNF01

|          RNF01          |                                        O sistema deve restringir a idade para uso do app                                        |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#32-sig-de-confiabilidade) |
|           ES            |       [Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#33-confiabilidade)        |
| Status da implementação |                                               Requisito parcialmente implementado                                               |

### RNF02

|          RNF02          |                                               O sistema deve ser responsivo                                               |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                                             -                                                             |

### RNF03

|          RNF03          |                 O sistema deve ser disponível para android versão 5.0 ou superior e IOS versão IOS 11 ou superior                 |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Suportabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#33-sig-de-suportabilidade) |
|           ES            |       [Suportabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#35-suportabilidade)        |
| Status da implementação |                                                 Requisito totalmente implementado                                                 |

### RNF04

|          RNF04          |                                       O sistema deve possuir uma interface gráfica                                        |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF05

|          RNF05          |                    O sistema deve ter um tempo de comunicação com o servidor de no máximo 4 segundos                    |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#33-sig-de-desempenho) |
|           ES            |       [Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#34-desempenho)        |
| Status da implementação |                                                            -                                                            |

### RNF06

|          RNF06          |                             O sistema deve garantir a privacidade e segurança dos dados do usuário                              |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#32-sig-de-confiabilidade) |
|           ES            |       [Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#33-confiabilidade)        |
|           iStar            |       [Conta](../../modelagem/iStar/#31-conta)        |
| Status da implementação |                                                Requisito totalmente implementado                                                |

### RNF07

|          RNF07          |                  O sistema deve permitir com que pagamentos sejam realizados com segurança                   |
| :---------------------: | :----------------------------------------------------------------------------------------------------------: |
|           NFR           | [Restaurante](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante) |
|           ES            |  [Pagamento](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/backlog/#42-epico-restaurante)  |
|           iStar            |  [Segurança](../../modelagem/iStar/#33-pedido)  |
| Status da implementação |                                      Requisito totalmente implementado                                       |

### RNF08

|          RNF08          |                                   O sistema deve ter integração com o sistema do restaurante                                    |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#32-sig-de-confiabilidade) |
|           ES            |       [Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#33-confiabilidade)        |
| Status da implementação |                                                Requisito totalmente implementado                                                |

### RNF09

|          RNF09          |                                      O sistema deve apresentar um design minimalista                                      |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF10

|          RNF10          |                                 O sistema não deve ficar fora do ar por mais de 4 horas                                 |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#33-sig-de-desempenho) |
|           ES            |       [Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#34-desempenho)        |
|           iStar            |  [Confiabilidade](../../modelagem/iStar/#33-pedido)  |
| Status da implementação |                                                            -                                                            |

### RNF11

|          RNF11          |                       O sistema deve permitir a navegação pelo app sem a necessidade de um cadastro                       |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF12

|          RNF12          |         A navegação pelo [cardápio](../../modelagem/lexicos/#lexico-03-cardapio)  dos restaurantes deve ser de fácil entendimento e mostrar imagens dos produtos          |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF13

|          RNF13          |                                      O pagamento pelo app deve ser simples e rápido                                       |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF14

|          RNF14          |                                  O sistema deve fornecer uma interface gráfica intuitiva                                  |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#31-sig-de-usabilidade) |
|           ES            |       [Usabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#32-usabilidade)        |
|           iStar            |       [Facilidade](../../modelagem/iStar/#32-pesquisa)        |
| Status da implementação |                                             Requisito totalmente implementado                                             |

### RNF15

|          RNF15          |                               O sistema deve ter um tempo de resposta de no máximo 100ms                                |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#33-sig-de-desempenho) |
|           ES            |       [Desempenho](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#34-desempenho)        |
| Status da implementação |                                            Requisito totalmente implementado                                            |

### RNF16

|          RNF16          |                             O sistema deve ter integração com o google e facebook para criar contas                             |
| :---------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|           NFR           | [SIG de Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/nfrframework/#32-sig-de-confiabilidade) |
|           ES            |       [Confiabilidade](https://requisitos-de-software.github.io/2022.1-Noruh/modelagem/especificacao/#33-confiabilidade)        |
| Status da implementação |                                                Requisito totalmente implementado                                                |

## Referencias

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. 1º/2022. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de versão

| Versão |                             Alteração                             |  Responsável   |    Revisor    |   Data   |      Hora      |
| :----: | :---------------------------------------------------------------: | :------------: | :-----------: | :------: | :------------: |
|  1.0   |                       Colocando RFs 1 ao 9                        | João Henrique  |    Eurico     | 22/08/22 | 16:00 às 17:00 |
|  1.1   |                 Colocando imagens aos RFs 1 ao 9                  | João Henrique  |    Eurico     | 23/08/22 | 10:00 às 11:30 |
|  1.2   |              Adição dos RFs 30 e 31 e NFs do 1 ao 7               | Karla Chaiane  |     Lucas     | 23/08/22 | 19:00 às 23:00 |
|  1.3   |                      Adição dos NFs 8 ao 16                       | Bruno Oliveira |     Lucas     | 24/08/22 | 11:00 às 11:30 |
|  1.4   | Adicionando artefatos à tabela e excluindo criterios de aceitação | João Henrique  |     Lucas     | 24/08/22 | 17:45 às 18:30 |
|  1.5   |                Adicionando as tabelas RF20 - RF29                 |     Eurico     | João Henrique | 24/08/22 | 18:00 às 18:30 |
|  1.6   |                Adicionando as tabelas RF09 - RF19                 |     Lucas      |    Eurico     | 24/08/22 | 18:00 às 19:30 |
|  1.7   |                     Finalizado os RF20 - RF29                     |     Eurico     | João Henrique | 24/08/22 | 19:00 às 20:00 |
|  1.8   |                        Finalizado os RNFs                         |     Bruno      | João Henrique | 24/08/22 | 19:00 às 20:10 |
|  1.9   |                   Adiciona hyperlinks léxicos e iStar                   |     Lucas      | João Henrique | 7/09/22 | 16:00 às 16:40 |
|  1.10   |                   Adiciona gif protótipo RF23                   |     Lucas      | - | 8/09/22 | 17:50 às 18:00 |
