HTML _tabela dados pessoais e académicos 
<table border="1">
  <tr>
    <th colspan="2">Dados Pessoais</th>
  </tr>
  <tr>
    <th>Nome</th>
    <td>Maria Ulika Pacheco</td>
  </tr>
  <tr>
    <th>Naturalidade</th>
    <td>Benguela</td>
  </tr>
  <tr>
    <th>Bairro</th>
    <td>Madeira Jumbo</td>
  </tr>
  <tr>
    <th>Idade</th>
    <td>26</td>
  </tr>
  <tr>
    <th>Pai</th>
    <td>Domingos Félix Pacheco</td>
  </tr>
  <tr>
    <th>Mãe</th>
    <td>Luísa Filomena Mendes</td>
  </tr>
  <tr>
    <th>Email</th>
    <td>mariapachecomanuela@gmail.com</td>
  </tr>
  <tr>
    <th colspan="2">Dados Académicos</th>
  </tr>
  <tr>
    <th>Escola</th>
    <td>Instituto Médio Comercial de Luanda</td>
  </tr>
  <tr>
    <th>Turno</th>
    <td>Noite</td>
  </tr>
  <tr>
    <th>Número</th>
    <td>23</td>
  </tr>
  <tr>
    <th>Sala</th>
    <td>18</td>
  </tr>
  <tr>
    <th>Curso</th>
    <td>Técnico Informática de Gestão</td>
  </tr>
</table>



<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Formulário Pessoal</title>
</head>
<body>
  <h1>Formulário com meus dados</h1>
  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" value="Maria Ulika Pacheco" readonly><br><br>

    <label for="naturalidade">Naturalidade:</label>
    <input type="text" id="naturalidade" value="Benguela" readonly><br><br>

    <label for="bairro">Bairro:</label>
    <input type="text" id="bairro" value="Madeira Jumbo" readonly><br><br>

    <label for="idade">Idade:</label>
    <input type="number" id="idade" value="26" readonly><br><br>

    <label for="pai">Pai:</label>
    <input type="text" id="pai" value="Domingos Félix Pacheco" readonly><br><br>

    <label for="mae">Mãe:</label>
    <input type="text" id="mae" value="Luísa Filomena Mendes" readonly><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" value="mariapachecomanuela@gmail.com" readonly><br><br>

    <label for="escola">Escola:</label>
    <input type="text" id="escola" value="Instituto Médio Comercial de Luanda" readonly><br><br>

    <label for="turno">Turno:</label>
    <input type="text" id="turno" value="Noite" readonly><br><br>

    <label for="numero">Número:</label>
    <input type="number" id="numero" value="23" readonly><br><br>

    <label for="sala">Sala:</label>
    <input type="number" id="sala" value="18" readonly><br><br>

    <label for="curso">Curso:</label>
    <input type="text" id="curso" value="Técnico Informática de Gestão" readonly><br><br>
  </form>
</body>
</html>
