# ponderada-cypress
## 1. O que é o Cypress e para que serve?
Cypress é uma ferramenta de teste frontend desenvolvida para a web moderna. O Cypress permite que o desenvolvedor escreva testes mais rápidos, fáceis e confiáveis. Foi criada para simplificar o processo de configuração, escrita, execução e depuração de testes.

## 2. Vantagens e desvantagens do Cypress em relação a outras ferramentas de teste.
### Vantagens
Com uma abordagem única, o Cypress opera no mesmo ciclo de execução da aplicação, fornecendo acesso nativo a cada objeto. Isso permite uma resposta em tempo real aos eventos da aplicação e uma manipulação mais fácil do estado da aplicação. Além disso, elimina a necessidade de bibliotecas, tornando a configuração mais simples e os testes mais confiáveis e rápidos.

### Desvantagens
Pode não ser a melhor escolha para testes unitários ou de integração de serviços de backend. A ferramenta é especificamente adaptada para testes de ponta a ponta de aplicações web, o que faz dela não ser a melhor opção para quem quer fazer testes unitários ou de integração. Além disso, o Cypress suporta apenas JavaScript.

## 3. Arquitetura do Cypress.
O Cypress opera tanto no navegador quanto em um servidor Node.js em segundo plano, permitindo controlar todo o processo de teste. Esta operação dupla permite ao Cypress monitorar eventos da aplicação em tempo real, manipular o tráfego da web e realizar tarefas de maior privilégio fora do navegador.

## 4. Seletores de elementos no Cypress.
O Cypress oferece um conjunto de comandos para selecionar elementos do DOM, como '.get()', '.contains()', '.find()' e outros. Esses comandos são projetados para simplificar o processo de localização de elementos em uma página web, permitindo a escrita de testes mais intuitivos e estáveis.

## 5. Comandos e asserções no Cypress.
O Cypress fornece vários comandos e asserções que são encadeáveis e semelhantes a promessas, permitindo a escrita de testes complexos com menos código. Comandos incluem ações como .click(), .type(), .scrollIntoView(), e asserções como .should() ou .and() para verificar o estado da sua aplicação. Esta configuração garante que os testes sejam legíveis e expressivos, alinhando-se de perto com a linguagem natural.

## 6. Descrição das etapas de preparação de um testes de interface, execução e verificação no Cypress.
A preparação de um teste no Cypress envolve configurar o ambiente de teste e o estado da aplicação. A execução envolve interagir com a aplicação web por meio de comandos do Cypress, simulando ações reais do usuário. A verificação é feita usando asserções para garantir que a aplicação responda conforme o esperado. A arquitetura do Cypress e a lógica de repetição de comandos reduzem significativamente a flutuação dos testes e melhoram a confiabilidade.

## 7. Como estruturar testes de forma eficiente no Cypress?
Para estruturar os testes de maneira eficiente, é possível seguir os seguintes passos:

- Organizar os testes logicamente usando blocos describe e it.
- Utilizar fixtures do Cypress e comandos personalizados para configuração de teste reutilizável.
- Empregar padrões de objeto de página para abstrair seletores de elementos.
- Aproveitar as opções de configuração do Cypress para personalizar execuções de teste, incluindo tempos de espera, tamanho da viewport e variáveis ambientais.
