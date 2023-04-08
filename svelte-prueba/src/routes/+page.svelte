<main class="contenedor">
	<h1>Este es el inicio de la pagina aqui encontraras la introduccion:</h1>
	<p>
		Hola, bienvenido a "nombre de la pagina" <br /> El lugar donde podras potenciar tus habilidades personales
		y compartirlas con otros
	</p>

	<div class="contenedor-input">
		<h2>Registrate:</h2>
		<span class="input-conainter">
			<div class="mb-3">
				<label for="exampleFormControlInput1" class="form-label">Email address</label>
				<input
					type="email"
					class="form-control"
					id="exampleFormControlInput1"
					placeholder="name@example.com"
				/>
			</div>
			<div class="mb-3">
				<label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
				<textarea class="form-control" id="exampleFormControlTextarea1" rows="3" />
			</div>
		</span>
	</div>
	<!-- <div class="imagen-contenedor">
		<img
			src="https://thumbs.dreamstime.com/b/nuevo-concepto-de-la-tecnolog%C3%ADa-internet-del-negocio-entrenamiento-webinar-conocimiento-las-habilidades-121274023.jpg"
			alt="tecnologia"
			class="imagen"
		/>
        <div class="lorem">
            <p>Holaaa Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aut ea similique nemo facilis fugit doloribus totam at, sapiente aliquid minus dolores possimus perspiciatis quod ipsam dolor laborum, illum quia. Nihil!</p>
        </div>
	</div> -->
</main>

<style>
	h1 {
		margin: 20px;
		text-align: center;
	}
	p {
		font-size: 30px;
		color: rgb(79, 79, 79);
		text-align: center;
	}
	.contenedor {
		margin-top: 100px;
	}
	.contenedor-input {
		width: 30%;
		margin-top: 50px;
		padding: 20px;
		border-radius: 10px;
		transform: translateX(50px);
		transition-property: outline;
		transition-duration: 0.4s;
		outline: 2px dashed rgba(0, 0, 0, 0.218);
	}
	.form-control {
		resize: none;
	}
	.contenedor-input:hover {
		outline: 2px dashed black;
	}
   
</style>
