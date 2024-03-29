# Observação

## 1. Introdução

&emsp;&emsp; A observação é uma técnica de elicitação de requisitos onde o engenheiro observa no próprio ambiente que o software será implantado, as tarefas sendo executadas, onde se obtém os requisitos, analisando essas tarefas.

## 2. Metodologia

&emsp;&emsp; Para a realização desta técnica, o integrante do grupo Lucas acompanhou dois usuários do app, Matheus Zacarias e Eduardo Luiz, até um o restaurante Spot Bar & Burguers cadastrado no aplicativo Noruh, para que desta forma pudesse observá-los enquanto faziam tarefas no sistema. Vale ressaltar que Matheus já era um usuário já cadastrado do app Noruh e Eduardo era um novo usuário.

&emsp;&emsp; Com o objetivo de evidenciar nossas observações pedimos para que usuários gravassem a tela de seus celulares enquanto faziam o uso do app e eles aceitaram o pedido, além disso, permitiram que utilizássemos estes vídeos no trabalho.

&emsp;&emsp; Além disso, para que pudessemos extrair o máximo desta técnica sem que exigíssimos demais dos usuários que concordaram em colaborar, os próprios membros do grupo se reuniram em uma chamada no Discord e simularam o uso do app, assim nos permitindo encontrar novas funcionalidades.

## 3. Vídeos Usuários

### 3.1 Usuário já cadastrado

&emsp;&emsp; Como sugestão de tarefa, foi solicitado que o usuário entrasse no sistema, criasse uma comanda e pedisse uma água. Abaixo segue o vídeo da execução da tarefa:

<center>
<iframe width="320" height="560" src="https://www.youtube.com/embed/fDbP7QnnVHs" title="Usuário Já Cadastrado realizando tarefa | App Noruh | Requisitos de Software UnB" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<figcaption align='center'>
    <b>Vídeo 1: Usuário já cadastrado realizando tarefa</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>

### 3.1 Novo usuário

&emsp;&emsp; Como sugestão de tarefa, foi solicitado que ele criasse uma conta e entrasse na mesma comanda que o outro usuário. Podemos ver a realização da tarefa pelo vídeo abaixo.

<center>
<iframe width="320" height="560" src="https://www.youtube.com/embed/fDbP7QnnVHs" title="Usuário Já Cadastrado realizando tarefa | App Noruh | Requisitos de Software UnB" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<figcaption align='center'>
    <b>Vídeo 2: Novo usuário realizando tarefa</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>

## 4. Resultados

&emsp;&emsp; A partir das ideias discutidas, chegamos aos seguintes requisitos que não haviam sido levantados:

|  ID   |                              Requisitos Funcionais                               |
| :---: | :------------------------------------------------------------------------------: |
| OBS01 |                   O usuário deve poder fazer logout do perfil                    |
| OBS02 |           O usuário deve poder adicionar multiplas formas de pagamento           |
| OBS03 | O usuário deve poder selecionar a cidade em que deseja buscar restaurantes/bares |
| OBS04 |              O usuário deve poder cadastrar endereços para entregas              |
| OBS05 |    O usuário deve poder entrar na fila de espera do estabelecimento pelo app     |
| OBS06 |     O usuário deve receber notificações sobre o andamento da fila de espera      |
| OBS07 |   O usuário deve poder ter a opção de parcelar seus pagamentos quando possível   |
| OBS08 |                O usuário deve receber um tutorial no primeiro uso                |
| OBS09 |               O usuário deve poder criar uma comanda compartilhada               |
| OBS10 |               O usuário deve poder pesquisar produtos no cardápio                |

<figcaption align='center'>
    <b>Tabela 1: Requisitos Funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

|  ID   |                                        Requisitos Não Funcionais                                         |
| :---: | :------------------------------------------------------------------------------------------------------: |
| OBS11 |              O sistema deve permitir a navegação pelo app sem a necessidade de um cadastro               |
| OBS12 | O navegação pelo cardápio dos restaurantes deve ser de fácil entendimento e mostrar imagens dos produtos |
| OBS13 |                              O pagamento pelo app deve ser simples e rápido                              |
| OBS14 |                     O sistema deve ter um tempo de resposta de no máximo 2 segundos                      |
| OBS15 |                 O sistema deve ter integração com o google e facebook para criar contas                  |

<figcaption align='center'>
    <b>Tabela 2: Requisitos Não Funcionais  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## Referências

- AURUM, Aybuke; WOHLIN, Claes. Engineering and Managing Software Requirements. Springer, 2005

## Histórico de Versão

| Versão |                   Alteração                    |            Responsável             | Revisor | Data  |
| :----: | :--------------------------------------------: | :--------------------------------: | :-----: | :---: |
|  1.0   |                       -                        | João Henrique, Bruno, Karla, Lucas | Eurico  | 09/07 |
|  2.0   | Adiciona videos de usuários e novos requisitos |               Lucas                |  João   | 02/08 |
|  2.1   |               Documento revisado               |                João                |    -    | 02/08 |
|  2.2   |           Corrige IDs dos requisitos           |               Lucas                |  João   | 30/08 |
