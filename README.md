<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indicadores de Sostenibilidad - GUAPITOS, SL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
            transition: background-color 0.5s ease;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 1s ease-in-out forwards;
        }
        h1, h2, h3 {
            color: #2c3e50;
            text-align: center;
            transition: color 0.3s;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: #ecf0f1;
            margin: 10px 0;
            padding: 12px;
            border-radius: 5px;
            display: flex;
            align-items: center;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, background 0.3s;
            cursor: pointer;
        }
        ul li:hover {
            transform: scale(1.05);
            background: #d5dbdb;
        }
        .icon {
            font-size: 1.4em;
            margin-right: 10px;
        }
        p {
            text-align: justify;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .fadeInSection {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fadeInSection.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const sections = document.querySelectorAll(".fadeInSection");
            const observer = new IntersectionObserver(entries => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add("visible");
                    }
                });
            }, { threshold: 0.3 });
            sections.forEach(section => {
                observer.observe(section);
            });
        });
    </script>
</head>
<body>
    <div class="container">
        <h1>Indicadores de Sostenibilidad - GUAPITOS, SL</h1>
        
        <h2 class="fadeInSection">Indicadores Ambientales 🌱</h2>
        <ul class="fadeInSection">
            <li>✅ Implementación de sistemas de ahorro de agua y reducción de consumo en sus tratamientos.</li>
            <li>✅ Elaboración de productos de higiene con ingredientes naturales.</li>
            <li>✅ Uso de energías renovables y sostenibles.</li>
            <li>✅ Incorporación de vehículos eléctricos para minimizar la contaminación.</li>
        </ul>

        <h2 class="fadeInSection">Indicadores Sociales 🤝</h2>
        <ul class="fadeInSection">
            <li>✅ Aplicación de políticas laborales inclusivas que fomentan la conciliación entre la vida personal y profesional.</li>
            <li>✅ Compromiso con el bienestar de las comunidades locales mediante acciones de responsabilidad social.</li>
        </ul>

        <h2 class="fadeInSection">Indicadores de Gobernanza 🏢</h2>
        <ul class="fadeInSection">
            <li>✅ Mantenimiento de un entorno laboral seguro, con mecanismos de prevención que han logrado la ausencia de accidentes.</li>
            <li>✅ Implementación de estrategias de responsabilidad social que generan beneficios tanto en la empresa como en su entorno.</li>
        </ul>

        <h2 class="fadeInSection">Importancia de los Indicadores de Sostenibilidad</h2>
        <p class="fadeInSection">Los indicadores de sostenibilidad son herramientas esenciales que permiten a las empresas medir y mejorar su impacto en el medioambiente, la sociedad y la economía. Funcionan como una guía para garantizar un crecimiento equilibrado y responsable, sin comprometer los recursos naturales ni el bienestar de las personas.</p>

        <h3 class="fadeInSection">Aspectos clave en la evaluación de la sostenibilidad:</h3>
        <ul class="fadeInSection">
            <li>🌿 Tecnologías limpias y eficiencia energética, que optimizan el uso de recursos y reducen la huella ambiental.</li>
            <li>♻️ Gestión de residuos y diseño ecológico, promoviendo un modelo de producción más consciente y sostenible.</li>
            <li>✅ Certificaciones ambientales, que reflejan el compromiso real de la empresa con la preservación del entorno.</li>
            <li>🚛 Innovación en envases y transporte sostenible, elementos esenciales para fomentar una economía circular y reducir el impacto ambiental.</li>
            <li>💡 Responsabilidad Social Empresarial (RSE), que impulsa iniciativas en beneficio de las comunidades y garantiza condiciones laborales justas.</li>
            <li>📚 Educación y formación continua, pues la concienciación y el conocimiento son la base para lograr cambios sostenibles a largo plazo.</li>
        </ul>
        
        <p class="fadeInSection">Estos indicadores no solo miden el progreso, sino que representan una oportunidad para transformar nuestro presente en un futuro más equitativo y sostenible para todos.</p>
    </div>
    <p>TRABAJO REALIZADO POR:YUSSEF DAMMIR Y NOUR</p>

</body>
