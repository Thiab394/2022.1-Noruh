## 1. Introdução

&emsp;&emsp;Para verificar os Casos de Uso do projeto de Requisitos de software do aplicativo Noruh, usaremos a estratégia de "inspeções", no qual se objetiva o descobrimento de defeitos em documentos, buscando assim achar os defeitos no documento do [iStar](../../modelagem/iStar.md).

## 2. Preparação

&emsp;&emsp;Baseado na metodologia adotada no [Planejamento da Verificação](planejamento.md), a preparação, inspeção e acompanhamento da verificação serão feitos a partir de um *checklist* com algumas perguntas com base nas referências sobre a técnica iStar citadas nessa página, e nas observações feitas pelo professor. Dessa forma, podemos ver se o nosso está correto com base nessas perguntas. Quando a questão tiver sido atendida terá um "check", quando não atendida um "X", e quando não se aplicar ao projeto será utilizada a sigla N/A (not applicable).  Conforme a legenda abaixo:

- ✅ : Atendido
- ❌ : Não Atendido
- **N/A** : Não se aplica

&emsp;&emsp;A checklist a ser seguida encontra-se abaixo na Tabela 1.

| ID  | Questão                                                                    |
| --- | -------------------------------------------------------------------------- |
| 1   | O iStar condiz com os requisitos elicitados do aplicativo?                 |
| 2   | Os tipos de atores foram representados corretamente?                       |
| 3   | As relaçoes entre atores foram representadas corretamente?                 |
| 4   | Os elementos intencionais foram representados corretamente?                |
| 5   | As dependências foram representadas corretamente?                          |
| 6   | As direções das ligações de dependência estão no sentido correto?          |
| 7   | As regras e restrições foram devidamente aplicadas?                        |
| 8   | Os links entre os elementos intencionais foram representados corretamente? |
| 9   | Os links estão no sentido correto?                                         |
| 10  | Os símbolos dos links estão corretos?                                      |
| 11  | Há o modelo dependência?                                                   |
| 12  | Há o modelo rationale?                                                     |

<figcaption align='center'>
    <b>Tabela 1: Modelo de checklist do iStar</b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## 3. Inspeção: Checklist do iStar

| ID  | Questão                                                           | Conta | Pesquisa | Pedido |
| --- | ----------------------------------------------------------------- | ----- | -------- | ------ |
| 1   | O iStar condiz com os requisitos elicitados do aplicativo?        | ✅     | ✅        | ✅      |
| 2   | Os tipos de atores foram representados corretamente?              | ✅     | ✅        | ✅      |
| 3   | As relaçoes entre atores foram representadas corretamente?        | N/A   | N/A      | N/A    |
| 4   | Os elementos intencionais foram representados corretamente?       | ❌     | ❌        | ❌      |
| 5   | As dependências condizem com os requisitos elicitados?            | ✅     | ✅        | ✅      |
| 6   | As direções das ligações de dependência estão no sentido correto? | ✅     | ✅        | ❌      |
| 7   | As regras e restrições foram devidamente aplicadas?               | ✅     | ✅        | ✅      |
| 8   | Os links entre os elementos intencionais estão condizentes?       | ✅     | ✅        | ✅      |
| 9   | Os links estão no sentido correto?                                | ✅     | ✅        | ✅      |
| 10  | Os símbolos dos links estão corretos?                             | ✅     | ✅        | ✅      |
| 11  | Há o modelo dependência?                                          | ✅     | ✅        | ✅      |
| 12  | Há o modelo rationale?                                            | ✅     | ✅        | ✅      |

<figcaption align='center'>
    <b>Tabela 2: Checklist do iStar </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## 4 Acompanhamento: Porcentagem de sucesso do checklist

<center>
<iframe width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQZY0hb3YNRVAmizXxR9bcjmwcAUhfl-vteMbV7OT0CVvYA55lj1rr7c0c3SbrqjXxUqyzwkHR3cbl7/pubchart?oid=1088649009&amp;format=interactive"></iframe>
</center>
<figcaption align='center'>
    <b>Gráfico 1: Porcentagem de sucesso do checklist do iStar </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>

## 4. Correção

&emsp;&emsp;Após a execução da etapa de Inspeção utilizando os checklists, alguns critérios não foram atendidos nos 3 temas e precisam ser corrigidos. São eles:

**Conta**:

| ID  | Questão                                                     |
| --- | ----------------------------------------------------------- |
| 4   | Os elementos intencionais foram representados corretamente? |

**Pesquisa**:

| ID  | Questão                                                     |
| --- | ----------------------------------------------------------- |
| 4   | Os elementos intencionais foram representados corretamente? |

**Pedido**:

| ID  | Questão                                                           |
| --- | ----------------------------------------------------------------- |
| 4   | Os elementos intencionais foram representados corretamente?       |
| 6   | As direções das ligações de dependência estão no sentido correto? |

## Referências
- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 23. 1º/2022. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
- Dalpiaz, F., Franch, X. and Horkoff, J. (2016) iStar 2.0 language guide. Disponível em: https://arxiv.org/abs/1605.07767. Acesso em: 09/09/2022

## Histórico de versão
| Versão |      Alteração       | Responsável | Revisor |   Data   |
| :----: | :------------------: | :---------: | :-----: | :------: |
|  1.0   | Criação do documento |    Karla    |    -    | 09/09/22 |
