
<br />
<div align="center">
  <a href="https://github.com/Dizziolica/SuperMariioJs">
    <img src="/dizziolica.jpg" alt="Logo" width="80" height="80">
  </a>




<h1>Super Mario Jump Game</h1>

  <h3 align="center">Super Mario Project</h3>

  <p align="center">
    Utility Project
    <br />
    <a href="https://github.com/Dizziolica/SuperMariioJs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Dizziolica/SuperMariioJs">View Demo</a>
    
   
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Content</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href= "https://github.com/Dizziolica/SuperMariioJs" >Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#tools">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<p>Este é um pequeno projeto de jogo do Super Mario criado com HTML, JavaScript e CSS. O objetivo do jogo é fazer com que o Super Mario pule os canos que passam rapidamente pela janela do jogo. O jogo é simples de jogar e pode ser executado em um navegador da web.</p>
<h2>Como jogar</h2>
<p>Para começar a jogar, siga as instruções abaixo:</p>
<ol>
  <li>Abra o arquivo <code>index.html</code> em seu navegador da web.</li>
  <li>Pressione a tecla "espaço" para fazer com que o Super Mario pule.</li>
  <li>Evite os canos que passam rapidamente pela tela. Se o Super Mario colidir com um cano, o jogo termina.</li>
</ol>
<h2>Exemplos de código</h2>
<p>O código-fonte deste projeto está disponível no Github. Aqui estão alguns exemplos de código relevantes:</p>
<pre><code>

const mario = document.querySelector('.mario');
const pipe = document.querySelector('.pipe');
const jump = () => {
  mario.classList.add('jump');
  
  setTimeout(() => {
        mario.classList.remove('jump');
  }, 500);
}
</code></pre>
<p>Este código cria a função <code>jump()</code>, que adiciona a classe "animate" ao elemento HTML do Mario e, em seguida, remove essa classe após meio segundo. Esta função é chamada quando a tecla "espaço" é pressionada.</p>
<h2>Instalação</h2>
<p>Para executar o jogo localmente, siga as instruções abaixo:</p>
<ol>
  <li>Clone este repositório: <code>git clone https://github.com/seunome/super-mario-jump-game.git</code></li>
  <li>Abra o arquivo <code>index.html</code> em seu navegador da web.</li>
  <li>Pressione a tecla "espaço" para fazer com que o Super Mario pule.</li>
</ol>
<h2>Contribuição</h2>
<p>Sinta-se à vontade para contribuir com este projeto criando um pull request. Se você encontrar algum bug ou problema, por favor, crie uma issue.</p>
<h2>Créditos</h2>
<p> Este projeto foi inspirado no jogo Super Mario da Nintendo. As imagens utilizadas neste jogo são propriedade da Nintendo.</p>
<h2>Licença</h2>
<p>Este projeto é licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.</p>
