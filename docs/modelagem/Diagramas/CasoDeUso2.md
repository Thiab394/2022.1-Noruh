# Fluxo de Pedido

&emsp;&emsp; O diagrama de casos de uso do fluxo de pedidos pode ser encontrado abaixo:

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2Ff8m1NiBXcM9ZuMHtz4a1vq%2FFluxo-de-Pedidos-no-Restaurante%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

<figcaption align='center'>
    <b>Figura 1: Diagrama de casos de uso fluxo de pedidos</b>
    <br><small>Fonte: Elaboração Própia</small>
</figcaption>

## Casos de Uso

### Caso de Uso 1 - Fazer Pedido

<center>

| UC05 | Informações | 
| :----: | :------:|
| Descrição | O usuário faz um pedido sentado em uma mesa do restaurante |
| Pré-condições | Acesso à internet, ter uma conta cadastrada e estar em um restaurante diponível no app|
| Ator | <ul><li>Usuário cadastrado</li> <li>Banco</li> <li>Restaurante</li></ul> |
| Fluxo principal | <ul><li>O usuário acessa o app</li><li>O usuário faz login em sua conta</li><li>O usuário escanea QRCode na mesa</li><li>O usuário acessa o cardápio do restaurante</li><li>O usuário seleciona os itens que deseja pedir</li><li>O usuário confirma o pedido</li><li>O usuário recebe o pedido na mesa</li><li>O usuário escolhe uma forma de pagamento o pedido</li><li>O usuário faz o pagamento</li></ul> |
| Pós-condições | O usuário poderá fazer avaliações sobre o restaurante|

</center>

<figcaption align='center'>
    <b>Tabela 1: caso de uso 1</b>
     <br><small>Fonte: Elaboração Própia</small>
</figcaption>

### Caso de Uso 2 - Entrar na fila de espera

<center>

| UC06 | Informações | 
| :----: | :------:|
| Descrição | O usuário entra na fila de espera pelo app |
| Pré-condições | Acesso à internet, ter uma conta cadastrada|
| Ator | <ul><li>Usuário cadastrado</li> |
| Fluxo principal | <ul><li>O usuário acessa o app</li><li>O usuário faz login em sua conta</li><li>O usuário seleciona o restaurante</li><li>O usuário entra na fila de espera</li> <li>O usuário recebe uma notificação ao chegar sua vez</li>   |
| Pós-condições | O usuário poderá fazer leitura do QRCode da mesa e fazer pedido|

</center>

<figcaption align='center'>
    <b>Tabela 2: caso de uso 2</b>
     <br><small>Fonte: Elaboração Própia</small>
</figcaption>


## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  |                    Criação do documento                  |    Lucas | João Henrique | 17/07 |
|   1.1  |                   Documento Revisado                   |    João Henrique | - | 18/07 |
|   1.2  |                  Adiciona legendas e texto introdutório                   |    Lucas | - | 02/08 |
|   1.3  |                  Correções após a etapa de verificação                    |    Karla | - | 16/08 |    
