# Angatu — Conceito de Morte entre os Povos

Site desenvolvido como **Projeto Integrador** do 1º ano do Ensino Médio Técnico em **Desenvolvimento de Sistemas** da **ETEC Parque Belém** (2023).

O site explora como a morte é compreendida e vivida em diferentes culturas, épocas e religiões — da Antiguidade à Modernidade, passando pela filosofia, pela arte e pelos povos indígenas. Todo o conteúdo está disponível em **português** e **inglês**.

## Como abrir

Não precisa instalar nada: basta abrir o arquivo `index.html` (na raiz) em qualquer navegador. Ele redireciona para a página inicial em português.

> É necessário estar conectado à internet, pois o Bootstrap, o Font Awesome e as fontes do Google são carregados via CDN.

## Navegação

```
Página inicial ──► Login / Cadastro ──► Introdução ──► Capítulos, livros, filmes e "Sobre"
```

| Página | Português | Inglês |
| --- | --- | --- |
| Página inicial | [`pt/index.html`](pt/index.html) | [`en/index.html`](en/index.html) |
| Login | [`pt/login.html`](pt/login.html) | [`en/login.html`](en/login.html) |
| Cadastro | [`pt/cadastro.html`](pt/cadastro.html) | [`en/cadastro.html`](en/cadastro.html) |
| Introdução | [`pt/introducao.html`](pt/introducao.html) | [`en/introducao.html`](en/introducao.html) |
| Cap. 1 — A morte na Antiguidade | [`pt/antiguidade.html`](pt/antiguidade.html) | [`en/antiguidade.html`](en/antiguidade.html) |
| Cap. 2 — Rituais antigos | [`pt/rituais-antigos.html`](pt/rituais-antigos.html) | [`en/rituais-antigos.html`](en/rituais-antigos.html) |
| Cap. 3 — A morte nas religiões | [`pt/religiao.html`](pt/religiao.html) | [`en/religiao.html`](en/religiao.html) |
| Cap. 4 — A morte na visão dos indígenas | [`pt/povos-indigenas.html`](pt/povos-indigenas.html) | [`en/povos-indigenas.html`](en/povos-indigenas.html) |
| Cap. 5 — A morte na filosofia | [`pt/filosofia.html`](pt/filosofia.html) | [`en/filosofia.html`](en/filosofia.html) |
| Cap. 6 — A morte na Modernidade | [`pt/modernidade.html`](pt/modernidade.html) | [`en/modernidade.html`](en/modernidade.html) |
| Cap. 7 — A morte na arte | [`pt/arte.html`](pt/arte.html) | [`en/arte.html`](en/arte.html) |
| Livro 1 — *História da morte no Ocidente* (Philippe Ariès) | [`pt/historia-da-morte-no-ocidente.html`](pt/historia-da-morte-no-ocidente.html) | [`en/historia-da-morte-no-ocidente.html`](en/historia-da-morte-no-ocidente.html) |
| Livro 2 — *Histórias lindas de morrer* (Ana Claudia Quintana Arantes) | [`pt/livro.html`](pt/livro.html) | [`en/livro.html`](en/livro.html) |
| Filmes | [`pt/filmes.html`](pt/filmes.html) | [`en/filmes.html`](en/filmes.html) |
| Sobre / Desenvolvedores | [`pt/desenvolvedores.html`](pt/desenvolvedores.html) | [`en/desenvolvedores.html`](en/desenvolvedores.html) |

As páginas `carregando-login.html` e `carregando-cadastro.html` são telas de carregamento rápidas exibidas antes do login e do cadastro.

> As telas de login e cadastro são apenas visuais (protótipo): não há back-end nem validação dos dados.

## Estrutura de pastas

```
├── index.html            # redireciona para pt/index.html
├── pt/                   # páginas em português
├── en/                   # páginas em inglês (mesmos nomes de arquivo)
└── assets/
    ├── css/
    │   ├── tema.css      # visual comum a todas as páginas (cores, fontes, menu, rodapé)
    │   ├── acesso.css    # telas de login e cadastro
    │   ├── pt/           # um arquivo CSS por página
    │   └── en/
    ├── img/              # imagens organizadas por página (logo.png é compartilhado)
    └── js/
        └── carrossel.js  # carrossel de imagens da Introdução
```

Como as páginas têm o mesmo nome nas duas pastas, trocar de idioma é só trocar `pt/` por `en/` no caminho.

## Visual

O arquivo `assets/css/tema.css` é carregado por último em todas as páginas e define a identidade visual do site:

- **Cores:** a paleta original do projeto: fundo azul-marinho (`#262736`), texto claro e detalhes em azul (`#4292bf`).
- **Fontes:** *Cormorant Garamond* nos títulos e *Inter* no texto corrido.
- **Responsivo:** as páginas se adaptam a celular, tablet e computador.

Para mudar alguma cor do site inteiro, basta alterar as variáveis no começo de `tema.css`.

## Tecnologias

- HTML5 e CSS3
- JavaScript
- [Bootstrap 5](https://getbootstrap.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) e Google Fonts

## Apresentação

A apresentação do projeto foi feita no Canva: [slides do projeto](https://www.canva.com/design/DAFyJEIvnqE/lzP3qozoC-rrbT45QTGSsQ/view).

## Equipe

| Nome | Participação |
| --- | --- |
| **Isabelly Pereira de França** | Pesquisa, criação de páginas de conteúdo, parte do design do site, modelagem de dados e ligação/interação entre as páginas |
| **Sabrina Costa** | Pesquisa inicial, criação de páginas, levantamento de requisitos mínimos, modelagem do banco de dados e criação de formulários |
| **Thabata Oliveira** | Páginas de banco de dados, interação entre páginas, virtualização do site, wireframe e protótipo |
| **Thais Mamani Rodriguez** | Código base do site (menu e rodapé), casos de uso, design e interação do site |

---

Projeto acadêmico, sem fins comerciais. As imagens e os trechos citados pertencem aos seus respectivos autores.
