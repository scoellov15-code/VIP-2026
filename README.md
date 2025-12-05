<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIP PRO SC 2026 - ¡Domina el Juego!</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;900&family=Rajdhani:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        /* VARIABLES DE COLOR GAMER/NEÓN */
        :root {
            --dark-bg: #0c0c0c;
            --mid-bg: #1a1a1a;
            --neon-red: #ff3366;
            --neon-blue: #00ccff;
            --neon-green: #00ff99;
            --text-light: #f0f0f0;
        }

        /* ESTILOS GLOBALES */
        body {
            font-family: 'Rajdhani', sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            width: 95%;
            max-width: 1300px;
            margin: 0 auto;
            padding: 20px 0;
        }

        /* HEADER & HERO SECTION */
        header {
            background-color: var(--mid-bg);
            text-align: center;
            padding: 50px 0;
            border-bottom: 4px solid var(--neon-blue);
            box-shadow: 0 0 20px rgba(0, 204, 255, 0.4);
        }
        .hero-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 4.5em;
            color: var(--neon-red);
            text-shadow: 0 0 10px rgba(255, 51, 102, 0.8);
            margin: 0;
        }
        .hero-subtitle {
            font-size: 2em;
            color: var(--neon-green);
            margin-top: 10px;
            text-transform: uppercase;
        }

        /* SECCIONES Y TÍTULOS */
        .section-title {
            font-family: 'Orbitron', sans-serif;
            text-align: center;
            font-size: 2.5em;
            color: var(--neon-blue);
            margin-top: 60px;
            margin-bottom: 40px;
            text-transform: uppercase;
            letter-spacing: 2px;
            border-bottom: 2px solid var(--neon-blue);
            display: inline-block;
            padding-bottom: 5px;
        }
        .center-content {
            text-align: center;
        }

        /* GRID DE CARACTERÍSTICAS (SIMULACIÓN DE MÓDULOS) */
        .feature-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding: 20px 0;
        }
        .feature-module {
            background-color: var(--mid-bg);
            padding: 30px;
            border: 1px solid var(--neon-green);
            border-radius: 10px;
            width: calc(30% - 30px);
            min-width: 280px;
            box-shadow: 0 0 15px rgba(0, 255, 153, 0.5);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .feature-module:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 25px var(--neon-green);
        }
        .feature-module h4 {
            font-family: 'Orbitron', sans-serif;
            color: var(--neon-red);
            font-size: 1.5em;
            margin-top: 0;
        }
        .feature-module p {
            font-size: 1.1em;
        }

        /* SECCIÓN DE NIVELES Y COMPATIBILIDAD */
        .level-chart {
            background-color: var(--mid-bg);
            padding: 40px;
            border-radius: 15px;
            border: 2px dashed var(--neon-blue);
            margin: 40px auto;
            max-width: 800px;
        }
        .level-chart h4 {
            color: var(--neon-green);
            font-size: 1.8em;
            margin-bottom: 20px;
        }
        .level-chart ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }
        .level-chart li {
            font-size: 1.2em;
            padding: 10px;
            border: 1px solid var(--neon-red);
            background-color: #2b000a;
            border-radius: 5px;
        }

        /* BOTÓN CTA (CALL TO ACTION) */
        .cta-button {
            display: block;
            width: 90%;
            max-width: 500px;
            margin: 50px auto;
            padding: 20px 30px;
            background-color: var(--neon-red);
            color: var(--dark-bg);
            text-align: center;
            text-decoration: none;
            font-size: 2em;
            font-family: 'Orbitron', sans-serif;
            font-weight: 900;
            border-radius: 8px;
            box-shadow: 0 0 20px var(--neon-red);
            animation: pulse 1.5s infinite alternate; /* Animación de pulso */
        }
        .cta-button:hover {
            background-color: var(--neon-blue);
            box-shadow: 0 0 30px var(--neon-blue);
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            100% { transform: scale(1.03); }
        }
        
        /* FOOTER Y CONTACTO */
        footer {
            text-align: center;
            padding: 30px 0;
            background-color: var(--mid-bg);
            border-top: 4px solid var(--neon-red);
            margin-top: 50px;
        }
        .whatsapp-contact {
            font-size: 1.8em;
            font-weight: bold;
            color: var(--neon-green);
        }
        .whatsapp-contact a {
            color: var(--neon-green);
            text-decoration: none;
        }
        
        /* AFICHE GALLERY (ESTILO CON CÓDIGOS DE CIRCUITO) */
        .afiche-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 50px;
        }
        .afiche-gallery img {
            width: 100%;
            max-width: 320px;
            border: 3px solid var(--neon-blue);
            box-shadow: 0 0 10px var(--neon-blue);
            transition: border-color 0.3s;
        }
        .afiche-gallery img:hover {
            border-color: var(--neon-red);
        }
    </style>
</head>
<body>

    <header>
        <p style="color: var(--neon-green); font-size: 1.2em; margin-bottom: 0;">🚀 NUEVA ACTUALIZACIÓN VIP PRO SC 2026 🚀</p>
        <h1 class="hero-title">VIP PRO SC 2026</h1>
        <p class="hero-subtitle">¡DOMINA EL JUEGO COMO NUNCA ANTES!</p>
    </header>

    <div class="container">

        <div class="center-content">
            <h2 class="section-title">🛡️ SEGURIDAD INIGUALABLE</h2>
            <p style="font-size: 1.3em; color: var(--neon-green);">
                Diseñado para ser **100% SEGURO e INDETECTABLE**.
            </p>
            <p style="font-size: 1.1em;">
                Juega con tu cuenta principal gracias a nuestra tecnología **Anti-Baneo y Anti-Reporte**, sin alterar los códigos originales.
            </p>
        </div>

        <div class="center-content">
            <h2 class="section-title">🎯 TECNOLOGÍA ÉLITE (REGEDIT)</h2>
        </div>
        
        <div class="feature-grid">
            <div class="feature-module">
                <h4>PRECISIÓN | NO RECOIL</h4>
                <p>¡Cero retrocesos! **(NO RECOIL %)**. Dispara con precisión milimétrica. Optimiza cada bala.</p>
            </div>
            <div class="feature-module">
                <h4>AUTO APUNTADO | AIM BOT</h4>
                <p>Apuntado Automático **(AUTO APUNTADO %)**. Puntería Asistida avanzada **(AIM FOV % y AIM BOT %)**. Reacciona más rápido.</p>
            </div>
            <div class="feature-module">
                <h4>HEADSHOTS IMPARABLES</h4>
                <p>Aumenta drásticamente tus disparos a la cabeza con **(HEADTRICK %)**. ¡Impactos directos garantizados!</p>
            </div>
            <div class="feature-module">
                <h4>COMPATIBILIDAD TOTAL</h4>
                <p>**ANDROID, PC, y IPHONE**. No importa tu plataforma, tenemos la solución perfecta. *[Iconos de Dispositivos]*</p>
            </div>
            <div class="feature-module">
                <h4>SENSIBILIDAD PRO</h4>
                <p>Control total con **Sensibilidad Personalizada (%)**. Ajusta tu configuración para el rendimiento óptimo.</p>
            </div>
        </div>

        <div class="center-content">
            <h2 class="section-title">🚀 ELIGE TU NIVEL DE POTENCIA</h2>
        </div>
        <div class="level-chart">
            <h4 style="text-align: center;">Selecciona la versión que mejor se adapte a tu estilo:</h4>
            <ul>
                <li>ANDROID: 60%, 70%, 80%</li>
                <li>IPHONE: 60%, 70%, 80%</li>
                <li>PC: 60%, 70%, 80%</li>
            </ul>
        </div>
        
        <a href="https://wa.me/51979679324" class="cta-button" target="_blank">
            ¡CONSIGUE VIP PRO SC 2026 HOY!
        </a>

        <div class="center-content">
             <h2 class="section-title">VERIFICA NUESTRA CREDIBILIDAD</h2>
             <p style="color: var(--neon-green);">🌟 ¡SOLICITA REFERENCIAS Y EVITA ESTAFAS! 🌟</p>
        </div>
        <div class="afiche-gallery">
            <img src="https://uploads.onecompiler.io/446pw6tzp/446puxgcb/VIP%202.png" alt="Afiche 1 VIP PRO SC 2026">
            <img src="https://uploads.onecompiler.io/446pw6tzp/446puxgcb/VIP%202%20-%202026.png" alt="Afiche 2 VIP PRO SC 2026">
            <img src="https://uploads.onecompiler.io/446pw6tzp/446puxgcb/VIP%201%20-%202026.png" alt="Afiche 3 VIP PRO SC 2026">
            
        </div>

    </div>

    <footer>
        <p style="color: var(--neon-red);">🚨 ¡ATENCIÓN! Venta y Soporte Únicamente en:</p>
        <p class="whatsapp-contact">
            <a href="https://wa.me/51979679324" target="_blank">
                📲 WhatsApp: +51 979679324
            </a>
        </p>
    </footer>

</body>
</html>
