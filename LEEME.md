# Base de arranque · Semana 3 · Taller del día B

Esto es **el punto de partida**, no una solución. Sirve para las parejas que no tienen el
proyecto de la semana 2. Quien ya lo tenga, sigue con el suyo: no necesita esta carpeta.

## Ponerlo a andar (una vez, cinco minutos)

```
npm install
npm run dev
```

Se abre en `http://localhost:5173` y se ve un párrafo que dice que lo reemplacen. Eso es lo
normal: el esqueleto está en un comentario dentro de `src/App.svelte`, listo para copiar.

**Mientras quede un `<____>` sin reemplazar, la página no compila** y Vite muestra un error rojo
que dice `Expected a valid element or component name`. No está roto el proyecto: es el hueco que
falta. Trabajen de arriba abajo y el error desaparece con el último.

## Crear el repositorio de la pareja

```
git init
git add .
git commit -m "chore: proyecto inicial"
```

Después, en GitHub, creen un repositorio **vacío** (sin README) y conéctenlo:

```
git remote add origin URL_DEL_REPOSITORIO
git branch -M main
git push -u origin main
```

Antes de cada commit, firma quien lo va a hacer:

```
git config user.name "Nombre Apellido"
git config user.email "correo@uleam.edu.ec"
```

## Qué trae y qué no

| Archivo | Estado | Qué hacer con él |
| --- | --- | --- |
| `index.html` | **Listo.** Ya tiene la metaetiqueta `viewport` y `lang="es"` | No lo toquen. Si borran el `viewport`, la prueba de 360 px falla |
| `src/main.ts` | **Listo.** Ya tiene `import './app.css'` | No lo toquen. Sin esa línea, el CSS no se aplica |
| `src/app.css` | **Vacío a propósito** | Todo su CSS va aquí. Nada de `style="..."` en el marcado |
| `src/App.svelte` | **El esqueleto con huecos** | Es el trabajo del día. Solo marcado: nada de `<script>` ni `<style>` |
| `docs/dominio.md` | **Plantilla en blanco** | Se llena en la **fase 1**, paso 5, con lo del cuaderno del lunes |
| `docs/decisiones.md` | **Plantilla en blanco** | Se llena en la **fase 2**, paso 4, con las dos decisiones |

Con esto, **el paso 2 de la fase 1 ya está hecho** (la hoja de estilos existe y está importada).
Arranquen en el paso 3.

## Lo que esta carpeta no les da

Qué elemento va en cada `<____>`, qué nivel de encabezado, qué columnas dejar fuera y cuál de las
tres mecánicas usar para la tabla estrecha. Eso es lo que se califica, y está en el enunciado del
taller y en la lectura del kit previo del lunes.
