<script lang="ts">
  import "../site.css";

  function open() {
    window.open("https://wa.me/" + "5511953079175");
  }
</script>

<main class="wrapper">
  <nav class="navigation">
    <section class="container">
      <a class="navigation-title">
        <h1 class="title">Patrícia Lisboa</h1>
      </a>
      <ul class="navigation-list float-right">
        <li class="navigation-item ">
          <a class="navigation-link" href="#abordagem">Objetivo</a>
        </li>
        <li class="navigation-item ">
          <a class="navigation-link" href="#ajudar">Terapia</a>
        </li>
        <li class="navigation-item ">
          <a class="navigation-link" href="#atendo">Atendimento</a>
        </li>

        <li class="navigation-item">
          <a class="navigation-link" href="#contato">
            <a class="navigation-link">Contato</a>
          </a>
        </li>
      </ul>
    </section>
  </nav>




  <header class="header">
    <section class="container">
      <h4>Psicóloga Clínica - Terapia Online e Presencial</h4>
      <h1>Psicóloga Patrícia Lisboa</h1>
      <p class="small">
        Psicóloga Clínica CRP 10/08202 formada pela Universidade UNASP-SP, Pós
        graduada em Gerontologia e pós graduando em Terapia Cognitivo
        Comportamental.
      </p>

      <button class="button clear grow" on:click={open}>Entrar em Contato</button>
      <!-- <div class="spacer" /> -->
    </section>
  </header>
  <div class="content pink">
    <section class="container fade-in">
      <div class="row">
        <div class="column">
          <h3 class="sm">Sobre Mim</h3>

          <img id="me1" class="img-myself only-mobile" src="/me.jpg" alt="me" />
          <p>
            Sou formada desde 2019. Essa foto foi tirada dentro do
            meu consultório, pois é um dos lugares que mais eu gosto de estar, é
            nesse ambiente onde atendo os meus pacientes online e presencial,
            aqui é um lugar de acolhimento, trocas e muita escuta com qualidade. É aqui que
            criamos uma conexão, é aqui que fazemos uma caminhada para o
            encontro do sentido de vida.
          </p>
          <p class="only-pc">
            Trabalho dentro de uma abordagem chamada Terapia Cognitivo
            Comportamental, essa abordagem é comprovada cientificamente e os
            pacientes tem um maior resultado.
          </p>
          <button class="button clear only-pc" on:click={open}>Entrar em Contato</button>
        </div>
        <div class="column only-pc">
          <img id="me2"  class="img-myself only-pc" src="/me.jpg" alt="me" />
        </div>
      </div>
      <div class="row only-mobile">
        <div class="column">
          <p>
            Trabalho dentro de uma abordagem chamada Terapia Cognitivo
            Comportamental, essa abordagem é comprovada cientificamente e os
            pacientes tem um maior resultado.
          </p>
          <!-- <p class="highlight"> -->
          <!--   Forneço recibo para convênios que trabalham com a modalidade de -->
          <!--   reembolso. -->
          <!-- </p> -->
          <button class="button clear" on:click={open}>Entrar em Contato</button>
        </div>
      </div>
    </section>
  </div>

  <div class="content" id="abordagem">
    <section class="container">
      <h3>Objetivo</h3>
      <p>
        Um dos meus maiores objetivos de vida é poder contribuir com a sua saúde
        mental por meio da terapia online, na verdade é isso que dá sentido à
        minha vida, saber que eu posso ajudar uma pessoa a encontrar o seu
        sentido de vida, e durante todo esse tempo de formada eu tenho
        contribuído junto das pessoas que tem ansiedade e depressão que me
        procuram.
      </p>
      <p>
        A minha maior satisfação é poder dar alta ao meu paciente, pois quando
        esse dia chega fazemos uma retrospectiva e juntos fazemos uma análise de
        como essa pessoa chegou e de como ela está saindo um momento singular.
      </p>
    </section>
  </div>

  <div class="content green" id="ajudar">
    <section class="container">
      <div class="row">
        <div class="column">
          <h3>Como a psicoterapia online pode te ajudar?</h3>
          <p>
            A terapia pode ajudar a você a lidar com sua ansiedade, com esse
            sentimento de vazio que as vezes você sente, ela pode te ajudar a se
            organizar, a você aprender a se conhecer a aumentar sua autoestima,
            trabalhar os seus traumas que as vezes lhe atrapalha e você nem
            percebe.
          </p>

          <p>
            E um dos maiores benefícios da terapia online é por que você não
            precisa sair da sua casa, onde quer que você estiver você pode
            realizar.
          </p>
        </div>
        <!-- <button class="button" on:click={open}>Entrar em Contato</button> -->

        <div class="column">
          <img class="img-myself" src="/me2.jpg" alt="me" />
        </div>
      </div>
      <p>
        <strong
          >Vem, pois estou pronta para fazer essa caminhada junto com você.</strong
        >
      </p>
          <button class="button clear" on:click={open}>Entrar em Contato</button>
    </section>
  </div>

  <div class="content" id="atendo">
    <section class="container">
      <div class="row">
        <div class="column">
          <h3>Quem eu atendo?</h3>
          <p>Adolescente, adulto, idoso e casal.</p>

          <p>
            Existem algumas coisas na vida que podem esperar, e outras coisas
            que não tem como aguardar e quando falamos da saúde mental estamos
            falando de algo importante na sua vida que no qual não dá para
            esperar.
          </p>
        </div>
        <!-- <button class="button" on:click={open}>Entrar em Contato</button> -->

        <div class="column">
          <p>Então lhe aguardo para trabalharmos em terapia</p>
          <ul>
            <li>Ansiedade</li>
            <li>Depressão</li>
            <li>Pânico</li>
            <li>Traumas</li>
            <li>Estresse</li>
            <li>Baixa Autoestima</li>
            <li>Insegurança</li>
            <li>Medo</li>
            <li>Dificuldade de se posicionar e dizer não</li>
            <li>Problemas de relacionamentos</li>
            <li>Autoconhecimento</li>
          </ul>
        </div>
      </div>
      <div class="row">
        <div class="column">
          <img class="img-myself" src="/me3.jpeg" alt="me" />
        </div>
      </div>
      <p class="small centered">
        “A pessoa mais forte não é aquela fazendo mais barulho, mas aquela que
        consegue, calmamente, dirigir a conversa para a definição e solução dos
        problemas.” - Aaron Beck
      </p>
    </section>
  </div>

  <div class="content alternate" id="contato">
    <section class="container">
      <h3>Agende seu horário agora</h3>
      <a class="inverted" href="" on:click={open}>
        Whatsapp:
        <img class="whatscontact" src="whats.svg" alt="whatsapp" />
      </a>
      <a class="inverted" href="tel:1195307-9175">Telefone: (11) 953079175</a>
      <a class="inverted" href="mailto:lisboapatricia098@gmail.com"
        >Email: lisboapatricia098@gmail.com</a
      >
      <a class="inverted" href="http://instagram.com/psicologa.patricia7"
        >Instagram: @psicologa.patricia7
      </a>
      <p>Faço recibos para planos de saúde que trabalham com reembolso.</p>
    </section>
  </div>

  <div class="content blue">
    <section class="container">
      <p class="centered">
        Atenção: Este site não oferece atendimento imediato a pessoas em crise
        suicida. Em caso de crise ligue para o CVV 188. Em caso de emergência,
        procure o hospital mais próximo. Havendo risco de morte, ligue
        imediatamente para o SAMU (telefone 192).
      </p>
    </section>
  </div>
</main>

<svelte:head>
  <title>Psicóloga Patrícia Lisboa</title>
</svelte:head>

<style>
  .img-myself {
    border: solid 3pt white;
    border-radius: 4px;
    margin-bottom: 1rem;
  }

  @media (max-width: 600px) {
    .sm {
      max-width: 230px;
    }
    .img-myself {
      object-fit: fill;
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      align-self: center;
    }
    .computer {
      display: none;
    }

    .navigation .navigation-list {
      margin-right: 1rem !important;
    }
    .header .container {
      padding-bottom: 1rem;
      padding-top: 1rem;
    }
  }

  .button-outline {
    color: var(--color1);
    border-color: var(--color1);
  }

  .button:not(.button-outline) {
    background-color: var(--inverted);
    border-color: var(--inverted);
  }

  .button.clear {
    background-color: var(--color4);
    border-color: var(--color4);
  }

  .content {
    padding-top: 4rem;
    padding-bottom: 4rem;
    background-color: var(--bg);
    font-size: 13pt;
    font-weight: bolder;
  }

  p {
    font-size: 12pt;
    font-weight: normal;
  }

  .centered {
    text-align: center;
  }

  .content.orange {
    background-color: var(--orange);
    color: white;
  }

  .content.green {
    background-color: var(--green);
    color: white;
  }

  .content.blue {
    background-color: var(--blue);
    color: white;
  }
  .content.yellow {
    background-color: var(--yellow);
    color: white;
  }

  .content.pink {
    background-color: var(--pink);
    color: white;
  }

  .content.alternate {
    background-color: var(--alternate);
    color: white;
  }

  .content.inverted {
    background-color: var(--inverted);
    color: white;
  }
  a.inverted {
    color: white;
    display: block;
  }

  .whatscontact {
    height: 25px;
  }

  .spacer {
    padding: 2rem;
  }

  p.small {
    margin-bottom: 1rem;
  }

  .highlight {
    margin-top: 50px;
    font-size: 14pt;
  }

  li {
    margin-bottom: 0px;
  }

  .grow{
    animation: leaves 1s ease-in-out infinite alternate;
    -webkit-animation: leaves 1s ease-in-out infinite alternate;
  }

  .fade-in{
    animation: fin 1s ease-in-out;
    -webkit-animation: fin 1s ease-in-out;
  }

  .fade-in-2{
    animation: fin 2s ease-in-out;
    -webkit-animation: fin 2s ease-in-out;
  }

@keyframes leaves {
    0% {
        transform: scale(1.0);
    }
    100% {
        transform: scale(1.1);
    }
}

@keyframes fin {
    0% {
        opacity: 0;
    }
    100% {
        opacity:  1;
    }
}

</style>
