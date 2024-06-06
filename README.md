# WordPress Theme Tutorial

Join me on a journey to master WordPress theme development from the ground up.

## What Is a Theme?

A WordPress theme represents the design of your website. It can control everything from colors to fonts, to the entire layout.
In essence, what you see when viewing the front-end of your site is shaped by the theme.

## Theme types

WordPress supports two primary types of themes: [block](https://github.com/FlowExtractAPI/Wordpress-Theme?tab=readme-ov-file#block-themes) and [classic](https://github.com/FlowExtractAPI/Wordpress-Theme?tab=readme-ov-file#theme-types)
.
There is also a classic subtype that is called a hybrid theme

### Block themes

Block themes rely on HTML-based block templates that contain block markup. Both creators and users can edit the templates in the Site Editor. Users can also customize global settings and styles defined by the theme’s theme.json file through the Styles interface. 
It’s also possible to export a theme directly from the Site Editor without touching any code. Technically, you cannot create a new theme from scratch entirely from the editor, but you can modify the templates and styles of an existing theme—in essence, creating a custom theme of your own.

### Classic themes

Classic themes use a PHP-based templating system, unlike block themes, classic themes have far fewer standards to adhere to, but there are APIs you can use for specific features. The classic theme creation process also requires some minimal PHP, HTML, and CSS code knowledge, at least.
