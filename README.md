# trvely-fichas — Fichas de venta para asesores

Material **interno** de apoyo comercial, publicado como GitHub Pages.
Una ficha por hotel: **cómo venderlo**, no un folleto del hotel.

> *«Que el comercial encuentre todo el apoyo para que aprenda, se llene de conocimiento, y cuando
> vaya a asesorar, sepa qué vender.»* — EL PATRÓN

## 🔴 La regla que no se rompe

**El material del asesor NUNCA enlaza a la página pública del hotel** (`trvely.com.co`), ni a nada
con WhatsApp corporativo, formulario o canal de contacto de la empresa.

El asesor trabaja el cliente durante semanas. Si le manda la página pública, el cliente escribe al
canal de la empresa y **la venta se le va a otro**.

Para enseñar fotos se usa **la Vitrina** (`galerias.trvely.com.co`), que no tiene canal de venta.
**Ese es su motivo de existir.** Si hay que explicar algo, se explica **dentro de la propia ficha**.

> *Una herramienta que le quita la venta a quien la usa no es una herramienta: es una fuga.*

## Estructura de cada ficha (aprobada por el CEO, no se rediseña)

1. **En 10 segundos** — el pitch, con frase de apertura lista
2. **A quién sí y a quién no** — dos columnas
3. **Enséñaselo** — fotos + enlace a la galería
4. **Lo que entra / lo que se paga aparte**
5. **Habitaciones y cómo subir de categoría** — argumento de upgrade y sus trampas
6. **Lo que te van a preguntar** — desplegables, cada uno con el guion listo
7. **Errores que no puedes cometer**
8. **Datos duros** + botones

La ficha incluye **lo que NO se puede prometer**. Un asesor que sabe dónde están las trampas vende
con más seguridad que uno que solo conoce las virtudes.

## Reglas de contenido

- **Nada se afirma sin documento.** La fuente es el `VERDAD_<hotel>_v1.md` del Área de Producto,
  que a su vez sale del Fact Sheet oficial y del contrato.
- **Gana el que menos promete.** Si el folleto del hotel y el contrato se contradicen, manda el
  contrato: es el que responde en el mostrador.
- **Una verdad de un hotel no se hereda a otro.** Cada ficha se escribe contra el documento de *su*
  hotel.
- **Sin pies de foto inventados.** Si no está registrado qué espacio muestra una imagen, no se
  nombra.
- Cada página lleva `noindex, nofollow`.

## Cómo se añade una ficha

1. Crear `<slug-del-hotel>/index.html` copiando una existente.
2. Escribirla **contra el `VERDAD_<hotel>_v1.md`** de ese hotel.
3. Comprobar que su galería existe en la Vitrina — si no existe, la regla del enlace se rompe sola.
4. Añadir la tarjeta en el `index.html` raíz.
5. `git push` — GitHub Pages publica solo.

## Fichas publicadas

| Hotel | Destino | Estado |
|---|---|---|
| Catalonia Royal Bávaro | Punta Cana, RD | ✅ v1 · 9-ago-2026 |

---

*Serie `45_SITIO_WEB` · proyecto `2026-08_FICHAS_ASESOR` · Área de Producto Trvely.*
