# NFR Framework

## 1. Introdução
<p>&emsp;&emsp;Como descritp por Silva (2019), o framework NFR (CHUNG et al., 2000), foi admitido por propor uma abordagem especifica para o processamento de requisitos não funcionais e fornecer uma profunda representação para expressar esses requisitos, além das relações e correlações entre os mesmos.</p>
<p>&emsp;&emsp;Os requisitos não funcionais representados pelo framework NFR, são normalmente expressados através de um grafo SIG, e o seu principal objetivo é ajudar os desenvolvedores na implementacao de soluções personalizadas.</p>
<p>&emsp;&emsp;O framework leva em consideração algumas características do domínio e do sistema, sendo elas:</p>

 * Requisitos não funcionais
 * Requisitos funcionais
 * Prioridades e carga de trabalho

## 2. Legendas
### 2.1 Softgoals
<p>&emsp;&emsp;Softgoals são objetivos que não possuem uma clara definição nem critérios de satisfação precisos.</p>

 * Softgoals NFR: Representam requisitos não funcionais
 * Softgoals de Operacionalização: Representam soluções de implementação para satisfazer softgoals NFR ou outras softgoals de operacionalização
 * Softgoals de Afirmação: Justificativas para apioar ou negar a forma como softgoals são priorizados

<center>
![Imagem softgoals](../assets/nfr/tipos-softgoal2.png)
</center>

<figcaption align='center'>
    <b>Figura 1: Representação gráfica softgoals</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

### 2.2 Decomposições
<p>&emsp;&emsp;As decomposições refinam os softgoals para obter softgoals mais especializados, de forma que estes possam auxiliar na construção do projeto.</p>

 * Decomposição de Softgoal NFR
 * Decomposição de Operacionalização
 * Decomposição de Afirmação (Claims)
 * Priorização

<center>
![Imagem softgoals](../assets/nfr/tipos-decomposicao.png)
</center>

<figcaption align='center'>
    <b>Figura 2: Representação gráfica tipos de decomposição</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

### 2.3 Contribuições
<p>&emsp;&emsp;Quando um softgoal descendente contribui de forma total ou parcial, e de forma positiva ou negativa, para a satisfação de um softgoal ascendente</p>

<center>
![Imagem softgoals](../assets/nfr/contribuicao.png)
</center>

<figcaption align='center'>
    <b>Figura 3: Representação gráfica contribuições make, break, help, hurt</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

<center>
![Imagem softgoals](../assets/nfr/contribuicao2.png)
</center>

<figcaption align='center'>
    <b>Figura 4: Representação gráfica contribuições Some, Unknown e equals</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

### 2.4 Rótulos
<p>&emsp;&emsp;Os rótulos sao graus de satisfacao, determinados a partir de um processo de avaliacao.</p>


<center>
![Imagem softgoals](../assets/nfr/rotulos.png)
</center>

<figcaption align='center'>
    <b>Figura 4: Representação gráfica rótulos</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

## 3. Gráficos de Interdependência de Softgoals (SIG)

### 3.1 SIG de Segurança

<center>
![Imagem softgoals](../assets/nfr/segurancav2.png)
</center>

<figcaption align='center'>
    <b>Figura 5: SIG de segurança</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>

### 3.1.1 SIG de Segurança com propagação

<center>
![Imagem softgoals](../assets/nfr/segurancaAvalicao.png)
</center>

<figcaption align='center'>
    <b>Figura 6: SIG de segurança com propagação</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>


## Referências
- NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados [Reinaldo Antônio da Silva; Universidade Federal de Pernambuco; 2019]

## Histórico de Versão

| Versão |                Alteração               | Responsável |         Revisor        |  Data |
|:------:|:--------------------------------------:|:-----------:|:----------------------:|:-----:|
|   1.0  | Criação do documento           |    Eurico  | Lucas | 31/07 |
|   1.1  | Adicao do conteudo (introducao, legendas, referencias e historico de versao)           |    Eurico  | Lucas | 01/08 |
|   1.2  | Correções gramáticais e em imagens e legendas           |    Eurico  | Lucas | 02/08 |