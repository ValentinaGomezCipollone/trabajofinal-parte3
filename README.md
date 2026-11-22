# trabajofinal-parte3

# Bomberos Voluntarios de Berisso — Sitio web y sistema de diseño

Trabajo práctico final: diseño y construcción de un sitio web para una organización, con un sistema de diseño propio documentado dentro del mismo sitio.

**Estudiante:** Valentina Gómez Cipollone

**Sitio publicado:** https://valentinagomezcipollone.github.io/trabajofinal-parte3/

## La organización

La Sociedad de Bomberos Voluntarios de Berisso es una asociación civil sin fines de lucro fundada el 25 de abril de 1924 por un grupo de inmigrantes encabezado por Domingo Leveratto. Tiene un cuartel central y dos destacamentos (El Carmen y Villa Zula), y cubre todo el partido, incluidos el puerto, el polo petroquímico y la costa del Río de la Plata. Sus integrantes prestan servicio de manera voluntaria y sin remuneración, y la institución se sostiene con el aporte de vecinos, socios y empresas locales.

**Objetivo del sitio:** convocar a que más vecinos se asocien y más personas se sumen al cuerpo activo. Como objetivo secundario, informar y visibilizar qué hace la institución más allá de apagar incendios.

**Público:** vecinos y vecinas de Berisso; personas de cualquier género que quieran ser bomberos o bomberas; familias, escuelas y empresas a las que se orientan las charlas de prevención.

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Inicio: portada, quiénes somos, servicios, asociate, sumate y contacto |
| `historia.html` | Historia desde 1924 e hitos |
| `que-hacemos.html` | Detalle de cada servicio |
| `asociate.html` | Cómo asociarse y en qué se usa el aporte |
| `sumate.html` | Requisitos, curso de ingreso y día a día |
| `contacto.html` | Emergencias, cuarteles, mapa y visitas |
| `documentacion.html` | Documentación del sistema de diseño |

## Tecnologías

- HTML semántico y CSS propio, sin frameworks.
- Variables CSS (custom properties) en `:root` para color, tipografía y espaciado.
- CSS Grid para el layout (4, 8 y 12 columnas) y Flexbox para el interior de los componentes.
- Container queries en las tarjetas de servicios (`.tarjeta`) y en la línea de tiempo (`.hito`).
- Diseño responsivo mobile-first: 375 px, 768 px y 1280 px.
- Tipografía ADLaM Display (Google Fonts, licencia OFL), incluida en la carpeta `fuentes/`.

## Estructura

```
├── index.html
├── historia.html
├── que-hacemos.html
├── asociate.html
├── sumate.html
├── contacto.html
├── documentacion.html
├── estilos.css
├── img/
│   ├── hero-bomberos.jpg
│   └── favicon.svg
└── fuentes/
    └── ADLaMDisplay-Regular.ttf
```

---

Sitio no oficial, realizado como trabajo práctico. Los datos de contacto corresponden a la Sociedad de Bomberos Voluntarios de Berisso.
