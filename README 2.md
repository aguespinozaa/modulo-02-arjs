# Ocean Discovery AR PRO
### El océano fuera de la pantalla

**Taller de Diseño de Interfaces · Unidad 3 · Módulo 02**

## La idea

Quise llevar la temática marina del primer módulo al espacio físico. La propuesta es un pequeño museo submarino que aparece sobre un marcador Hiro: en vez de mirar una imagen fija, podemos acercarnos, cambiar de perspectiva y descubrir seis organismos mediante la realidad aumentada.

El diseño combina turquesas, azules y colores cálidos para diferenciar los animales. Los modelos son interpretaciones estilizadas, construidas con geometrías tridimensionales, no reproducciones anatómicas exactas.

## Cómo explorar

1. Abre la página publicada en GitHub Pages desde Chrome.
2. Abre el [marcador Hiro](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png) en otro dispositivo o imprímelo.
3. Presiona **Activar cámara y explorar** y concede el permiso.
4. Apunta la cámara al marcador completo, con buena luz.
5. Selecciona un organismo y prueba los controles.

| Control | Qué permite hacer |
|---|---|
| Catálogo | Cambiar entre pez, medusa, coral, tortuga, pulpo y caballito de mar. |
| Escanear | Registrar un organismo en la colección y mostrar una onda de escaneo. |
| Anatomía | Consultar las principales estructuras del organismo. |
| Escala y rotación | Examinar el modelo desde distintas perspectivas. |
| Día / noche | Cambiar la iluminación artística. |
| Alimentar | Visualizar partículas de alimento; no reproduce conductas reales. |
| Sonido | Activar efectos sonoros sintetizados. |

## Tecnología y propósito

AR.js reconoce el marcador mediante la cámara y A-Frame permite situar los objetos tridimensionales sobre él. HTML y CSS organizan la interfaz; JavaScript controla las animaciones, la colección y las interacciones. Web Audio genera los efectos sonoros.

La intención es explorar cómo una interfaz puede conectar el entorno físico con información digital. Este ejercicio complementa Ocean Motion y Expedición Hadal, aunque los organismos del catálogo no representan necesariamente especies de la Fosa de Atacama.

## Consideraciones

Se necesita internet, cámara y HTTPS. Si el marcador desaparece, vuelve a colocarlo dentro del campo visual. La colección se reinicia al recargar la página. Los modelos y efectos son artísticos.
