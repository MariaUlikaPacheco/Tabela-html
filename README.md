
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tabela de Dados Pessoais e Académicos</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      font-family: Arial, sans-serif;
    }
    th, td {
      border: 1px solid #555;
      padding: 8px;
      text-align: left;
    }
    th {
      background-color: #f2f2f2;
    }
    caption {
      font-weight: bold;
      font-size: 18px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <table>
    <caption>Dados Pessoais e Académicos</caption>
    <tr>
      <th>Nome Completo</th> 
      <th>Idade</th> 
      <th>Gênero</th> 
      <th>Filiação</th> 
      <th>Data de Nascimento</th> 
      <th>Naturalidade</th> 
      <th>Número de Telemóvel</th> 
      <th>Email</th>
      <th>Morada</th> 
      <th>Escola</th> 
      <th>Classe</th> 
      <th>Número</th> 
      <th>Sala</th> 
      <th>Turno</th> 
    </tr>

    <tr>
      <td>Maria Ulika Pacheco</td> 
      <td>22 anos</td> 
      <td>Feminino</td> 
      <td>Domingos Félix Pacheco e Luísa Filomena</td> 
      <td>06 de dezembro de 2001</td> 
      <td>Benguela</td> 
      <td>928 998 835</td>
      <td>mariapachecomanuela@gmail.com</td> 
      <td>Jumbo</td> 
      <td>Instituto Médio Comercial de Luanda</td> 
      <td>12ª Classe</td> 
      <td>18</td> 
      <td>18</td> 
      <td>Pós-Laboral</td> 
    </tr>
  </table>

</body>
</html>


Formulário com dados académicos e pessoais 

<form>
  <h3>Dados Pessoais</h3>
  <table border="1">
    <tr>
      <td>Nome Completo:</td>
      <td><input type="text" value="Maria Ulika Pacheco"></td>
    </tr>
    <tr>
      <td>Filiação:</td>
      <td><input type="text" value="Filha de Domingos Félix Pacheco e de Luísa Filomena"></td>
    </tr>
    <tr>
      <td>Data de Nascimento:</td>
      <td><input type="text" value="06 de Dezembro de 1997"></td>
    </tr>
    <tr>
      <td>Naturalidade:</td>
      <td><input type="text" value="Província de Benguela"></td>
    </tr>
    <tr>
      <td>Email:</td>
      <td><input type="email" value="mariapachecomanuela@gmail.com"></td>
    </tr>
  </table>

  <h3>Dados Académicos</h3>
  <table border="1">
    <tr>
      <td>Escola:</td>
      <td><input type="text" value="Instituto Médio Comercial de Luanda"></td>
    </tr>
    <tr>
      <td>Classe:</td>
      <td><input type="text" value="12ª Classe"></td>
    </tr>
    <tr>
      <td>Número:</td>
      <td><input type="text" value="18"></td>
    </tr>
    <tr>
      <td>Sala:</td>
      <td><input type="text" value="18"></td>
    </tr>
    <tr>
      <td>Turno:</td>
      <td><input type="text" value="Pós-laboral"></td>
    </tr>
  </table>
</form>



