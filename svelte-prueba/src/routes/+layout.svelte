<script>
	import '../app.css';
    import 'bootstrap/dist/css/bootstrap.min.css';
</script>

<main class="navegacion">
	<nav class="navbar navbar-expand-lg bg-body-tertiary ">
		<div class="container-fluid">
			<a class="navbar-brand nombre" href="/">Nombre de la app</a>
			<button
				class="navbar-toggler"
				type="button"
				data-bs-toggle="collapse"
				data-bs-target="#navbarNav"
				aria-controls="navbarNav"
				aria-expanded="false"
				aria-label="Toggle navigation"
			>
				<span class="navbar-toggler-icon" />
			</button>
			<div class="collapse navbar-collapse" id="navbarNav">
				<ul class="navbar-nav">
					<li class="nav-item">
						<a class="nav-link active introduccion" aria-current="page" href="/">Introduccion</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/"> ¿Que puedes hacer? </a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">¿Por que usarlo?</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">Premium</a>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</main>

<slot />

<style>
	.container-fluid{
		padding: 20px;
		font-size: 20px;
	}
	.nombre{
		border-right: 1px solid black;
		padding: 0 20px 0 0;
	}
</style>
