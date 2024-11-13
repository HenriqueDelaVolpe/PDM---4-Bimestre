# PDM---4-Bimestre

Alessandra Cristina
Isabelle Natale
Henrique Volpe
Enzo Copia
Sofia de Sousa


O que é o projeto?

A Calculadora de Gastos é um aplicativo desenvolvido para ajudar os usuários a monitorar e controlar seus gastos diários. 
Ele permite registrar despesas, categorizar transações e visualizar gráficos que ilustram os padrões de consumo de forma 
clara e prática.

Permite registrar suas despesas diárias e categorizar cada despesa, facilitando o acompanhamento do destino do seu dinheiro.
Ao documentar claramente seus gastos, você pode identificar padrões com mais facilidade, identificar áreas onde pode economizar 
e criar um orçamento mais eficaz.

A principal função da calculadora de gastos é registrar e somar gastos em diversas categorias, como alimentação, moradia, 
transporte e lazer. Algumas calculadoras também oferecem gráficos para uma visualização mais clara, permitindo que você 
veja rapidamente quais categorias estão consumindo mais dinheiro para você. O uso de gráficos, como aqueles fornecidos 
por bibliotecas como react-native-chart-kit, pode melhorar a experiência visual e facilitar a compreensão.

Além disso, a calculadora de gastos também pode incluir lembretes de contas não pagas e alertas quando você estiver se aproximando do 
limite do seu orçamento. Ferramentas mais completas podem permitir exportar dados em formatos como PDF ou CSV para análise mais detalhada ou arquivamento de 
registros. Para alguém que desenvolve uma calculadora de despesas em um aplicativo, a lógica básica envolve a criação de um formulário para inserir o valor, a data
e a categoria da despesa. Os dados podem ser armazenados em algum estado, como em um aplicativo React Native, onde as despesas são somadas para mostrar o gasto total.
Melhorias poderiam ser feitas adicionando a opção de filtrar cobranças por data, adicionando gráficos interativos ou até mesmo integrando APIs de câmbio para quem 
precisa rastrear cobranças em moedas diferentes.

Tecnologias e bibliotecas utilizadas
Este projeto foi desenvolvido com as seguintes tecnologias e bibliotecas:

React Native
Um framework popular para o desenvolvimento de aplicativos móveis multiplataforma (iOS e Android) 
com JavaScript, garantindo alto desempenho e flexibilidade no design.

react-native-chart-kit
A react-native-chart-kit é uma biblioteca para a criação de gráficos no React Native. 
Ela permite incorporar visualizações interativas para representar dados de maneira clara 
e intuitiva e é útil para criar gráficos em aplicativos React Native. Ela oferece vários 
tipos de gráficos como linhas, barras, progress circles, entre outros, e é fácil de integrar 
e customizar. Exemplo:


Instalação:
Primeiro, adicione a biblioteca ao seu projeto:

npm install react-native-chart-kit
ou
yarn add react-native-chart-kit

npm install react-native-svg

Exemplos de gráficos usados no projeto:

Gráficos de Linha: Para acompanhar os gastos ao longo do tempo.
Gráficos de Barras: Para comparar gastos entre categorias ou períodos.
Gráficos de Pizza: Para ilustrar a distribuição percentual dos gastos por categoria.

Funcionalidades principais
Registro de despesas com categorias personalizadas.
Exibição de gráficos detalhados para análise de gastos, criados com a biblioteca react-native-chart-kit. Interface intuitiva e design responsivo.
