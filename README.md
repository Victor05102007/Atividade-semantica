<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Atv2</title>
  </head>
  <body>
    <h2>Cadastro do aluno</h2>
    <label for="nome">Nome:</label>
    <input type="text" name="" id="nome" required />
    <br />
    <br />
    <label for="idade">Idade:</label>
    <input type="number" name="idade" id="idade" min="0" max="60" />
    <br />
    <br />
    <label for="imgPerfil">Imagem Perfil:</label>
    <input type="file" name="imgPerfil" id="imgPerfil" />

    <br />
    <br />
    <label for="Email">Email:</label>
    <input type="Email" name="Email" id="Email" required />
    <br />
    <br />
    <label for="senha">senha:</label>
    <input type="password" name="senha" id="senha" />
    <br />
    <br />
    <label for="Data">Data de nascimento</label>
    <input type="date" name="Data" id="Data" />
    <br />
    <br />
    <label for="tel">Telefone:</label>
    <input
      type="tel"
      name="Telefone"
      id="Telefone"
      placeholder="(xx)xxxxx-xxxx"
    />
    <br />
    <br />
    <label for="text">Genêro</label>

    <input type="radio" name="sexo" id="feminino" value="feminino" />
    <label for="feminino">Feminino</label>

    <input type="radio" name="sexo" id="masculino" value="masculino" />
    <label for="masculino">Masculino</label>

    <br />
    <br />
    <label for="country">Estado:</label>
    <select name="country" id="country">
      <option>Selecione um estado</option>
      <option value="Sp">Sp</option>
      <option value="Rj">Rj</option>
      <option value="Mt">Mt</option>
      <option value="Ms">Ms</option>
    </select>

    <br />
    <br />
    <label for="Mensagem">Mensagem</label>
    <textarea
      id="Mensagem"
      name="Mensagem"
      placeholder="Digite a mensagem para o contato"
      required
      rows="4"
      cols="50"
    >
    </textarea>
    <br />
    <br />
    <input type="submit" value="Enviar" />
  </body>
</html>
