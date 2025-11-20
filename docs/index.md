# Bienvenido al Proyecto Agrícola CostaFrut

Este sitio documenta la propuesta tecnológica desarrollada para **Agrícola CostaFrut**, una empresa de la región del Maule dedicada a la producción de frutillas y paltas. Nuestro objetivo es integrar la informática con la agricultura para resolver problemáticas críticas de gestión de recursos.

---

## ¿Qué esperamos conseguir?

El objetivo principal de este proyecto es la **optimización de recursos hídricos y fertilizantes** mediante el monitoreo en tiempo real.

Actualmente, la agricultura enfrenta desafíos globales como la sequía y el cambio climático. A través de esta implementación, esperamos alcanzar los siguientes resultados cuantificables:

* **Ahorro de Agua:** Reducción estimada entre un **25% y 30%** en el consumo hídrico, validado por estudios previos de riego automatizado.
* **Eficiencia en Fertilizantes:** Disminución del desperdicio de insumos químicos, evitando la sobre-fertilización y reduciendo costos operativos.
* **Mejora en la Calidad:** Garantizar una fruta de mejor calidad para la exportación mediante condiciones de suelo controladas.

---

## ¿Cómo lo vamos a lograr?

La solución consiste en un sistema de **Agricultura de Precisión** que digitaliza procesos que antes eran manuales.

### La Solución Técnica

Implementaremos una red de **nodos solares autónomos** distribuidos en el campo. El siguiente diagrama ilustra el flujo de datos en tiempo real:

<div style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap; gap: 10px; margin: 20px 0; font-family: sans-serif;">

  <div style="background: #e8f5e9; border: 2px solid #2e7d32; border-radius: 10px; padding: 10px; text-align: center; width: 160px; height: 140px; display: flex; flex-direction: column; align-items: center; justify-content: center; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <div style="font-size: 28px; margin-bottom: 10px;">📡</div>
    <strong style="color: #1b5e20; font-size: 16px;">1. Captura</strong>
    <div style="font-size: 13px; color: #555; margin-top: 5px; line-height: 1.2;">Sensores de Humedad y Temp.</div>
  </div>

  <svg width="60" height="40" style="flex-shrink: 0;">
    <defs>
      <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
        <polygon points="0 0, 10 3.5, 0 7" fill="#2e7d32" />
      </marker>
    </defs>
    <line x1="0" y1="20" x2="50" y2="20" stroke="#2e7d32" stroke-width="2" stroke-dasharray="5,5" marker-end="url(#arrowhead)" />
    <circle cx="0" cy="20" r="4" fill="#4caf50">
      <animate attributeName="cx" from="0" to="50" dur="1.5s" repeatCount="indefinite" />
    </circle>
  </svg>

  <div style="background: #e3f2fd; border: 2px solid #1565c0; border-radius: 10px; padding: 10px; text-align: center; width: 160px; height: 140px; display: flex; flex-direction: column; align-items: center; justify-content: center; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <div style="font-size: 28px; margin-bottom: 10px;">📶</div>
    <strong style="color: #0d47a1; font-size: 16px;">2. Transmisión</strong>
    <div style="font-size: 13px; color: #555; margin-top: 5px; line-height: 1.2;">Red LoRa de Largo Alcance</div>
  </div>

  <svg width="60" height="40" style="flex-shrink: 0;">
    <line x1="0" y1="20" x2="50" y2="20" stroke="#1565c0" stroke-width="2" stroke-dasharray="5,5" marker-end="url(#arrowhead)" />
    <circle cx="0" cy="20" r="4" fill="#2196f3">
      <animate attributeName="cx" from="0" to="50" dur="1.5s" repeatCount="indefinite" begin="0.75s" />
    </circle>
  </svg>

  <div style="background: #fff3e0; border: 2px solid #ef6c00; border-radius: 10px; padding: 10px; text-align: center; width: 160px; height: 140px; display: flex; flex-direction: column; align-items: center; justify-content: center; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <div style="font-size: 28px; margin-bottom: 10px;">💻</div>
    <strong style="color: #e65100; font-size: 16px;">3. Acción</strong>
    <div style="font-size: 13px; color: #555; margin-top: 5px; line-height: 1.2;">Dashboard y Riego Inteligente</div>
  </div>

</div>

> *El sistema visualiza el estado del cultivo y activa el riego automáticamente cuando el suelo lo necesita.*

---

## ¿Por qué este proyecto?

Identificamos que CostaFrut, a pesar de sus 15 años de experiencia, enfrenta problemáticas asociadas al desperdicio de recursos y la falta de información precisa para la toma de decisiones.

Nuestra propuesta genera impacto en tres dimensiones clave:

* **Impacto Económico:** Ahorros considerables en costos de energía, agua y logística, aumentando la rentabilidad.
* **Impacto Ambiental:** Uso responsable de recursos naturales y reducción de la huella química en los suelos.
* **Impacto Social:** Modernización del trabajo agrícola, facilitando la labor de operarios y técnicos con herramientas digitales.

> *"La informática hoy es un componente clave en el mundo frutícola. Esta ejecución no solo garantiza mejor fruta, sino un liderazgo responsable."*

---

## Sobre el Equipo

Este proyecto es desarrollado en el contexto del **Módulo Integrador (INF-226)** de la carrera de Ingeniería Civil Informática de la **Universidad Católica del Maule**.

| Integrantes del Equipo |
| :--- |
| Williams Campos |
| Eric Cerna |
| Pablo Cofré |
| Benjamín Flores Alegría |
| Luis Palma |
| Ignacio Vásquez |