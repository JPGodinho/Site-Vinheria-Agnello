# Site Vinheria Agnello

## Descrição do Projeto
Este projeto consiste no desenvolvimento de um site para a Vinheria Agnello, uma empresa especializada na comercialização de vinhos nacionais e importados. O site foi criado com o objetivo de apresentar a história da vinheria, seus produtos e facilitar o contato com os clientes.

## Caso da Vinheria Agnello
A Vinheria Agnello é uma empresa tradicional no mercado de vinhos, fundada em 1985 pela família Agnello, de origem italiana. O que começou como um pequeno negócio familiar hoje se tornou uma referência no mercado de vinhos, oferecendo uma seleção cuidadosamente escolhida de rótulos nacionais e importados. A empresa valoriza a qualidade, tradição, conhecimento e sustentabilidade em todas as suas operações.

## Estrutura do Projeto

### Páginas do Site

1. **Página Inicial (index.html)**
   - Apresentação da Vinheria Agnello
   - Destaques de produtos
   - Categorias de vinhos
   - Informações sobre o clube de assinatura

2. **História (historia.html)**
   - Narrativa sobre a fundação e trajetória da Vinheria Agnello
   - Valores da empresa
   - Linha do tempo com marcos importantes
   - Galeria de fotos

3. **Produtos (produtos.html)**
   - Listagem de vinhos tintos e brancos
   - Tabela comparativa de vinhos

4. **Contato (contato.html)**
   - Formulário de contato
   - Informações de contato da vinheria
   - Mapa de localização
   - Perguntas frequentes

5. **Blog (blog.html)**
   - Artigo em destaque
   - Listagem de posts recentes
   - Vídeo sobre degustação de vinhos
   - Agenda de eventos
   - Formulário de newsletter

# Efeitos Visuais
O site da Vinheria Agnello conta com uma série de efeitos visuais aplicados por meio de pseudo-classes, pseudo-elementos, transições e animações que enriquecem a experiência do usuário e promovem uma navegação mais fluida e interativa.

# Pseudo-classes
## :hover
Utilizada para realçar elementos interativos quando o usuário passa o cursor sobre eles. Exemplos:

Botões (.btn, .btn-comprar, .btn-categoria, .btn-blog, .btn-evento) mudam de cor ao serem destacados.

Cartões como .produto-card, .valor-card, .blog-card e .timeline-conteudo elevam-se levemente com transform: translateY(-5px).

Imagens em .categoria-card e .galeria-item aplicam um leve zoom com transform: scale(1.05).

## :focus
Aplicado a campos de formulário para indicar que estão ativos, destacando a borda e adicionando box-shadow com a cor primária da vinheria.

## :nth-child(even)
Usado para alternar a cor de fundo em linhas de tabelas e itens da linha do tempo, criando contraste visual.

## .active (classe customizada)
Estiliza o link da navegação que representa a página atual, oferecendo uma melhor orientação ao usuário.

## Validação de formulário (.valido, .invalido)
Realce visual de campos conforme a validação do conteúdo inserido, com cores específicas para erros ou preenchimento correto.

# Pseudo-elementos

## ::before
.banner::before: Cria uma sobreposição escura sobre o banner para melhorar a legibilidade dos textos.

.clube-beneficios li::before: Insere um ícone de check (✓) antes de cada item da lista de benefícios.

## ::after
.timeline::after: Gera a linha central da seção de linha do tempo, criando uma separação visual entre os marcos históricos.

# Transições
Transições foram utilizadas para suavizar alterações visuais, criando uma experiência mais natural ao interagir com elementos da interface:

## Transformações suaves

Aplicadas a elementos como cartões de produto, categorias, valores e blog com transform: translateY(-5px).

## Mudança de cores

Botões e links utilizam transition: background-color 0.3s para tornar a mudança de cor menos abrupta ao passar o mouse.

## Outros elementos com transições

Imagens com zoom, botões com opacidade gradual (.btn-categoria), entre outros.

# Animações

### Logo animada
A logo possui uma animação contínua definida por @keyframes logoAumentar, que alterna o tamanho da marca com o efeito de pulsar (scale: 100% → 80% → 100%), trazendo leveza e movimento para o topo da página.

## Integrantes do Projeto
- Desenvolvido por: João Pedro Godinho
- Desenvolvido por: Vítor Borsato
- Desenvolvido por: Gabriel Droppa
- Desenvolvido por: Ian Teharata
- Desenvolvido por: Isabela de Deus

## Link para o site publicado
- Link: https://jpgodinho.github.io/Site-Vinheria-Agnello/