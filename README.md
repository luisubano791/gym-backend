# gym-backend
Sitio web GYM
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IRONFORGE GYM | Forja Tu Mejor Versión</title>
  <meta name="description" content="IRONFORGE GYM — El gimnasio premium donde forjas tu cuerpo y mente. Entrenamiento personalizado, clases grupales y equipos de última generación." />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Outfit:wght@300;400;500;600;700;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- ========== NAVBAR ========== -->
  <nav class="navbar" id="navbar">
    <div class="nav-container">
      <a href="#hero" class="nav-logo">IRON<span>FORGE</span></a>
      <ul class="nav-links" id="nav-links">
        <li><a href="#about">Nosotros</a></li>
        <li><a href="#services">Servicios</a></li>
        <li><a href="#classes">Clases</a></li>
        <li><a href="#trainers">Entrenadores</a></li>
        <li><a href="#pricing">Planes</a></li>
        <li><a href="#contact">Contacto</a></li>
      </ul>
      <a href="#pricing" class="btn btn-primary nav-cta">Únete Ahora</a>
      <button class="hamburger" id="hamburger" aria-label="Menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </nav>

  <!-- ========== HERO ========== -->
  <section class="hero" id="hero">
    <div class="hero-bg"></div>
    <div class="hero-overlay"></div>
    <div class="hero-content">
      <span class="hero-badge">🔥 #1 GYM DE LA CIUDAD</span>
      <h1 class="hero-title">FORJA TU<br/><span class="gradient-text">MEJOR VERSIÓN</span></h1>
      <p class="hero-subtitle">Sin excusas. Sin límites. Solo resultados. Entrena con los mejores equipos y entrenadores de élite.</p>
      <div class="hero-cta">
        <a href="#pricing" class="btn btn-primary btn-lg">Comenzar Ahora</a>
        <a href="#classes" class="btn btn-outline btn-lg">Ver Clases</a>
      </div>
      <div class="hero-stats">
        <div class="stat"><span class="stat-num" data-target="1200">0</span><span class="stat-label">Miembros Activos</span></div>
        <div class="stat-divider"></div>
        <div class="stat"><span class="stat-num" data-target="15">0</span><span class="stat-label">Entrenadores Expertos</span></div>
        <div class="stat-divider"></div>
        <div class="stat"><span class="stat-num" data-target="8">0</span><span class="stat-label">Años de Experiencia</span></div>
      </div>
    </div>
    <div class="hero-scroll-indicator">
      <span>Scroll</span>
      <div class="scroll-line"></div>
    </div>
  </section>

  <!-- ========== ABOUT ========== -->
  <section class="about section" id="about">
    <div class="container">
      <div class="about-grid">
        <div class="about-images">
          <div class="img-card img-card-main reveal">
            <img src="assets/gym_interior.png" alt="Interior del gimnasio IRONFORGE" loading="lazy"/>
            <div class="img-badge">Est. 2016</div>
          </div>
          <div class="img-card img-card-secondary reveal">
            <img src="assets/trainer_coaching.png" alt="Entrenamiento personalizado" loading="lazy"/>
          </div>
        </div>
        <div class="about-text reveal">
          <span class="section-tag">Sobre Nosotros</span>
          <h2 class="section-title">Más que un gimnasio,<br/><em>una comunidad</em></h2>
          <p>En IRONFORGE creemos que cada persona tiene un potencial ilimitado esperando ser desbloqueado. Nuestras instalaciones de clase mundial y nuestro equipo de entrenadores certificados están aquí para guiarte en cada paso del camino.</p>
          <p>Desde 2016 hemos transformado miles de vidas. Nuestro método combina ciencia del ejercicio con motivación real para que alcances tus metas de forma sostenible.</p>
          <div class="about-features">
            <div class="feature-item"><span class="feature-icon">⚡</span><span>Equipos de última generación</span></div>
            <div class="feature-item"><span class="feature-icon">🏆</span><span>Entrenadores certificados internacionalmente</span></div>
            <div class="feature-item"><span class="feature-icon">🕐</span><span>Abierto 24/7 los 365 días del año</span></div>
            <div class="feature-item"><span class="feature-icon">🥗</span><span>Asesoría nutricional incluida</span></div>
          </div>
          <a href="#pricing" class="btn btn-primary">Conoce Nuestros Planes</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== SERVICES ========== -->
  <section class="services section" id="services">
    <div class="container">
      <div class="section-header reveal">
        <span class="section-tag">Lo Que Ofrecemos</span>
        <h2 class="section-title">Servicios <span class="gradient-text">Premium</span></h2>
        <p class="section-desc">Todo lo que necesitas para transformar tu cuerpo bajo un mismo techo</p>
      </div>
      <div class="services-grid">
        <div class="service-card reveal" style="--delay:0.1s">
          <div class="service-icon">💪</div>
          <h3>Musculación & Fuerza</h3>
          <p>Zona de pesas libre con más de 200 equipos. Barras olímpicas, mancuernas hasta 60kg y máquinas de cable.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
        <div class="service-card reveal" style="--delay:0.2s">
          <div class="service-icon">🏃</div>
          <h3>Cardio & Resistencia</h3>
          <p>Cintas de correr, elípticas, bicicletas y remos de última generación con entretenimiento integrado.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
        <div class="service-card reveal" style="--delay:0.3s">
          <div class="service-icon">🥊</div>
          <h3>Artes Marciales & Boxeo</h3>
          <p>Ring de boxeo profesional, sacos de golpeo, clases de MMA, Muay Thai y kickboxing.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
        <div class="service-card reveal" style="--delay:0.4s">
          <div class="service-icon">🧘</div>
          <h3>Yoga & Pilates</h3>
          <p>Sala exclusiva con ambiente relajante para yoga, pilates y meditación guiada por expertos certificados.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
        <div class="service-card reveal" style="--delay:0.5s">
          <div class="service-icon">🎯</div>
          <h3>Entrenamiento Personal</h3>
          <p>Programa 100% personalizado diseñado por tu entrenador según tus objetivos y nivel de condición física.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
        <div class="service-card reveal" style="--delay:0.6s">
          <div class="service-icon">🥗</div>
          <h3>Nutrición Deportiva</h3>
          <p>Asesoría nutricional con dietistas certificados, planes de alimentación y suplementación deportiva.</p>
          <a href="#" class="service-link">Saber más →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== CLASSES ========== -->
  <section class="classes section" id="classes">
    <div class="container">
      <div class="section-header reveal">
        <span class="section-tag">Clases Grupales</span>
        <h2 class="section-title">Entrena con <span class="gradient-text">Energía</span></h2>
        <p class="section-desc">Más de 30 clases semanales para todos los niveles</p>
      </div>
      <div class="schedule-tabs reveal">
        <button class="tab-btn active" data-day="lunes">Lunes</button>
        <button class="tab-btn" data-day="martes">Martes</button>
        <button class="tab-btn" data-day="miercoles">Miércoles</button>
        <button class="tab-btn" data-day="jueves">Jueves</button>
        <button class="tab-btn" data-day="viernes">Viernes</button>
        <button class="tab-btn" data-day="sabado">Sábado</button>
      </div>
      <div class="schedule-grid" id="schedule-grid">
        <!-- Filled by JS -->
      </div>
    </div>
  </section>

  <!-- ========== TRAINERS ========== -->
  <section class="trainers section" id="trainers">
    <div class="container">
      <div class="section-header reveal">
        <span class="section-tag">Nuestro Equipo</span>
        <h2 class="section-title">Entrenadores de <span class="gradient-text">Élite</span></h2>
        <p class="section-desc">Certificados, apasionados y listos para llevar tu rendimiento al máximo</p>
      </div>
      <div class="trainers-grid">
        <div class="trainer-card reveal" style="--delay:0.1s">
          <div class="trainer-img-wrap">
            <div class="trainer-avatar" style="background: linear-gradient(135deg,#ff6b1a,#ff3d00)">💪</div>
          </div>
          <div class="trainer-info">
            <h3>Carlos Mendoza</h3>
            <span class="trainer-role">Musculación & Fuerza</span>
            <p>Campeón nacional de powerlifting. 10 años transformando cuerpos y vidas.</p>
            <div class="trainer-social">
              <a href="#" aria-label="Instagram">📸</a>
              <a href="#" aria-label="Facebook">👥</a>
            </div>
          </div>
        </div>
        <div class="trainer-card reveal" style="--delay:0.2s">
          <div class="trainer-img-wrap">
            <div class="trainer-avatar" style="background: linear-gradient(135deg,#7c3aed,#4f46e5)">🥊</div>
          </div>
          <div class="trainer-info">
            <h3>Sofía Ramírez</h3>
            <span class="trainer-role">Boxeo & MMA</span>
            <p>Ex-atleta olímpica. Especialista en artes marciales mixtas y acondicionamiento funcional.</p>
            <div class="trainer-social">
              <a href="#" aria-label="Instagram">📸</a>
              <a href="#" aria-label="Facebook">👥</a>
            </div>
          </div>
        </div>
        <div class="trainer-card reveal" style="--delay:0.3s">
          <div class="trainer-img-wrap">
            <div class="trainer-avatar" style="background: linear-gradient(135deg,#059669,#10b981)">🧘</div>
          </div>
          <div class="trainer-info">
            <h3>Valentina Cruz</h3>
            <span class="trainer-role">Yoga & Bienestar</span>
            <p>Instructora certificada RYT-500. Especialista en yoga terapéutico y mindfulness.</p>
            <div class="trainer-social">
              <a href="#" aria-label="Instagram">📸</a>
              <a href="#" aria-label="Facebook">👥</a>
            </div>
          </div>
        </div>
        <div class="trainer-card reveal" style="--delay:0.4s">
          <div class="trainer-img-wrap">
            <div class="trainer-avatar" style="background: linear-gradient(135deg,#dc2626,#ef4444)">🏃</div>
          </div>
          <div class="trainer-info">
            <h3>Miguel Torres</h3>
            <span class="trainer-role">Cardio & HIIT</span>
            <p>Maratonista y especialista en entrenamiento de alta intensidad y pérdida de grasa.</p>
            <div class="trainer-social">
              <a href="#" aria-label="Instagram">📸</a>
              <a href="#" aria-label="Facebook">👥</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== PRICING ========== -->
  <section class="pricing section" id="pricing">
    <div class="container">
      <div class="section-header reveal">
        <span class="section-tag">Membresías</span>
        <h2 class="section-title">Elige Tu <span class="gradient-text">Plan</span></h2>
        <p class="section-desc">Sin contratos ocultos. Cancela cuando quieras.</p>
      </div>
      <div class="pricing-toggle reveal">
        <span class="toggle-label">Mensual</span>
        <label class="toggle-switch" for="billing-toggle">
          <input type="checkbox" id="billing-toggle" />
          <span class="toggle-slider"></span>
        </label>
        <span class="toggle-label">Anual <span class="badge-save">Ahorra 20%</span></span>
      </div>
      <div class="pricing-grid">
        <div class="pricing-card reveal" style="--delay:0.1s">
          <div class="plan-header">
            <span class="plan-icon">🌱</span>
            <h3>Básico</h3>
            <div class="plan-price">
              <span class="price monthly">$29</span>
              <span class="price annual" style="display:none">$23</span>
              <span class="price-period">/mes</span>
            </div>
          </div>
          <ul class="plan-features">
            <li>✅ Acceso a zona de cardio</li>
            <li>✅ Vestuarios y duchas</li>
            <li>✅ 2 clases grupales/semana</li>
            <li>✅ App de seguimiento</li>
            <li>❌ Entrenador personal</li>
            <li>❌ Zona de musculación libre</li>
          </ul>
          <a href="#contact" class="btn btn-outline btn-full">Comenzar</a>
        </div>
        <div class="pricing-card featured reveal" style="--delay:0.2s">
          <div class="plan-badge">Más Popular</div>
          <div class="plan-header">
            <span class="plan-icon">🔥</span>
            <h3>Pro</h3>
            <div class="plan-price">
              <span class="price monthly">$59</span>
              <span class="price annual" style="display:none">$47</span>
              <span class="price-period">/mes</span>
            </div>
          </div>
          <ul class="plan-features">
            <li>✅ Acceso completo 24/7</li>
            <li>✅ Clases grupales ilimitadas</li>
            <li>✅ 4 sesiones de entrenador/mes</li>
            <li>✅ Asesoría nutricional</li>
            <li>✅ App de seguimiento premium</li>
            <li>❌ Entrenamiento exclusivo VIP</li>
          </ul>
          <a href="#contact" class="btn btn-primary btn-full">Comenzar</a>
        </div>
        <div class="pricing-card reveal" style="--delay:0.3s">
          <div class="plan-header">
            <span class="plan-icon">👑</span>
            <h3>Elite</h3>
            <div class="plan-price">
              <span class="price monthly">$99</span>
              <span class="price annual" style="display:none">$79</span>
              <span class="price-period">/mes</span>
            </div>
          </div>
          <ul class="plan-features">
            <li>✅ Todo lo del plan Pro</li>
            <li>✅ Entrenador personal dedicado</li>
            <li>✅ Plan nutricional personalizado</li>
            <li>✅ Acceso zona VIP</li>
            <li>✅ Masajes deportivos</li>
            <li>✅ Evaluaciones mensuales</li>
          </ul>
          <a href="#contact" class="btn btn-outline btn-full">Comenzar</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TESTIMONIALS ========== -->
  <section class="testimonials section">
    <div class="container">
      <div class="section-header reveal">
        <span class="section-tag">Testimonios</span>
        <h2 class="section-title">Lo Que Dicen Nuestros <span class="gradient-text">Miembros</span></h2>
      </div>
      <div class="testimonials-slider reveal">
        <div class="testimonial-card active">
          <div class="stars">⭐⭐⭐⭐⭐</div>
          <p>"IRONFORGE cambió mi vida. En 6 meses perdí 18kg y gané confianza. Los entrenadores son increíbles y el ambiente te motiva cada día."</p>
          <div class="testimonial-author">
            <div class="author-avatar" style="background:linear-gradient(135deg,#ff6b1a,#ff3d00)">AM</div>
            <div><strong>Andrés Morales</strong><span>Miembro desde 2023</span></div>
          </div>
        </div>
        <div class="testimonial-card">
          <div class="stars">⭐⭐⭐⭐⭐</div>
          <p>"Las instalaciones son de primer nivel. El plan Elite vale cada centavo, el entrenador personal me diseñó un programa perfecto para mis objetivos."</p>
          <div class="testimonial-author">
            <div class="author-avatar" style="background:linear-gradient(135deg,#7c3aed,#4f46e5)">LG</div>
            <div><strong>Laura González</strong><span>Miembro desde 2022</span></div>
          </div>
        </div>
        <div class="testimonial-card">
          <div class="stars">⭐⭐⭐⭐⭐</div>
          <p>"Vine por curiosidad y me quedé por los resultados. La comunidad de IRONFORGE es única, siempre hay alguien dispuesto a motivarte."</p>
          <div class="testimonial-author">
            <div class="author-avatar" style="background:linear-gradient(135deg,#059669,#10b981)">RC</div>
            <div><strong>Roberto Castro</strong><span>Miembro desde 2024</span></div>
          </div>
        </div>
        <div class="testimonial-controls">
          <button id="prev-testimonial" aria-label="Anterior">‹</button>
          <div class="testimonial-dots">
            <span class="dot active" data-idx="0"></span>
            <span class="dot" data-idx="1"></span>
            <span class="dot" data-idx="2"></span>
          </div>
          <button id="next-testimonial" aria-label="Siguiente">›</button>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== CONTACT ========== -->
  <section class="contact section" id="contact">
    <div class="container">
      <div class="contact-grid">
        <div class="contact-info reveal">
          <span class="section-tag">Contáctanos</span>
          <h2 class="section-title">¡Da el <span class="gradient-text">Primer Paso</span>!</h2>
          <p>¿Listo para transformar tu cuerpo? Escríbenos y un asesor te contactará en menos de 24 horas.</p>
          <div class="contact-details">
            <div class="contact-item"><span>📍</span><div><strong>Dirección</strong><p>Av. Principal 123, Centro Comercial Fitness Plaza, Local 45</p></div></div>
            <div class="contact-item"><span>📞</span><div><strong>Teléfono</strong><p>+1 (555) 123-4567</p></div></div>
            <div class="contact-item"><span>📧</span><div><strong>Email</strong><p>info@ironforge.gym</p></div></div>
            <div class="contact-item"><span>🕐</span><div><strong>Horario</strong><p>Lunes a Domingo: 24/7</p></div></div>
          </div>
        </div>
        <div class="contact-form-wrap reveal">
          <form class="contact-form" id="contact-form">
            <div class="form-row">
              <div class="form-group">
                <label for="name">Nombre Completo</label>
                <input type="text" id="name" name="name" placeholder="Tu nombre" required />
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="tu@email.com" required />
              </div>
            </div>
            <div class="form-group">
              <label for="phone">Teléfono</label>
              <input type="tel" id="phone" name="phone" placeholder="+1 (555) 000-0000" />
            </div>
            <div class="form-group">
              <label for="plan">Plan de Interés</label>
              <select id="plan" name="plan">
                <option value="">Selecciona un plan</option>
                <option value="basico">Básico — $29/mes</option>
                <option value="pro">Pro — $59/mes</option>
                <option value="elite">Elite — $99/mes</option>
              </select>
            </div>
            <div class="form-group">
              <label for="message">Mensaje</label>
              <textarea id="message" name="message" rows="4" placeholder="Cuéntanos tus objetivos..."></textarea>
            </div>
            <button type="submit" class="btn btn-primary btn-full">Enviar Mensaje 🚀</button>
            <div class="form-success" id="form-success">✅ ¡Mensaje enviado! Te contactaremos pronto.</div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== FOOTER ========== -->
  <footer class="footer">
    <div class="container">
      <div class="footer-grid">
        <div class="footer-brand">
          <a href="#hero" class="nav-logo">IRON<span>FORGE</span></a>
          <p>Forjando cuerpos y mentes desde 2016. El gimnasio premium donde tus límites se rompen.</p>
          <div class="social-links">
            <a href="#" aria-label="Instagram" class="social-link">📸</a>
            <a href="#" aria-label="Facebook" class="social-link">👥</a>
            <a href="#" aria-label="Twitter" class="social-link">🐦</a>
            <a href="#" aria-label="YouTube" class="social-link">▶️</a>
          </div>
        </div>
        <div class="footer-links">
          <h4>Servicios</h4>
          <ul>
            <li><a href="#services">Musculación</a></li>
            <li><a href="#services">Cardio</a></li>
            <li><a href="#services">Boxeo</a></li>
            <li><a href="#services">Yoga</a></li>
            <li><a href="#services">Entrenamiento Personal</a></li>
          </ul>
        </div>
        <div class="footer-links">
          <h4>Empresa</h4>
          <ul>
            <li><a href="#about">Sobre Nosotros</a></li>
            <li><a href="#trainers">Entrenadores</a></li>
            <li><a href="#pricing">Planes</a></li>
            <li><a href="#contact">Contacto</a></li>
            <li><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="footer-links">
          <h4>Legal</h4>
          <ul>
            <li><a href="#">Términos y Condiciones</a></li>
            <li><a href="#">Política de Privacidad</a></li>
            <li><a href="#">Política de Cookies</a></li>
          </ul>
        </div>
      </div>
      <div class="footer-bottom">
        <p>© 2026 IRONFORGE GYM. Todos los derechos reservados.</p>
        <p>Hecho con 💪 para los que no se rinden</p>
      </div>
    </div>
  </footer>

  <script src="app.js"></script>
</body>
</html>
