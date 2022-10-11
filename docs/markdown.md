

# le Markdown


Quelques exemples
D'abord le guide de celui qui a écris le markdown :
[John Gruber’s Markdown documentation.](https://daringfireball.net/projects/markdown/) 

ensuite

[Entrainer vous en ligne](https://www.markdowntutorial.com/fr/)

**Pandoc** librairie incontournable
la reine des conversions tout genre

https://pandoc.org/

Vous ne voulez pas installer la suite microsoft sur votre machine ou avoir quelconque lien avec microsoft
il est possible de convertir des fichiers word avec la ligne ci-dessous 
vous remarquerez les extentions qui se charge de copier les images dans un répertoire 

```
pandoc mondocument.docx -o mondocument.md --extract-media=./images/

```

[John Gruber’s Markdown documentation.](https://daringfireball.net/projects/markdown/) The original guide written by the creator of Markdown.
[Markdown Tutorial.](https://www.markdowntutorial.com/fr/) An open source website that allows you to try Markdown in your web browser.
[Awesome Markdown.](https://github.com/mundimark/awesome-markdown) A list of Markdown tools and learning resources.
[Typesetting Markdown](https://dave.autonoma.ca/blog/2019/05/22/typesetting-markdown-part-1). A multi-part series that describes an ecosystem for typesetting Markdown documents using pandoc and ConTeXt.