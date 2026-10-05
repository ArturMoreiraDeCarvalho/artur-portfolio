# Artur Moreira de Carvalho — portfólio

Site estático do portfólio de Artur Moreira de Carvalho, desenvolvedor de software júnior com foco em backend (PHP/Laravel, SQL/Oracle e Python) em sistemas financeiros e contábeis.

- Português: <https://arturmoreiradecarvalho.github.io/artur-portfolio/>
- English: <https://arturmoreiradecarvalho.github.io/artur-portfolio/en/>

## Conteúdo

- Hero com links para os cases, o currículo em PDF, LinkedIn e GitHub, e uma faixa com quatro fatos verificáveis.
- Cases no mesmo roteiro (problema, contexto, contribuição, arquitetura, decisões, tecnologia e status), cada um com um diagrama em HTML/CSS:
  - Assistente de Contabilidade com IA (trabalho, código proprietário; o site publica só uma demonstração em vídeo com dados fictícios, sem código nem dados reais);
  - TrilhaDocs (código público).
- Experiência, tecnologias, projetos de estudo e contato (e-mail, LinkedIn, GitHub e currículo em PT e EN).

## Técnica

- HTML e CSS, sem JavaScript, build step, fontes remotas, analytics ou recursos de terceiros. Fontes do sistema.
- HTML semântico, link para pular ao conteúdo, foco visível, tema claro/escuro por `prefers-color-scheme`, transições desligadas com `prefers-reduced-motion` e layout responsivo de 360 px a 1920 px.
- SEO: `title` e `description` por idioma, `canonical`, `hreflang` (pt-BR, en, x-default), Open Graph/Twitter Card com imagem por idioma (`og-image.png`, `og-image-en.png`, 1200×630, geradas a partir dos SVGs), JSON-LD `ProfilePage`/`Person`, `sitemap.xml` e `robots.txt`.
- Currículos públicos em `assets/cv/` (sem telefone).

## Desenvolvimento local

Sirva a pasta pai com qualquer servidor estático e abra `/artur-portfolio/` (a página 404 usa caminhos absolutos do GitHub Pages). GitHub Pages publica a branch `main` a partir da raiz.

## Licença

Código sob a licença [MIT](LICENSE). O Assistente de Contabilidade com IA descrito no site é propriedade do Grupo PZM; a licença não se estende a marcas ou materiais de terceiros, nem ao vídeo de demonstração (música de Sascha Ende, CC BY 4.0; efeitos sonoros Kenney, CC0).
