# O que é uma página?

Podemos pensar num site como ==uma pasta com arquivos HTML que podemos acessar no navegador==. Uma página, no caso, é um arquivo HTML que está no projeto.

Ao criarmos vários arquivos HTML no mesmo projeto, estaremos criando um website de múltiplas páginas, podendo linkar páginas a páginas usando [[HTML - Âncoras|âncoras]] e [[Caminho dos arquivos#Caminhos relativos|caminhos relativos]].

```text
projeto/
projeto/index.html
projeto/sobre.html
projeto/assets/
projeto/assets/css
projeto/assets/css/style.css
```

No projeto acima, temos duas páginas. Se, por exemplo, fôssemos *linkar* index.html em sobre.html, bastaria adicionar ao conteúdo de sobre.html:

```html
<a href="./index.html" alt="Página inicial">Página inicial</a>
```

>[!tip] DICA
>Organize arquivos, como imagens, CSS e JavaScript, dentro de uma pasta chamada "assets", para separar o que é página (HTML) do que é recurso.

#HTML #Websites