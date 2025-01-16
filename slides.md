---
title: AICA+ Industria 4.0
titleTemplate: '%s - Presentación'
description: Presentación del proyecto de Industria 4.0 de los Laboratorios Farmacéuticos AICA+
keywords: aica+,industria4.0
info: Presentación del proyecto de Industria 4.0 de los Laboratorios Farmacéuticos AICA+
author: AICA+
favicon: /favicon.ico

theme: seriph

highlighter: shiki
lineNumbers: false

class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
---

<style>
  .background-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/team.webp');
    background-size: cover;
    background-position: center;
    filter: blur(3px);
    z-index: -1;
  }

  .fade-in {
      animation: fadeIn 1s ease-in-out forwards;
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

  span {
    background-color: #81dbff;
    background-image: linear-gradient(45deg, #89effd 20%, #46c0ed 50%);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }
</style>

<div class="background-container"></div>

# <span class="fade-in">Industria 4.0 en los Laboratorios Farmacéuticos AICA+</span>

<div class="text-xl text-gray-200 mt-4 fade-in">
Casi Ing. Eduardo Alejandro Gonzalez Martell
</div>

<div class="abs-br m-6 text-xl fade-in">
  <a href="https://github.com/EduardoProfe666/aica-industry-4.0" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<footer style="color: #05d8f3; font-weight: bold;" class="fade-in abs-b m-6">
  © 2025 <a href="https://www.aica.cu" target="_blank">AICA+</a>
</footer>

---
transition: slide-up
---

# Desarrollo de la Industria 4.0

<div class="timeline-grid m-6">
  <v-click>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:building-insights-1 />&nbsp; 1784</div>
      <div class="content">
        <h3>Primera Revolución</h3>
        <p>Mecanización y energía de vapor</p>
      </div>
    </div>
  </v-click>

  <v-click>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:lightning />&nbsp; 1870</div>
      <div class="content">
        <h3>Segunda Revolución</h3>
        <p>Producción en masa y electricidad</p>
      </div>
    </div>
  </v-click>

  <v-click>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:machine-learning />&nbsp; 1969</div>
      <div class="content">
        <h3>Tercera Revolución</h3>
        <p>Automatización y computadoras</p>
      </div>
    </div>
  </v-click>

  <v-click>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:ibm-cloud-internet-services />&nbsp; 2010</div>
      <div class="content">
        <h3>Cuarta Revolución</h3>
        <p>IoT, IA y sistemas ciber-físicos</p>
      </div>
    </div>
  </v-click>
</div>

<footer style="color: #05d8f3; font-weight: bold;" class="fade-in abs-b m-6 text-center">
  © 2025 <a href="https://www.aica.cu" target="_blank">AICA+</a>
</footer>

<style>
.timeline-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  padding: 20px;
}

.timeline-item {
  padding: 15px;
  border-left: 3px solid #0097a7;
  background-color: rgba(255, 255, 255, 0.04);
  border-radius: 5px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.year {
   color: #0097a7;
   font-weight: bold;
   margin-bottom: 5px;
   font-size: 2em;
   display: flex;
   align-items: center;
}

.content {
   padding-left: 10px;
}

.content h3 {
   color: #0097a7;
   margin-top: -5px;
   margin-bottom: -5px;
   font-size: 1.2em;
}

.content p {
   margin-top: -5px;
   margin-bottom: -5px;
   font-size: 0.95em;
   color: #666;
}

h1 {
    background-color: #81dbff;
    background-image: linear-gradient(45deg, #89effd 20%, #46c0ed 50%);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }
</style>


---
transition: slide-left
---

# Niveles de Madurez de la Academia acatech

<div class="grid grid-cols-3 gap-4 mt-8">
  <v-click>
    <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">1</div>
    <h3>Informatizar</h3>
    <p>Digitalización básica de procesos individuales</p>
  </div>
 </v-click>

  <v-click>
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">2</div>
    <h3>Integrar</h3>
    <p>Conexión de sistemas aislados en plataformas integradas</p>
  </div>
  </v-click>

  <v-click>
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">3</div>
    <h3>Visualizar</h3>
    <p>¿Qué está pasando? <br>Monitoreo en tiempo real</p>
  </div>
  </v-click>

  <v-click>
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">4</div>
    <h3>Entender</h3>
    <p>¿Por qué está pasando? <br>Generación de conocimiento a partir de datos</p>
  </div>
  </v-click>

  <v-click>
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">5</div>
    <h3>Predecir</h3>
    <p>¿Qué pasará? <br>Capacidad predictiva en procesos productivos</p>
  </div>
  </v-click>

  <v-click>
  <div
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 150 } }"
    class="maturity-card"
  >
    <div class="card-number">6</div>
    <h3>Optimizar</h3>
    <p>¿Cómo puedo responder autónomamente? <br>Mejora continua y adaptativa</p>
  </div>
  </v-click>
</div>

<footer style="color: #05d8f3; font-weight: bold;" class="fade-in abs-b m-6 text-center">
  © 2025 <a href="https://www.aica.cu" target="_blank">AICA+</a>
</footer>

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

h1 {
    background-color: #81dbff;
    background-image: linear-gradient(45deg, #89effd 20%, #46c0ed 50%);
    background-size: 100%;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
  }
</style>

