# Template: Hoja de Modelo de Personaje 3D (Perfil de Imagen)

> **Uso:** Cuando el usuario pida un "perfil de imagen" o "character reference sheet", usar este prompt template.
> **Relacionado:** ComfyUI, generación de imágenes, workflows ultrareal.

---

## Prompt Base

```
Crea una HOJA DE MODELO DE PERSONAJE 3D realista y profesional con calidad AAA basado en la imagen de referencia. El personaje final debe verse como un ser humano real reconstruido con precisión, NO como un personaje animado, anime, Pixar, Disney, estilizado o ilustrado.

## BLOQUEO DE IDENTIDAD Y REFERENCIA:

Preservar la identidad y apariencia exacta del tema cargado. Mantener la correcta estructura facial, forma de la cara, ojos, cejas, labios, línea de la mandíbula, estructura de las mejillas, tono de piel, edad, peinado, color de cabello, textura del cabello, forma del cuerpo, proporciones, altura, ropa, accesorios, y todos los detalles reconocibles de la imagen de referencia.

NO embellezca, rediseñe, estilice, adelgace, agrande, remodele, envejezca o rejuvenezca al tema. NO cree una persona diferente. La imagen de referencia cargada es la fuente absoluta de la verdad.

Crear UN personaje consistente mostrando el MISMO personaje desde varios ángulos.

## DISEÑO DE HOJA MODELO:

Diseñar una hoja de modelo de personaje limpia y profesional similar a una hoja de modelo real de película/juego/desarrollo de personajes.

### SECCIÓN SUPERIOR - VISTAS DEL PERSONAJE:

Mostrar vistas completas del personaje en 3D realista:

- VISTA FRONTAL
- 3/4 VISTA FRONTAL
- VISTA LATERAL / DE PERFIL
- VISTA TRASERA 3/4
- VISTA TRASERA

Todas las vistas deben mostrar el MISMO personaje, consistentes:
- Rostros, peinados, proporciones corporales, accesorios, colores, materiales y detalles físicos.
- El personaje debe mantener una postura neutral y natural en las vistas de giro.
- Mantener la altura, la escala, las proporciones y el encuadre de la cámara.

### SECCIÓN DE PRIMER PLANO DE LA CABEZA:

Incluir varios primeros planos de cabeza/rostro en resolución alta:

- Cara frontal
- 3/4 cara
- Perfil lateral
- Ángulo opuesto 3/4

Mostrar el MISMO rostro en todos los ángulos con anatomía facial precisa y piel humana natural.

### EXPRESIONES FACIALES:

Crear una pequeña fila de referencia mostrando expresiones del MISMO personaje:

- Neutral
- Enfadado
- Sonriente
- Sorprendido
- Triste
- Serio
- Expresión natural y relajada

Las expresiones deben cambiar naturalmente sin alterar la identidad o la estructura facial de la persona.

### SECCIÓN DETALLE MANOS/CUERPO:

Incluir estudio de referencia de manos que muestre posiciones y gestos naturales diferentes, preservando al mismo tiempo el tono de piel, las proporciones y la anatomía del personaje.

### PALETA DE COLORES Y MATERIALES:

Incluir un área de referencia profesional de color/material que muestre pequeñas muestras y texturas de materiales relevantes, como:

- Cabello
- Piel
- Telas para prendas de vestir
- Cuero
- Mezclilla
- Metal
- Materiales para calzado
- Accesorios
- Otros materiales visibles

### PANELES DE DETALLE ADICIONALES:

Incluir varios paneles de primeros planos de detalles del personaje, como:

- Los ojos
- Peinado/textura del cabello
- Tela de ropa
- Costuras
- Accesorios
- Calzado
- Joyas
- Elementos de diseño distintivos

### REFERENCIA DE ALTURA/PROPORCIÓN:

Incluir un área limpia de altura de referencia/proporción al lado del personaje, que muestre la silueta de todo el cuerpo y las proporciones anatómicas reales.

## ESTILO VISUAL:

- Modelado de personajes 3D fotorealista de alta gama
- Anatomía humana real
- Poros naturales de la piel e imperfecciones sutiles
- Mechones de cabello individuales
- Materiales fotorrealistas
- Pliegues y costuras de tela reales
- Ojos realistas con iris natural
- Materiales PBR de alta calidad
- Iluminación de estudio profesional
- Fondo de estudio neutro limpio
- Enfoque nítido
- Calidad premium de desarrollo de personajes de juegos AAA
- Escultura 3D realista con calidad cinematográfica
- Extremadamente creíble pero detallado

## PRESENTACIÓN:

Hacer que toda la imagen presente una presentación real de desarrollo de personajes / hoja de modelo para una película de presupuesto alto o producción de videojuego AAA.

Usar líneas guía limpias y ceremoniales, etiquetas técnicas pequeñas, espaciado consistente de alineación y una presentación de diseño profesional.

## IMPORTANTE:

- La imagen de referencia cargada determina EL PERSONAJE
- El ejemplo de hoja de modelo determina SÓLO la presentación/diseño/estilo de la hoja
- NO copiar la cara, la ropa, el peinado, los colores, el cuerpo o el diseño del personaje de ejemplo
- NO tomar el sujeto del material cargado en el ejemplo
- Cada vista debe mostrar EXACTAMENTE EL MISMO personaje
- Sin deriva de identidad
- Sin cambio de cara
- Sin cambio de expresiones base
- No hay cambios en las proporciones corporales
- No se cambia de ropa entre vistas
- Sin accesorios extraños
- Sin extremidades duplicadas
- Sin anatomía alienígena
- Sin apariencia de animación
- Sin anime
- Sin categoría cartoon
- Nada de estilo Pixar/Disney
- Sin rediseño de fantasía
- Sin piel de plástico
- Sin rostro artificial

---

## Uso en ComfyUI

Este template se usa en workflows de generación de imágenes con ComfyUI para crear character reference sheets consistentes.

**Workflow recomendado:**
1. Cargar imagen de referencia del personaje
2. Usar CLIP Vision para extraer características faciales
3. Aplicar IPAdapter para preservar identidad
4. Generar múltiples vistas con el prompt template
5. Compilar en hoja de modelo única

**Nodes relacionados:**
- `IPAdapter Apply` - Preservar identidad facial
- `CLIP Vision Encode` - Extraer features de referencia
- `FaceDetailer` - Mantener consistencia facial
- `Impact Pack` - Detalles y máscaras

---

*Template creado: 2026-09-11*
*Versión: 1.0*
*Relacionado: ComfyUI, ANIME→ULTRAREAL, ultrareal-krea2-flux*