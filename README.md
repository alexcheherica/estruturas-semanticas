# 📚 Estruturas Semânticas + CSS

## 🧱 O que são Estruturas Semânticas?

As **estruturas semânticas** do HTML são elementos que descrevem claramente o significado do seu conteúdo tanto para navegadores quanto para desenvolvedores. Elas melhoram a **acessibilidade**, **SEO** e a **manutenção** do código.

### Exemplos de Tags Semânticas:
| Tag         | Significado                                  |
|-------------|----------------------------------------------|
| `<header>`  | Cabeçalho da página ou de uma seção          |
| `<nav>`     | Navegação (links de menu, por exemplo)       |
| `<main>`    | Conteúdo principal da página                 |
| `<section>` | Seção de conteúdo relacionado                |
| `<article>` | Conteúdo independente (ex: post de blog)     |
| `<aside>`   | Conteúdo secundário (ex: sidebar)            |
| `<footer>`  | Rodapé da página ou de uma seção             |

## 🎨 Aplicando CSS

É possível estilizar essas tags normalmente com CSS, como qualquer outra tag HTML.

### Exemplo:
```html
<header>
  <h1>Meu Site</h1>
</header>
<nav>
  <a href="/">Início</a>
  <a href="/sobre">Sobre</a>
</nav>
<main>
  <section>
    <h2>Bem-vindo</h2>
    <p>Conteúdo principal aqui.</p>
  </section>
</main>
