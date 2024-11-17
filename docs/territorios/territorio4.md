---
hide:
  - toc
---

# Aplicação do Território 4 - Análise de dados em IHC

O Território 4 introduz a análise de dados em Interação Humano-Computador (IHC), abordando aspectos fundamentais como fontes de dados, ferramentas utilizadas para análise e métodos para garantir a confiabilidade dos dados. A análise quantitativa e qualitativa dos dados coletados será essencial para melhorar a interface do Moovit Web, de forma que possamos avaliar e validar as melhorias implementadas.

### Abordagem:
#### Fontes de Dados:
- **Questionários**: Utilizaremos questionários estruturados, com escalas de Likert, para coletar dados sobre a experiência do usuário na interface atual. Esses questionários ajudarão a medir a satisfação dos usuários, suas percepções sobre a facilidade de uso e a eficiência da plataforma.

#### Ferramentas de Análise:
- **Excel**: Usaremos o Excel para tabular os dados coletados e realizar análises preliminares, como cálculo da média, desvio padrão e criação de gráficos que ajudem a visualizar as tendências dos dados.
- **R e RStudio**: O R será utilizado para análises mais avançadas. Através do RStudio, será possível importar facilmente os dados do Excel e aplicar funções estatísticas para calcular a confiabilidade dos dados e a similaridade entre variáveis. O R tem uma vasta comunidade e bibliotecas que podem ser exploradas para análises mais complexas.

#### Métodos Estatísticos:
- **Confiabilidade**: Utilizaremos o **Alpha de Cronbach** para medir a confiabilidade interna dos questionários. Este índice nos permitirá verificar se as perguntas relacionadas a uma mesma variável estão consistentes, ou seja, se os dados obtidos são confiáveis.
- **Média e Desvio Padrão**: Calcularemos a **média** e o **desvio padrão** dos dados coletados para entender as tendências gerais da experiência do usuário.
- **Similaridade**: Aplicaremos a **Correlação de Pearson** para verificar a relação entre diferentes variáveis, como a satisfação do usuário e a facilidade de uso percebida da interface. Isso nos ajudará a identificar se as mudanças feitas no Moovit Web impactam positivamente a experiência do usuário de forma significativa.

### Aplicação no Projeto:
- Após a coleta dos dados por meio de questionários, realizaremos uma análise estatística usando as ferramentas mencionadas.
- Usaremos os resultados para avaliar a eficácia das melhorias implementadas no Moovit Web, fazendo ajustes baseados nos dados obtidos.
- A análise ajudará a validar as hipóteses e a ajustar as mudanças no design da interface, sempre com foco na usabilidade e na experiência do usuário.