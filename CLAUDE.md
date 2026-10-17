# Portfolio de Cristina Garrido

Web estática de presentación profesional (portfolio/CV online) para postular a
puestos de **Desarrolladora Full Stack Junior**. Cristina viene de 15 años en
administración y está haciendo un bootcamp en NEOLAND.

## Cómo trabajar conmigo

- Responde siempre en **español**.
- Estoy aprendiendo: explica lo que haces en pocas palabras y sin jerga innecesaria.
- **Antes de crear o cambiar archivos, cuéntame el plan en pocas líneas y espera mi visto bueno.**
- Haz cambios pequeños y revisables. No borres ni renombres archivos o carpetas sin preguntar.
- Respeta el diseño actual: no lo rehagas desde cero salvo que te lo pida.

## Contenido

- Los textos de la web están en `index.html`. Su copia de referencia es
  `assets/cv/contenido-portfolio.md`: si cambio un texto, actualiza los dos.
- Usa los textos tal cual: no los resumas, no los reescribas y no inventes datos.
- **No hay sección de proyectos** todavía. Cuando la pida, irá entre "Tecnologías" y "Lo que aporto".
- **No muestres el teléfono ni la dirección.** El email solo aparece al final (bloque de contacto y pie).
- Los enlaces de **GitHub y LinkedIn** están pendientes: en `index.html` llevan `href="#"`
  y un comentario `PENDIENTE`. Aparecen en la cabecera y en el pie; cuando te dé las
  direcciones, cámbialas en los dos sitios.

## Estructura de archivos

```
index.html                                   ← la página (una sola, en la raíz)
assets/css/styles.css                        ← todos los estilos
assets/img/profile/foto-perfil.jpg           ← foto de perfil optimizada para web
assets/img/profile/Foto profesional.png      ← foto original (no usar en la web, pesa mucho)
assets/img/templates/                        ← imágenes de referencia del estilo (no se publican)
assets/cv/CV_Cristina_Garrido_Full_Stack.pdf ← CV del botón "Descargar CV"
assets/cv/contenido-portfolio.md             ← textos de referencia (no se publica)
```

## Tecnología

- Solo **HTML y CSS**, sin frameworks ni librerías (proyecto de aprendizaje).
  Si algún día hace falta JavaScript, irá en `assets/js/main.js`.
- HTML semántico (`header`, `nav`, `main`, `section`, `footer`), accesible
  (textos alternativos, buen contraste) y con `lang="es"`.
- **Responsive**: puntos de corte en 960px y 600px.
- Código limpio y comentado de forma breve, para que pueda entenderlo.

## Diseño (basado en las muestras de `assets/img/templates/`)

- Colores (variables en `:root` de `styles.css`): naranja `#ff6a1a`, naranja oscuro
  `#e2410f`, rojo `#c8210e`, amarillo `#ffb547`, negro `#111111`, gris de títulos
  `#9a9a9a`, fondo claro `#f6f4f1`.
- Tipografía: **Inter** (Google Fonts).
- Cabecera con degradado naranja, mi nombre en grande, foto con marco blanco y dos etiquetas flotantes.
- Títulos de sección en dos tonos (negro + gris) y etiqueta `[ SECCIÓN ]` encima.
- Tarjetas con esquinas redondeadas; etiquetas (chips) arriba de cada tarjeta, nunca abajo.
- Poco espacio vacío: secciones compactas y tarjetas sin relleno excesivo.
- Textos largos justificados para que queden en bloque.
- Pie oscuro con mi nombre centrado en degradado naranja.

## Secciones

Inicio · Cifras · Sobre mí · Tecnologías · Lo que aporto + Competencias ·
Experiencia · Formación · Contacto · Pie
