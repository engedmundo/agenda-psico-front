<template>
  <div>
      <ul class="navigation">
        <li><a>Espaço para abrir painel esquerdo</a></li>
        <li><a>Espaço do meio</a></li>
        <li><a>Info de usuário</a></li>
      </ul>
  </div>
  <div class="body">rtrtg</div>
  <footer class="footer">
    <span>
      Rodapé da página
    </span>
  </footer>
</template>

<script>

</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,700;1,300&display=swap');

  :root {
  --primaryColor: #00121e;
  --secondaryColor: #2facff;
  --terciaryColor: #95d5ff ;
  }

  html, body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
  }

  .navigation {
    min-height: 50px;
    width: 100%;
    padding: 5px 50px;
    color: var(--primaryColor);
    background-image: 
      linear-gradient( 
        to right, var(--secondaryColor), var(--terciaryColor)
      );
    box-shadow: 0px 2px 5px var(--primaryColor);
    display: flex;
    align-items: center;
    flex-flow: row wrap;
    justify-content: space-between;
  }

  .navigation li {
    display: block;
    list-style: none;
  }

  .navigation a {
    text-decoration: none;
    color: var(--primaryColor);
  }

  .body {
    min-height: 600px;
  }

  .footer {
    text-align: center;
    box-shadow: 0 -1.5px 5px var(--primaryColor);
    background-image: 
      linear-gradient( 
        to top, var(--terciaryColor), #FFF 
      );
    min-height: 80px;
    align-items: flex-end;
  }
</style>
