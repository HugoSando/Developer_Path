# project notes

node.js
-sudo apt update
-sudo apt install nodejs
-node -v

npm
-sudo apt install npm
-npm -v
-npm init -y

sass
-npm install sass --save-dev
-sudo npm install -g sass

crear carpeta de sass y crear style.scss
-sass --watch sass:css

BEM convention (Block Element Modifier)
-Double Underscore (__): to separate a block and its elemnts `<nav class="nav">
    <a class="nav__link" href="#">Home</a>
    <a class="nav__link" href="#">About</a>
    <a class="nav__link" href="#">Contact</a>
</nav>
`
-Double Hyphen (--): to add variations to a block or element `<button class="button button--primary">Primary Button</button>
<button class="button button--secondary">Secondary Button</button>
`

