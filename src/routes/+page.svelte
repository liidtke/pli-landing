<script lang="ts">
  import "../site.css";

  function open() {
    window.open("https://wa.me/" + "5519996899619");
  }
</script>

<main class="wrapper">
  <nav class="navigation">
    <section class="container">
      <a class="navigation-title">
        <h1 class="title">Patrícia Lisboa</h1>
      </a>
      <ul class="navigation-list float-right">
        <li class="navigation-item computer">
          <a class="navigation-link" href="#abordagem">Abordagem</a>
        </li>
        <li class="navigation-item">
          <a class="navigation-link" href="#contato">
            <button class="button button-outline">Contato</button>
          </a>
        </li>
      </ul>
    </section>
  </nav>

  <header class="header">
    <section class="container">
      <h4>Especialista em Psicologia Clínica</h4>
      <h1>Psicóloga Patrícia Lisboa</h1>
      <p class="small">
        Psicóloga Clínica CRP 10/08202 formada pela Universidade UNASP-SP, Pós
        graduada em Gerontologia e pós graduando em Terapia Cognitivo
        Comportamental.
      </p>

      <button class="button clear" on:click={open}>Entrar em Contato</button>
      <div class="spacer" />
    </section>
  </header>
  <div class="content pink">
    <section class="container">
      <div class="row">
        <div class="column">
          <h3 class="sm">Sobre Mim</h3>
          <p>
            Sou formada desde 2019, tenho 29 anos, nessa foto é tirada dentro do
            meu consultório, pois é um dos lugares que mais eu gosto de estar, é
            nesse ambiente onde atendo os meus pacientes online e presencial,
            aqui é um lugar de acolhimento, trocas e muita escuta com qualidade,
            é nesse espaço também que atendo os meus pacientes online é aqui que
            criamos uma conexão, é aqui que fazemos uma caminhada para o
            encontro do sentido de vida. Trabalho dentro de uma abordagem
            chamada Terapia Cognitivo Comportamental, essa abordagem é
            comprovada cientificamente e os pacientes tem um maior resultado.
          </p>
          <!-- <p class="highlight"> -->
          <!--   Forneço recibo para convênios que trabalham com a modalidade de -->
          <!--   reembolso. -->
          <!-- </p> -->
        </div>
        <div class="column">
          <img class="img-myself" src="/me.jpg" alt="me" />
        </div>
      </div>

      <button class="button" on:click={open}>Entrar em Contato</button>
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
        A minha maior satisfação é poder dar alta ao meu paciente, pois quando esse dia chega fazemos uma retrospectiva e juntos fazemos
        uma análise de como essa pessoa chegou e de como ela está saindo um
        momento singular.
      </p>
    </section>
  </div>

  <div class="content green">
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
    </section>
  </div>

  <div class="content alternate" id="contato">
    <section class="container">
      <h3>Contato</h3>
      <a class="inverted" href="" on:click={open}>
        Whatsapp:
        <img class="whatscontact" src="whats.svg" alt="whatsapp" />
      </a>
      <a class="inverted" href="tel:1999689-9619">Telefone: (19) 99689-9619</a>
      <a class="inverted" href="lisboapatricia098@gmail.com"
        >Email: lisboapatricia098@gmail.com</a
      >
      <a class="inverted" href="http://instagram.com/ouse.pensar"
        >Instagram: @ouse.pensar
      </a>
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
  <title>Psicóloga Maria Julia Marques</title>
</svelte:head>

<style>
  .img-myself {
    border: solid 3pt white;
    border-radius: 4px;
  }

  @media (max-width: 600px) {
    .sm {
      max-width: 230px;
    }
    .img-myself {
      object-fit: fill;
      width: 40%;
      top: 485px;
    }
    .computer {
      display: none;
    }

    .navigation .navigation-list {
      margin-right: 1rem !important;
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
</style>
