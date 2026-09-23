# PokéDiario

## Cómo tenerla en PC y teléfono

1. En tu PC, abre `index.html` con Chrome o Edge.
2. Para instalarla como aplicación, primero debes publicarla con HTTPS (ver el paso siguiente). Abre entonces tu enlace en Chrome/Edge y usa el botón de instalar de la barra de direcciones.
3. En Android, abre el enlace publicado en Chrome y toca `⋮` → `Instalar aplicación` o `Añadir a pantalla de inicio`.
4. En iPhone, abre el enlace en Safari, toca `Compartir` → `Añadir a pantalla de inicio`.

## Publicarla gratis con Netlify (sin programar)

1. Entra a https://app.netlify.com/drop.
2. Arrastra **la carpeta completa** `pokedex-aprendizaje` a la página.
3. Netlify te mostrará un enlace como `https://algo.netlify.app`. Ese es tu enlace para PC y teléfono.
4. Si quieres un nombre personalizado, crea una cuenta gratis en Netlify, entra a `Site configuration` y cambia el nombre del sitio.

> Importante: si publicas una nueva versión, repite el arrastre de la carpeta. Mantén juntos todos los archivos: no subas solo `index.html`.

## Cómo editarla tú

- `index.html`: frases, títulos y textos que se ven en pantalla.
- `styles.css`: colores, tamaños, tipografía y diseño.
- `app.js`: las reglas: cinco cartas al día, preguntas y progreso.

Para editar, haz clic derecho sobre un archivo → `Abrir con` → Bloc de notas o, mejor, Visual Studio Code. Guarda y recarga la página para ver tu cambio. Antes de tocar código, haz una copia de la carpeta por seguridad.

## Qué incluye

- Selección por las nueve generaciones (Kanto a Paldea).
- Cinco Pokémon distintos por día y generación, elegidos de forma determinista: al recargar no cambia tu misión.
- Fichas con número, tipo, altura, peso y habilidad, más un enlace individual a la Pokédex oficial de Pokémon.
- Marcado de aprendizaje, racha y mini preguntas; todo se guarda localmente en el navegador.

## Datos y procedencia

Pokémon.com es la fuente oficial enlazada para cada ficha. PokeAPI es una API comunitaria que aporta los campos técnicos que hacen viable consultar el catálogo completo desde una aplicación estática. Si el proyecto va a publicarse o a requerir una base de datos oficial propia, pide licencia o acceso de datos a The Pokémon Company; no existe una exportación pública oficial integral para reutilizar en una base de datos.

Las ilustraciones intentan cargarse desde los activos públicos de Pokémon.com; como respaldo se usa la ilustración disponible en PokeAPI.
