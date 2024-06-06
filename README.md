# WordPress Theme Tutorial

Join me on a journey to master WordPress theme development from the ground up.

## What Is a Theme?

A WordPress theme represents the design of your website. It can control everything from colors to fonts, to the entire layout.

In essence, what you see when viewing the front-end of your site is shaped by the theme.

<details>

<summary>Theme types</summary>

WordPress supports two primary types of themes: [block](https://github.com/FlowExtractAPI/Wordpress-Theme?tab=readme-ov-file#block-themes) and [classic](https://github.com/FlowExtractAPI/Wordpress-Theme?tab=readme-ov-file#theme-types)
.
There is also a classic subtype that is called a hybrid theme

### Block themes

Block themes utilize HTML-based block templates containing block markup.

Both creators and users can make edits to the templates in the Site Editor.

Users can customize global settings and styles defined by the theme’s theme.json file through the Styles interface. Additionally, it is entirely feasible to export a theme directly from the Site Editor without any need to modify the code. While creating a new theme from scratch within the editor is technically not possible, it is feasible to adapt the templates and styles of an existing theme to craft a custom theme.

### Classic themes

Classic themes use a PHP-based templating system, unlike block themes, classic themes have far fewer standards to adhere to, but there are APIs you can use for specific features. The classic theme creation process also requires some minimal PHP, HTML, and CSS code knowledge, at least.

### Hybrid themes
Hybrid themes are merely classic themes that have adopted some modern block-related features, such as global settings and styles or block template parts. This is a widely agreed-upon term by the community, but it is not an “official” theme type. At the end of the day, hybrids are still classic themes.

### What are themes made of?
Themes can include many different folders and file types. The list below is non-exhaustive, but it includes some common things you might see:

- Templates (.html in block themes and .php in classic themes)
- CSS Stylesheets
- JavaScript
- PHP
- Media (images, audio, video, etc.)
-JSON

### Requirements

You can create a theme with no coding knowledge. But you will find it much easier to familiarize yourself with a few web languages.

You will see HTML, CSS, PHP, JSON, and JavaScript within the handbook, so it helps to be able to easily recognize what language you are looking at. HTML and CSS are foundational pieces of the web, so those should be prioritized over others. 

The following are external resources that you can use to learn more:

- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).
- [MDN Web Docs: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS).
- [PHP official documentation](https://www.php.net/docs.php).
- [MDN Web Docs: JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON).
- [MDN Web Docs: JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript).

</details>

<details>

<summary>Core Concepts</summary>

### Theme Structure

WordPress themes are nothing more than a collection of various files that rely on different web technologies, such as HTML, CSS, and PHP.

Block themes also follow a standard structure in how many of those files are laid out.

At its most basic, a theme’s structure will look similar to the following:

- parts/
  - footer.html
  - header.html
- patterns/
  - example.php
styles/
  - example.json
- templates/
  - 404.html
  - archive.html
  - index.html (required)
  - singular.html
  - README.txt
  - functions.php
  - screenshot.png
  - style.css (required)
  - theme.json


</details>
