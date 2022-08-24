# Histórias de usuário

## 1- Introdução
&emsp;&emsp; Em Agile, a técnica de Histórias de usuário, é utilizada para se fazer uma breve descrição, com linguagem simples, e informal, do que um certo usuário quer fazer com o produto de software.Nessas histórias de usuário, utilizaremos os usuários, baseados nas personas que foram criadas na elicitação de requisitos.

## 2- Metodologia

&emsp;&emsp; Para a elaboração das Histórias de Usuários, a equipe utilizou na técnica de role playing, para que desta forma pudessemos simular a participação de um usário real do sistema. Nesta técnica, os integrantes Eurico e João Henrique tiveram uma conversa com a integrante Karla que estava interpretando a [persona](../elicitacao/personas.md) Julia. Podemos ver esta interação a partir do vídeo abaixo:

<center>
<iframe width="942" height="530" src="https://www.youtube.com/embed/Vs2QrBwkFas" title="Role playing História de Usuário | Requisitos de Software UnB" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<figcaption align='center'>
    <b>Vídeo 1: Role playing</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>

&emsp;&emsp;Também definimos como padrão de formtado da história o seguinte modelo: 
<center>
** Eu, como um usuário, gostaria de < OBJETIVO >, para poder < UMA RAZÃO > **
</center>

## 3- Histórias de usuário

| Número | Rastreabilidade | História de usuário| Prioridade(MoscoW)| Criterios de Aceitação |
| :------: | :------------------------------------------------:|:--------:|:--------:|:----------:|
| US01 | RF1 | Eu, como um usuário, gostaria de criar uma conta no Noruh para poder ter acesso às funcionalidades do aplicativo.| Must|-Deve ter email/conta facebbok/conta google|
| US02 | RF2 | Eu, como um usuário, gostaria de realizar login na minha conta, para poder acessar e fazer pedidos.| Must|-Deve ser possivel com conta facebook/google;<br> -Deve ser de fácil compreensão, e rápido.|
| US03 | RF3 | Eu, como um usuário, gostaria de fazer pedidos, para poder com meu celular, pedir a minha comida no restaurante. | Must|-Deve ser feito para todo restaurante cadastrado;<br>-Deve ser feito após clicar no restaurante escolhido;|
| US04 | RF4 | Eu, como um usuário, gostaria de poder acessar o cardápio do restaurante, para poder escolher o meu pedido.| Must|-Deve ser feito para todo restaurante cadastrado;<br>-Deve ser mostrado após clicar no restaurante selecionado em "abrir comanda"|
| US05 | RF5 | Eu, como um usuário, gostaria de abrir a comanda por um QR code, para poder dessa forma mais prática escolher meu pedido.| Must|-Estar na tela inicial do aplicativo;<br>|
| US06 | RF6 | Eu, como um usuário, gostaria de editar o meu perfil , para poder mudar informações da minha conta.| Must|-Estar na parte de perfil no canto superior esquerdo;|
| US07 | RF7 | Eu, como um usuário, gostaria de pesquisar restaurantes no aplicativo, para poder escolher o restaurante de minha preferência.| Must|-Estar na lupa no canto superior direito da pagina inicial;<br>-Poder pesquisar por categoria.|
| US08 | RF8 | Eu, como um usuário, gostaria de ter acesso aos termos de uso, para poder analisar as informações que o aplicativo utiliza.| Must|-Ter acesso no momento em que cria a conta no aplicativo.|
| US09 | RF9 | Eu, como um usuário, gostaria de ver as localizações dos estabelecimentos, para poder chegar ao restaurante com o GPS.| Must|-Ter acesso ao clicar no restaurante selecionado.|
| US10 | RF10 | Eu, como um usuário, gostaria de cadastrar múltiplos endereços, para poder salvar no aplicativo caso eu precise.| Must|-Conseguir cadastrar na parte do seu perfil no canto superior esquerdo da tela inicial.|
| US11 | RF11 | Eu, como um usuário, gostaria de fazer logout no meu perfil, para poder fazer login com outro perfil no meu celular.| Must|-Conseguir desconectar da sua conta na parte do perfil no canto superior esquerdo da tela inicial.|
| US12 | RF12 | Eu, como um usuário, gostaria de selecionar uma cidade, para poder buscar bares/restaurantes perto da minha localização.| Must|-Perguntar quando abrir o aplicativo pela primeira vez;<br>-Conseguir trocar a cidade no canto superior direito ao lado da lupa.|
| US13 | RF13 | Eu, como um usuário, gostaria de selecionar solicitar a conta, para poder realizar o pagamento de outra forma fora do app.| Must|-Ser feito isso através da comanda feita, podendo escolher a forma de pagamento desejada.|
| US14 | RF14 | Eu, como um usuário, gostaria de cadastrar cartões de crédito/débito, para poder acessá-los de forma rápida e prática.| Should|-Poder cadastrar na parte do perfil no canto superior esquerdo da tela inicial;<br>-Poder cadastrar ao precisar pagar a conta em algum estabelecimento.|
| US15 | RF15 | Eu, como um usuário, gostaria de realizar pagamentos, para poder concluir o pedido e fechar a comanda.| Should|-Poder realizar pagamento pelo app após fechar a comanda, e pagar o valor necessário.|
| US16 | RF16 | Eu, como um usuário, gostaria de ver restaurantes abertos, para poder identificar quais lugares estão em serviço no horário atual.| Should|-Sinalizar os restaurantes que estão abertos e fechados na pagina inicial;<br>-Sinalizar quando clicar no restaurante se ele está aberto no momento;<br>-Na tela inicial ter um botão "aberto agora" para os restaurantes abertos.|
| US17 | RF17 | Eu, como um usuário, gostaria de receber notificações do pedido, para poder ficar atualizado sobre o andamento do pedido.| Should|-Após fazer um pedido, receber notificações sobre o andamento dele no celular(notificações do Noruh precisa estar permitido nas configurações do celular).|
| US18 | RF18 | Eu, como um usuário, gostaria de acessar o histórico de contas, para poder verificar informações sobre contas anteriores.| Should|-Conseguir acessar o histórico de contas na parte superior esquerda do perfil nas "ultimas contas".|
| US19 | RF19 | Eu, como um usuário, gostaria de ver descrições sobre os bares/restaurantes, para poder verificar informações mais detalhadas sobre o estabelecimento.| Should|-Após clicar no restaurante selecionado, ele ter uma descrição detalhada sobre como é, o que oferece,..., para o cliente saber o que o espera.|
| US20 | RF20 | Eu, como um usuário, gostaria de adicionar múltiplas formas de pagamento, para poder escolher entre diferentes opções ao realizar o pagamento.| Should|-Conseguir adicionar mais de uma forma de pagamento na hora da compra;<br>-Conseguir salvar mais de um cartão de crédito no seu perfil para usar o de sua escolha.|
| US21 | RF21 | Eu, como um usuário, gostaria de parcelar pagamentos, para poder realizar o pagamento em parcelas ao invés de à vista.| Should|-Na hora do pagamento da comanda, ter a opção de dividir o pagamento no cartão, e não pagar apenas a vista.|
| US22 | RF22 | Eu, como um usuário, gostaria de filtrar bares/restaurantes pela localização, para poder escolher o local de acordo com minha necessidade.| Could|-Na tela inicial ter um botão "proximos a você", para poder mostrar os restaurantes mais próximos(precisa dar acesso ao aplicativo à sua localização atual).|
| US23 | RF23 | Eu, como um usuário, gostaria de avaliar bares/restaurantes, para poder dar opiniões sobre minha experiência no estabelecimento.| Could|-Após comparecer ao estabelecimento, o usuário poder avaliar o que achou do restaurante.|
| US24 | RF24 | Eu, como um usuário, gostaria de filtrar bares/restaurantes por categoria, para poder especificar qual tipo de especialidade eu desejo.| Could|-Após clicar na lupa de pesquisa da página inicial, ter como filtrar os estabelecimentos por especialidade/ o que ele vende, para o que a pessoa deseja.|
| US25 | RF25 | Eu, como um usuário, gostaria de filtrar bares/restaurantes por avaliação, para poder ter uma noção da qualidade do estabelecimento.| Could|-Na parte de pesquisa, mostrar os estabelecimentos mais bem avaliados;<br>-Mostrar a avaliação ao clicar nos restaurantes;<br>-Mostrar os melhores avaliados no botão "Destaques" da página inicial.|
| US26 | RF26 | Eu, como um usuário, gostaria de ver bares/restaurantes com promoções, para poder economizar ao frequentar um estabelecimento.| Could|-Na página inicial, mostrar os restaurantes que estão com desconto no botão "descontos".|
| US27 | RF27 | Eu, como um usuário, gostaria de entrar na fila de espera dos bares/restaurantes, para poder esperar minha vez de ser atendido.| Could|-Ter a opção de esperar ser atendido por um restaurante ao clicar nele.|
| US28 | RF28 | Eu, como um usuário, gostaria de receber notificações sobre a fila de espera, para poder me manter atualizado sobre a situação da fila.| Could|-Receber notificações sobre a fila de espera(precisa permitir as notificações ao aplicativo Noruh)|
| US29 | RF29 | Eu, como um usuário, gostaria de ter acesso a um tutorial, para poder facilitar o uso do aplicativo.| Could|-Receber um tutorial no primeiro uso.|

## 4. Referências

- https://aprender3.unb.br/pluginfile.php/2124496/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf

## Histórico de Versão

| Versão |      Alteração      | Responsável |           Revisor            |   Data   | Hora  |
| :----: | :-----------------: | :---------: | :--------------------------: | :------: | :------: |
|  1.0   |          -          |    João Henrique    |      Eurico, Lucas                | 29/07/22 |09:50 às 11.30 |
|  1.0.1   |Arrumando tabelas  |    João Henrique    |      Eurico, Lucas                | 29/07/22 |09:50 às 11.30 |
|  1.1   | Incluindo História de Usuários  |    Karla Chaiane    |    Eurico, Lucas      | 02/07/22 | 20:00 às 22:30 |
|  2.0   | Adicionando criterios de avaliação  |    João Henrique    |    Lucas      | 05/07/22 | 11:30 às 12:30|    
|  2.1   | Atualizando uma US  |    Eurico    |    Lucas      | 23/08/22 | 22:50 às 23:00|
