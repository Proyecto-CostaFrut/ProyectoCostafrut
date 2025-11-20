# Aplicacion y Recursos

En esta seccion centralizamos el acceso a la plataforma de gestion, el codigo fuente de los nodos y la documentacion tecnica del proyecto **CostaFrut**.

---

## Plataforma de Gestion

La aplicacion web es el centro de control del sistema. Desde aqui, los agricultores podran visualizar el estado de sus cultivos y tomar decisiones informadas.

!!! warning "Estado: En Desarrollo"
    La plataforma web se encuentra actualmente en fase de construccion y pruebas alfa.

<div style="margin-top: 20px; margin-bottom: 30px; text-align: center;">
    <a href="#" target="_blank" style="
        background-color: #0277bd; 
        color: white; 
        padding: 15px 40px; 
        text-decoration: none; 
        border-radius: 50px; 
        font-weight: bold; 
        font-family: sans-serif;
        display: inline-block;
        box-shadow: 0 4px 10px rgba(2, 119, 189, 0.3);
        transition: transform 0.2s, background-color 0.3s;
    " onmouseover="this.style.backgroundColor='#01579b'; this.style.transform='scale(1.05)'" onmouseout="this.style.backgroundColor='#0277bd'; this.style.transform='scale(1)'">
        Acceder al Sistema CostaFrut
    </a>
    <p style="font-size: 11px; color: #666; margin-top: 5px;">(Acceso restringido a usuarios registrados)</p>
</div>

### Funcionalidades Previstas
* **Dashboard en Tiempo Real:** Visualizacion grafica de humedad y temperatura.
* **Historial de Datos:** Descarga de reportes en Excel/CSV para analisis agronomico.
* **Sistema de Alertas:** Notificaciones automaticas cuando los niveles salgan del rango optimo.

---

## Documentacion Tecnica

Para profundizar en la ingenieria, los costos y la justificacion teorica del proyecto, ponemos a disposicion el informe tecnico completo desarrollado durante el Modulo Integrador.

### Informe del Proyecto
Este documento contiene el Estado del Arte, la Arquitectura detallada, la Logica de Control y el Presupuesto detallado.

<div style="margin-top: 20px; margin-bottom: 40px; text-align: center;">
    <a href="../imagenes/Informe_CostaFrut.pdf" target="_blank" style="
        background-color: #2e7d32; 
        color: white; 
        padding: 15px 30px; 
        text-decoration: none; 
        border-radius: 50px; 
        font-weight: bold; 
        font-family: sans-serif;
        display: inline-block;
        box-shadow: 0 4px 10px rgba(46, 125, 50, 0.3);
        transition: transform 0.2s, background-color 0.3s;
    " onmouseover="this.style.backgroundColor='#1b5e20'; this.style.transform='scale(1.05)'" onmouseout="this.style.backgroundColor='#2e7d32'; this.style.transform='scale(1)'">
        Ver Informe Tecnico (PDF)
    </a>
</div>

---

## Firmware y Simulacion

Aqui puedes consultar el codigo fuente utilizado en los nodos de control (ESP32) para la lectura de sensores y la logica de decision.

### Codigo Fuente del Nodo

<details style="background-color: #ffffff; border: 1px solid #ddd; border-radius: 5px; padding: 10px;">
    <summary style="cursor: pointer; font-weight: bold; color: #333; padding: 10px;">
        <span style="margin-left: 25px;">Haz clic aqui para desplegar el codigo (C++/Arduino)</span>
    </summary>

<pre style="text-align: left; background-color: #f4f4f4; padding: 15px; border-radius: 5px; overflow-x: auto; font-family: monospace; font-size: 13px; line-height: 1.5; border: 1px solid #eee; color: #333; margin-top: 10px;">
// PROYECTO COSTAFRUT - NODO SENSOR
// Plataforma: ESP32 / Arduino

const int sensorPin = 34;  // Pin analogico del sensor
const int relayPin = 26;   // Pin digital rele
const int umbralRiego = 30; // Porcentaje humedad minima

void setup() {
  Serial.begin(115200);
  pinMode(relayPin, OUTPUT);
  digitalWrite(relayPin, LOW);
  Serial.println("Sistema CostaFrut Iniciado...");
}

void loop() {
  // 1. Lectura del Sensor
  int lectura = analogRead(sensorPin);
  // Ajustar valores 4095 y 0 segun calibracion real
  int porcentajeHumedad = map(lectura, 4095, 0, 0, 100); 

  Serial.print("Humedad: ");
  Serial.println(porcentajeHumedad);

  // 2. Logica de Decision
  if (porcentajeHumedad < umbralRiego) {
    Serial.println("-> SUELO SECO: Riego ON");
    digitalWrite(relayPin, HIGH);
  } else {
    Serial.println("-> HUMEDAD OPTIMA: Riego OFF");
    digitalWrite(relayPin, LOW);
  }
  
  delay(5000);
}
</pre>

</details>

