# pag-4-html-css-js
com js
<body>
  
    <style>
        body {
        background-color: #000
        }
        </style>

    <style>
        body {
            color:#FFFFFF

        }
        
    </style>
    <center>
        <p><h1>Bem vindo(a) á pagina de Cadastro do usuario. É um prazer te-lô como cliente</h1></p>
    <form>
      <center>
        <script src="https://code.jquery.com/jquery-latest.min.js"></script>
      </head>
      <body>
        <form action="javascript:void(0);">
          <label>Escolha seu sexo</label>
          <input type="radio" name="sexo" id="feminino"><label>Feminino</label>
          <input type="radio" name="sexo" id="masculino"><label>Masculino</label>
          <input type="submit" id="button">
        </form>
      </body>
    
      <script>
       $('#button').click(function(){
          if($('#feminino').is(':checked')){
            alert("Você escolheu feminino");
          }else if($('#masculino').is(':checked')){
            alert('Você escolheu masculino');
          }else{
            alert('Você não escolheu');
          }
        });
      </script>
      </center>
        <label for="name">Nome</label><input type="text" id="name"><p>insira o seu Nome</p><hr><br>
        Sobre nome</label>
        <input type="text" id="name">
        <p>insira o seu Sobre nome</p>
        <hr><br>
        <label for="date-example">Data do seu nascimento</label>
        <input type="date" id="date-example">
        <hr><br>
        <label for="email-example">Digite seu e-mail</label>
        <input type="email" id="email-example">
        <hr><br>
        <label for="file-example">Documentos anexos ou arquivos upload</label>
        <input type="file" id="file-example">
        <hr><br>
        <label for="number-example">Digite seu número de telefone </label>
        <input type="number" id="number-example">
        <hr><br>
        <label for="password-example">Digite uma senha</label>
        <input type="password" id="password-example">
        <hr><br>
        <label for="checkbox-exemple">Você leu e aceita todas ás condições de nossa loja</label>
        <input type="checkbox" 
        <p>Concorda ás informações acima</p>
        <input type="button" value="Clique aqui">
        <p>botão do usuario (Próximo)</p>
        <hr><br>
    </center>
        </form>
    </body>
