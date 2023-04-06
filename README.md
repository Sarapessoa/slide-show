## Descrição

<p>Este é um projeto de um slider de imagens desenvolvido utilizando HTML, CSS e JavaScript. O slider é responsivo e possui controles de navegação e indicadores visuais para ajudar o usuário a navegar pelas imagens.</p>

## Estrutura do Código

<p>O código está organizado em três arquivos: <code>index.html</code>, <code>style.css</code> e <code>script.js</code>.</p>
<p>1. O arquivo <code>index.html</code> contém a estrutura básica da página com a marcação HTML para exibir as imagens, controles e indicadores visuais. Ele também inclui os arquivos CSS e JavaScript necessários.</p>
<p>2. O arquivo <code>style.css</code> é responsável pelo estilo da página e define o layout, as cores, as dimensões e a posição dos elementos na tela. Ele utiliza classes CSS para estilizar os elementos do slider.</p>
<p>3. O arquivo <code>script.js</code> é responsável pela lógica do slider e define as funções para mover as imagens, atualizar os indicadores visuais e exibir o texto correspondente à imagem atual. Ele também utiliza seletores de classe CSS para selecionar os elementos necessários.</p>

## Funcionamento

<p>O slider funciona da seguinte maneira:</p>

- As imagens são exibidas em uma div com a classe "slider-items". Cada imagem é um elemento img com a classe "slider-item".
- Os controles de navegação são exibidos em uma div com a classe "slider-controls". Cada controle é um elemento span com as classes "bx bxs-chevron-left" para o controle de navegação para a esquerda e "bx bxs-chevron-right" para o controle de navegação para a direita. Ao clicar em um dos controles, a função "changeSlide" é acionada.
- Os indicadores visuais são exibidos em uma div com a classe "slider-indicators". Cada indicador é um elemento span. Ao clicar em um dos indicadores, a função <code>moveTo(e)</code> é acionada.
- Os textos que acompanham as imagens são exibidos em uma div com a classe "slider-content". Cada texto é um elemento h3.

<p>A função <code>showSlide()</code> é responsável por exibir a imagem atual e o texto correspondente. Ela é chamada ao carregar a página e sempre que o usuário navega para uma imagem diferente.</p>

## Personalização

<p>É possível personalizar o slider editando o arquivo <code>style.css</code> e <code>script.js</code>. Algumas possibilidades incluem:</p>

- Alterar as cores, dimensões e posição dos elementos do slider.
- Adicionar mais imagens ao slider e seus respectivos textos.
- Alterar a animação de transição entre as imagens.
- Utilizar outras bibliotecas de ícones para os controles de navegação.

## Autor

Este projeto foi desenvolvido por Sara Pessoa Silva
