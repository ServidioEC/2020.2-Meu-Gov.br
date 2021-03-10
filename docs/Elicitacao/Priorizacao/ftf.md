## Histórico de Versões

| Data       | Versão | Descrição                                                                                               | Autores          | Revisor |
| ---------- | ------ | ------------------------------------------------------------------------------------------------------- | ---------------- | ------- |
| 08/03/2021 | 0.1    | Criação do documento e adição da introdução.                                              | Pedro Haick      | ------- |
| 10/03/2021 | 0.2    | Descrição do método de priorização.                                              | Pedro Haick      | ------- |

## Definição

Técnica de priorização de requisitos não vitais para um produto, baseado no valor gerado por cada requisito ao produto, assim como seus custos e riscos.

## Método

O método First Things First possui 8 passos:

1. Lista-se todos os requisitos, recursos ou casos de usos a serem priorizados. Em caso de requisitos com relação lógica, inclui-se apenas o principal.

2. Estima-se o benefício de cada um dos requisitos entre 1 (menor) e 9 (maior).

3. Estima-se a penalidade no caso de uma possível não entrega do requisito, também de 1 (baixa penalidade) a 9 (alta penalidade).

4. Soma-se o valor do benefício ao valor da penalidade, geralmente ambos com peso 1. O peso pode ser ajustado para um priorizar um em detrimento do outro.

5. Estima-se o custo de implementação dos requisitos, de 1 (baixo custo) e 9 (alto custo).

6. Estima-se o grau dos riscos associados ao requisito, de 1 (facilmente programável) e 9 (alto risco de desenvolvimento).

7. Calcula-se a prioridade de cada requisito a partir da seguinte fórmula: **prioridade = valor_percentual / (custo_percentual * peso_custo + risco_percentual % * peso_risco)**. Cada atributo percentual representa o atributo do requisito dividido pelo total de todos os requisitos, por exemplo: **valor_percentual = valor_do_requisito + valor_todos_requisitos**

8. Ordena-se os requisitos de maneira decrescente em relação às suas prioridades. É recomendado que se revise a tabela.