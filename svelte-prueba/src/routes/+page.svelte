<main class="contenedor">
	<div class="contenido-introductorio-container">
		<h1>Este es el inicio de la pagina aqui encontraras la introduccion:</h1>
		<p class="parrafo-introduccion">
			Hola, bienvenido a "nombre de la pagina" <br /> El lugar donde podras potenciar tus habilidades
			personales y compartirlas con otros
		</p>
	</div>
	<div class="contenedor-abajo">
		<div class="contenedor-input">
			<h2>Registrate:</h2>
			<span class="input-conainter">
				<div class="mb-3">
					<label for="exampleFormControlInput1" class="form-label">Correo electronico:</label>
					<input
						type="email"
						class="form-control"
						id="exampleFormControlInput1"
						placeholder="nombre@ejemplo.com"
					/>
				</div>
				<div class="mb-3">
					<label for="exampleFormControlTextarea1" class="form-label">Primeras impresiones:</label>
					<textarea class="form-control" id="exampleFormControlTextarea1" rows="3" />
				</div>
			</span>
		</div>
		<span>
			<p class="parrafo-explicacion">
				Crea tu cuenta para iniciar <br />
				Si ya tienes una ingresala en el siguiente espacio
			</p>
		</span>
	</div>
	<div class="contenedor-imagen-parrafo">
		<div class="parrafo-con-imagen">
			<h1 class="h1-pregunta1">¿Estás interesado en realizar un proyecto educativo?</h1>
			<p class="parrafo-explicacion2">
				Tenemos herramientas y materiales para ayudarte a desarrollar tus ideas y llevarlas a la
				práctica. ¿Quieres emprender un proyecto personal? También tenemos recursos y consejos para
				que puedas llevar adelante tu proyecto de manera exitosa. Y si lo que buscas es generar
				ingresos con tus proyectos, te ofrecemos ideas y estrategias para hacer que tu proyecto sea
				lucrativo.
			</p>
		</div>
	</div>
</main>

<style>
	.contenido-introductorio-container {
		transform: translateY(-50px);
		margin: 4rem;
		margin-bottom: 45px;
		background: rgba(255, 255, 255, 0.67);
		box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
		backdrop-filter: blur(3.5px);
		-webkit-backdrop-filter: blur(3.5px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
		-webkit-box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
		-moz-box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
		box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
	}
	h1 {
		margin: 20px;
		text-align: center;
	}
	.parrafo-introduccion {
		font-size: 30px;
		color: rgb(79, 79, 79);
		text-align: center;
		padding: 20px;
	}
	.contenedor {
		margin-top: 100px;
	}
	.contenedor-input {
		transform: translateY(-50px);
		background: rgba(255, 255, 255, 0.15);
		box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
		backdrop-filter: blur(1px);
		-webkit-backdrop-filter: blur(1px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
		padding: 2rem;
		margin: 0 4rem;
		width: 60%;
		-webkit-box-shadow: -10px 10px 16px 0px rgba(0, 0, 0, 0.4);
		-moz-box-shadow: -10px 10px 16px 0px rgba(0, 0, 0, 0.4);
		box-shadow: -10px 10px 16px 0px rgba(0, 0, 0, 0.4);
	}
	.form-control {
		resize: none;
	}
	.contenedor-input:hover {
		outline: 2px dashed black;
	}
	.contenedor-abajo {
		display: flex;
		align-items: center;
		justify-content: space-around;
	}
	.parrafo-explicacion {
		transform: translateY(-50px);
		text-align: center;
		font-size: 1.6rem;
		background: rgba(255, 255, 255, 0.7);
		box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
		backdrop-filter: blur(20px);
		-webkit-backdrop-filter: blur(20px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
		padding: 4rem;
		-webkit-box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
		-moz-box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
		box-shadow: 10px 7px 16px 0px rgba(0, 0, 0, 0.4);
		margin-right: 4rem;
	}
	.contenedor-imagen-parrafo {
		display: flex;
		margin-top: 2rem;
		align-items: center;
		padding: 4rem;
		background-image: url('https://www.xtrafondos.com/descargar.php?id=3128&resolucion=2880x1800');
		border-top: 2px dashed black;

		background-repeat: no-repeat;
		background-size: cover;
		background-attachment: fixed;
	}
	.parrafo-con-imagen {
		width: 60%;
		margin-top: 20px;
		margin-left: 4rem;
		background: rgba(255, 255, 255, 0.5);
		box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
		backdrop-filter: blur(4px);
		-webkit-backdrop-filter: blur(4px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
		padding: 30px;
	}
	textarea {
		background: rgba(255, 255, 255, 0.65);
		box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
		backdrop-filter: blur(16px);
		-webkit-backdrop-filter: blur(16px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
	}
	.parrafo-explicacion2 {
		font-size: 1.5rem;
		text-align: center;
	}
</style>
