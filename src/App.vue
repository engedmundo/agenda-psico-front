<template>
  <div class="sidenav">
    <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Clients</a>
    <a href="#">Contact</a>
  </div>
  
  <main>
    <header>
        <ul class="navigation">
          <li><a>Espaço para abrir painel esquerdo</a></li>
          <li><a>Espaço do meio</a></li>
          <li><a>Info de usuário</a></li>
        </ul>
    </header>

    <div class="main-area">
      <h1>
        Área de formulários e relatórios
      </h1>
      <table>
        <thead>
          <th>teste</th>
          <th>teste</th>
          <th>teste</th>
          <th>teste</th>
        </thead>
        <tbody>
          <tr>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
          </tr>
          <tr>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
          </tr>
          <tr>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
          </tr>
          <tr>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
            <td>
              dado
            </td>
          </tr>
        </tbody>
      </table>
    </div>

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>

    <footer class="footer">
      <span>
        Rodapé da página
      </span>
    </footer>
  </main>
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

  .sidenav {
    height: 100%;
    width: 200px;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: rgba(150, 201, 249, 0.5);
    color: var(--primaryColor);
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
  }

  .sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: var(--primaryColor);
    display: block;
    transition: 0.3s;
  }

  .sidenav a:hover {
    color: #f1f1f1;
  }

  .sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
  }

  #main {
    transition: margin-left .5s;
    padding: 16px;
  }

  @media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
    .sidenav a {font-size: 18px;}
  }

  main {
    margin-left: 200px;
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

  .main-area {
    width: 80%;
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
