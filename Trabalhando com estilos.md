# Aula 3 - Trabalhando com estilos

Ensinar como manipular estilos de elementos HTML

## Classes
```js
Element.classList
```
<br>

Exemplo no HTML
```html
<div id="meu-elemento" class="classe">
 <!-- resto do código aqui -->
</div>
```
```js
const meuElemento = document.getElementById("meu-elemeto")

meuElemento.classList.add("novo-estilo");
// Adiciona a classe "meu estilo"

meuElemento.classList.remove("classe")
// Remove a classe "classe"

meuElemento.classList.toggle("dark-mode")
// Adiciona a classe "dark-mode" caso ela não exista em toda lista e caso exista ele remove
```
<br>

Resultado dessa operação
```html
<div id="meu-elemento" class="novo-estilo dark-mode">
 <!-- resto do código aqui -->
</div>
```

## CSS

Acessando diretamente o CSS de um elemento
```js
document.getElementByTagName("p").style.color = "blue";
```
