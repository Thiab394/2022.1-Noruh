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
- O sistema deve ser fácil de aprender.
- O sistema deve ser fácil de se usar.
### 3.3 Desempenho
- O sistema deve ter um tempo de resposta de no máximo 100ms.
- O sistema não pode sobrecarregar o dispositivo do usuário.
- As buscas dentro do sistema não podem ultrapassar os 3 segundos.
### 3.4 Suportabilidade
- O sistema tem que estar disponível na PlayStore (android) e na AppStore (Apple).
- O sistema tem que suportar 10 mil usuários simultâneos.
- O sistema deve suportar o cadastro de 1 milhão de usuários.
### 3.5 Design
- O sistema deve seguir uma paleta de cores pré definida
### 3.6 Implementação
- O sistema deve ser compativel com android e IOS.
- O sistema não deve ocupar mais que 20mb.
### 3.7 Interface
- A interface deve ter um padrão em todas as telas para facilitar o uso e entendimento do usuário.
- A interface deve ser responsiva.
### 3.8 Físico
- O dispositivo Android deve estar na versão 8.0 ou superior.
- O dispositivo IOS deve estar na versão IOS 11 ou superior.

## 4. Referências
- FURPS+ [https://qualidadebr.wordpress.com/2008/07/10/furps/], acesso em 17 de julho de 2022
- Eberlein, Armin; [Agile Requirements Definition: A View from Requirements Engineering]

## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  | Criação do documento           |    Eurico  | - | 17/07 |
