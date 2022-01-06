<!DODCTYPE html>
<html>
	<head>
	<html lang="pt-br">
	<meta charset="utf-8">
	<title>Direcionamento de Links</title>
	
	
	<!-- CSS -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	
	<!-- JAVASCRIPT -->
	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
	
	<!-- Jquery -->
	<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
	
	</head>
	
	<body>
		<form action="processa.php" method="post">
		<div class="container-fluid" style="background-color:black">
			<div class="row">
				<div class="col-6" style="color:white">
					<h1> <em><u>Deseja ir para qual site</u></em>? </h1>
				</div>
				<div class="col-3 rounded float-left">
					<h5> <em> Desenvolvido por </em>: <strong>Rickson Henrique</strong>
				</div>
				<div class="col-3" style="color:white">
					<label>Login</label>
					<input type="text" name="Login" placeholder="Usuário">
				</div>
			</div>	
			<div class="row" style="grey" height="20px">
				<div class="col-9" 
					<h4> <em> Links disponiveis</em>: </h4>
					<br>
				</div>
				<div class="col-3 rounded" style="color:white">
					<label>Password</label>
					<input type="password" name="Senha" placeholder="Senha">
				</div>
			</div>
			<div class="row">
				<div class="col-9">
					<img src="img/google.png" width="20px" class="rounded">
					<a href="http://google.com.br" class="btn btn-default" style="background-color:white">Google<a/>
					<br>
					<br>
				</div>
			</div>
			<div class="row">
				<div class="col-12">
					<img src="img/facebook.jpg" width="20px" class="rounded">
					<a href="http://facebook.com" class="btn btn-default" style="background-color:blue">Facebook<a/>
					<br>
					<br>
				</div>
			</div>
			<div class="row">
				<div class="col-12">
					<img src="img/instagram.png" width="20px" class="rounded">
					<a href="http://instagram.com" class="btn btn-default" style="background-color:#9400D3">Instagram<a/>
					<br>
					<br>
				</div>
			</div>
			<div class="row">
				<div class="col-12">
					<img src="img/twitter.png" width="20px" class="rounded">
					<a href="http://twitter.com" class="btn btn-default" style="background-color:#00BFFF">Twitter<a/>
					<br>
					<br>
				</div>
			</div>
			
			<div class="jumbotron">
			<h1>Site de cores</h1>
			<p> <strong>Ir diretamente para o site de cores hexadecimal RGB</strong></p>
			<br>
			<p><a class="btn btn-primary btn-lg" href="https://celke.com.br/artigo/tabela-de-cores-html-nome-hexadecimal-rgb" role="button" style="background-color:#4169E1 ">RGB Celke</a></p>
			<p><u>Imagem ilustrativa do site</u>: </p>
			<img src="img/celke.png" width="600px" class="rounded">
			</div>
		</div>
	</body>
	
	
	
</html>
