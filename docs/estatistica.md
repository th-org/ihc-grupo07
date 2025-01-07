---
hide:
  - navigation
---

## Introdução

Os métodos estatísticos desempenham um papel fundamental na análise de dados, permitindo interpretar e compreender informações de maneira objetiva e precisa. No contexto da pesquisa sobre a experiência do usuário, utilizaremos três métodos principais para avaliar e validar os dados coletados. O **Alpha de Cronbach** será utilizado para medir a confiabilidade interna dos questionários, verificando se as perguntas relacionadas a uma mesma variável são consistentes e confiáveis. A média e o desvio padrão serão calculados para fornecer uma visão geral das tendências dos dados e a variação nas respostas dos usuários. Por fim, a **Correlação de Pearson** será aplicada para explorar a relação entre diferentes variáveis, como a satisfação do usuário e a facilidade de uso da interface, ajudando a identificar se as mudanças implementadas no Moovit Web impactam positivamente a experiência do usuário de forma significativa.

## Alpha de Cronbach

Para obtenção dos dados, utilizamos do Excel, que estará acessível nesse link: [Dados do Excel]().

Para calcular o Alpha de Cronbach por meio do excel, seguimos os seguintes passos:
1. Importar as respostas do formulário para o Excel, onde cada coluna é uma pergunta (B a K) e cada linha é uma resposta (2 a 108)
2. Calcular as variâncias de cada coluna
3. Somar as respostas de cada linha e calcular essa variância 
4. Aplicar a fórmula para achar o valor do Alpha de Cronbach: =10/(10-1) * (1 - (SOMA(B109:K109)/L109)), onde de B9 a K9 são as variâncias de cada pergunta e L9 é a variância da soma das respostas

Após o cálculo, o **Alpha de Cronbach** foi obtido como **0.911245312**. Este valor indica que as 10 perguntas do questionário possuem uma excelente consistência interna, já que o valor do Alpha de Cronbach está bem acima do limite mínimo de 0.7, sendo considerado um valor muito bom para a confiabilidade do conjunto de itens. Este valor sugere que o questionário utilizado apresenta uma excelente confiabilidade, com as perguntas do questionário medindo o mesmo construto de forma consistente. O valor obtido reforça que o questionário pode ser utilizado de maneira eficaz em futuras análises, com a garantia de que as respostas dos usuários estão relacionadas de maneira significativa entre si.