# Componentes del Proyecto

Para la implementación de la solución en **CostaFrut**, hemos diseñado nodos solares autónomos de bajo costo.

## Galería de Hardware

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-bottom: 40px;">

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_esp32.jpg" alt="ESP32" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">ESP32 DevKit V1</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Microcontrolador principal con WiFi y Bluetooth integrado.</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_lora.jpg" alt="NRF24L01" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">NRF24L01 + PA + LNA</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Módulo de transmisión RF de largo alcance (hasta 1km).</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_sensor_humedad.jpg" alt="Sensor Humedad" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">Sensor Capacitivo v1.2</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Mide la humedad del suelo. Resistente a la corrosión.</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_sensor_temp.jpg" alt="DS18B20" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">DS18B20</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Sonda de temperatura sumergible de acero inoxidable.</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_panel.jpg" alt="Panel Solar" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">Panel Solar 5W 5V</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Fuente de energía renovable para autonomía total.</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_bateria.jpg" alt="Batería 18650" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">Batería Li-ion 18650</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Almacenamiento de energía (3800mAh x2).</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_cn3065.jpg" alt="CN3065" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">Módulo CN3065</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Gestor de carga solar seguro para baterías de litio.</p>
        </div>
    </div>

    <div style="width: 200px; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 5px rgba(0,0,0,0.05); background: white; text-align: center;">
        <div style="height: 180px; overflow: hidden; display: flex; align-items: center; justify-content: center; background: #f9f9f9;">
            <img src="../imagenes/hard_mp1584.jpg" alt="MP1584" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <div style="padding: 10px;">
            <h4 style="margin: 0; color: #0d47a1; font-size: 16px;">Regulador MP1584</h4>
            <p style="margin: 5px 0 0; font-size: 11px; color: #666; line-height: 1.3;">Reduce el voltaje de la batería para alimentar el ESP32.</p>
        </div>
    </div>

</div>

## Listado de Costos

A continuación, se detallan los componentes utilizados por cada nodo, incluyendo precios estimados.

| Componente | Cantidad | Precio Aprox. | Función Principal |
| :--- | :---: | :--- | :--- |
| **ESP32** | 2 | $ 3.679 | Microcontrolador principal (Cerebro) |
| **NRF24L01 + PA + LNA** | 2 | $ 3.927 | Módulo inalámbrico de largo alcance (2.4G) |
| **Sensor Humedad Suelo** | 1 | $ 2.932 | Medición capacitiva de humedad |
| **Sensor Temperatura** | 1 | $ 2.539 | Modelo DS18B20 (Sumergible) |
| **Panel Solar 5W 5V** | 1 | $ 5.300 | Fuente de energía renovable |
| **Batería Litio 18650** | 2 | $ 7.500 | Almacenamiento de energía (3800mAh) |
| **Cargador CN3065** | 1 | $ 1.581 | Gestión de carga solar |
| **Regulador MP1584** | 1 | $ 1.004 | Regulación de voltaje |
| **Condensadores** | 1 pack | $ 1.250 | Estabilidad eléctrica (100uF) |
| **TOTAL ESTIMADO** | | **$ 29.712** | Costo por nodo |

---

### Beneficios Clave del Diseño

!!! success "Eficiencia Energética"
    El sistema está diseñado para ser 100% autónomo mediante el uso de paneles solares y baterías de litio, permitiendo su funcionamiento continuo en el campo sin necesidad de cableado eléctrico ni generadores.

!!! success "Impacto Hídrico Positivo"
    Gracias a los sensores de humedad capacitivos, el sistema permite aplicar el agua exacta que la planta necesita. Se estima un **ahorro de agua entre el 25% y 30%** comparado con el riego tradicional por calendario.

!!! success "Reducción de Costos Operativos"
    Al automatizar la decisión de riego y fertilización, se reduce drásticamente el desperdicio de insumos químicos y horas-hombre dedicadas a la supervisión manual del campo.

---

## Diagrama de Flujo del Sistema


<div id="diagramPreview" onclick="openModal()" style="cursor: pointer; overflow: hidden; border: 1px solid #ddd; border-radius: 12px; padding: 10px; background: white; transition: transform 0.2s; box-shadow: 0 4px 10px rgba(0,0,0,0.08); position: relative; height: 120px; display: flex; align-items: center; justify-content: center; margin: 20px auto; max-width: 600px;">
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-image: radial-gradient(#cfd8dc 1.5px, transparent 1.5px); background-size: 20px 20px; opacity: 0.4; z-index: 0;"></div>
    
    <div style="z-index: 1; text-align: center; background: rgba(255,255,255,0.95); padding: 15px 40px; border-radius: 50px; border: 1px solid #b0bec5; box-shadow: 0 2px 5px rgba(0,0,0,0.05); display: flex; flex-direction: column; align-items: center; gap: 5px;">
        <div style="font-size: 18px; font-weight: bold; color: #263238; display: flex; align-items: center; gap: 10px;">
            <span style="font-size: 22px;"></span> Ver Diagrama de Flujo Interactivo
        </div>
        <div style="font-size: 13px; color: #546e7a;">Haga clic para ampliar y explorar el proceso completo</div>
    </div>
</div>

<div id="diagramModal" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.95); z-index: 9999; align-items: center; justify-content: center;">
    
    <span onclick="closeModal()" style="position: absolute; top: 20px; right: 30px; color: white; font-size: 40px; font-weight: bold; cursor: pointer; z-index: 10001;">&times;</span>

    <div id="scrollContainer" style="width: auto; height: auto; max-width: 98%; max-height: 95%; background: #222; border-radius: 8px; overflow: auto; position: relative; cursor: grab; padding: 20px; box-shadow: 0 0 50px rgba(0,0,0,0.5);">
        
        <style>
            #scrollContainer { scrollbar-width: none; }
            #scrollContainer::-webkit-scrollbar { display: none; }
            
            /* Estilos de Cajas */
            .node {
                position: absolute;
                width: 140px; height: 60px;
                display: flex; align-items: center; justify-content: center; text-align: center;
                border-radius: 8px; font-family: sans-serif; font-size: 11px; font-weight: bold;
                color: white; border: 2px solid; z-index: 10;
                box-shadow: 0 4px 6px rgba(0,0,0,0.3);
            }
            .n-green { background: #1b5e20; border-color: #2e7d32; }
            .n-blue { background: #0d47a1; border-color: #1565c0; }
            .n-purple { background: #4a148c; border-color: #7b1fa2; }
            .n-orange { background: #e65100; border-color: #ff9800; }
            
            /* Base de Datos */
            .db {
                position: absolute; width: 140px; height: 80px;
                background: #0d47a1; border: 2px solid #1565c0; border-radius: 50% / 20%;
                display: flex; flex-direction: column; align-items: center; justify-content: center;
                color: white; font-size: 11px; font-weight: bold; z-index: 10;
            }
            .db::before {
                content: ''; position: absolute; top: 10px; left: 0; right: 0; bottom: 0;
                border-top: 2px solid #1565c0; border-radius: 50% / 20%; background: inherit; z-index: -1;
            }

            /* Rombos de Decisión */
            .diamond {
                position: absolute; width: 100px; height: 100px;
                background: #f57f17; border: 2px solid #fbc02d;
                transform: rotate(45deg); z-index: 10;
                display: flex; align-items: center; justify-content: center;
            }
            .diamond span {
                transform: rotate(-45deg); display: block; width: 100%;
                text-align: center; color: white; font-size: 10px; font-weight: bold; line-height: 1.2;
            }

            /* Etiquetas de Texto */
            .label { 
                position: absolute; 
                font-family: sans-serif; 
                font-size: 11px; 
                font-weight: bold; 
                z-index: 11; 
                text-shadow: 0px 0px 3px #000;
            }
            .l-yes { color: #69f0ae; }
            .l-no { color: #ff5252; }

        </style>

        <div style="width: 1700px; height: 700px; position: relative;">
            
            <svg width="1700" height="700" style="position: absolute; top: 0; left: 0; z-index: 1;">
                <defs>
                    <marker id="head-w" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="white"/></marker>
                    <marker id="head-g" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="#69f0ae"/></marker>
                    <marker id="head-r" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto"><path d="M0,0 L6,3 L0,6" fill="#ff5252"/></marker>
                </defs>

                <line x1="160" y1="150" x2="200" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                <line x1="340" y1="150" x2="380" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                <line x1="520" y1="150" x2="560" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                <line x1="700" y1="150" x2="740" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                <line x1="880" y1="150" x2="920" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                <line x1="1060" y1="150" x2="1100" y2="150" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>

                <line x1="1150" y1="200" x2="1150" y2="270" stroke="#69f0ae" stroke-width="2" marker-end="url(#head-g)"/>
                <line x1="1200" y1="150" x2="1280" y2="150" stroke="#ff5252" stroke-width="2" marker-end="url(#head-r)"/>

                <path d="M 1330 100 L 1330 40 L 1360 40" fill="none" stroke="#69f0ae" stroke-width="2" marker-end="url(#head-g)"/>
                
                <line x1="1380" y1="150" x2="1480" y2="150" stroke="#ff5252" stroke-width="2" marker-end="url(#head-r)"/>

                <path d="M 1220 300 L 1550 300 L 1550 180" fill="none" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>
                
                <path d="M 1500 40 L 1550 40 L 1550 120" fill="none" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>

                <line x1="1550" y1="180" x2="1550" y2="330" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>

                <path d="M 1500 380 L 1410 380 L 1410 430" fill="none" stroke="#ff5252" stroke-width="2" marker-end="url(#head-r)"/>
                <path d="M 1600 380 L 1640 380 L 1640 430" fill="none" stroke="#69f0ae" stroke-width="2" marker-end="url(#head-g)"/>

                <line x1="1480" y1="460" x2="1570" y2="460" stroke="white" stroke-width="2" marker-end="url(#head-w)"/>

                <path d="M 1640 490 L 1640 580 L 810 580 L 810 190" fill="none" stroke="#aaa" stroke-dasharray="5,5" stroke-width="2" marker-end="url(#head-w)"/>
                
                <text x="1100" y="570" fill="#aaa" font-family="sans-serif" font-size="12">Retroalimentación Histórica</text>

            </svg>

            <div class="node n-green" style="left: 20px; top: 120px;">Sensores<br>Humedad/Temp</div>
            <div class="node n-blue" style="left: 200px; top: 120px;">Captura Datos<br>ESP32</div>
            <div class="node n-blue" style="left: 380px; top: 120px;">Transmisión<br>LoRa / WiFi</div>
            <div class="node n-blue" style="left: 560px; top: 120px;">Sistema Central<br>Recepción</div>
            <div class="db" style="left: 740px; top: 110px;">Almacenamiento<br>Base de Datos</div>
            <div class="node n-blue" style="left: 920px; top: 120px;">Procesamiento<br>Análisis</div>

            <div class="diamond" style="left: 1100px; top: 100px;"><span>¿Necesita<br>Riego?</span></div>
            <div class="diamond" style="left: 1280px; top: 100px;"><span>¿Necesita<br>Fertilizante?</span></div>
            
            <div class="node n-purple" style="left: 1080px; top: 270px;">ACTIVAR<br>RIEGO</div>
            <div class="node n-purple" style="left: 1360px; top: 10px;">INFORME<br>FERTILIZACIÓN</div>

            <div class="node n-orange" style="left: 1480px; top: 120px;">Monitoreo<br>Tiempo Real</div>
            <div class="diamond" style="left: 1500px; top: 330px;"><span>Generación<br>Alertas</span></div>
            
            <div class="node n-purple" style="left: 1340px; top: 430px;">Enviar<br>Notificación</div>
            <div class="node n-orange" style="left: 1570px; top: 430px;">Generación<br>Reportes</div>

            <div class="label l-yes" style="left: 1160px; top: 215px;">SÍ</div>
            <div class="label l-no" style="left: 1230px; top: 130px;">NO</div>
            
            <div class="label l-yes" style="left: 1310px; top: 60px;">SÍ</div>
            <div class="label l-no" style="left: 1415px; top: 130px;">NO</div>
            
            <div class="label l-no" style="left: 1435px; top: 360px;">Anormal</div>
            <div class="label l-yes" style="left: 1610px; top: 355px;">Normal</div>

        </div>
    </div>
</div>

<script>
    const modal = document.getElementById('diagramModal');
    const container = document.getElementById('scrollContainer');
    let isDown = false, startX, scrollLeft, startY, scrollTop;

    function openModal() { modal.style.display = 'flex'; }
    function closeModal() { modal.style.display = 'none'; }

    container.addEventListener('mousedown', (e) => {
        isDown = true; container.style.cursor = 'grabbing';
        startX = e.pageX - container.offsetLeft; scrollLeft = container.scrollLeft;
        startY = e.pageY - container.offsetTop; scrollTop = container.scrollTop;
    });
    container.addEventListener('mouseleave', () => { isDown = false; container.style.cursor = 'grab'; });
    container.addEventListener('mouseup', () => { isDown = false; container.style.cursor = 'grab'; });
    container.addEventListener('mousemove', (e) => {
        if (!isDown) return; e.preventDefault();
        const x = e.pageX - container.offsetLeft; const walkX = (x - startX) * 2;
        const y = e.pageY - container.offsetTop; const walkY = (y - startY) * 2;
        container.scrollLeft = scrollLeft - walkX; container.scrollTop = scrollTop - walkY;
    });
    document.addEventListener('keydown', (e) => { if (e.key === "Escape") closeModal(); });
</script>