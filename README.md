<h1>Olá, mundo!</h1>

<p>Esta é minha primeira página.</p>

<img src="https://picsum.photos/300/200">

<h2>Minhas coisas favoritas</h2>

<ul>

  <li>Pizza</li>

  <li>Futebol</li>

  <li>Música</li>

</ul>

<a href="https://www.google.com">Ir para o Google</a> 

<h1>Meus sites favoritos</h1>

<ul>

  <li><a href="https://www.google.com">Google</a></li>

  <li><a href="https://www.youtube.com">YouTube</a></li>

  <li><a href="https://www.wikipedia.org">Wikipédia</a></li>

</ul>

<div class="cartao">

  <h1>Seu Nome</h1>

  <p>Uma frase curta sobre você.</p> h1 {

  color: blue;

  text-align: center;

}

p {

  color: gray;

  font-size: 18px;

}

img {

  border-radius: 10px;

  width: 200px;

  height: auto;

} 

.cartao {

  max-width: 300px;

  margin: 30px auto;

  padding: 20px;

  background-color: white;

  border-radius: 10px;
function mudarFrase() {

  document.getElementById("frase").innerText = "Você clicou no botão!";

}

let cliques = 0;

function mudarFrase() {

  document.getElementById("frase").innerText = "Você clicou no botão!";

}

function contarClique() {

  cliques = cliques + 1;

  document.getElementById("contador").innerText = "Cliques: " + cliques;

}
