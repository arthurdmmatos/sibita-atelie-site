Sibita Ateliê
Parte I
Links:
Site Publicado (Rodando!): https://arthurdmmatos.github.io/sibita-atelie-site/ 
Protótipo de Design (Figma): https://www.figma.com/design/DzcNJxT7CxhxwgmEcIN29p/Ateli%C3%AA?node-id=0-1&t=GT1776HJ5zsXzFDM-1
Repositório: https://github.com/arthurdmmatos/sibita-atelie-site 
(Observação: O link do Repositório e do Site Publicado são iguais, conforme configurado no GitHub Pages.)

Sobre o Projeto

Este projeto consiste na criação da interface de uma loja online para o Sibita Ateliê (loja da minha mãe), um negócio de artesanato que trabalha com crochê e amigurumis. O objetivo principal era construir um site responsivo e acolhedor, utilizando as cores da marca (rosa e lilás) para criar uma experiência de navegação agradável e focada na usabilidade móvel.

Destaques da Implementação

Design Afetivo: A paleta de cores e a tipografia foram escolhidas para refletir o carinho das peças de crochê.
Mobile-First: Toda a estilização e layout foram pensados primeiro para o celular (Mobile-First), garantindo o acesso fácil de qualquer dispositivo.
Interatividade: Links funcionais para contato direto (WhatsApp e Email) para facilitar as encomendas.

Ferramentas e Linguagens

HTML5: Estrutura semântica (o esqueleto do site).
CSS3: Estilização, variáveis (root) e Media Queries.
Git & GitHub: Versão do código e publicação do site.
Figma: Protótipo visual.

Estrutura de Pastas

A estrutura é simples para um projeto estático:
- ./ (Raiz): index.html e arquivos essenciais
- ./css/: style.css
- ./img/: Arquivos de imagens do projeto (logo, fotos dos produtos)

Jornada do Código e Datas

Tudo foi feito hoje, dia 14/10/2025. Cheguei na católica 11:40 da manhã e estou fazendo o README às 20:30 (Tive pausa para almoçar).

Tive muitos problemas:
1.  Ajustes no Figma para alinhamento final do design.
2.  Configuração inicial do GitHub.
3.  Um problema do github não carregar as imagens e o CSS (ficando só o HTML puro).

Depois de tempos ajustando o HTML e CSS, está tudo resolvido e o site está feito!

Parte II
06/11/2025
O que está funcionando bem?
- Os botões dos menus, media query, o e-mail e número para contato e o formulário.

Quais elementos HTML se repetem em várias páginas?
- Header e footer.

Onde o layout quebra ou fica estranho?
- Nenhum lugar.
  
Quais melhorias fariam diferença real para o usuário do pequeno negócio?
-Catálogo maior dos produtos, o formulário no futuro poderia ser realmente 100% funcional.

Quais componentes foram criados e como eles estão organizados?
- Foram criados componentes reutilizáveis para o header (cabeçalho) e o footer (rodapé), que aparecem em todas as páginas do site.
- O header inclui o logo da marca e o menu de navegação. Ele foi separado em um arquivo próprio e incluído via iframe, facilitando atualizações em todas as páginas ao mesmo tempo.
- O footer contém as informações de direitos da loja e também foi separado para reutilização.

Como o site está estruturado?
- Toda a estrutura utiliza o padrão de pastas recomendado: arquivos HTML na raiz, pasta css/ para estilos, pasta img/ para imagens e pasta componentes/ para os componentes reaproveitáveis.
- Em todos os arquivos HTML principais (index.html, sobre.html, contato.html), o header é incluído pelo iframe. Depois vem o conteúdo principal, seguido pelo footer.
- Os elementos que se repetem em várias páginas (header, footer) foram modularizados para evitar duplicidade e fazer a manutenção ser mais simples.

Como os componentes e a estrutura ajudam na manutenção e acessibilidade do site?
-Separar o header e o footer permite modificar fácil o menu ou informações sem precisar editar cada página manualmente.
- O uso correto das tags semânticas HTML (como <main>, <section>, <nav>, <footer>) melhorou a navegação para leitores de tela e motores de busca.
-Labels foram associados aos campos do formulário para garantir acessibilidade. O skip-link foi implementado para permitir navegação rápida pelo teclado.

Resumo da estrutura de pastas do site:
- Raiz do projeto: arquivos principais (index.html, etc.)
- css/: contém style.css com estilos globais
- img/: imagens da marca e dos produtos
- componentes/: arquivos de header e footer reutilizáveis

Testes e validacões
O site foi testado utilizando navegação por teclado (Tab e Shift+Tab), validador do Google Lighthouse e verificador WAVE online para análise de acessibilidade básica. Todas as áreas interativas e formulários possuem labels corretas, imagens com texto alternativo e o skip-link está funcional em todas as páginas.

Rubrica:
- Modularização do Código HTML: Proeficiente 5 a 6 (Talvez dê para separar mais coisas, separei o header,footer, produto card e o FAQ, que sao elementos que se repetem)

- Acessibilidade: Em desenvolvimento 3 a 4 (Talvez as cores não foram as melhores para a visibilidade, porem combina com a proposta do trabalho da minh mãe, o botão tab está funcionando tudo certo)

- Responsividade: Avançado 7 a 8 (Tudo perfeito, atraves do media query e os grids, as paginas ficam proporcionais independentes se for no desktop ou mobile)

-Organização e manutenibilidade do código: Em desenvolvimento 3 a 4 (Dá para organizar melhor, por mais que cada coisa está em devida pasta, pode ser que na parte do codigo, algo fique colocado em outro lugar apos eu ter corrigido e so ter colocado no final)

-Design Visual Coerente: Em desenvolvimento 3 a 4 (Talvez as cores que escolhi possam ser ruim para pessoas com dificuldades, elas foram escolhidas por que acho que representa bem o trabalho da minha mãe)

-Hierarquia visual e layout: Proeficiente 5 a 6 (Separei o que era mais importante e coloquei de forma que fosse melhor de ver)

-Usabilidade e Experiencia do Usuario: Proeficiente 5 a 6 (Está bem visivel os botoes que são para interagir e o formulario, para que não cause confusao)

-Alinhamento com o negocio: Proeficiente 5 a 6 (As cores e o design todo remete muito ao trabalho da minha mãe, onde vende coisas que são feitas com muito amor e carinho, e por isso a cor rosa foi escolhida como principal cor do site)



- Sibita Ateliê;
- Arthur Dantas Machado Matos, Fiz tudo;
- Loja virtual de Amigurimis personalizados;
- https://www.figma.com/design/DzcNJxT7CxhxwgmEcIN29p/Ateli%C3%AA?node-id=0-1&t=GT1776HJ5zsXzFDM-1;
- HTML5, CSS3;
- sibita-atelie-site-main
  |
  ├  componentes
  |      |
  |      ├faq-item
  |      ├footer
  |      ├header
  |      ├produto-card
  |
  ├     css
  |      |
  |      ├style
  |
  ├     img
  |      |
  |      ├enfeite-quarto
  |      ├jesus
  |      ├logo
  |      ├papelaria-personalizada
  |      ├pets
  |      ├urso
  |
  ├     contato
  ├     index
  ├     README.md
  ├     sobre
- Parte 1: Construção do site, Parte 2: Implementação do que faltava e alguns ajustes, Parte 3:;
- Ent);
- **Espaço reservado para o link do GitHub Pages** (vocês vão adicionar depois).
   


Desenvolvedor

Arthur Dantas Machado Matos 
Matrícula: UC25200448
