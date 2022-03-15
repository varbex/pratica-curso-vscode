# Visual Studio Code: Cheat Sheet
## Atalhos de Interface
- Abrir Code na pasta atual do terminal -> code . (precisa estar no path)
- Abrir/Buscar arquivos -> Control + P
- Mostrar Todos os Commandos -> Control + Shift + P
- Seguir link de arquivo -> Control + Left Click
- Alternar a sideBar -> Control + B
- Alternar o file explorer -> Control + Shift + E
- Alternar o painel de problemas -> Control + Shift + M
- Alternar o painel do terminal -> Control + '
- Mudar o tema -> Control + K Control + T
- Abrir Settings -> Control + ,
- Side-By-Side -> Control + ]
- Alternar entre os SBS -> Control + \<numero da janela>
- Fechar aba Control + W ou Control + F4
- Fechar aba Control + K W
- Alternar aba Control + Tab
- Abrir aba fechada recentemente -> Control + SHIFT + T
- Modo-Zen -> Control + K Z
## Atalhos do Editor
- Edição em multiplos locais -> Alt + Left Click
- Próxima palavras igual -> Control + D
- Todas as palavras iguais -> Control + Shift + L
- Seleção de coluna -> Alt + Shift + Left Click hold.
- Mover linhas -> Alt + Up/Down Arrow
- Expandir seleção -> Alt + Shift + Left/Right Arrow
- Goto -> Control + G 
- Retornar o Cursor -> Control + U
- Desfazer -> Control + Z
- Refazer -> Control + Y
- Remover espaços -> Control - K Control + X
- Inicio do arquivo -> Control + Home
- Fim do arquivo -> Control + End
- Buscar (conta as ocorrencias) -> Control +  F
- Buscar nos Arquivos -> Control + Shift + F
- Substituir nos Arquivos -> Control + Shift + H
- Deletar atrás do cursor -> Control + Backspace
- Deletar a frente do cursor -> Control + Delete
- Pular palavra -> Control + Left/Right Arrow
- Selecionar Linha -> Control + L
- Deletar Linha -> Control + X
- IntelliSense -> Control + Espaço
- Comentar/Descomentar linha -> Control + /
- Comentar/Descomentar Bloco -> Control + Shift + A
- Identar -> Tab
- Desindentar-> Shift + Tab
## Atalhos do Painel
- Abrir CMD externo -> Control + Shift + C
- Abrir Link -> Control + Left Click
- Abrir novo terminal -> Control + Shift + '
- Alternar o painel do terminal -> Control + '
- Alternar terminais -> Alt + Arrow Key
- Buscar -> Control + F
- Fim do terminal -> Control + End
- Inicio do terminal -> Control + Home
- Terminais Side-By-Side -> Control + Shift + 5

## Plugins Recomendados
- Auto rename tag
- Better Align
- Better Comments
- Bookmarks
- Bracket pair colorizer
- CSS peak
- Code Runner
- Code spell checker
- Color Highlight
- Docker
- ESLint
- GitGraph
- GitLens
- Icon fonts
- Javascript ES6 code snippets
- Live Share
- Live server
- Material Icon Theme
- Open in Browser
- Polacode
- Prettier
- React Native Tools
- Sort Lines
- Todo Highlight
- Todo Tree

### React
- ES7 React/Redux/React-Native snippets
- Auto Import
- React Pure to Class

## Emmet HTML

Emmet adiciona snippets de codigo HTML e CSS para o VSCode.

Referencia completa aqui: https://docs.emmet.io/cheat-sheet/.

hdr + Tab
```html
<header></header>
```

ftr + Tab
```html
<footer></footer>
```

bq + Tab
```html
<blockquote></blockquote>
```

h1{titulo1} + Tab
```html
<h1>titulo1</h1>
```

btn + Tab
```html
<button></button> 
```

div.conteiner + Tab
```html
<div class="conteiner"></div>
```

.conteiner + Tab
```html
<div class="teste"></div>
```

btn.main-btn + Tab
```html
<button class="main-btn"></button>
```

btn.classe1.classe2.classe3 + Tab
```html
<button class="classe1 classe2 classe3"></button>
```

btn#submit + Tab
```html
<button id="submit"></button>
```

btn#submit.btn-enviar + Tab
```html
<button id="submit" class="btn-enviar"></button>
```

header+main+footer + Tab
```html
<header></header>
<main></main>
<footer></footer>
```

div#lista.lista-itens{Ingredientes}+p.item-lista{Banana}+span.bold{Macia} + Tab
```html
<div id="lista" class="lista-itens">Ingredientes</div>
<p class="item-lista">Banana</p>
<span class="bold">Macia</span>
```

nav#nav-bar>ul.lista-link>li.nav-link*5 + Tab
```html
<nav id="nav-bar">
    <ul class="lista-link">
        <li class="nav-link"></li>
        <li class="nav-link"></li>
        <li class="nav-link"></li>
        <li class="nav-link"></li>
        <li class="nav-link"></li>
    </ul>
</nav>
```

a[href="www.google.com" target="_black"] + Tab
```html
<a href="www.google.com" target="_black"></a>
```

form:get[action=buscar.php] + Tab      
```html
<form action="buscar.php" method="get"></form>
```

form:post[action=submit.php] + Tab
```html
<form action="submit.php" method="post"></form>
```

input:email + Tab
```html
<input type="email" name="" id="">
```

! + Tab
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

ul.lista>lorem.item*5
```html
<ul class="lista">
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam quo assumenda cum at labore numquam, eius odit mollitia quos sequi nihil eum voluptatum earum possimus hic obcaecati reiciendis ipsum maxime.</li>
    <li>Qui accusamus sint temporibus non amet? Tempora reprehenderit eveniet, minus natus a omnis nemo tempore quos necessitatibus. Pariatur mollitia minima eligendi, optio et commodi deserunt neque quae reprehenderit fugiat dolores.</li>
    <li>Ullam veritatis sequi nesciunt explicabo totam qui, praesentium, omnis tempora pariatur consectetur ad voluptas, voluptatum repudiandae maxime nostrum eum fugiat iste soluta blanditiis eligendi libero. Eaque quas quo officiis quod?</li>
    <li>Fugiat quia est explicabo dolorem molestias nisi repellendus! Fugit optio nisi non tempora sapiente! Iure, natus vitae nostrum, commodi molestiae provident magnam officiis placeat architecto officia quidem quasi ab veniam.</li>
    <li>Voluptatem rerum iure debitis! Doloribus, veritatis reiciendis. Sit ab deserunt delectus nihil. Rem nihil quas, nobis quaerat id maiores at, perspiciatis veniam placeat minus qui eum tempora molestias esse distinctio!</li>
</ul>
```

h${header $}*5
```html
<h1>header 1</h1>
<h2>header 2</h2>
<h3>header 3</h3>
<h4>header 4</h4>
<h5>header 5</h5>
```

## Emmet CSS

c:#0
```css
color: #000;
```

po:s
```css
position: static;
```

po:a
```css
position: absolute;
```

m:40px
```css
margin: 40px;
```

fl:l
```css
float: left;
```

d:b
```css
display: block;
```

