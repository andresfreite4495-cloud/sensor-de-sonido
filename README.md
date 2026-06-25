
# sensor de sonido
- Andrés Freite
- Abel Garcia
  
Descripción del proyecto
  
Este proyecto consiste en un sistema electrónico interactivo basado en Arduino Uno capaz de detectar estímulos acústicos, como aplausos o golpes, mediante un sensor de sonido. Cuando la intensidad del sonido supera un umbral previamente establecido, el sistema activa un LED indicador durante un tiempo determinado.
Este principio puede ser aplicado en sistemas de domótica, alarmas y automatización básica.

Problema identificado

En muchas aplicaciones domésticas y de automatización es necesario detectar eventos sonoros para activar dispositivos sin intervención manual. La ausencia de mecanismos automáticos limita el desarrollo de sistemas de control simples y de bajo costo.
La implementación de un detector de sonido permite desarrollar soluciones para iluminación automática, alarmas y sistemas inteligentes.

Objetivo general

Diseñar e implementar un sistema detector de sonido basado en Arduino Uno capaz de activar un indicador luminoso cuando la intensidad acústica supere un umbral determinado.

Pruebas Realizadas

Prueba	Descripción	Resultado
Lectura del sensor:	Aplausos y golpes	Correcta

Activación del LED:	Sonido superior al umbral	Exitosa

Calibración	Ajuste del potenciómetro:	Adecuada

Prueba integral	Sistema completo:	Funcionamiento correcto

Dificultades encontradas
•	Ajuste del nivel de sensibilidad del sensor.

•	Presencia de ruido ambiental.

•	Falsas activaciones durante las pruebas.

•	Necesidad de calibrar el potenciómetro del módulo.

Conclusiones
•	Se comprobó el funcionamiento del convertidor analógico-digital del Arduino.

•	Fue posible detectar variaciones sonoras y procesarlas mediante programación.

•	El sistema responde de manera inmediata a estímulos acústicos.

•	Se integraron sensores, programación y actuadores en una aplicación real de automatización.

•	Detectar señales acústicas mediante un sensor de sonido.

•	Procesar la información utilizando un Arduino Uno.

•	Activar un LED cuando la intensidad del sonido supere un valor establecido.

•	Ajustar la sensibilidad del sistema mediante calibración.

•	Verificar el funcionamiento del prototipo mediante pruebas experimentales.

Componentes utilizados

Componente	 |Cantidad	| Función
Arduino Uno R3	| 1	|Controlador | principal
Sensor de sonido |	 1	|Detección de señales  |acústicas
 LED	1	 |Indicador  |visual
Resistencia 220 Ω	|1|	|Protección del LED
Protoboard|	|1|	|Montaje del circuito
Jumpers	Varios|	|Conexiones eléctricas
<img width="414" height="233" alt="Captura de pantalla 2026-06-16 180554" src="https://github.com/user-attachments/assets/0ea5af30-1c69-4fd0-b7fe-7a85fbf05cf0" />
