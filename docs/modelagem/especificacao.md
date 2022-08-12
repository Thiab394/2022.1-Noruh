# Especificação suplementar

## 1. Introdução
<p>&emsp;&emsp;A especificação suplementar é um documento em linguagem natural, constituído pela descrição dos requisitos não funcionais. Como a metodologia escolhida foi a FURPS+, as principais categorias de requisitos serão as seguintes: funcionabilidade, usabilidade, confiabilidade, suportabilidade e desempenho. Além desses, temos também os requisitos de design, de implementação, de interface e físicos.</p>

## 2. Metodologia
<p>&emsp;&emsp;A metodologia escolhida para a definição dos requisitos foi a FURPS+. Essa metodologia classifica os requisitos com os atributos de qualidade de software. A sigla FURPS+ representa essas classificações, sendo elas:</p>

* Funcionabilidade: representa o aspecto funcional do software
* Usabilidade: atributo que avalia a interface do usuário
* Confiabilidade: refere-se a integridade, conformidade e interoperabilidade do software
* Desempenho: requisitos de desempenho do software
* Suportabilidade: várias características, como por exemplo: testabilidade, adaptabilidade, manutenibilidade, compatibilidade entre outras

- O "+" na sigla FURPS+, é referente aos seguintes outros requisitos não funcionais:

* Design: especifica ou restringe o design de um sistema
* Implementação: especifica ou restringe o código ou a construção de um sistema
* Interface: especifica ou restringe as funcionalidades da interface do sistema com o usuário
* Físico: especifica uma limitação física do hardware

## 3. Especificação suplementar
### 3.1 Funcionalidade
&emsp;&emsp;Os requisitos funcionais podem ser encontrados nos casos de uso, ou então por esse [link](../modelagem/casosDeUso.md).

### 3.2 Usabilidade
- O sistema deve permitir a navegação pelo app sem a necessidade de um cadastro.
- A navegação pelo cardápio dos restaurantes deve ser de fácil entendimento e mostrar imagens dos produtos.
- O pagamento pelo app deve ser simples e rápido.
- O sistema deve fornecer uma interface gráfica intuitiva.
- O sistema deve fornecer uma interface responsiva.
- O sistema deve apresentar um design minimalista
- O aplicativo precisa de 42.5 mb de espaço para baixar no iphone e de 20 mb para baixar no android

### 3.3 Confiabilidade
- O sistema deve garantir a privacidade e segurança dos dados do usuário
- O sistema deve permitir com que pagamentos sejam realizados com segurança
- O sistema deve fornecer ao usuário segurança em caso de falhas e proteger o usuário e seus dados
- O sistema deve se manter ativo pelo maior tempo possível, com seus servidores ativos quase 100% do tempo, e em caso de quedas, ou manutenção do sistema, os usuários devem ser previamente informados.

### 3.4 Desempenho
- O sistema deve ter um tempo de resposta de no máximo 100ms.
- O sistema não deve ficar fora do ar por mais de 4 horas
- O sistema não pode sobrecarregar o dispositivo do usuário.
- As buscas dentro do sistema não podem ultrapassar os 4 segundos.
- O sistema não deve ocupar mais que 20mb.

### 3.5 Suportabilidade
- O sistema tem que estar disponível na PlayStore (android) e na AppStore (Apple).
- O sistema deve ser compativel com android versão 8.0 ou superior e IOS versão IOS 11 ou superior.

### 3.6 Requisitos de licenciamento
- O sistema do Noruh apresenta termos de uso e de privacidade para que o usuário concorde para a utilização do aplicativo. [Termo de Uso Duolingo](https://novo.noruh.com/Home/Politica?codigo=termosDeServico)




## 4. Referências
- FURPS+ [https://qualidadebr.wordpress.com/2008/07/10/furps/], acesso em 17 de julho de 2022
- Eberlein, Armin; [Agile Requirements Definition: A View from Requirements Engineering]

## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  | Criação do documento           |    Eurico  | Lucas | 17/07 |
|   1.1  | Documento revisado          |    Eurico  | Lucas | 18/07 |
|   2.0  | Correção após feedback do professor          |    Lucas  | - | 02/08 |
|   3.0  | Adicionando melhorias após inspeção          |    João Henrique  | - | 12/08 |
