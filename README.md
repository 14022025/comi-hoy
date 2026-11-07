# Comí Hoy

Diario de alimentación, agua, medicinas y ciclo. Una sola página, sin instalar nada.

## Cómo usarlo

Abre `index.html` en el navegador. Ya está.

- Doble clic sobre el archivo en el Mac, o
- súbelo a cualquier sitio y ábrelo por su URL.

## Dónde se guardan los datos

En el navegador donde lo abras (`localStorage`). No se manda nada a ningún servidor.

Eso tiene dos consecuencias:

- Funciona sin internet y nadie más ve tus datos.
- **Cada navegador guarda lo suyo.** Lo del Mac no aparece en el celular.
- Si borras los datos de navegación del sitio, se borra el diario.

## Qué hace

- **Día** — comidas por franja, con calorías escribibles a mano. Agua en termos
  (el tamaño del tuyo se configura). Tus medicinas las añades tú desde la app:
  no viene ninguna puesta. Electrolitos, ciclo, peso, cómo te sentiste y notas.
- **Mes** — calendario de un vistazo: regla en disco vinotinto, día libre con 🍔,
  agua en barra, y puntos para medicinas, electrolitos y peso.
- **Listas** — compra de comida y de cuidado personal, continuas y con historial,
  más la despensa.
- **Notas** — recetas, y notas con fotos.
- **Widget** — abre `index.html#widget` para una ventanita de cristal con lo mínimo
  del día. En el Mac: Safari → Archivo → Añadir al Dock.

## Qué NO hace aquí

Las calorías por foto y la lectura de productos desde una imagen necesitaban el
entorno de Claude. En esta versión suelta no están: las calorías se escriben a
mano tocando el número de cada fila.
