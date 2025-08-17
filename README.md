[Formulario.html](https://github.com/user-attachments/files/21824431/Formulario.html)
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulario</title>
  </head>
  <body>
    <header>
      <fieldset>
        <h1>For Name</h1>
      </fieldset>
    </header>
    <main>
        <fieldset>
      <nav><label>Nome:</label><input type="text" placeholder="placeholder" /> <br />help</nav>
      <nav>
        <label>Data Nascimento:</label><input type="text" placeholder="placeholder" />
        <br />help
      </nav>
      <nav>
        <label>Endereço:</label><input type="text" placeholder="placeholder" /> <br />help
      </nav>
      <nav><label>Nro:</label><input type="text" placeholder="placeholder" /> <br />help
      <nav>
        <label>Cidade:</label><input type="text" placeholder="placeholder" /> <br />help
      </nav>
        <nav>
      <label> Estado:</label><select name="optionOne" id="">
        <option value="optionOne">optionOne</option>
       </select>
      </nav>
        <nav>
       <label>Sexo:</label><select name="optionOne" id="">
        <option value="optionOne">optionOne</option>
       </select>
      </nav>
      <nav>
        <label>Bens Pessoais:</label><input type="checkbox" name="Casa" id="">Casa
      </nav>
       <nav>
        <label>Bens Pessoais:</label><input type="checkbox" name="Carro" id="">Carro
      </nav>
       <nav>
        <label>Bens Pessoais:</label><input type="checkbox" name="Moto" id="">Moto
      </nav>
      <label>Text Area</label><textarea placeholder="Experiências Pessoais:" name="textoArea" id=""></textarea>
      <br>
      <button>Enviar</button>
        <button>limpar</button>
        </fieldset>
    </main>
  </body>
  <style>
* {
  margin: 0;
  font-family: Verdana;
}

body {
  background-color: silver;
  color: black;
}
h1 {
  color: purple;
  text-align: center;
}
fieldset {
  width: 60%;
  margin: 0 auto;
  border-radius: 15px;
  background-color: white;
  box-shadow: 2px 2px 2px gray;
}
input,
select,
textarea {
  border-radius: 4px;
  padding: 5px;
  margin: 5px;
}
label {
  font-weight: bold;
}
  </style>
</html>
