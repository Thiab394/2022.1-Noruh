# NFR Framework

## 1. Introdução
<p>&emsp;&emsp;Criado por (CHUNG et al., 2000), o framework NFR, foi admitido por propor uma abordagem especifica para o processamento de requisitos nao funcionais e fornecer uma profunda representacao para expressar esses requisitos, alem das relacoes e correlacoes entre os mesmos.</p>
<p>&emsp;&emsp;Os requisitos nao funcionais representados pelo framework NFR, sao normalmente expressados atraves de um grafo SIG. E o seu principal objetivo e ajudar os desenvolvedores na implementacao de solucoes personalizadas.</p>
<p>&emsp;&emsp;Leva em consideracao algumas caracteristicas do dominio e do sistema, sendo elas:</p>

 * Requisitos nao funcionais
 * Requisitos funcionais
 * Prioridades e carga de trabalho

## 2. Legendas
### 2.1 Softgoals
<p>&emsp;&emsp;Softgoals sao objetivos que não possuem uma clara definição nem critérios de satisfação precisos.</p>

 * Softgoals NFR
 * Softgoals de Operacionalização
 * Softgoals de Afirmação
  
![Fonte: (CHUNG et al., 2000)](/docs/assets/nfr/tipos-softgoal2.png)
<p>Fonte: (CHUNG et al., 2000)</p>

### 2.2 Decomposições
<p>&emsp;&emsp;As decomposições refinam os softgoals para obter softgoals mais especializados, de forma que estes possam auxiliar na construção do projeto.</p>

 * Decomposição de Softgoal NFR
 * Decomposição de Operacionalização
 * Decomposição de Afirmação (Claims)
 * Priorização

![Fonte: (CHUNG et al., 2000)](/docs/assets/nfr/tipos-decomposicao.png)
<p>Fonte: (CHUNG et al., 2000)</p>

### 2.3 Contribuições
<p>&emsp;&emsp;Quando um softgoal descendente contribui de forma total ou parcial, e de forma positiva ou negativa, para a satisfação de um softgoal ascendente</p>

![Fonte: (CHUNG et al., 2000)](/docs/assets/nfr/contribuicao.png)
<p>Fonte: (CHUNG et al., 2000)</p>

![Fonte: (CHUNG et al., 2000)](/docs/assets/nfr/contribuicao2.png)
<p>Fonte: (CHUNG et al., 2000)</p>

### 2.4 Rótulos
<p>&emsp;&emsp;Os rótulos sao graus de satisfacao, determinados a partir de um processo de avaliacao.</p>

![Fonte: (CHUNG et al., 2000)](/docs/assets/nfr/rotulos.png)
<p>Fonte: (CHUNG et al., 2000)</p>

## 3. Referências
- NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados [Reinaldo Antônio da Silva; Universidade Federal de Pernambuco; 2019]

## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  | Criação do documento           |    Eurico  | - | 31/07 |
|   1.1  | Adicao do conteudo (introducao, legendas, referencias e historico de versao)           |    Eurico  | - | 01/08 |