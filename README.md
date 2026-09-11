# Lidl España — Home (caso de estudio)

Recreación front-end de la página de inicio corporativa de Lidl España, construida desde cero en un único archivo HTML autocontenido.

**Demo:** https://TU-USUARIO.github.io/case-study-lidl-home-es/

---

## Sobre el proyecto

Ejercicio de recreación fiel de una landing corporativa real: maquetación, sistema tipográfico, paleta, componentes interactivos y comportamiento responsive completo.

### Qué incluye

- **Header** con navegación por pastillas y menús desplegables flotantes que no desplazan el contenido.
- **Barra sticky** de anclas a secciones.
- **Hero** corporativo con cifras destacadas en tiles.
- **Carrusel** de 22 imágenes con vista central al 84 % y asomas laterales, navegación por puntos.
- **Mapa mundial interactivo** de países con presencia, lista con banderas y contadores.
- **Acordeón** de contenido por país (Sostenibilidad abierta por defecto).
- **FAQs**, sección de empleo y footer completo.

### Responsive

Fluido de 390 px a 1440 px+:

- Tipografía escalada con `clamp()`.
- Rejillas que reflujen en tablet y móvil.
- Breakpoint principal a 900 px: la navegación pasa a menú hamburguesa con acordeones.

---

## Tecnologías

| | |
|---|---|
| Maquetación | HTML5 semántico |
| Estilos | CSS3 — Grid, Flexbox, `clamp()`, custom properties |
| Interacción | JavaScript vanilla (sin dependencias) |
| Assets | Imágenes y SVG embebidos en base64 |
| Despliegue | GitHub Pages |

Un solo archivo (`index.html`, ~3,3 MB). Sin build, sin `node_modules`, sin CDN: funciona offline abriéndolo en el navegador.

---

## Uso local

```bash
git clone https://github.com/TU-USUARIO/case-study-lidl-home-es.git
cd case-study-lidl-home-es
open index.html   # o doble clic en el archivo
```

---

## Aviso legal

Recreación **no oficial** realizada con fines educativos y de portafolio. Este proyecto no está afiliado, asociado, autorizado ni respaldado en modo alguno por Lidl.

«Lidl», su logotipo y su identidad visual son marcas registradas de Lidl Stiftung & Co. KG. Todos los derechos sobre dichas marcas pertenecen a sus titulares y se emplean aquí únicamente a título descriptivo.

El código de este repositorio se publica bajo licencia MIT.
