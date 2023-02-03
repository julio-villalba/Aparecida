<template>
  <div class="home">
    <div class="line"></div>
    <div class="page-title">
      <div>
        <h1>Aparecida Miranda</h1>
        <h3>Psicóloga Clínica e Esportiva</h3>
        <h3>CRP 05/42778</h3>
      </div>
      <div class="line"></div>
    </div>
    <img class="foto" src="../assets/foto2.jpg" />
    <div class="line"></div>
    <div class="about">
      <h2>Sobre</h2>          
      <ul class="lista-portfolio">
        <li class="item-lista-portfolio">
          Graduada em Psicologia pela UVA.
        </li>
        <li class="item-lista-portfolio">
          Graduada em Pedagogia pelo UNIFESO.
        </li>
        <li class="item-lista-portfolio">
          Especialista em Psicoterapia de Família e Casal pela PUC-Rio.
        </li>
        <li class="item-lista-portfolio">
          Especialista em Psicologia e Neurociências do Esporte pelo IBMR / Laureate International
          Universities.
        </li>
        <li class="item-lista-portfolio">
          Terapeuta Cognitivo Comportamental pelo IBH.
        </li>
        <li class="item-lista-portfolio">Coach pela Academia Emocional.</li>
        <li class="item-lista-portfolio">
          Atende pacientes com transtornos de ansiedade, transtornos psicóticos,
          problemas de relacionamentos, transtornos do controle dos impulsos,
          transtornos dissociativos, transtornos de adaptação, transtornos do
          humor, transtornos da personalidade, transtornos da aprendizagem.
        </li>
        <li class="item-lista-portfolio">
          Atua como orientadora vocacional e profissional com adolescentes em
          fase da primeira escolha profissional e jovens adultos em reorientação
          profissional.
        </li>
        <li class="item-lista-portfolio">
          Trabalha com atletas de alto rendimento de diversas modalidades, desde
          2010.
        </li>
        <li class="item-lista-portfolio">
          Atendimento Individual, Casal e Família
        </li>
      </ul>
    </div>
    <div class="line"></div>
    <div class="book">
      <h2>Publicação</h2> 
      <img class="foto2" src="../assets/livro.jpg" />  
      <p>
        <strong>
          Sinopse
        </strong>
      </p>              
      <p>
        &nbsp; &nbsp; A Filha de Onélia oferece-nos sua história de vida como ponto de partida para um diálogo sobre vivências comuns à muitas mulheres. Ao revisitar o passado, mais propriamente a história da mulher, ela debate como a construção de um lugar de igualdade e autonomia para a mulher foi um processo de muitas lutas que possibilitaram que pudesse estudar, trabalhar e fazer escolhas, para além da maternidade e do casamento.
      </p>
      <p>
        &nbsp; &nbsp; No livro A Filha de Onélia: a visão de uma mulher na contemporaneidade, Aparecida Miranda nos apresenta uma reflexão importante sobre temas sensíveis e necessários na atualidade. A autora transita por dois universos ricos, iniciando pela sua história de vida, com momentos de vulnerabilidade, de fé, de coragem, de resiliência e de muito amor, e o das reflexões sobre as inúmeras mudanças que se deram na sociedade contemporânea para a vivência das mulheres.
      </p>     
      <br>
      <p>        
        <strong>
          Como adquirir:
        </strong>
      </p>
      <p><a href="https://www.gruponovoseculo.com.br/index.php?route=product/product&product_id=2239&search=filha+de+onelia" target="_blank" rel="www.gruponovoseculo.com.br">www.gruponovoseculo.com.br</a></p>
      <p><a href="https://www.amazon.com.br/Filha-On%C3%A9lia-vis%C3%A3o-mulher-contemporaneidade/dp/6555614331/ref=sr_1_1?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2ZK9E61019M8I&keywords=a+filha+de+onelia&qid=1672317321&sprefix=a+filha+de+oneli%2Caps%2C281&sr=8-1" target="_blank" rel="www.amazon.com.br">www.amazon.com.br</a></p>
      <p><a href="https://linktr.ee/aparecidamiranda" target="_blank" rel="linktr">linktr.ee</a></p>
      <br>
    </div>
    <div class="line"></div>
    <div class="footer">
      <h2>Contatos</h2>
      <div>
        <ul>
          <li>
            <a href="https://linktr.ee/aparecidamiranda" target="_blank"
              ><i class="fa-brands fa-whatsapp fa-2xl"></i
            ></a>
          </li>
          <li>
            <a
              href="https://instagram.com/aparecidamirandapsicologa?utm_medium=copy_link"
              target="_blank"
              ><i class="fa-brands fa-instagram fa-2xl"></i
            ></a>
          </li>
          <!-- <li>
            <a href="#" ><i class="fa-brands fa-linkedin fa-2xl"></i></a>
          </li> -->
        </ul>
        <br>
      </div>
    </div>
    <div class="line2">
      <p class="copyright">© 2023 Aparecida Miranda - All Rights Reserved</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
};
</script>

<style>

.foto {
  height: 38%;
  width: 38%;
  border-radius: 50%;
  margin-bottom: 30px;
}

.foto2 {
  height: 38%;
  width: 38%;
  margin-bottom: 30px;
  padding: 15px;
}

h1 {
  color: beige;
  font-weight: bolder;
  font-size: xx-large;
}

h2 {
  color: beige;
  font-weight: bolder;
}

h3 {
  color: beige;
  font-weight: bolder;
  font-size: medium;
}

p {
  font-size: medium;
  margin-bottom: 10px;
  color: beige;
  margin-right: 10px;
}

a {
  color: gold;
}

.lista-portfolio {  
  text-align: left; 
  margin-left: 30px;
}

.item-lista-portfolio {
  list-style: disc;  
  font-size: medium;
  margin-bottom: 10px;
}

.page-title {
  margin-bottom: 30px;
}

.home {
  background: #000 url("../assets/bg.jpg");
}

.about {    
    text-align: left;
    margin-left: 30px;
}

.book {
   text-align: left;
   margin-left: 30px;
}

.line {
  height: 10px;
  background: #000 url("../assets/h.png") repeat top center;
}

.line2 {
  height: 50px;
  background: #000 url("../assets/n.png") repeat top center;
}

.footer {
  /* height: 80px;
  width: 100%;
  margin-bottom: 30px;
  background: #000 url("../assets/bg.jpg"); */
  text-align: left;
  margin-left: 30px;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

li {  
  padding: 15px;
  font-size: x-large;
  color: beige;
}

.copyright {
  color: beige;
  font-size: small;
  padding: 20px;
  text-align: left;
}

</style>