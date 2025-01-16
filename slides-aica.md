https://cover.sli.dev

---
theme: seriph
background: '#f8f9fa'
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Industria 4.0 en los Laboratorios Farmacéuticos AICA+
drawings:
  persist: false
transition: slide-left
title: Industria 4.0 en AICA+
mdc: true
---

# Industria 4.0 en los Laboratorios Farmacéuticos AICA+

<div class="text-xl text-gray-500 mt-4">
Casi Ing. Eduardo Alejandro Gonzalez Martell
</div>

<div
  v-motion
  :initial="{ y: 100, opacity: 0 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 300, duration: 1000 } }"
  class="mt-8"
>
  <img
    class="mx-auto w-60 opacity-80"
    src="https://cdn-icons-png.flaticon.com/512/5360/5360804.png"
  />
</div>

<style>
h1 {
  background-color: #0097a7;
  background-image: linear-gradient(45deg, #0097a7 10%, #00bcd4 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
---

# Desarrollo de la Industria 4.0

<div class="timeline-container">
  <v-clicks>
    <div class="timeline-item">
      <div class="year">1784</div>
      <div class="content">
        <h3>Primera Revolución</h3>
        <p>Mecanización y energía de vapor</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="year">1870</div>
      <div class="content">
        <h3>Segunda Revolución</h3>
        <p>Producción en masa y electricidad</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="year">1969</div>
      <div class="content">
        <h3>Tercera Revolución</h3>
        <p>Automatización y computadoras</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="year">Actual</div>
      <div class="content">
        <h3>Cuarta Revolución</h3>
        <p>IoT, IA y sistemas ciber-físicos</p>
      </div>
    </div>
  </v-clicks>
</div>

::right::

<div class="ml-4">
  <img
    v-motion
    :initial="{ x: 100, opacity: 0 }"
    :enter="{ x: 0, opacity: 1, transition: { delay: 300 } }"
    src="/bot.webp"
    class="rounded-lg shadow-xl"
  />
</div>

<style>
.timeline-container {
  padding: 20px;
}

.timeline-item {
  margin-bottom: 20px;
  padding: 10px;
  border-left: 3px solid #0097a7;
  position: relative;
}

.year {
  color: #0097a7;
  font-weight: bold;
  margin-bottom: 5px;
}

.content {
  padding-left: 10px;
}

.content h3 {
  color: #0097a7;
  margin: 0;
  font-size: 1.1em;
}

.content p {
  margin: 5px 0 0;
  font-size: 0.9em;
  color: #666;
}
</style>

---
layout: default
---

# Niveles de Madurez de la Academia acatech

<div class="grid grid-cols-3 gap-4 mt-8">
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 200 } }"
    class="maturity-card"
  >
    <div class="card-number">1</div>
    <h3>Informatizar</h3>
    <p>Digitalización básica de procesos individuales</p>
  </div>

  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 400 } }"
    class="maturity-card"
  >
    <div class="card-number">2</div>
    <h3>Integrar</h3>
    <p>Conexión de sistemas aislados en plataformas integradas</p>
  </div>

  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 600 } }"
    class="maturity-card"
  >
    <div class="card-number">3</div>
    <h3>Visualizar</h3>
    <p>¿Qué está pasando? Monitoreo en tiempo real</p>
  </div>

  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 800 } }"
    class="maturity-card"
  >
    <div class="card-number">4</div>
    <h3>Entender</h3>
    <p>Generación de conocimiento a partir de datos</p>
  </div>

  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 1000 } }"
    class="maturity-card"
  >
    <div class="card-number">5</div>
    <h3>Predecir</h3>
    <p>Capacidad predictiva en procesos productivos</p>
  </div>

  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 1200 } }"
    class="maturity-card"
  >
    <div class="card-number">6</div>
    <h3>Optimizar</h3>
    <p>Mejora continua y adaptativa</p>
  </div>
</div>

<style>
.maturity-card {
  background: rgba(0, 151, 167, 0.1);
  border-radius: 8px;
  padding: 20px;
  position: relative;
  transition: transform 0.3s;
}

.maturity-card:hover {
  transform: translateY(-5px);
}

.card-number {
  position: absolute;
  top: -10px;
  right: -10px;
  background: #0097a7;
  color: white;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
}

.maturity-card h3 {
  color: #0097a7;
  margin-bottom: 10px;
}

.maturity-card p {
  font-size: 0.9em;
  color: #666;
}
</style>

---
layout: center
---

# Laboratorios Farmacéuticos AICA+

<div class="container mx-auto px-4">
  <div
    v-motion
    :initial="{ scale: 0.8, opacity: 0 }"
    :enter="{ scale: 1, opacity: 1, transition: { delay: 300 } }"
    class="aica-card"
  >
    <h2 class="text-2xl font-bold text-[#0097a7] mb-4">¿Qué es AICA+?</h2>
    <p class="text-gray-700 mb-6">
      AICA+ es una empresa líder en el sector farmacéutico, comprometida con la innovación
      y la excelencia en la producción de medicamentos. Nuestra misión es mejorar la vida
      de las personas a través de soluciones farmacéuticas de alta calidad.
    </p>

    <div class="grid grid-cols-2 gap-6">
      <div class="feature-card">
        <div class="icon">🔬</div>
        <h3>Innovación</h3>
        <p>Desarrollo continuo de nuevas soluciones y tecnologías</p>
      </div>
      <div class="feature-card">
        <div class="icon">✨</div>
        <h3>Calidad</h3>
        <p>Compromiso con los más altos estándares de la industria</p>
      </div>
    </div>
  </div>
</div>

<style>
.aica-card {
  background: white;
  border-radius: 16px;
  padding: 2rem;
  box-shadow: 0 4px 6px rgba(0, 151, 167, 0.1);
  max-width: 800px;
}

.feature-card {
  background: rgba(0, 151, 167, 0.05);
  border-radius: 12px;
  padding: 1.5rem;
  text-align: center;
  transition: transform 0.3s;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.icon {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  color: #0097a7;
  margin-bottom: 0.5rem;
}

.feature-card p {
  color: #666;
  font-size: 0.9rem;
}
</style>

---
layout: default
---

# Implementación de Industria 4.0 en AICA+

<div class="grid grid-cols-2 gap-8">
  <div
    v-motion
    :initial="{ x: -50, opacity: 0 }"
    :enter="{ x: 0, opacity: 1 }"
  >
    <div class="stats-container">
      <div class="stat-item">
        <div class="stat-value">85%</div>
        <div class="stat-label">Procesos Automatizados</div>
      </div>
      <div class="stat-item">
        <div class="stat-value">90%</div>
        <div class="stat-label">Eficiencia Operativa</div>
      </div>
      <div class="stat-item">
        <div class="stat-value">95%</div>
        <div class="stat-label">Control de Calidad</div>
      </div>
    </div>
  </div>

  <div
    v-motion
    :initial="{ x: 50, opacity: 0 }"
    :enter="{ x: 0, opacity: 1, transition: { delay: 300 } }"
  >
    <img
      src="https://www.automationworld.com/sites/default/files/styles/article_featured_retina/public/2019-11/Screen%20Shot%202019-11-26%20at%2010.07.48%20AM.png"
      class="rounded-lg shadow-xl"
    />
  </div>
</div>

<style>
.stats-container {
  display: grid;
  gap: 1rem;
  margin-top: 2rem;
}

.stat-item {
  background: rgba(0, 151, 167, 0.1);
  border-radius: 12px;
  padding: 1.5rem;
  text-align: center;
  transition: transform 0.3s;
}

.stat-item:hover {
  transform: scale(1.05);
}

.stat-value {
  font-size: 2.5rem;
  font-weight: bold;
  color: #0097a7;
  margin-bottom: 0.5rem;
}

.stat-label {
  color: #666;
  font-size: 1.1rem;
}
</style>

---
layout: center
class: text-center
---

# ¿Preguntas?

<div
  v-motion
  :initial="{ scale: 0.8, opacity: 0 }"
  :enter="{ scale: 1, opacity: 1 }"
  class="mt-8"
>
  <div class="text-2xl text-[#0097a7] mb-4">
    ¿Tienes alguna duda o comentario sobre lo que hemos discutido?
  </div>

  <div class="text-gray-600">
    Estamos aquí para responder todas tus preguntas
  </div>
</div>

<div
  v-motion
  :initial="{ y: 50, opacity: 0 }"
  :enter="{ y: 0, opacity: 1, transition: { delay: 500 } }"
  class="mt-12"
>
  <img
    class="mx-auto w-32 opacity-50"
    src="https://cdn-icons-png.flaticon.com/512/1484/1484799.png"
  />
</div>

<style>
h1 {
  background-color: #0097a7;
  background-image: linear-gradient(45deg, #0097a7 10%, #00bcd4 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>