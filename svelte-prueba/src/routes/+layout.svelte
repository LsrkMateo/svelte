<script>
	import '../app.css';
    import 'bootstrap/dist/css/bootstrap.min.css';
</script>

<main class="navegacion">
	<nav class="navbar navbar-expand-lg bg-body-tertiary ">
		<div class="container-fluid">
			<a class="navbar-brand" href="/">Navbar</a>
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
						<a class="nav-link active" aria-current="page" href="/">Home</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">Features</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="/">Pricing</a>
					</li>
					<li class="nav-item">
						<a class="nav-link disabled" href="/">Disabled</a>
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
</style>
