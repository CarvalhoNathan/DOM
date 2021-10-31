# Aula 4 - Eventos

Explicar o que são eventos
Apresentar eventos mais utilizados
Ensinar como acionar os eventos

## Tipos de eventos

Eventos do mouse:
```
mouseover, mouseout
```
<br>

Eventos de clique:
```
click, dbclick
```
<br>

Eventos de atualização:
```
Change, load
```
## Adicionando os eventos

### Event listener:

É feito diretamente no Javascript, cria um evento que vai ser adicionado no momento em que o usuário realizar determinanda ação.
```js
const botao = document.getElementById("meuBotao");

botao.addEventListener("click", outraFuncao);
```

## Atributo HTML

Especifica a função a ser chamada diretamente no elemento HTML.
```html
<html>
<body>

<h1 onclick="mudaTexto(this)"Clique aqui!</h1>

<script>
 function mudaTexto(id) {
  id.innerHTML = "Mudei!";
 }
</script>

</body>
</html>
```
