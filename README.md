# rintoulcarpinteria.github.io
Somos una carpinteria con mas de 40 años de experiencia, fabricamos y diseñamos cualquier tipo de muebles 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DormiBox | Carpintería Técnica para Arquitectos y Diseñadores</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #2c3e50;
            background: #fff;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
            color: white;
            padding: 80px 20px 60px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 2.8em;
            margin-bottom: 15px;
            font-weight: 700;
            letter-spacing: -1px;
        }
        
        .hero .tagline {
            font-size: 1.4em;
            margin-bottom: 10px;
            color: #f39c12;
            font-weight: 500;
        }
        
        .hero .subtitle {
            font-size: 1.1em;
            color: #bdc3c7;
            margin-bottom: 20px;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .hero .experience {
            font-size: 1.1em;
            color: #ecf0f1;
            margin-bottom: 35px;
            font-weight: 600;
        }
        
        .cta-primary {
            display: inline-block;
            background: #f39c12;
            color: white;
            padding: 18px 45px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1em;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(243, 156, 18, 0.3);
            margin: 10px;
        }
        
        .cta-primary:hover {
            background: #e67e22;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(243, 156, 18, 0.4);
        }
        
        .cta-secondary {
            display: inline-block;
            background: transparent;
            color: white;
            padding: 18px 45px;
            text-decoration: none;
            border-radius: 50px;
            border: 2px solid white;
            font-weight: 600;
            font-size: 1.1em;
            transition: all 0.3s;
            margin: 10px;
        }
        
        .cta-secondary:hover {
            background: white;
            color: #2c3e50;
        }
        
        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Section Styles */
        section {
            padding: 70px 20px;
        }
        
        section h2 {
            font-size: 2.4em;
            margin-bottom: 15px;
            text-align: center;
            color: #2c3e50;
            font-weight: 700;
        }
        
        section .intro {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 50px;
            font-size: 1.15em;
            color: #555;
            line-height: 1.8;
        }
        
        /* Value Proposition */
        .value-prop {
            background: #f8f9fa;
        }
        
        .value-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .value-card {
            background: white;
            padding: 35px 25px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
            transition: transform 0.3s;
            text-align: center;
        }
        
        .value-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0,0,0,0.12);
        }
        
        .value-card .icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        
        .value-card h3 {
            color: #2c3e50;
            margin-bottom: 12px;
            font-size: 1.3em;
        }
        
        .value-card p {
            color: #666;
            line-height: 1.6;
        }
        
        /* Projects Section */
        .projects {
            background: white;
        }
        
        .project {
            margin-bottom: 80px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }
        
        .project:nth-child(even) {
            direction: rtl;
        }
        
        .project:nth-child(even) .project-info {
            direction: ltr;
        }
        
        .project-images {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        
        .project-image {
            width: 100%;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 15px rgba(0,0,0,0.1);
        }
        
        .project-image img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }
        
        .project-image.full {
            grid-column: 1 / -1;
        }
        
        .project-image.full img {
            height: 350px;
        }
        
        .project-info {
            padding: 20px;
        }
        
        .project-type {
            display: inline-block;
            background: #f39c12;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 600;
            margin-bottom: 15px;
        }
        
        .project-info h3 {
            font-size: 1.8em;
            color: #2c3e50;
            margin-bottom: 15px;
        }
        
        .project-materials {
            color: #7f8c8d;
            font-style: italic;
            margin-bottom: 20px;
            font-size: 0.95em;
        }
        
        .project-challenge {
            background: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #f39c12;
        }
        
        .project-challenge strong {
            color: #2c3e50;
            display: block;
            margin-bottom: 8px;
        }
        
        /* Partner Program */
        .partner-program {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
        }
        
        .partner-program h2 {
            color: white;
        }
        
        .partner-program .intro {
            color: #ecf0f1;
        }
        
        .partner-benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .benefit-card {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
        }
        
        .benefit-card .icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        
        .benefit-card h3 {
            font-size: 1.3em;
            margin-bottom: 10px;
        }
        
        .benefit-card p {
            color: #ecf0f1;
            line-height: 1.6;
        }
        
        .commission-tiers {
            background: rgba(243, 156, 18, 0.15);
            padding: 40px;
            border-radius: 12px;
            margin-top: 40px;
            border: 2px solid rgba(243, 156, 18, 0.3);
        }
        
        .commission-tiers h3 {
            text-align: center;
            font-size: 1.8em;
            margin-bottom: 30px;
            color: #f39c12;
        }
        
        .tier {
            background: white;
            color: #2c3e50;
            padding: 25px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        
        .tier h4 {
            font-size: 1.4em;
            margin-bottom: 10px;
            color: #f39c12;
        }
        
        .tier p {
            color: #555;
            line-height: 1.6;
        }
        
        /* Work Models */
        .work-models {
            background: #f8f9fa;
        }
        
        .models-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .model-card {
            background: white;
            padding: 40px 30px;
            border-radius: 12px;
            box-shadow: 0 3px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }
        
        .model-card:hover {
            transform: translateY(-5px);
        }
        
        .model-card .model-number {
            background: #f39c12;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8em;
            font-weight: 700;
            margin: 0 auto 20px;
        }
        
        .model-card h3 {
            font-size: 1.5em;
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        .model-card p {
            color: #666;
            line-height: 1.7;
            margin-bottom: 15px;
        }
        
        .model-card .margin {
            background: #ecf0f1;
            padding: 12px;
            border-radius: 6px;
            font-weight: 600;
            color: #2c3e50;
            margin-top: 20px;
        }
        
        /* Capabilities */
        .capabilities {
            background: white;
        }
        
        .capabilities-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }
        
        .capability-item {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            border-left: 4px solid #f39c12;
        }
        
        .capability-item strong {
            display: block;
            color: #2c3e50;
            font-size: 1.1em;
        }
        
        /* Social Proof */
        .social-proof {
            background: #ecf0f1;
            text-align: center;
        }
        
        .clients-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 30px;
        }
        
        .client-item {
            background: white;
            padding: 20px 35px;
            border-radius: 8px;
            font-weight: 600;
            color: #2c3e50;
            box-shadow: 0 2px 10px rgba(0,0,0,0.08);
        }
        
        /* Contact Section */
        .contact {
            background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
            color: white;
            text-align: center;
        }
        
        .contact h2 {
            color: white;
        }
        
        .contact .intro {
            color: #ecf0f1;
        }
        
        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
            margin-bottom: 40px;
        }
        
        .contact-item {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
        }
        
        .contact-item .icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        
        .contact-item h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        
        .contact-item a {
            color: #f39c12;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        
        .contact-item a:hover {
            color: #e67e22;
        }
        
        /* Footer */
        footer {
            background: #1a1a1a;
            color: #bdc3c7;
            text-align: center;
            padding: 30px 20px;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }
            
            .hero .tagline {
                font-size: 1.1em;
            }
            
            section h2 {
                font-size: 1.8em;
            }
            
            .project {
                grid-template-columns: 1fr;
                direction: ltr !important;
            }
            
            .project:nth-child(even) .project-info {
                direction: ltr;
            }
            
            .project-images {
                grid-template-columns: 1fr;
            }
            
            .project-image img {
                height: 200px;
            }
            
            .project-image.full img {
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>DORMIBOX</h1>
            <p class="tagline">Carpintería Técnica para Arquitectos y Diseñadores</p>
            <p class="subtitle">Somos tu partner de confianza para convertir diseños en realidad. Calidad, cumplimiento y comunicación fluida.</p>
            <p class="experience">🏆 Más de 40 años de experiencia | Maipú, Mendoza</p>
            <a href="#contact" class="cta-primary">📞 Hablemos de tu Proyecto</a>
            <a href="#partner" class="cta-secondary">Programa Partners</a>
        </div>
    </section>

    <!-- Value Proposition -->
    <section class="value-prop">
        <div class="container">
            <h2>¿Por qué elegirnos como tu carpintería?</h2>
            <p class="intro">Sabemos lo que necesitás: un proveedor que no te falle, que entienda tus diseños y que entregue resultados que hagan brillar tu trabajo.</p>
            
            <div class="value-grid">
                <div class="value-card">
                    <div class="icon">✅</div>
                    <h3>Cumplimiento Real</h3>
                    <p>Timeline realista desde el principio. Sin sorpresas, sin excusas. Tu proyecto en tiempo y forma.</p>
                </div>
                
                <div class="value-card">
                    <div class="icon">🎯</div>
                    <h3>Calidad Consistente</h3>
                    <p>40 años de experiencia. Trabajamos con clientes como María Elena Walsh y CARI. Tu reputación está en buenas manos.</p>
                </div>
                
                <div class="value-card">
                    <div class="icon">💬</div>
                    <h3>Comunicación Fluida</h3>
                    <p>Presupuestos en 24-48hs. WhatsApp directo. Fotos de avance semanales. Soluciones técnicas cuando las necesitás.</p>
                </div>
                
                <div class="value-card">
                    <div class="icon">🔧</div>
                    <h3>Capacidad Técnica</h3>
                    <p>De plano a realidad. Resolvemos desafíos técnicos complejos. Co-diseño cuando lo necesitás.</p>
                </div>
                
                <div class="value-card">
                    <div class="icon">📐</div>
                    <h3>Escala Flexible</h3>
                    <p>Proyectos desde pequeños hasta 11 metros lineales. Residencial y comercial. Todo el país según escala.</p>
                </div>
                
                <div class="value-card">
                    <div class="icon">💰</div>
                    <h3>Comisiones Atractivas</h3>
                    <p>8-15% de comisión según volumen. Tus clientes pagan directo, vos cobrás por referir.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Portfolio -->
    <section class="projects" id="projects">
        <div class="container">
            <h2>Portfolio: Del Plano a la Realidad</h2>
            <p class="intro">Cada proyecto es un desafío técnico resuelto. Así trabajamos con estudios de arquitectura en Mendoza y todo el país.</p>
            
            <!-- Project 1 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/8B4513/FFFFFF?text=Biblioteca+Caoba+-+Plano" alt="Plano biblioteca">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/D2691E/FFFFFF?text=Resultado+1" alt="Biblioteca finalizada 1">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/D2691E/FFFFFF?text=Resultado+2" alt="Biblioteca finalizada 2">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Residencial</span>
                    <h3>Biblioteca Caoba Lustrada</h3>
                    <p class="project-materials">Enchapado caoba natural · Lustrado a mano</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>El cliente trajo su biblioteca personal de Estados Unidos. Diseñamos un mueble de grandes dimensiones con resistencia óptima para soportar el peso de cientos de libros. Se fabricó semi-armado para que el montaje in-situ no llevara más de 8 horas.</p>
                    </div>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/556B2F/FFFFFF?text=Cocina+Monoambiente+-+Plano" alt="Plano cocina">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/8FBC8F/FFFFFF?text=Resultado+1" alt="Cocina finalizada 1">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/8FBC8F/FFFFFF?text=Resultado+2" alt="Cocina finalizada 2">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Residencial</span>
                    <h3>Cocina Integral para Monoambiente</h3>
                    <p class="project-materials">Enchapado Leriex · Eucalipto macizo</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Aumentar capacidad de guardado en un mueble estético visible desde todos los ángulos. Isla funcional que "separa" la cocina del living. Todo el proyecto ejecutado de 0 a 100 en solo 10 días.</p>
                    </div>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/4682B4/FFFFFF?text=Cómoda+a+Medida+-+Plano" alt="Plano cómoda">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/87CEEB/FFFFFF?text=Resultado+1" alt="Cómoda finalizada">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Residencial</span>
                    <h3>Cómoda a Medida</h3>
                    <p class="project-materials">Melamina sobre MDF</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Aprovechar un rincón específico sin utilidad para ampliar la capacidad de guardado. Diseño exacto a medida del espacio disponible.</p>
                    </div>
                </div>
            </div>

            <!-- Project 4 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/2F4F4F/FFFFFF?text=Mueble+TV+-+Plano" alt="Plano mueble TV">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/696969/FFFFFF?text=Resultado+1" alt="Mueble TV finalizado">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Residencial</span>
                    <h3>Cómoda con Mueble de TV</h3>
                    <p class="project-materials">Melamina sobre MDF</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Unificar cómoda y mueble para TV con equipos de sonido en un solo diseño estético. Gestión de cables ocultos con facilidad para conexiones y desconexiones.</p>
                    </div>
                </div>
            </div>

            <!-- Project 5 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/8B7355/FFFFFF?text=Mueble+Laundry+-+Plano" alt="Plano laundry">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/D2B48C/FFFFFF?text=Resultado+1" alt="Laundry finalizado">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Residencial</span>
                    <h3>Mueble Laundry</h3>
                    <p class="project-materials">Leriex lustrado</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Mueble de gran porte en espacio pequeño. Diseño modular simétrico para múltiples configuraciones. Espacios específicos para cada etapa del proceso: lavado, planchado y guardado de productos.</p>
                    </div>
                </div>
            </div>

            <!-- Project 6 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/8B4513/FFFFFF?text=Mostrador+Comercial+-+Plano" alt="Plano mostrador">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/A0522D/FFFFFF?text=Resultado+1" alt="Mostrador finalizado">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Comercial</span>
                    <h3>Mostrador de Ingreso y Vitrinas</h3>
                    <p class="project-materials">Enchapado cedro · Teñido wengue</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Local de moda y accesorios. Recibir mercadería de forma elegante y funcional aprovechando el espacio disponible. Diseño que refleja la estética premium del negocio.</p>
                    </div>
                </div>
            </div>

            <!-- Project 7 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/722F37/FFFFFF?text=Bodega+Exhibidor+-+Plano" alt="Plano bodega">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/8B4789/FFFFFF?text=Resultado+1" alt="Bodega finalizada">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Comercial - Vinoteca</span>
                    <h3>Bodega Exhibidor</h3>
                    <p class="project-materials">MDF enchapado caoba · Lustrado</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Absorber diferencias de profundidad por columnas y tabiques del ambiente, logrando que el mueble se vea totalmente simétrico. Solución técnica invisible para el cliente final.</p>
                    </div>
                </div>
            </div>

            <!-- Project 8 -->
            <div class="project">
                <div class="project-images">
                    <div class="project-image full">
                        <img src="https://via.placeholder.com/800x400/1C1C1C/FFFFFF?text=Biblioteca+11m+-+Plano" alt="Plano biblioteca 11m">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/404040/FFFFFF?text=Resultado+1" alt="Biblioteca 11m finalizada 1">
                    </div>
                    <div class="project-image">
                        <img src="https://via.placeholder.com/400x300/404040/FFFFFF?text=Resultado+2" alt="Biblioteca 11m finalizada 2">
                    </div>
                </div>
                <div class="project-info">
                    <span class="project-type">Comercial - Papelería</span>
                    <h3>Biblioteca Pared a Pared (11 metros)</h3>
                    <p class="project-materials">Cliente: Papelera Palermo</p>
                    <div class="project-challenge">
                        <strong>Desafío Técnico:</strong>
                        <p>Albergar todo el material de trabajo del taller de encuadernación. Balance entre exhibición al público y stock operativo. Diseño de 11 metros lineales con máxima capacidad.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Work Models -->
    <section class="work-models" id="work-models">
        <div class="container">
            <h2>3 Formas de Trabajar Juntos</h2>
            <p class="intro">Elegí el modelo que mejor se adapte a tu proyecto y forma de trabajar</p>
            
            <div class="models-grid">
                <div class="model-card">
                    <div class="model-number">1</div>
                    <h3>Ejecutamos tu Diseño</h3>
                    <p>Vos diseñás 100% del proyecto. Nosotros fabricamos e instalamos según tus planos y especificaciones técnicas.</p>
                    <p><strong>Ideal para:</strong> Diseñadores con estudio establecido que manejan todo el proceso creativo.</p>
                    <div class="margin">Tu comisión: 8-12%</div>
                </div>
                
                <div class="model-card">
                    <div class="model-number">2</div>
                    <h3>Co-Diseño Técnico</h3>
                    <p>Vos aportás el concepto general, estética y medidas. Nosotros optimizamos el diseño técnico, detalles constructivos y fabricación.</p>
                    <p><strong>Ideal para:</strong> Arquitectos que necesitan soporte técnico en carpintería especializada.</p>
                    <div class="margin">Tu comisión: 10-15%</div>
                </div>
                
                <div class="model-card">
                    <div class="model-number">3</div>
                    <h3>Llave en Mano</h3>
                    <p>Tu cliente contacta directo a DormiBox (por tu referido). Nosotros gestionamos todo: diseño, fabricación e instalación.</p>
                    <p><strong>Ideal para:</strong> Referencias de clientes que necesitan carpintería pero vos no querés gestionar el proyecto.</p>
                    <div class="margin">Tu comisión: 10%</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Partner Program -->
    <section class="partner-program" id="partner">
        <div class="container">
            <h2>Programa Partner DormiBox</h2>
            <p class="intro">Más que un proveedor, somos tu aliado estratégico. Crecemos juntos.</p>
            
            <div class="partner-benefits">
                <div class="benefit-card">
                    <div class="icon">💰</div>
                    <h3>Comisiones Escalables</h3>
                    <p>8% en el primer proyecto, hasta 15% cuando consolidamos la relación. Tus clientes pagan directo, vos cobrás tu comisión.</p>
                </div>
                
                <div class="benefit-card">
                    <div class="icon">⚡</div>
                    <h3>Presupuestos Express</h3>
                    <p>Respuesta en 24-48hs. Te ayudamos a cerrar proyectos rápido con cotizaciones profesionales y detalladas.</p>
                </div>
                
                <div class="benefit-card">
                    <div class="icon">📱</div>
                    <h3>Línea Directa</h3>
                    <p>WhatsApp directo con Jess. Respuestas en menos de 2 horas en horario laboral. Sin intermediarios.</p>
                </div>
                
                <div class="benefit-card">
                    <div class="icon">🎯</div>
                    <h3>Prioridad en Calendario</h3>
                    <p>Partners tienen prioridad en nuestro timeline de producción. Tu proyecto no espera.</p>
                </div>
                
                <div class="benefit-card">
                    <div class="icon">📸</div>
                    <h3>Fotos de Avance</h3>
                    <p>Actualizaciones semanales durante fabricación. Vos y tu cliente siempre al tanto del progreso.</p>
                </div>
                
                <div class="benefit-card">
                    <div class="icon">🔧</div>
                    <h3>Soporte Técnico</h3>
                    <p>Visitas a obra cuando sean necesarias. Resolvemos juntos los desafíos que surgen in-situ.</p>
                </div>
            </div>
            
            <div class="commission-tiers">
                <h3>Sistema de Comisiones Escalonadas</h3>
                
                <div class="tier">
                    <h4>Nivel 1 - Proyecto Inicial</h4>
                    <p>Tu primer proyecto con nosotros: <strong>8% de comisión</strong> sobre el valor total del proyecto. Queremos conocernos y demostrarte nuestra calidad.</p>
                </div>
                
                <div class="tier">
                    <h4>Nivel 2 - Partner Activo</h4>
                    <p>A partir del segundo proyecto: <strong>12% de comisión</strong>. Ya nos conocemos, optimizamos tiempos y comunicación.</p>
                </div>
                
                <div class="tier">
                    <h4>Nivel 3 - Partner Estratégico</h4>
                    <p>A partir del quinto proyecto: <strong>15% de comisión + beneficios extra</strong>. Crédito a 30 días, prioridad absoluta en calendario, muestras de materiales gratis.</p>
                </div>
            </div>
            
            <div style="text-align: center; margin-top: 50px;">
                <a href="#contact" class="cta-primary">Quiero ser Partner</a>
            </div>
        </div>
    </section>

    <!-- Capabilities -->
    <section class="capabilities">
        <div class="container">
            <h2>Capacidades Técnicas</h2>
            <p class="intro">40 años de experiencia nos permiten abordar cualquier desafío de carpintería</p>
            
            <div class="capabilities-grid">
                <div class="capability-item">
                    <strong>🪑 Cocinas Integrales</strong>
                </div>
                <div class="capability-item">
                    <strong>🚿 Muebles de Baño</strong>
                </div>
                <div class="capability-item">
                    <strong>👔 Placares / Vestidores</strong>
                </div>
                <div class="capability-item">
                    <strong>🏢 Mobiliario Comercial</strong>
                </div>
                <div class="capability-item">
                    <strong>🍷 Muebles para Bodegas</strong>
                </div>
                <div class="capability-item">
                    <strong>🔨 Restauración de Muebles</strong>
                </div>
            </div>
            
            <div style="margin-top: 50px;">
                <h3 style="text-align: center; margin-bottom: 30px; color: #2c3e50;">Materiales con los que Trabajamos</h3>
                <div class="capabilities-grid">
                    <div class="capability-item">
                        <strong>🌳 Maderas Macizas</strong>
                        <p>Roble, Pino, Eucalipto, Cedro, Caoba</p>
                    </div>
                    <div class="capability-item">
                        <strong>📋 Melamina / MDF</strong>
                        <p>Alta calidad, diversidad de colores</p>
                    </div>
                    <div class="capability-item">
                        <strong>✨ Enchapados Premium</strong>
                        <p>Leriex, Caoba, Cedro y más</p>
                    </div>
                </div>
            </div>
            
            <div style="margin-top: 50px; background: #f8f9fa; padding: 40px; border-radius: 12px;">
                <h3 style="text-align: center; margin-bottom: 20px; color: #2c3e50;">Tiempos de Entrega</h3>
                <p style="text-align: center; color: #666; margin-bottom: 30px;">Siempre a evaluar según complejidad de cada proyecto</p>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px;">
                    <div style="text-align: center; padding: 20px;">
                        <div style="font-size: 2em; margin-bottom: 10px;">⚡</div>
                        <strong style="display: block; margin-bottom: 10px; color: #2c3e50;">Proyecto Pequeño</strong>
                        <p style="color: #666;">7 a 60 días</p>
                    </div>
                    <div style="text-align: center; padding: 20px;">
                        <div style="font-size: 2em; margin-bottom: 10px;">🔨</div>
                        <strong style="display: block; margin-bottom: 10px; color: #2c3e50;">Proyecto Mediano</strong>
                        <p style="color: #666;">4 a 6 semanas</p>
                    </div>
                    <div style="text-align: center; padding: 20px;">
                        <div style="font-size: 2em; margin-bottom: 10px;">🏗️</div>
                        <strong style="display: block; margin-bottom: 10px; color: #2c3e50;">Proyecto Grande</strong>
                        <p style="color: #666;">6 a 16 semanas</p>
                    </div>
                </div>
            </div>
            
            <div style="margin-top: 40px; text-align: center; background: #ecf0f1; padding: 30px; border-radius: 12px;">
                <h4 style="color: #2c3e50; margin-bottom: 15px;">Alcance Geográfico</h4>
                <p style="font-size: 1.1em; color: #555;">📍 Base en Maipú, Mendoza | Trabajamos en <strong>todo el país</strong> según escala del proyecto</p>
                <p style="margin-top: 10px; color: #666;">Instalación incluida | Logística propia para proyectos grandes</p>
            </div>
        </div>
    </section>

    <!-- Social Proof -->
    <section class="social-proof">
        <div class="container">
            <h2>Clientes que Confiaron en Nosotros</h2>
            <p class="intro">40 años fabricando para los más exigentes</p>
            
            <div class="clients-list">
                <div class="client-item">
                    🎵 María Elena Walsh
                </div>
                <div class="client-item">
                    🌐 CARI - Consejo Argentino para Relaciones Internacionales
                </div>
                <div class="client-item">
                    📚 Papelera Palermo
                </div>
                <div class="client-item">
                    🏛️ Múltiples estudios de arquitectura en Mendoza
                </div>
            </div>
            
            <div style="margin-top: 50px; max-width: 700px; margin-left: auto; margin-right: auto;">
                <div style="background: white; padding: 40px; border-radius: 12px; box-shadow: 0 3px 15px rgba(0,0,0,0.1);">
                    <div style="font-size: 3em; color: #f39c12; text-align: center; margin-bottom: 20px;">"</div>
                    <p style="font-size: 1.2em; line-height: 1.8; color: #2c3e50; text-align: center; font-style: italic;">
                        Más de 4 décadas transformando diseños en realidad. Cada proyecto es un compromiso con la excelencia.
                    </p>
                    <p style="text-align: center; margin-top: 20px; font-weight: 600; color: #f39c12;">— Jess Alós, DormiBox</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2>Hablemos de tu Próximo Proyecto</h2>
            <p class="intro">¿Tenés un proyecto en mente? ¿Querés sumarte al Programa Partner? Contactanos ahora.</p>
            
            <div class="contact-info">
                <div class="contact-item">
                    <div class="icon">📱</div>
                    <h3>WhatsApp / Teléfono</h3>
                    <a href="https://wa.me/5492612056984" target="_blank">+54 9 261 205-6984</a>
                    <p style="margin-top: 10px; font-size: 0.9em;">Respuesta en menos de 2 horas</p>
                </div>
                
                <div class="contact-item">
                    <div class="icon">📧</div>
                    <h3>Email</h3>
                    <a href="mailto:carpinteriarintoul@gmail.com">carpinteriarintoul@gmail.com</a>
                    <p style="margin-top: 10px; font-size: 0.9em;">Presupuestos en 24-48hs</p>
                </div>
                
                <div class="contact-item">
                    <div class="icon">📸</div>
                    <h3>Instagram</h3>
                    <a href="https://instagram.com/rintoul_carpinteria" target="_blank">@rintoul_carpinteria</a>
                    <p style="margin-top: 10px; font-size: 0.9em;">Seguí nuestros proyectos</p>
                </div>
                
                <div class="contact-item">
                    <div class="icon">📍</div>
                    <h3>Ubicación</h3>
                    <p style="color: #f39c12; font-weight: 600;">Maipú, Mendoza</p>
                    <p style="margin-top: 10px; font-size: 0.9em;">Trabajamos en todo el país</p>
                </div>
            </div>
            
            <div style="margin-top: 50px;">
                <a href="https://wa.me/5492612056984?text=Hola!%20Soy%20arquitecto/diseñador%20y%20me%20interesa%20el%20Programa%20Partner%20de%20DormiBox" class="cta-primary" target="_blank">💬 Enviar WhatsApp Ahora</a>
                <a href="mailto:carpinteriarintoul@gmail.com?subject=Consulta%20Programa%20Partner%20DormiBox" class="cta-secondary">📧 Enviar Email</a>
            </div>
            
            <div style="margin-top: 60px; padding-top: 40px; border-top: 1px solid rgba(255,255,255,0.2);">
                <h3 style="margin-bottom: 20px;">Proceso Simple para Empezar:</h3>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 30px; margin-top: 30px;">
                    <div style="text-align: center;">
                        <div style="background: rgba(243, 156, 18, 0.2); width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 15px; font-size: 1.8em; font-weight: 700;">1</div>
                        <p>Contactanos por WhatsApp o Email</p>
                    </div>
                    <div style="text-align: center;">
                        <div style="background: rgba(243, 156, 18, 0.2); width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 15px; font-size: 1.8em; font-weight: 700;">2</div>
                        <p>Reunión de 20 min (presencial o virtual)</p>
                    </div>
                    <div style="text-align: center;">
                        <div style="background: rgba(243, 156, 18, 0.2); width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 15px; font-size: 1.8em; font-weight: 700;">3</div>
                        <p>Cotizamos tu próximo proyecto</p>
                    </div>
                    <div style="text-align: center;">
                        <div style="background: rgba(243, 156, 18, 0.2); width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 15px; font-size: 1.8em; font-weight: 700;">4</div>
                        <p>¡Arrancamos a trabajar juntos!</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p style="margin-bottom: 10px;"><strong>DORMIBOX - Carpintería Técnica</strong></p>
            <p>Maipú, Mendoza, Argentina | Más de 40 años de experiencia</p>
            <p style="margin-top: 20px; font-size: 0.9em;">© 2024 DormiBox. Tu visión, nuestra ejecución.</p>
        </div>
    </footer>
</body>
</html>
