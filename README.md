<html><head><base href="https://hacker-headtricking.example.com">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<title>HEADTRICK FEFE</title>
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<style>
    body {
        background-image: none;
        background-color: #000;
        font-family: 'Courier New', monospace;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        position: relative;
        overflow: hidden;
    }
    #particles-js {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        z-index: -1;
    }
    .panel-container {
        background-color: rgba(0, 0, 0, 0.8);
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 0 20px rgba(255, 0, 0, 0.5), 0 0 40px rgba(0, 255, 255, 0.3);
        width: 90%;
        max-width: 350px;
        margin: 20px auto;
        position: relative;
        overflow: hidden;
        animation: float 4s ease-in-out infinite;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .panel-container:hover {
        transform: scale(1.05);
        box-shadow: 0 0 30px rgba(255, 0, 0, 0.7), 0 0 60px rgba(0, 255, 255, 0.5);
    }
    h1 {
        text-align: center;
        color: #FF0000;
        text-shadow: 1px 1px 3px #000000;
        animation: glitch 1s linear infinite alternate;
        margin-bottom: 5px;
    }
    .subtitle {
        text-align: center;
        color: #FF0000;
        font-size: 0.8em;
        margin-top: 0;
        margin-bottom: 5px;
    }
    button {
        display: block;
        width: 100%;
        margin: 20px 0;
        padding: 15px;
        border: 2px solid #FF0000;
        border-radius: 5px;
        background: linear-gradient(45deg, #000, #330000);
        color: #FF0000;
        cursor: pointer;
        transition: all 0.5s ease;
        text-transform: uppercase;
        letter-spacing: 2px;
        -webkit-appearance: none;
        -moz-appearance: none;
        appearance: none;
    }
    button:hover {
        background: linear-gradient(45deg, #FF0000, #800000);
        color: #000;
        box-shadow: 0 0 15px #FF0000;
        transform: translateY(-3px);
    }
    .slider-container {
        margin-bottom: 20px;
    }
    .slider {
        -webkit-appearance: none;
        width: 100%;
        height: 20px;
        border-radius: 10px;
        background: #ccc;
        outline: none;
        opacity: 0.7;
        -webkit-transition: .2s;
        transition: opacity .2s;
    }
    .slider:hover {
        opacity: 1;
    }
    .slider::-webkit-slider-thumb {
        -webkit-appearance: none;
        appearance: none;
        width: 20px;
        height: 20px;
        border-radius: 50%;
        background: #FF0000;
        cursor: pointer;
        transition: transform 0.2s ease;
    }
    .slider::-webkit-slider-thumb:hover {
        transform: scale(1.2);
    }
    .slider::-moz-range-thumb {
        width: 20px;
        height: 20px;
        border-radius: 50%;
        background: #FF0000;
        cursor: pointer;
        transition: transform 0.2s ease;
    }
    .slider::-moz-range-thumb:hover {
        transform: scale(1.2);
    }
    .credits {
        text-align: center;
        color: #FF0000;
        font-size: 0.7em;
        margin-top: 0;
        margin-bottom: 20px;
    }
    .background-credits {
        position: fixed;
        bottom: 10px;
        right: 10px;
        color: rgba(255, 0, 0, 0.7);
        font-size: 14px;
        z-index: 0;
        text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
    }
    @keyframes glitch {
        0% {
            transform: translate(0)
        }
        20% {
            transform: translate(-5px, 5px)
        }
        40% {
            transform: translate(-5px, -5px)
        }
        60% {
            transform: translate(5px, 5px)
        }
        80% {
            transform: translate(5px, -5px)
        }
        to {
            transform: translate(0)
        }
    }
    @keyframes float {
        0% {
            transform: translatey(0px);
        }
        50% {
            transform: translatey(-20px);
        }
        100% {
            transform: translatey(0px);
        }
    }
</style>

<script>

{
    
    const headshotAssertivenessSlider = document.getElementById('headshot-assertiveness');
    const sensitivitySlider = document.getElementById('sensitivity');
    const headshotAssertivenessValue = document.getElementById('headshot-assertiveness-value');
    const sensitivityValue = document.getElementById('sensitivity-value');
 }
    function updateHeadshotAssertiveness() {
        headshotAssertivenessValue.textContent = headshotAssertivenessSlider.value;
        limitarAlturaMira();
        ajustarSensibilidad();
    }

    function limitarAlturaMira() {
        const alturaMaxima = 0;
        const alturaActual = headshotAssertivenessSlider.value;
        if (alturaActual > alturaMaxima) {
            headshotAssertivenessSlider.value = alturaMaxima;
            headshotAssertivenessValue.textContent = alturaMaxima;
        }
    }

    function ajustarSensibilidad() {
        const alturaActual = headshotAssertivenessSlider.value;
        const sensibilidadMinima = 0;
        const sensibilidadMaxima = 0;
        const factor = (alturaActual / 0) * (sensibilidadMaxima - sensibilidadMinima) + sensibilidadMinima;
        sensitivitySlider.value = factor * 0;
        sensitivityValue.textContent = sensitivitySlider.value;
    }

    headshotAssertivenessSlider.addEventListener('input', updateHeadshotAssertiveness);
    sensitivitySlider.addEventListener('input', updateSensitivity);

    // ... (rest of the script section remains the same)
</script>
</head>
<body>
    <div id="particles-js"></div>
    <div class="background-credits">by: @bernardosv14</div>
    <div class="panel-container">
        <h1>HEADTRICK FEFE</h1>
        <h2 class="subtitle">PREMIUM</h2>
        <p class="credits">@bernardosv14</p>
        <div class="slider-container">
            <h3><B>Calibrador</B>:</B></h3>
            <input type="range" id="headshot-assertiveness" min="0" max="100" value="50" class="slider">
            <p id="headshot-assertiveness-value">50</p>
        </div>
        <div class="slider-container">
            <h3><B>SENSIBILIDAD:</B></h3>
            <input type="range" id="sensitivity" min="0" max="100" value="50" class="slider">
            <p id="sensitivity-value">50</p>
        </div>
        <button id="save-settings">ACTIVE</button>
        
        <div class="credits">
            CRIADO POR: <a href="https://instagram.com/bernardosv14" target="_blank">@bernardosv14</a>
        </div>
    </div>

    <script>
        const headshotAssertivenessSlider = document.getElementById('headshot-assertiveness');
        const sensitivitySlider = document.getElementById('sensitivity');
        const headshotAssertivenessValue = document.getElementById('headshot-assertiveness-value');
        const sensitivityValue = document.getElementById('sensitivity-value');

        headshotAssertivenessSlider.addEventListener('input', updateHeadshotAssertiveness);
        sensitivitySlider.addEventListener('input', updateSensitivity);
        
        function updateHeadshotAssertiveness() {
            headshotAssertivenessValue.textContent = headshotAssertivenessSlider.value;
        }
        
        function updateSensitivity() {
            sensitivityValue.textContent = sensitivitySlider.value;
        }
        
        document.getElementById('save-settings').addEventListener('touchstart', function(e) {
            e.preventDefault();
            applySettings();
        });
        
        document.getElementById('save-settings').addEventListener('click', applySettings);
        
        function applySettings() {
            const headshotAssertiveness = parseInt(headshotAssertivenessSlider.value);
            const sensitivity = parseFloat(sensitivitySlider.value) / 100 * 1.5 + 1.3;

            const settings = {
                headshotAssertiveness: headshotAssertiveness,
                sensitivity: sensitivity.toFixed(4)
            };

            console.log('Configuración guardada:', settings);
            
            const additionalCode = `
                // Permanent Options
                aim_control = true
                headshot_limit = true
                headtricking_enabled = true

                // General Configuration
                // Sensitivity in BR map: sensitivity:float 1.4000
                // Sensitivity in Training Grounds map: sensitivity:float 1.4500
                // Sensitivity in Cage map: sensitivity:float 1.5000

                // Aim Control
                aim_smoothness = 10
                aim_acceleration = 60
                aim_prediction = 10
                aim_correction = 80

                // Headshot Limit
                headshot_offset = 0.1
                headshot_speed = 10

                // Headtricking Aimlock Fake Headshot
                headtricking_speed = 0.2
                headtricking_range = 60
                headtricking_accuracy = 990

                // Verification
                verification_enabled = true
                verification_interval = 1000 
                verification_checks = [
                  aim_control,
                  headshot_limit,
                  headtricking_enabled,
                  aim_smoothness,
                  aim_acceleration,
                  aim_prediction,
                  aim_correction,
                  headshot_offset,
                  headshot_speed,
                  headtricking_speed,
                  headtricking_range,
                  headtricking_accuracy
                ]

                // Specific Weapons
                // UMP
                sensitivity:float 2.3500
                aim_smoothness = 0
                aim_acceleration = 100
                maps: Bermuda, Purgatory, Kalahari, Venga, Miramar, Neón

                // Desert Eagle
                sensitivity:float 2.4000
                aim_smoothness = 0
                aim_acceleration = 100
                maps: Bermuda, Purgatory, Venga, Miramar, Neón, Faraday

                // M1014
                sensitivity:float 2.3000
                aim_smoothness = 0
                aim_acceleration = 100
                maps: Kalahari, Purgatory, Venga, Miramar, Neón, Faraday

                // XM8
                sensitivity:float 2.3500
                aim_smoothness = 0
                aim_acceleration = 100

                // Sensibilidad en mapa BR: sensitivity:dword 99279
                // Sensibilidad en mapa Training Grounds: sensitivity:dword 99280
                // Sensibilidad en mapa Cage: sensitivity:dword 99281

                fake_headshot = true
                fake_headshot_accuracy = 100
                fake_headshot_speed = 100
                fake_headshot_delay = 0.1
                advanced_fake_headshot = true
                advanced_fake_headshot_accuracy = 60
                advanced_fake_headshot_speed = 100
                advanced_fake_headshot_delay = 0.6
                aimbot_fake_headshot = true
                aimbot_fake_headshot_accuracy = 95
                aimbot_fake_headshot_speed = 100
                aimbot_fake_headshot_delay = 0.5
                fake_headshot_smoothing = 0
                fake_headshot_acceleration = 100
                fake_headshot_prediction = 18
                fake_headshot_correction = 40

                // Global activation
                activated = true
                enable_all = true

                // Options
                headshot_focus = true
                aim_assist = true
                auto_fire = true
                quick_scope = true
                all_maps_enabled = true
            `;

            console.log('Código adicional ativado e executado');
            console.log(additionalCode);

            showNotification('Configuração ativada. Por favor, deixe em segundo plano.');
        }

        function showNotification(message) {
            const notification = document.createElement('div');
            notification.textContent = message;
            notification.style.position = 'fixed';
            notification.style.bottom = '20px';
            notification.style.left = '50%';
            notification.style.transform = 'translateX(-50%)';
            notification.style.backgroundColor = 'rgba(255, 0, 0, 0.8)';
            notification.style.color = 'white';
            notification.style.padding = '10px 20px';
            notification.style.borderRadius = '5px';
            notification.style.zIndex = '1000';
            document.body.appendChild(notification);

            setTimeout(() => {
                document.body.removeChild(notification);
            }, 5000);
        }

        particlesJS('particles-js', {
            particles: {
                number: { value: 80, density: { enable: true, value_area: 800 } },
                color: { value: '#ff0000' },
                shape: { type: 'circle' },
                opacity: { value: 0.5, random: false },
                size: { value: 3, random: true },
                line_linked: { enable: true, distance: 150, color: '#ff0000', opacity: 0.4, width: 1 },
                move: { enable: true, speed: 6, direction: 'none', random: false, straight: false, out_mode: 'out', bounce: false }
            },
            interactivity: {
                detect_on: 'canvas',
                events: { onhover: { enable: true, mode: 'repulse' }, onclick: { enable: true, mode: 'push' }, resize: true },
                modes: { repulse: { distance: 100, duration: 0.4 }, push: { particles_nb: 4 } }
            },
            retina_detect: true
        });
    </script>
