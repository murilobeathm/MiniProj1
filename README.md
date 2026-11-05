# MiniProj1 — Currículo Vitae em SPA (VueJS)

Mini projeto de desenvolvimento web: um currículo vitae construído como **Single Page Application (SPA)** com a framework **VueJS 3** e o **Vue Router 4**.

## Estrutura do repositório

| Ficheiro | Descrição |
|---|---|
| `index.html` | A aplicação SPA (HTML, CSS e componentes Vue num só ficheiro). |
| `docs/wireframes.html` | Prototipagem (wireframes) de todas as páginas e janelas modais, com anotações de funcionalidade. |
| `docs/wireframes.pdf` | Os mesmos wireframes exportados em PDF. |
| `link-git.txt` | Link do projeto Git, para a submissão da tarefa. |

## Características

- **Framework VueJS:** Vue 3 e Vue Router 4 carregados por CDN, sem passo de build.
- **Componentes:** `AppHeader`, `AppFooter`, `ModalBox`, `ContactForm` e um componente por página (`InicioPage`, `QuemSouPage`, `OQueFacoPage`, `HobbiesPage`).
- **Navegação por links internos:** o Vue Router em modo hash (`#/`, `#/quem-sou`, `#/o-que-faco`, `#/hobbies`) mostra apenas a página ativa, sem recarregar. Os botões *Voltar* e *Avançar* do browser funcionam.
- **Conteúdo orientado a dados:** experiência, formação, competências, hobbies e redes sociais estão num objeto de dados e são desenhados com `v-for`, `v-if` e interpolação.
- **Janelas modais:** formulário de contacto (com `v-model` e validação) e detalhes de cada hobby. Fecham com ✕, com um clique fora da janela ou com a tecla Esc.
- **Rodapé com identidade virtual:** ícones de Facebook, X (Twitter), LinkedIn, GitHub, Instagram e YouTube, visíveis em todas as páginas.
- Design responsivo (menu móvel) e tema claro/escuro.

## Como abrir

Abrir o ficheiro `index.html` diretamente no browser (não precisa de servidor). É necessária ligação à internet para carregar o VueJS a partir da CDN.
