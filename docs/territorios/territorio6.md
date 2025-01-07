---
hide:
  - toc
---

# Aplicação do Território 6 - Modelos Conceituais Baseados em Atividades

No Território 6, abordamos **modelos conceituais baseados em atividades**, focando em dois modelos principais: **Manipulação e Navegação** e **Explorar e Navegar**. Estes modelos ajudam a otimizar a interação do usuário com o sistema, tornando as tarefas mais intuitivas e eficientes.

### 1. Manipulação e Navegação

A **Manipulação e Navegação** refere-se às ações diretas que o usuário realiza sobre os elementos do sistema, como arrastar, selecionar, abrir, fechar ou ampliar objetos virtuais. Essas interações são baseadas em como os usuários estão acostumados a se movimentar e manipular elementos no mundo físico, tornando-as mais naturais e acessíveis.

#### Exemplos no Moovit Web:
- **Fechar a aba de pesquisa**: A ação de fechar a aba ou janela de pesquisa deve ser realizada de maneira simples, como o uso de um botão "X" visível e intuitivo.
- **Voltar à aba anterior**: O sistema deve permitir que os usuários voltem facilmente à página anterior, com um botão de "Voltar" que seja claramente identificado.
- **Refazer opções indesejadas**: Implementar botões de **desfazer** e **refazer**, para que o usuário possa corrigir rapidamente ações feitas acidentalmente, como a seleção incorreta de uma rota.

#### Estratégia de Melhoria:
- Melhorar a **simpatia e simplicidade dos botões** e **ações rápidas** (por exemplo, botões para voltar ou desfazer), garantindo que sejam facilmente identificáveis e acessíveis para o usuário.
- Garantir que as **ações de navegação e manipulação** sejam consistentes, com feedback visual imediato, como animações ou mudanças de cor ao clicar ou interagir com os elementos.

---

### 2. Explorar e Navegar

O modelo **Explorar e Navegar** envolve a interação do usuário com o sistema para descobrir informações, funcionalidades ou opções por meio de menus, links, botões e outros elementos interativos. Esse modelo é comumente usado em websites, aplicativos móveis, jogos e sistemas com grandes quantidades de dados ou opções, como o Moovit Web.

#### Exemplos no Moovit Web:
- **Copiar e compartilhar a rota selecionada**: O usuário pode desejar copiar ou compartilhar informações sobre uma rota selecionada, como um link direto ou detalhes de horários e pontos de partida/chegada. O sistema deve permitir essa ação de forma simples, com botões claros para **compartilhar** em redes sociais ou **copiar** para a área de transferência.
- **Melhoria no menu de busca**: A barra de pesquisa deve ser aprimorada para facilitar a exploração de diferentes rotas e modos de transporte. Implementar **autocompletar** e **sugestões dinâmicas** à medida que o usuário digita, e melhorar a filtragem para que o usuário possa refinar suas buscas de forma rápida e eficiente.

#### Estratégia de Melhoria:
- **Reestruturar o menu de navegação** para facilitar a **descoberta de rotas** e **funcionalidades adicionais** (como ver horários detalhados, escolher modos de transporte alternativos, etc.).
- Implementar **elementos interativos** para incentivar o usuário a explorar mais opções de transporte e verificar alternativas que ele não havia considerado inicialmente.
- Adicionar uma **função de compartilhamento** direta das rotas e dados, com opções claras de **copiar** ou **compartilhar** as informações via links ou redes sociais.


# Aplicação do Território 6b - Metáforas de Interface 

## Melhorias Propostas

### 1. **Direções** - Melhorando a metáfora para **Rotas**

#### **Problema Identificado:**
A metáfora de "Direções" pode ser confusa para o usuário, não transmitindo claramente a funcionalidade de navegação.

#### **Solução:**
Alterar o termo **"Direções"** para **"Rotas"**, que é mais intuitivo e associado diretamente ao conceito de navegação, facilitando o entendimento do usuário sobre o que está sendo exibido ou solicitado.

### 2. **Separação entre Alertas e Notícias**

#### Problema Identificado:
Atualmente, a aba de **Alertas** está implementada junto com a aba de **Notícias**. As bolinhas azuis indicam notícias, enquanto as bolinhas amarelas são usadas para alertas. Essa implementação pode gerar confusão, pois a metáfora de alertas deveria ser exclusiva para alertas, e não para notícias.

#### Solução:
A solução é separar as abas de **Alertas** e **Notícias**, de forma que o usuário possa identificar facilmente qual é a funcionalidade de cada uma. Para isso, deve-se garantir que a metáfora de alertas seja exclusiva para alertas e a de notícias seja utilizada apenas para notícias.