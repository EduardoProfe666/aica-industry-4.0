---
title: AICA+ Industria 4.0
description: Presentación del proyecto de Industria 4.0 de los Laboratorios Farmacéuticos AICA+
head:
  - <link rel="icon" href="/favicon.ico" />
  - <meta property="og:title" content="AICA+ Industria 4.0" />
  - <meta property="og:description" content="Presentación del proyecto de Industria 4.0 de los Laboratorios Farmacéuticos AICA+" />
  - <meta property="og:image" content="https://raw.githubusercontent.com/EduardoProfe666/aica-industry-4.0/refs/heads/main/public/team.webp" />
  - <meta property="og:url" content="https://presentacion-aica-industria4.netlify.app" />

theme: seriph

highlighter: shiki
lineNumbers: false
info: |
  ## Industria 4.0 en los Laboratorios Farmacéuticos AICA+
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
transition: slide-left
---

# Desarrollo de la Industria 4.0

<div class="timeline-grid m-6">
  <v-clicks>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:building-insights-1 />&nbsp; 1784</div>
      <div class="content">
        <h3>Primera Revolución</h3>
        <p>Mecanización y energía de vapor</p>
      </div>
    </div>
  </v-clicks>

  <v-clicks>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:lightning />&nbsp; 1870</div>
      <div class="content">
        <h3>Segunda Revolución</h3>
        <p>Producción en masa y electricidad</p>
      </div>
    </div>
  </v-clicks>

  <v-clicks>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:machine-learning />&nbsp; 1969</div>
      <div class="content">
        <h3>Tercera Revolución</h3>
        <p>Automatización y computadoras</p>
      </div>
    </div>
  </v-clicks>

  <v-clicks>
    <div class="timeline-item" v-motion :initial="{ opacity: 0, scale: 0.8 }" :enter="{ opacity: 1, scale: 1, transition: { delay: 150 } }">
      <div class="year"><carbon:ibm-cloud-internet-services />&nbsp; 2010</div>
      <div class="content">
        <h3>Cuarta Revolución</h3>
        <p>IoT, IA y sistemas ciber-físicos</p>
      </div>
    </div>
  </v-clicks>
</div>

<footer style="color: #05d8f3; font-weight: bold;" class="fade-in abs-b m-6 text-center">
  © 2025 <a href="https://www.aica.cu" target="_blank">AICA+</a>
</footer>

<style>
.timeline-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* Dos columnas */
  gap: 20px; /* Espacio entre los elementos */
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
   font-size: 2em; /* Aumentado para destacar el ícono */
   display: flex; /* Para centrar el ícono */
   align-items: center; /* Centrar verticalmente */
}

.content {
   padding-left: 10px;
}

.content h3 {
   color: #0097a7;
   margin-top: -5px; /* Ajuste para mejor alineación */
   margin-bottom: -5px; /* Ajuste para mejor alineación */
   font-size: 1.2em;
}

.content p {
   margin-top: -5px; /* Ajuste para mejor alineación */
   margin-bottom: -5px; /* Ajuste para mejor alineación */
   font-size: 0.95em;
   color: #666;
}
</style>



