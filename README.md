# Cofre Sonoro Minecraft
**Dispositivo Interactivo mediante Keyboard Hack**  
Taller de Interfaces | Unidad 1: Interfaces Sonoras  
**Integrantes:** Martín Donoso, Luis-Felipe Benítez, Zainah Corvalán  

---

## Enlaces Rápidos
* **Demostración Web Interactiva:** [Abrir en GitHub Pages](https://martindonoso2005-cell.github.io/Cofre-Sonoro-Minecraft/)
* **Lámina de Presentación (PDF):** [Ver Lámina Técnica](./lamina_cofre_sonoro_minecraft%20pdf2.0.pdf)
* **Video de Demostración (YouTube):** [Ver Demostración en YouTube](https://youtu.be/gqNnVetmCBw)

---

## Descripción del Proyecto

### Concepto
Cofre Sonoro Minecraft es una interfaz física tangible inspirada en el cofre del videojuego Minecraft. Al interactuar físicamente abriendo o cerrando la tapa, el dispositivo reacciona en tiempo real con respuestas visuales y los efectos sonoros característicos de apertura y cierre.

### Inspiración (MIM)
El proyecto se basa en la experiencia vivencial del **Museo Interactivo Mirador (MIM)**, donde el aprendizaje y el descubrimiento ocurren a través de la acción corporal directa. Trasladamos esta lógica exploratoria al mundo digital, convirtiendo un objeto virtual en un dispositivo físico con el que interactuar directamente.

### Lógica de Interacción
En lugar de un botón tradicional, el cofre incorpora en su tapa un **interruptor de inclinación de bola metálica**. Al variar la posición de la tapa, la bolita interna abre o cierra el circuito eléctrico, reemplazando físicamente una tecla de un teclado desmontado (*keyboard hack*). La computadora interpreta cada movimiento como la pulsación o liberación de una tecla, activando el audio correspondiente mediante la Web Audio API y actualizando el estado en pantalla.

---

## Registro Audiovisual
Demostración del prototipo físico en uso real:  
* [Ver Video de Funcionamiento en YouTube](https://youtu.be/gqNnVetmCBw)

---

## Proceso de Fabricación, Ensamble y Pruebas

### 1. Fabricación Digital (Impresión 3D)
Modelado e impresión 3D en PLA mediante impresora Bambu Lab para el cuerpo, tapa y placas de encastre.
<p align="center">
  <img src="./proceso/Fabricacion%201.jpeg" width="45%" />
  <img src="./proceso/Fabricacion%202.jpeg" width="45%" />
</p>

### 2. Despiece y Ensamble de Hardware
Integración de la placa controladora del teclado desmontado (*keyboard hack*) en el fondo del cofre y montaje del interruptor de inclinación en la bisagra de la tapa.
<p align="center">
  <img src="./proceso/Fabricacion%203.jpeg" width="45%" />
  <img src="./proceso/Fabricacion%205.jpeg" width="45%" />
</p>

### 3. Acabado y Pruebas Operativas
Ensamble exterior final y calibración del sistema conectado por USB al computador, verificando la detección de eventos y el disparo de los sonidos.
<p align="center">
  <img src="./proceso/Fabricacion%204.jpeg" width="45%" />
  <img src="./proceso/Fabricacion%206.jpeg" width="45%" />
</p>
