# Cenarios

## 1.Introdução
&emsp;&emsp;A criação de Cenários na modelagem de requisitos, é uma etapa importante e de grande valor. A modelagem de requisitos por Cenários, é utilizada como uma forma de compreender melhor, as interações entre o usuário e sistema , buscando dessa forma obter uma descrição completa de uma atividade que o usuário utiliza.
## 2.Metodologia

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -             |
| **Contexto**         |              -             |
| **Atores**           |              -             |
| **Recursos**         |              -             |
| **Exceção**          |              -             |
| **Episódios**        |              -             |
| **Rastreabilidade**  |              -             |

## 3.Cenarios

### Caso 1: Criar perfil

| Elementos |                Respostas             |
|:------:|:---------------------------------------:|
| **Objetivo**         |               -Usuário do Noruh criar uma conta            |
| **Contexto**         |- Local: Tela de inicio no ícone da sua conta, ou logo depois que baixou na tela de inicio;<br> - Tempo: 1 a 3 minutos;<br> - Pré-condição: Possuir acesso a internet.              |
| **Atores**           |             -Usuário do Noruh               |
| **Recursos**         |             -Dispositivo com acesso à internet;<br>-Dispositivo com bateria <br>-dispositivo suportado pelo Noruh              |
| **Exceção**          |             -Queda de energia; <br>-falta de internet              |
| **Episódios**        |              -Ao abrir o aplicativo pela primeira vez o usuário clica no login pelo Facebook(ou google ou email); <br>-Usuário clica e coloca sua senha; <br>-Usuário lê e aceita os termos de uso;<br>-Usuário clica e adiciona suas informações e cria o perfil      |
| **Rastreabilidade**  |           RF1, RF2, RF8             |

### Caso 2: Logout no perfil

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -Usuário do Noruh deslogar e criar outra conta             |
| **Contexto**         |              -Local: Tela de início no ícone da sua conta;<br> - Tempo: 2 a 4 minutos;<br>-Pré condição: Possuir acesso à internet            |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>Dispositivo com bateria;-Dispositivo suportado pelo Noruh            |
| **Exceção**          |              -Queda de energia; <br>-falta de internet;<br>-Dispositivo não suporta o Noruh              |
| **Episódios**        |              - Na tela inicial usuário clica na sua conta no canto superior esquerdo;<br>- Usuário clica em "Sair" da conta;<br>- Usuário clica em cadastrar nova conta pela conta Google;<br>Usuário clica em aceitar os termos e condições;<br>-Usuário coloca seus dados;<br>Usuário cria a conta            |
| **Rastreabilidade**  |             -RF1, RF2, RF8, RF14             |

### Caso 3: Cadastrar endereço

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -O usuário deve poder cadastrar endereços no aplicativo             |
| **Contexto**         |              -Local: No perfil do usuário "Endereços";<br>-Tempo: 1 a 3 minutos;<br>-Pré condição: A pessoa ter acesso à internet             |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br>-Dispositivo ter acesso à localização            |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet;<br>-Dispositivo não ter acesso à localização            |
| **Episódios**        |              -Usuário clica no botão de perfil no superior esquerdo da tela inicial;<br>-Usuário clica em "Endereços";<br>-Usuário clica em "+", para adicionar endereço;<br>-Usuário adiciona informações do endereço;<br>-Usuário salva o endereço             |
| **Rastreabilidade**  |              -RF16             |

### Caso 4: Cadastrar forma de pagamento

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -O usuário deve poder cadastrar uma forma de pagamento no aplicativo            |
| **Contexto**         |              -Local: No perfil do usuário "Formas de pagamento";<br>-Tempo: 1 a 3 minutos;<br>-Pré condição: A pessoa ter acesso à internet             |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br>- Ter uma forma de pagamento             |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet;<br>-Não ter uma forma de pagamento             |
| **Episódios**        |              -Usuário clica no botão de perfil no superior esquerdo da tela inicial;<br>-Usuário clica em "Formas de pagamento";<br>-Usuário clica em "+", para adicionar forma de pagamento;<br>-Usuário adiciona informações do seu cartão de crédito;<br>-Usuário salva seu cartão no aplicativo              |
| **Rastreabilidade**  |              -RF18             |

### Caso 5: Pesquisa de estabelecimentos

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              Usuário do Noruh deve poder fazer pesquisas para decidir o estabelecimento desejado             |
| **Contexto**         |              -Local: Tela inicial do aplicativo;  <br>-Tempo:3 a 8 minutos;<br>-Pré condição: A pessoa ter acesso à internet           |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br> O aplicativo possuir acesso à sua localização           |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>Falta de internet;            |
| **Episódios**        |              -Usuário abre o aplicativo;<br>-Usuário clica no filtro "aberto agora";<br>Usuário clica no filtro "Destaques";Usuário clica no filtro "Descontos";Usuário clica no filtro "cozinhas" e seleciona a desejada;<br>Usuário clica no filtro "Próximos a você";<br>Após toda a pesquisa, o usuário escolhe o esabelecimento que mais o agradou      |
| **Rastreabilidade**  |              -RF9,RF15, RF21, RF24, RF28, RF29, RF30, RF31, RF32             |

### Caso 6: Formas de pagamento

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              Usuário do Noruh poder escolher sua forma de pagamento preferida para a compra             |
| **Contexto**         |              -Local: Tela de confirmação do pedido;<br>-Tempo:1 a 4 minutos;<br>-Pré condição: A pessoa ter acesso à internet e a uma forma de pagamento           |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br> O usuário ter uma forma de pagamento             |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet;<br>-Falta de uma forma de pagamento             |
| **Episódios**        |              -Usuário abre o aplicativo; <br>Usuário clica em seu perfil no botão superior esquerdo;<br>Usuário clica em "formas de pagamento";<br>Usuário adiciona seu cartão de crédito;<br>Usuário volta pra tela de início;<br>Usuário escolhe o restaurante desejado;<br>Usuário faz o pedido para comer no local;<br>Usuário escolhe a forma de pagamento parcelada no cartão de crédito;<br>Usuário faz o pagamento pelo cartão de crédito cadastrado;<br>-O usuário recebe a nota fiscal;<br>Usuário recebe o pedido;<br>-Usuário avalia o pedido            |
| **Rastreabilidade**  |              -RF4, RF5, RF6, RF7, RF12, RF17, RF18, RF19, RF25, RF26, RF27     |

### Caso 7: Edição do perfil 


| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -Usuário do Noruh poder mudar suas informações do perfil            |
| **Contexto**         |              -Local: Tela do perfil;<br>-Tempo: 1 a 3 minutos;<br>-Pré condição: A pessoa ter acesso à internet            |
| **Atores**           |              Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh             |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet;             |
| **Episódios**        |              -Usuário clica no botão superior esquerdo do perfil na página inicial;<br>-Usuário clica em "Editar perfil";<br>-Usuário muda a informação desejada;<br>-Usuário clica em "Salvar            |
| **Rastreabilidade**  |              RF6             |

### Caso 8: Escolha da cidade

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              -O usuário deve poder escolher a cidade que prefere das que o Noruh possui acesso             |
| **Contexto**         |              Local: Ao lado da lupa no canto superior direito da tela inicial;<br>Tempo:3 a 10 segundos;<br>-Pré condição: A pessoa ter acesso à internet             |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh             |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet             |
| **Episódios**        |              -Usuário clica no botão de mudar a cidade;<br>Usuário escolhe Brasília(ou qualquer outra que o Noruh possui acesso)             |
| **Rastreabilidade**  |              RF15             |

### Caso 9: Pedido delivery

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              Usuário do Noruh fazer pedidos delivery            |
| **Contexto**         |              -Local: Tela do restaurante selecionado;<br>-Tempo: 1 a 4 minutos; <br> -Pré condição: A pessoa ter como pagar, ter acesso à internet e energia(bateria) no seu dispositivo              |
| **Atores**           |              Usuário do Noruh            |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br>-Possuir uma forma de pagamento;<br>-O aplicativo possuir acesso à sua localização            |
| **Exceção**          |              -Falta de energia(bateria);<br>-Falta de internet;<br>-Falta de forma de pagamento;<br>-O aplicativo não ter acesso à sua localização            |
| **Episódios**        |              -Usuário pesquisa e clica no botão do estabelecimento desejado;<br>-Usuário clica no botão para abrir a comanda por Qr code ou outra forma;<br>-Usuário clica e escolhe o produto;<br>-Usuário clica no botão de entrega;<br>-Usuário cadastra seu endereço de entrega;<br>-Usuário clica na forma de pagamento e escolhe cartão de crédito salvo na conta;<br>-Usuário confirma o pedido;<br>-O usuário recebe a nota fiscal; Usuário recebe informações sobre sua entrega via Ifood            |
| **Rastreabilidade**  |       RF4, RF5, RF7, RF12, RF16, RF19, RF20, RF22,                  |


### Caso 10: Pedido no estabelecimento

| Elementos |                Respostas              |
|:------:|:----------------------------------------:|
| **Objetivo**         |              Usuário do Noruh fazer pedidos no estabelecimento pelo aplicativo             |
| **Contexto**         |              -Local: Tela do restaurante selecionado;<br>-Tempo: 1 a 5 minutos;<br>-Pré condição: A pessoa ter como pagar, ter acesso à internet e ter bateria em seu dispositivo           |
| **Atores**           |              -Usuário do Noruh             |
| **Recursos**         |              -Dispositivo com acesso à internet;<br>-Dispositivo suportado pelo Noruh;<br>-Possuir uma forma de pagamento;<br>            |
| **Exceção**          |              -Falta de bateria no dispositivo;<br>-Falta de internet;<br>-Falta de uma forma de pagamento             |
| **Episódios**        |              -Usuário clica no restaurante em que se encontra;<br>O usuário clica em "Abrir comanda por qr code" ou "Retirar no balcão";<br>O usuário clica escolhe o produto de sua escolha do restaurante;<br>O usuário adiciona no carrinho;<br> O usuário escolhe a forma de pagamento para pagar no estabelecimento e faz o pedido para consumir no estabelecimento;<br>-O usuário recebe a nota fiscal           |
| **Rastreabilidade**  |              RF3, RF4, RF5, RF7, RF12, RF17, RF19             |


## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  |                    -                   |    João Henrique  |  Eurico, Karla, Bruno, Lucas | 16/07 |
|   1.1  |            Melhora da Introdução       |    João Henrique  |  Eurico, Karla, Bruno, Lucas | 17/07 |

## Referências
- http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf
- http://pes.inf.puc-rio.br/cel/index_old.htm
