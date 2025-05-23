# timeCapsule

# The Fashion Club

Este projeto é um site institucional simples para o clube de moda **The Fashion Club**. Ele utiliza apenas **HTML e CSS**, com foco em um visual elegante e responsivo.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Google Fonts (`Playfair Display`, `Poppins`, `Jacques Francois`)
- Flexbox e Grid CSS para layout
- Media queries para responsividade

## Funcionalidades

- Cabeçalho fixo com navegação adaptável para desktop e mobile
- Seção hero com imagem de modelo e texto em destaque
- Seção de cartões com temas de moda
- Design responsivo até celulares pequenos (320px)

## Responsividade

A responsividade foi feita com `media queries` e `grid/flexbox` para:

- Esconder/mostrar o menu conforme o tamanho da tela
- Adaptar o layout da seção de cartões
- Reduzir o tamanho da imagem modelo na home

## Como visualizar

1. Clone ou baixe o repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Para simular o comportamento responsivo, redimensione a janela ou use o modo responsivo das ferramentas de desenvolvedor (`F12` > "Toggle device toolbar").

## Créditos

Projeto fictício desenvolvido com fins de prática de front-end.

---

Este projeto é um site institucional simples e elegante para um clube de moda fictício, desenvolvido inteiramente com HTML e CSS puro. A proposta é oferecer uma base sólida, semântica e responsiva, com foco em estrutura clara e visual refinado, ideal para uso pessoal, portfólio ou como base para projetos similares no ramo de moda ou eventos.

## Estrutura de Arquivos

O projeto é organizado de forma enxuta, com os seguintes arquivos e pastas:

- `index.html`: Arquivo principal da página, contendo a estrutura semântica completa.
- `style.css`: Folha de estilo única, contendo todo o CSS necessário para layout, tipografia, responsividade e estética.
- `images/`: Pasta com imagens utilizadas no projeto, como o logotipo e uma imagem de destaque para a seção hero.

## Estrutura do HTML

O HTML segue boas práticas de semântica e acessibilidade. O conteúdo está dividido em três grandes blocos:

- `<header>`: contém o logotipo fixo no topo da página e a navegação principal.
- `<main>`: inclui duas seções:
  - A seção hero, com uma imagem de modelo e um texto de destaque.
  - A seção de cartões, com três elementos destacados representando conteúdos ou categorias de interesse.
- `<footer>`: opcional, pode conter informações institucionais, direitos autorais, etc.

A navegação é clara, o conteúdo é organizado de forma hierárquica, e o layout facilita tanto a leitura quanto a navegação em diferentes tamanhos de tela.

## Organização do CSS

O CSS é dividido em blocos bem definidos, comentados e organizados por tipo de elemento ou seção:

1. **Reset e estilo base**: Aplica `box-sizing: border-box`, zera margens e paddings, define fonte padrão e cor de fundo neutra.
2. **Tipografia**: Uso de fontes Google Fonts — `Playfair Display` para títulos (visual sofisticado), `Poppins` para o texto corrido (moderna e legível) e, opcionalmente, `Jacques Francois` para toques decorativos.
3. **Layout principal com Flex e Grid**: O header usa Flexbox para posicionar logo e menu. A seção hero usa Grid com duas colunas (imagem + texto). A seção de cartões usa Grid responsivo com `auto-fit` e `minmax` para garantir adaptação automática.
4. **Responsividade**: O site se adapta completamente a telas menores através de media queries. Abaixo de 768px, a hero passa para uma única coluna, a imagem é centralizada e o menu pode ser ocultado ou convertido em botão. Os cartões se reorganizam automaticamente.
5. **Design e espaçamentos**: Utilização de padding e margin amplos, sombra sutil em alguns elementos, bordas simples. A estética é neutra e elegante, focando no conteúdo e na legibilidade.
6. **Classe por seção**: As classes são intuitivas e por bloco (`.hero`, `.card`, `.cards`, `.nav`, `.logo`, etc.), facilitando manutenções e escalabilidade.

## Decisões Técnicas

- **Sem JavaScript**: Tudo é feito com HTML e CSS para manter o projeto acessível e leve.
- **Semântica clara**: Uso correto de `<section>`, `<header>`, `<main>`, etc., com foco em SEO básico e estrutura compreensível.
- **Design neutro**: Evita excesso de cores, ícones ou efeitos visuais para manter um visual limpo, focado na marca e no conteúdo.
- **Adaptação garantida**: Grid e Flexbox permitem que o site se comporte bem em diferentes tamanhos de tela, desde desktops até smartphones pequenos.

## Como Visualizar

Basta abrir o arquivo `index.html` em qualquer navegador moderno. O site é totalmente estático e não depende de nenhum servidor ou backend.