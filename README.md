# AstroCode
<!DOCTYPE HTML>
<html lang="pt-br">
<head>
<meta charsete="utf-8">
<title> amostra de componentes </title> 
</head>
<body>

<img src="paris3.jpg" alt="Imagem com o fundo de Paris, e uma menina"">
    
<main>
<h1 id="vat"> Exemplos de componentes </h1>
<p> Acompanhe no site os principais componentes de uma aplicação WEB, e como são as suas verbalizações com os leitores de tela </p>

<h2> índice </h2>
<nav>
<ol>
<li>
<a href="#indice1">Rádio buttom </a>
 </li> 
<li>
<a href="#indice2">  Radio button desabilitado </a> 
</li>
<li>
 <a href="#indice3"> Select </a>
 </li>
<li>
<a href="#indice4">  Select desabilitado </a>
</li>
<li>
<a href="#indice5"> Check box </a> 
</li>
<li>
<a href="#indice6"> Check box desabilitada </a>
</li>
<li>
<a href="#indice7"> campos de input </a>
</li>
<li>
<a href="#indice8"> Campos de input desabilitados </a>
</li>
<li>
<a href="#indice9"> Campos de input com placeholder </a>
</li>
<li>
<a href="#indice10"> Botões </a>
</li>
<li>
<a href="#indice11"> Botões desabilitados </a>
</li>
<li>
<a href="#indice12"> Modal </a>
</li>
<li>
<a href="#indice13"> Accordion </a>
</li>
<li>
<a href="#indice14"> Menu suspenso de opções </a>
</li>
<li>
<a href="#indice15"> Lista ordenada </a>
</li>
<li>
<a href="#indice16"> Lista não ordenada </a>
</li>
<li>
<a href="#indice17"> Lista de definição </a>
</li>
<li>
<a href="#indice18"> Lista com números romanos </a>
</li>
<li>
<a href="#indice19"> Lista com letras </a>
</li>
<li>
<a href="#indice20"> Tabela </a>
</li>
<li>
<a href="#indice21"> Codificaçção de figura </a>
</li>
<li>
<a href="#indice22"> Ignorando conteúdo decorativo para o leitor de tela </a>
</li>  
</ol>
</nav>

<h3 id="indice1"> RÁDIO BUTTON </h3>
<form>
  <fieldset>
    <legend>Cores</legend>
<input type="radio" id="html" name="fav_language" value="HTML">
<label for="html">Dourado</label><br>
<input type="radio" id="css" name="fav_language" value="CSS">
<label for="css"> Prata</label><br>
<input type="radio" id="javascript" name="fav_language" value="JavaScript">
<label for="javascript"> Branco</label>
  </fieldset>
</form>

<h3 id="indice2"> RÁDIO BUTTON DESABILITADO </h3>

<form>
  <fieldset>
    <legend>Cores</legend>
<label><input type="radio" name="vinte1" disabled> prata</label>
<br>
<label><input type="radio" name="vinte1" disabled> Dourado</label>
<br>
<label><input type="radio" name="vinte1" disabled> Branco</label>
<br>
  </fieldset>
</form>

<h3 id="indice3"> Select </h3>
<form>
<label for="quinto"> Selecione uma cor</label>
<select id="quinto">
<option> Roxo </option>
<option> cinza </option>
<option> Amarelo </option>
<option> Preto </option>
</select>
</form>

<h3 id="indice4"> Select desabilitado </h3>

<form>
<label for="trinta1"> Selecione uma cor</label>
<select id="trinta1" disabled>
<option> Roxo </option>
<option> cinza </option>
<option> Amarelo </option>
<option> Preto </option>
</select>
</form>

<h3 id="indice5"> Check box </h3>

<form>
  <fieldset>
    <legend>Talheres</legend>
<input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
<label for="vehicle1"> Garfo</label><br>
<input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
<label for="vehicle2"> Faca</label><br>
<input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
<label for="vehicle3"> Colher</label><br>
  </fieldset>
</form>

<h3 id="indice6"> Check box desabilitada </h3>

<form>
  <fieldset>
    <legend>Talheres</legend>
<input type="checkbox" id="vehicle4" name="vehicle1" value="Bike" disabled>
<label for="vehicle4"> Garfo</label><br>
<input type="checkbox" id="vehicle5" name="vehicle2" value="Car" disabled>
<label for="vehicle5"> Faca</label><br>
<input type="checkbox" id="vehicle6" name="vehicle3" value="Boat" disabled>
<label for="vehicle6"> Colher</label><br>
  </fieldset>
</form>

<h3 id="indice7"> campos de input </h3>

<form>
<label for="oito"> Digite o seu nome completo</label>
<input type="text" name="txt-nome" id="oito">
<br>
<label for="nove"> Digite o seu e-mail</label>
<input type="email" name="txt-email" id="nove">
<br>
<label for="dez">Digite o seu celular com DDD</label>
<input type="tel" name="telefone" id="dez">
<br>
<label for="onze">Digite um comentário</label>
<input type="txt" name="txt-assunto" id="onze">
<br>
<label for="doze"> Digite uma mensagem</label>
<textarea cols="100" rows="10" name="como você deseja visualizar a especificação do campo na outra página" id="doze">
</textarea>
</form>


<h3 id="indice8"> Campos de input desabilitados </h3>

<form>
<label for="campo1"> Digite o seu nome completo</label>
<input type="text" name="txt-nome" id="campo1" disabled>
<br>
<label for="campo2"> Digite o seu e-mail</label>
<input type="email" name="txt-email" id="campo2" disabled>
<br>
</form>

<h3 id="indice9"> Campos de input com placeholder </h3>

<form>
<label for="dez1"> Digite o seu nome completo</label>
<input type="text" name="txt-nome" id="dez1" placeholder="EX: João Lima">
<br>
<label for="dez2"> Digite o seu e-mail</label>
<input type="email" name="txt-email" id="dez2" placeholder="exemplo@exemplo.com">
<br>
<label for="dez3">Digite o seu celular com DDD</label>
<input type="tel" name="telefone" id="dez3" placeholder="EX: (00) 00000-0000">
</form>


<h3 id="indice10"> Botões </h3>

<button> Enviar </button>
<br>
<button> Continuar </button>


<h3 id="indice11"> Botões desabilitados </h3>

<button disabled> Enviar </button>
<br>
<button disabled> Continuar </button>


<h3 id="indice12"> Modal </h3>

    <!-- Botão que abre a modal -->
    <button id="openModalButton">Abrir Modal</button>

    <!-- Modal -->
    <div id="myModal" class="modal" tabindex="-1" role="dialog">
        <div class="modal-content">
            <button class="close-button" id="closeButton">Fechar</button>
            <h2>Aviso</h2>
            <p> Ao realizar o cancelamento, essa ação não poderá ser desfeita.</p>
            <button class="back-button" id="backButton">Ok, entendi</button>
        </div>
    </div>

    <script>
        const openModalButton = document.getElementById("openModalButton");
        const modal = document.getElementById("myModal");
        const closeButton = document.getElementById("closeButton");
        const backButton = document.getElementById("backButton");

        openModalButton.addEventListener("click", () => {
            modal.style.display = "block";
            modal.setAttribute("aria-hidden", "false");
            modal.setAttribute("aria-modal", "true");

            // Definir o foco no botão de fechar ao abrir a modal
            closeButton.focus();
        });

        closeButton.addEventListener("click", () => {
            modal.style.display = "none";
            openModalButton.focus(); // Direcionar o foco de volta para o botão de abrir modal
        });

        backButton.addEventListener("click", () => {
            modal.style.display = "none";
            openModalButton.focus(); // Direcionar o foco de volta para o botão de abrir modal
        });

        modal.addEventListener("keydown", (e) => {
            if (e.key === "Escape") {
                modal.style.display = "none";
                openModalButton.focus(); // Direcionar o foco de volta para o botão de abrir modal
            }
        });

        modal.addEventListener("focusin", (e) => {
            if (!modal.contains(e.target) && e.target !== openModalButton) {
                closeButton.focus(); // Manter o foco no botão de fechar se estiver fora da modal
            }
        });

        modal.addEventListener("click", (e) => {
            if (e.target === modal) {
                modal.style.display = "none";
                openModalButton.focus(); // Direcionar o foco de volta para o botão de abrir modal
            }
        });
    </script>


  <h3 id="indice13">Accordion </h3>

  <div class="accordion">
    <button aria-expanded="false" aria-controls="section1">Saiba mais sobre HTML</button>
    <div class="panel" id="section1">
      <p>HTML, ou HyperText Markup Language, é a linguagem de marcação utilizada para criar páginas da web. Ela é fundamental para a estruturação e formatação de conteúdo na web. </p>
    </div>
  </div>

  <script>
    // JavaScript para tornar o Accordion acessível
    const accordionButtons = document.querySelectorAll('.accordion button');

    accordionButtons.forEach(button => {
      button.addEventListener('click', () => {
        const panel = button.nextElementSibling;

        button.setAttribute('aria-expanded', button.getAttribute('aria-expanded') === 'true' ? 'false' : 'true');
        panel.style.display = panel.style.display === 'block' ? 'none' : 'block';
      });
    });
  </script>



<h3 id="indice14"> Menu suspenso de opções </h3>

    <label for="menu">Selecione uma opção:</label>
    <select id="menu" aria-label="Menu Suspenso de Opções">
        <option value="opcao1">Carro</option>
        <option value="opcao2">Moto</option>
        <option value="opcao3">Barco</option>
    </select>



<h3 id="indice15"> Lista ordenada </h3>

<ol aria-label="Salgados">
<li> Coxinha </li>
<li> Kibe </li>
<li> Bolinho de queijo </li>
<li> Esfirra </li>
</ol>


<h3 id="indice16"> Lista não ordenada </h3>

<ul aria-label="Frutas">
<li> Limão </li>
<li> Melão </li>
<li> Amora </li>
<li> Abacaxi </li>
</ul>


<h3 id="indice17"> Lista de definição </h3>

<dl>
<dt> Banana </dt>
<dd> A banana é uma das frutas mais conhecidas e consumidas em todo o mundo. Contém grandes quantidades de açúcares e é rica em fibras e vitaminas. </dd>
 <dt> Uva </dt>
<dd> A uva é o fruto da videira ou parreira, uma planta da família Vitaceae. É originária da Ásia e uma das frutas mais antigas utilizadas na alimentação humana. </dd>
<dt> Limão </dt>
<dd> Limão (espécie Citrus limon) é o fruto do limoeiro, uma pequena árvore de folha perene originária da região sudeste da Ásia, da família das rutáceas. </dd>
</dl>

 
<h3 id="indice18"> Lista com números romanos </h3>

    <ol type="I" aria-label="Refeição da manhã">
<li> Café </li>
<li> Leite </li>
<li> Pão </li>
</ol>


<h3 id="indice19"> Lista com letras </h3>

    <ol type="a" aria-label="Bebidas">
<li> Café </li>
<li> Leite </li>
<li> Suco </li>
</ol>


<h3 id="indice20"> Tabela </h3>

<table>
  <caption> Informações dos funcionários</caption>
   <thead>
   <tr>
      <td> Nomes</td>
      <th scope="col">Função</th>
      <th scope="col">Número da inscrição</th>
   </tr>
   </thead>
   <tbody>
   <tr>
      <th scope="row"> João</th>
      <td> Desenvolvedor</td>
      <td> 000123</td>
   </tr>
   <tr>
      <th scope="row">Maria</th>
      <td> Analista de acessibilidade</td>
      <td> 000456</td>
    </tr>
    <tr>
       <th scope="row">Pedro</th>
       <td> QA funcional</td>
       <td> 000890</td>
    </tr>
    </tbody>
</table>



<h3 id="indice21"> Codificaçção de figura </h3>

<figure>
<img src="Captura de Tela (1).png" alt="Emoticon">
<figcaption> figura com olhos em forma de coração, sorrindo</figcaption>
</figure>
 

<h3 id="indice22"> Ignorando conteúdo decorativo para o leitor de tela </h3>

<img src="paris3.jpg" alt="Torre de paris a noite"> 

<img src="paris3.jpg" alt="Torre de paris a noite" aria-hidden="true"> 

<p> Aqui estão duas imagens visualmente idênticas. No entanto, para os usuários que dependem de leitores de tela, apenas uma delas é acessível, já que o atributo "aria-hidden="true"" está sendo usado. </p>




<a href="#vat"> Inicío da página </a>
</mein>
</body>
</html>




