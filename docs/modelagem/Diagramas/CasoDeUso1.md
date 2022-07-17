# Fluxo de Conta

## Diagrama 

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="500" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FR4iYxZgfl8foolUpTcSHZo%2FUntitled%3Fnode-id%3D0%253A1" allowfullscreen></iframe>

<figcaption align='center'>
    <b>Figura 1: Diagrama de casos de uso</b>
</figcaption>

## Casos de Uso

### Caso de Uso 1 - Criar Conta

<center>

| UC01 | Informações | 
| :----: | :------:|
| Descrição | O usuário cria uma conta no app |
| Pré-condições | Acesso à internet e um dispositivo válido |
| Ator | <ul><li>Usuário novo</li> <li>Serviço de verificação de dados</li></ul> |
| Fluxo principal | <ul><li>O usuário acessa o app</li><li>O usuário seleciona a opção de criar uma conta</li><li>O usuário aceita os termos de uso</li><li>O usuário fornece seus dados</li></ul> |
| Fluxo Secundário | <ul><li>O usuário acessa o app</li><li>O usuário seleciona a opção de criar uma conta</li><li>O usuário aceita os termos de uso</li><li>O usuário fornece seus dados pessoais</li><li>O usuário fornece seus dados bancários</li></ul> |
| Fluxo De Exceção | <ul><li>O usuário acessa o app</li><li>O usuário seleciona a opção de criar uma conta</li><li>O usuário não aceita os termos de uso</li><li>O usuário é barrado de criar uma conta</li></ul> |
| Pós-condições | O usuário poderá realizar login em sua conta |

</center>

<figcaption align='center'>
    <b>Tabela 1: caso de uso 1</b>
</figcaption>

### Caso de Uso 2 - Fazer login na conta

<center>

| UC02 | Informações | 
| :----: | :------:|
| Descrição | O usuário acessa sua conta no app |
| Pré-condições | Acesso à internet e uma conta registrada no app |
| Ator | <ul><li>Usuário registrado</li> <li>Serviço de verificação de dados</li></ul> |
| Fluxo principal | <ul><li>O usuário acessa o app</li><li>O usuário seleciona a opção de fazer login</li><li>O usuário informa seu e-mail e senha válidos</li><li>O usuário acessa tela principal do sistema</li></ul> |
| Fluxo De Exceção | <ul><li>O usuário acessa o app</li><li>O usuário seleciona a opção de fazer login</li><li>O usuário informa seu e-mail e senha inválidos</li><li>Mensagem de erro aparece na tela</li><li>O usuário é barrado de acessar a conta</li></ul> |
| Pós-condições | O usuário terá acesso as demais funcionalidades do app |

</center>

<figcaption align='center'>
    <b>Tabela 2: caso de uso 2</b>
</figcaption>

### Caso de Uso 3 - Editar conta

<center>

| UC03 | Informações | 
| :----: | :------:|
| Descrição | O usuário acessa a tela de edição de conta e altera seus dados cadastrados |
| Pré-condições | Acesso à internet e uma conta registrada no app |
| Ator | <ul><li>Usuário registrado</li> <li>Serviço de verificação de dados</li></ul> |
| Fluxo principal | <ul><li>O usuário acessa sua conta no app</li><li>O usuário seleciona a opção de editar conta</li><li>O usuário altera seus dados</li><li>O usuário volta para a tela principal do sistema</li></ul> |
| Fluxo Secundário | ul><li>O usuário acessa sua conta no app</li><li>O usuário seleciona a opção de editar conta</li><li>O usuário altera seus dados com informações válidas</li><li>O usuário adiciona dados bancários válidos</li><li>O usuário volta para a tela principal do sistema</li></ul> |
| Pós-condições | O usuário terá seus dados cadastrais alterados |

</center>

<figcaption align='center'>
    <b>Tabela 3: caso de uso 3</b>
</figcaption>

### Caso de Uso 4 - Fazer logout da conta

<center>

| UC04 | Informações | 
| :----: | :------:|
| Descrição | O usuário faz logout de sua conta no app |
| Pré-condições | Acesso à internet e estar logado em uma conta no app |
| Ator | <ul><li>Usuário cadastrado</li></ul> |
| Fluxo principal | <ul><li>O usuário selciona a opção de fazer logout de sua conta</li><li>O usuário volta para a tela de login/cadastro</li></ul> |
| Pós-condições | O usuário terá que fazer login ou criar nova conta para voltar a acessar o app |

</center>

<figcaption align='center'>
    <b>Tabela 3: caso de uso 3</b>
</figcaption>

## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  |                    -                   |    Lucas |  | 17/07 |