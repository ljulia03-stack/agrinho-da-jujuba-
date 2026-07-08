No arquivo index.html, identifique o nome de um autor em qualquer uma das postagens e transforme-o num link utilizando a tag <a>.
Escolha uma imagem de um dos seus posts e transforme-a também num link funcional, garantindo que o utilizador seja redirecionado para a fonte da imagem ao clicar nela.
Nessa aula, aprendemos a preparar o terreno para uma das funcionalidades mais pedidas em qualquer site: o Modo Escuro.
Começamos organizando as cores do nosso blog usando variáveis no CSS para facilitar a troca de estilos de uma só vez, garantindo que o layout seja flexível e moderno
Ainda existem várias possibilidades de personalização para o projeto. Você pode experimentar novos estilos de texto, alterar pesos de fonte, adicionar negrito em partes importantes e testar diferentes combinações visuais.
No seu arquivo style.css, dentro do :root, crie uma nova variável chamada --cor-destaque. Escolha uma cor bem vibrante que ainda não foi usada no blog.
Utilize essa variável --cor-destaque para mudar a cor da borda de todos os cartões de postagem.
No seletor do seu modo escuro, redefina o valor dessa variável --cor-destaque para uma nova cor que combine melhor com o fundo escuro.
Modo Escuro
Uma funcionalidade que altera o esquema de cores de uma interface para tons mais escuros, geralmente com texto claro sobre fundo escuro.

Variáveis CSS
Nomes definidos no CSS para armazenar valores que podem ser reutilizados em diferentes partes de uma folha de estilo, facilitando a manutenção e a alteração de estilos.

:root (seletor)
Um seletor CSS que representa o elemento raiz de um documento HTML ( o elemento < html> ), usado para definir variáveis CSS globais.

Cores Hexadecimais
Um sistema de representação de cores digitais usando uma combinação de seis caracteres (números e letras de A a F) precedidos por um #.

var() (função CSS)
Uma função CSS usada para acessar o valor de uma variável CSS personalizada.
No arquivo index.html, crie um novo botão logo abaixo do botão de tema escuro e atribua a ele uma classe chamada btn-voltar-topo.
No arquivo style.css, utilize o posicionamento fixed para garantir que ele não sobreponha o botão de tema.
No arquivo script.js, crie uma nova constante para selecionar este botão e adicione um evento de clique.
Dentro da função desse evento, utilize o comando window.scrollTo(0, 0) para que a página suba automaticamente para o topo quando o botão for clicado.
Raio da Borda - border-radius (CSS)
Propriedade CSS que define o nível de arredondamento dos cantos de um elemento visual.

Cursor (CSS)
Propriedade CSS que especifica o tipo de ponteiro do mouse a ser exibido quando ele está sobre um elemento.
Crie uma regra utilizando o seletor :hover para os seus cartões de postagem (article). Quando o usuário passar o mouse sobre o card, ele deve aumentar levemente de tamanho usando transform: scale(1.02).
Aproveite o efeito de sombra (box-shadow) aprendido em aula e faça com que essa sombra fique um pouco mais intensa ou mude de cor quando o card estiver com o mouse sobre ele (no mesmo seletor :hover).
No modo escuro, ajuste a cor da sombra dos cards para que ela seja uma variação mais clara (como um azul brilhante ou cinza suave), garantindo que o efeito de profundidade ainda seja visível mesmo em fundos escuros.
