
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>K-SABER MAYA ✨ (8 Años)</title>
	<script src="https://cdn.tailwindcss.com"></script>
	<style>
		@import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700;800&family=Chivo:wght@400;700;900&display=swap');
		* {
			font-family: 'Fredoka', sans-serif;
		}
		/* --- NUEVA PALETA DE COLORES Y FONDO --- */
		/* Colores: Esmeralda (#00A36C), Azul Profundo (#124F8A), Arena (#F5DEB3), Oro (#FFD700) */
		body {
			background: linear-gradient(135deg, #00A36C 0%, #008053 40%, #124F8A 100%);
			background-size: 400% 400%;
			animation: gradientShift 20s ease infinite;
			min-height: 100vh;
		}
		@keyframes gradientShift {
			0% { background-position: 0% 50%; }
			50% { background-position: 100% 50%; }
			100% { background-position: 0% 50%; }
		}
		.app-container {
			min-height: 100vh;
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			padding: 1rem;
		}
		.main-card {
			background: rgba(255, 255, 255, 0.9);
			backdrop-filter: blur(5px);
			border: 5px solid #00A36C;
			box-shadow: 0 0 30px rgba(18, 79, 138, 0.4), 0 0 60px rgba(0, 163, 108, 0.3), 0 15px 40px rgba(0, 0, 0, 0.3);
			max-width: 95%;
			width: 550px;
			border-radius: 20px;
			animation: none;
		}
		.title-main {
			font-family: 'Chivo', sans-serif;
			font-size: 3.5rem;
			background: linear-gradient(135deg, #FFD700, #00A36C);
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
			background-clip: text;
			text-shadow: 2px 2px 0px rgba(18, 79, 138, 0.3);
			letter-spacing: 2px;
			animation: pulse-slow 5s ease-in-out infinite;
		}
		@keyframes pulse-slow {
			0%, 100% { transform: scale(1); }
			50% { transform: scale(1.03); }
		}
		/* ...resto de estilos del usuario... */
	</style>
</head>
<body>
	<div id="app" class="app-container"></div>
	<script type="module">
		// --- Lógica completa del juego y preguntas ---
		// Incluye MATH_QUESTIONS, READING_QUESTIONS, SOCIAL_QUESTIONS
		// Funciones de utilidad, generación de preguntas, renderizado, manejo de respuestas
		// ...
		// Código JS completo del usuario
	</script>
</body>
</html>
