<header>
	<h1>Bem-vindo ao meu livro !!!!</h1>
	<h2>Espero que se apaixonem pela historia, riam, chorem e me xingem silenciosamente por algo escrito. Deixem seus comentarios, critiquem e viagem nesse mundo meio doido que criei.</h2>
</header>
<nav>
	<ul>
		<li><a href="/">Início</a></li>
		<li><a href="#">filmes</a></li>
		<li><a href="/livro">Livro</a></li>

	</ul>
</nav>

<div class="content">
	<h2>Livro em Destaque</h2>

	<div class="book-list">
		<div class="book">
			<img src="/fogo.jfif" alt="Mitologias de amor" />
			<h3>Mitologias De Amor</h3>
			<p>Por Belle Kosloski</p>
			<a href="/livro">Leia Mais</a>
		</div>
	</div>
</div>

<footer>
	<p>&copy; 2025 Mundo dos Livros - Todos os direitos reservados.</p>
</footer>

<style>
	
	body,
	h1,
	h2,
	p,
	ul,
	li,
	a {
		margin: 0;
		padding: 0;
		font-family: 'Arial', sans-serif;
	}
	body {
		background-color: #f0f0f0;
		color: #333;
		line-height: 1.6;
	}

	
	header {
		background-color: #5404e7;
		color: white;
		padding: 20px;
		text-align: center;
	}

	header h1 {
		font-size: 3rem;
	}

	header h2 {
		font-size: 1.5rem;
		margin-top: 10px;
	}

	
	nav {
		background-color: #333;
		overflow: hidden;
	}

	nav ul {
		list-style: none;
		padding: 0;
		margin: 0;
		display: flex;
		justify-content: center;
	}

	nav ul li {
		margin: 0 20px;
	}

	nav ul li a {
		color: white;
		text-decoration: none;
		padding: 10px 20px;
		display: block;
	}

	nav ul li a:hover {
		background-color: #575757;
	}

	
	.content {
		padding: 20px;
		text-align: center;
	}

	.book-list {
		display: flex;
		justify-content: space-around;
		flex-wrap: wrap;
		margin-top: 30px;
	}

	.book {
		background-color: #fff;
		border-radius: 8px;
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
		width: 200px;
		margin: 10px;
		text-align: center;
		padding: 10px;
	}

	.book img {
		width: 100%;
		border-radius: 5px;
		max-height: 300px;
		object-fit: cover;
	}

	.book h3 {
		font-size: 1.25rem;
		margin: 10px 0;
	}

	.book p {
		font-size: 1rem;
		color: #555;
	}

	.book a {
		display: inline-block;
		margin-top: 10px;
		padding: 10px 20px;
		background-color: #4caf50;
		color: white;
		text-decoration: none;
		border-radius: 5px;
	}

	.book a:hover {
		background-color: #45a049;
	}

	
	footer {
		background-color: #333;
		color: white;
		text-align: center;
		padding: 15px;
		margin-top: 30px;
	}
</style>
