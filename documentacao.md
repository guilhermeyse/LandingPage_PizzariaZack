# LandingPage_PizzariaZack
Aula 15/10 - Criação de landing Page - FMP - Prática de Programação Web

Documentação Técnica e de Design: Landing Page — Pizzaria do Zack
Aluno: Guilherme de Melo Goularte
Data: 15/10/2026

Sou aluno da primeira fase de ADS da faculdade FMP. 
Esse projeto se trata de uma Landing Page para a disciplina de Prática de Programação Web. Optei por uma pizzaria por ser minha comida favorita, e sempre achei interessante e “convidativo” o modo como os sites de pizzarias são apresentados. 
Gostei do projeto e creio que consegui realizar a proposta.

1. Visão Geral do Projeto
A Landing Page da Pizzaria do Zack foi desenvolvida com o objetivo de servir como um cartão de visitas digital de alta conversão e posicionamento de marca premium.
Diferente da página de pedidos (cardapio.html), esta Landing Page (index.html) adota uma abordagem ultra-minimalista e essencial. Sua função primária é comunicar o valor da marca (fermentação natural 48h, ingredientes D.O.P., forno a lenha) e guiar o visitante sem distrações para a ação principal: acessar o cardápio e realizar o pedido.

2. Estratégia de UX & Arquitetura de Informação
Foco Único de Conversão (Single Goal Funnel)
Para eliminar a fadiga de decisão do usuário e ruídos visuais, foram removidos elementos de e-commerce pesados da primeira dobra (como busca, abas de categorias, filtros e sacola lateral). Toda a navegação e botões da página convergem para o mesmo destino: cardapio.html.
Hierarquia Visual
Atração: Título forte focado no diferencial do forno a lenha e na massa artesanal.
Autoridade & Valor: Apresentação dos 3 pilares fundamentais da marca.
Chamada para Ação (CTA): Botões em posições estratégicas com gradientes e efeito de brilho (glow).

3. Identidade Visual & Guia de Estilo (Design System)
A paleta e a tipografia foram escolhidas para transmitir sofisticação rústica, combinando a tradição das pizzarias napolitanas com a modernidade do web design contemporâneo.
Paleta de Cores (Tailwind Custom Config)
Token Tailwind
Código HEX
Função & Aplicação
brand-black
#09090B
Fundo Principal: Preto profundo que dá o tom escuro premium e destaca as imagens.
brand-dark
#121216
Fundo Secundário: Utilizado em seções alternadas para criar contraste estrutural.
brand-card
#16161C
Superfície de Cards: Fundo elevado para componentes e quadros de destaques.
brand-border
#22222C
Bordas Sutis: Delimitação de cards e divisores com baixo contraste visual.
brand-accent
#E63946
Acatamento Quente: Vermelho vibrante usado nos botões de CTA e gradientes de fogo.
brand-fire
#FF4D30
Tom de Fogo: Laranja avermelhado utilizado em efeitos de brilho (fire-glow) e gradientes.
brand-gold
#D4AF37
Dourado Nobre: Usado para o logotipo, ícones principais e detalhes de luxo.
brand-muted
#8E8E9A
Texto de Apoio: Cinza suavizado para descrições, mantendo alta legibilidade sem poluição.

Tipografia
Playfair Display (Serif): Aplicada em títulos principais (h1, h2, h3). Confere o tom editorial, gastronômico e refinado.
Cinzel (Serif): Reservada para a tipografia do logotipo (ZACK) e marcas institucionais, transmitindo força e tradição romana/italiana.
Plus Jakarta Sans (Sans-Serif): Utilizada no corpo do texto, botões e elementos funcionais da interface para garantir máxima leitura em telas móveis e desktops.

4. Estrutura das Seções (Layout Breakdown)
A. Cabeçalho Minimalista (<header>)
Logotipo: Ícone de forno em dourado envolvido por gradiente com a marca estilizada.
CTA Direto: Botão com gradiente fogo (bg-gradient-to-r from-brand-accent to-brand-fire) redirecionando diretamente para cardapio.html.
Comportamento: Fixo no topo com desfoque de fundo (backdrop-blur-md).
B. Seção Principal / Hero Section (<main>)
Copywriting de Impacto: Headline com destaque em gradiente para "forno a lenha" e subtítulo focado no processo de 48h e tomates San Marzano.
Primary CTA: Botão proeminente com ícone de sacola e efeito de elevação no hover.
Visual Conceitual: Foto de alta qualidade em card elevado com borda sutil e gradiente escuro de sobreposição.
C. Seção dos 3 Pilares da Marca (<section>)
Apresenta os elementos essenciais da experiência gastronômica em um grid de 3 cards alinhados:
Massa 48h: Destaque para a fermentação natural e facilidade de digestão.
San Marzano D.O.P.: Destaque para a qualidade do molho de tomate italiano.
Forno a Lenha 450°C: Destaque para a lenha de macieira e o sabor defumado.
D. Banner Final de Conversão
Chamada direta e acolhedora ("Pronto para fazer seu pedido?") para reforçar a intenção de compra antes do rodapé.
E. Rodapé (<footer>)
Estrutura enxuta com nome da marca e direitos autorais.
5. Engenharia Frontend e Performance
Sem Dependências Pesadas: Desenvolvida puramente com HTML5, Tailwind CSS (via CDN) e FontAwesome 6, garantindo carregamento instantâneo.
Responsividade Mobile-First: O layout se adapta perfeitamente a dispositivos móveis, ajustando tamanhos de fonte, espaçamentos e grids automaticamente.
Acessibilidade: Alto contraste entre os textos claros/dourados e os fundos escuros, facilitando a leitura em qualquer iluminação de tela.

