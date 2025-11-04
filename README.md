<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Página Bonita 💫</title>
  <style>
    /* Fuente moderna desde Google Fonts */
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #a18cd1 0%, #fbc2eb 100%);
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      width: 100%;
      text-align: center;
      padding: 2rem 1rem;
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(10px);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #fff;
      text-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      text-decoration: none;
      color: white;
      margin: 0 1rem;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #333;
    }

    main {
      text-align: center;
      padding: 3rem 1rem;
      max-width: 800px;
      animation: fadeIn 1.2s ease-in-out;
    }

    main h2 {
      color: white;
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    main p {
      font-size: 1.1rem;
      color: #f8f8f8;
      line-height: 1.6;
    }

    footer {
      margin-top: auto;
      width: 100%;
      text-align: center;
      padding: 1rem;
      background: rgba(255, 255, 255, 0.15);
      color: white;
      font-size: 0.9rem;
    }

    button {
      background: white;
      border: none;
      padding: 0.8rem 1.5rem;
      margin-top: 1.5rem;
      border-radius: 25px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    button:hover {
      background: #333;
      color: white;
      transform: scale(1.05);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenido a Mi Página 💜</h1>
    <nav>
      <a href="#">Inicio</a>
      <a href="#">Sobre mí</a>
      <a href="#">Proyectos</a>
      <a href="#">Contacto</a>
    </nav>
  </header>

  <main>
    <h2>✨ Hola, soy [Tu Nombre]</h2>
    <p>
      Este es mi rincón en Internet. Aquí comparto mis proyectos, ideas y lo que me inspira.  
      ¡Explora, disfruta y no dudes en contactarme!
    </p>
    <button onclick="alert('¡Gracias por visitar mi página! 💖')">Haz clic aquí</button>
  </main>

  <footer>
    © 2025 Tu Nombre — Hecho con 💕 y HTML
  </footer>
</body>
</html>
Puedo adaptarlo a tu estilo fácilmente.

