# MÓDULO 7: Desarrollo de Aplicaciones Front-End con Framework VUE
María Teresa de la Fuente C.

## Ruta de repositorio: 
mt-dafonte/m7-abp5-librerias

# Actividad M7-ABP5_Librerías y Frameworks para Vue

---

# Exploración y comparación de librerías UI para Vue

**Objetivo:** Reconocer y comparar distintas librerías de interfaces de
usuario (UI) complementarias para Vue.js (BootstrapVue, Vuetify,
Buefy, Element UI), eligiendo la más adecuada para una aplicación
según sus necesidades.
## Descripción de la actividad:
### 1. Investigación Teórica:
El estudiante debe investigar y documentar las características,
ventajas y desventajas de las siguientes librerías UI:
- BootstrapVue: Integración de Bootstrap con Vue.js,
proporcionando componentes predefinidos como botones,
formularios, modales, etc.
- Vuetify: Librería basada en Material Design, que ofrece una
gran cantidad de componentes y es altamente personalizable.
- Buefy: Basada en Bulma, ofrece una interfaz limpia y ligera
con soporte para componentes como botones, cartas, modales,
etc.
- Element UI: Un framework UI que se enfoca en una
experiencia de usuario profesional, con componentes como
formularios, tablas, modales, etc.

---

### BootstrapVue

**Descripción:**

Extiende la potencia de Bootstrap dentro de Vue.js. Ofrece componentes listos como botones, grids, tarjetas, formularios, modales y utilidades de diseño responsivo basadas en Bootstrap.

**Características principales**
- Basada en Bootstrap 4 (la versión más estable para la librería).
- Componentes simples y rápidos de implementar.
- Soporta el sistema de grillas de Bootstrap.
- Fácil aprendizaje para quienes ya conocen Bootstrap.

**Ventajas**
- Curva de aprendizaje baja.
- Excelente para prototipos rápidos y aplicaciones con diseño tradicional.
- Buena documentación.
- Comunidad grande gracias a Bootstrap.

**Desventajas**
- Basada en Bootstrap 4; no aprovecha características recientes de Bootstrap 5 sin plugins externos.
- Visualmente menos moderna comparada con otras librerías como Vuetify.
- Menos opciones avanzadas de personalización.

---

### Vuetify

**Descripción**
Librería UI basada en Material Design. Es una de las más populares en el ecosistema Vue y destaca por su gran cantidad de componentes listos para producción.

**Características principales**
- Altísimo número de componentes (botones, datatables, formularios avanzados, diálogos, layouts, etc.).
- Sistema de diseño robusto basado en Material Design 3.
- Theming avanzado (modo oscuro, colores personalizados, variables de diseño).
- Compatible con Vue Router y navegación SPA fluida.

**Ventajas**
- Estándar visual consistente y moderno.
- Excelente para aplicaciones corporativas, dashboards y backoffice.
- Documentación extensa y comunidad muy activa.
- Muchas funcionalidades listas sin necesidad de plugins adicionales.

**Desventajas**
- Curva de aprendizaje más alta.
- Bundle más pesado que otras opciones.
- La personalización profunda puede requerir tiempo.

---

### Buefy

**Descripción**
Integra Vue.js con Bulma, un framework CSS puro (sin JavaScript). Buefy añade los componentes Vue que Bulma no incluye.

**Características principales**
- Basada en Bulma, por lo que utiliza sólo CSS puro.
- Ligera y fácil de integrar.
- Estética limpia y minimalista.
- Componentes básicos como botones, modales, notificaciones, selectores, tarjetas, etc.

**Ventajas**
- Peso muy liviano.
- Fácil de personalizar mediante variables Sass.
- Excelente para proyectos pequeños o medianos que buscan simplicidad.
- Diseño moderno sin ser complejo.

**Desventajas**
- Menos componentes que Vuetify o Element.
- No incluye soluciones avanzadas como tablas dinámicas complejas.
- Comunidad más pequeña.

---

### Element UI (Element Plus en Vue 3)

**Descripción**
Framework de UI con enfoque profesional, muy utilizado en paneles administrativos y sistemas internos. Tiene una apariencia elegante y formal.

**Características principales**
- Amplio set de componentes: tablas avanzadas, formularios completos, selectores, modales, steps, paginación, etc.
- Buen soporte para internacionalización.
- Estilo sobrio y corporativo.
- Muy usado en entornos empresariales.

**Ventajas**
- Excelente para aplicaciones profesionales y dashboards.
- Componentes muy completos (especialmente tablas y formularios).
- Buena documentación.
- Estética elegante lista para producción.

**Desventajas**
- Personalización visual menos flexible que Buefy o Vuetify.
- Bundle relativamente pesado.
- Comunidad más presente en Asia, lo que puede afectar la disponibilidad de ejemplos en español.

---

### Conclusión: ¿Cómo elegir la librería adecuada?

- **Rapidez y simplicidad**: BootstrapVue o Buefy  
- **Look moderno tipo Google (Material Design)**: Vuetify  
- **Estética profesional para app corporativa**: Element UI  
- **Componentes complejos como tablas con filtros integrados**: Element UI o Vuetify  
- **Ligero y fácil de personalizar**: Buefy  

---

### 2. Práctica de implementación
El estudiante debe crear una aplicación Vue.js básica con al
menos 3 de estas librerías.
- Tarea 1: Crear una interfaz con BootstrapVue.
- Tarea 2: Crear la misma interfaz con Vuetify.
- Tarea 3: Crear la misma interfaz con Buefy y Element UI

Este proyecto implementa una aplicación básica en Vue 3 utilizando tres librerías de componentes UI: **BootstrapVue 3**, **Vuetify 3** y **Element Plus**.  
El objetivo es evaluar la usabilidad, facilidad de integración, personalización y adecuación al diseño requerido para la aplicación.

---

## Estructura del proyecto y uso de ramas Git

Se crearon tres ramas principales para separar la implementación de cada librería:

- **rama-bootstrapvue** → Implementación usando BootstrapVue 3.  
- **rama-vuetify** → Implementación usando Vuetify 3.  
- **rama-elementplus** → Implementación usando Element Plus.

El flujo recomendado fue:

1. Crear el proyecto base en `main`.
2. Crear cada rama desde `main`.
3. Implementar la interfaz en cada rama por separado.
4. Comparar resultados sin necesidad de hacer *merge* ni *pull requests*, ya que el objetivo era evaluar diferencias, no unificar las ramas.


### Tarea 1: Interfaz con BootstrapVue 3

Se creó una interfaz sencilla que incluye:

- Card con título  
- Campo de entrada (`b-form-input`)  
- Botón (`b-button`)  
- Mensaje dinámico con `v-if`  

BootstrapVue destacó por:

- Instalación simple  
- Componentes fáciles de usar  
- Estilos responsive integrados  

---

### Tarea 2: Interfaz con Vuetify 3

La misma interfaz se implementó usando:

- `v-card`  
- `v-text-field`  
- `v-btn`  
- Sistema Material Design  

Vuetify destacó por:

- Catálogo muy completo de componentes  
- Alta personalización con temas  
- Diseño moderno y consistente  

Pero requirió:

- Configuración adicional (Sass, plugin Vite)  
- Tiempo extra para aprendizaje  

---

### Tarea 3: Interfaz con Element Plus

Se replicó nuevamente la interfaz usando:

- `el-card`  
- `el-input`  
- `el-button`  

Element Plus destacó por:

- Instalación muy sencilla  
- Componentes profesionales listos para producción  
- Documentación clara  
- Estética limpia y moderna  

---

## Evaluación de la implementación de las librerías

### BootstrapVue 3

**Ventajas**
- Muy fácil de aprender y usar.
- Ideal para prototipado rápido.
- Estilos responsive automáticos.

**Desventajas**
- Menos componentes disponibles.
- Personalización limitada sin sobrescribir CSS.
- Apariencia menos moderna.

---

### Vuetify 3

**Ventajas**
- Librería más completa y robusta.
- Componentes altamente personalizables.
- Excelente para aplicaciones grandes o complejas.
- Diseño estandarizado con Material Design.

**Desventajas**
- Instalación y configuración más complejas.
- Curva de aprendizaje mayor.
- Bundle más pesado.

---

### Element Plus

**Ventajas**
- Muy fácil de integrar con Vue 3.
- Componentes profesionales y modernos.
- Buena documentación.
- Estética limpia y flexible.

**Desventajas**
- Menos opciones avanzadas de theming que Vuetify.
- Sistema de layout menos completo.

---

## Comparativa general (ventajas y desventajas)

| Librería        | Ventajas | Desventajas |
|-----------------|----------|-------------|
| BootstrapVue 3  | Fácil, rápida, buena para prototipos | Menos componentes, poca personalización |
| Vuetify 3       | Completa, robusta, Material Design   | Instalación compleja, curva alta |
| Element Plus    | Fácil, profesional, moderna          | Menos flexible que Vuetify |

---

## Conclusión: 
La librería más útil depende del tipo de aplicación:

- **Para apps complejas → Vuetify 3**  
- **Para apps empresariales limpias y modernas → Element Plus**  
- **Para prototipos simples → BootstrapVue 3**

### Conclusión personal

Element Plus resultó ser la opción más equilibrada debido a:

- Facilidad de instalación  
- Componentes modernos  
- Estética limpia  
- Buen equilibrio entre simplicidad y profesionalismo  

Sin embargo, si se requiere un sistema de diseño más avanzado, **Vuetify** sigue siendo la mejor opción.

---
## Actividad 2:
### Exploración de frameworks para Server Side Rendering (SSR) y creación de una app SSR con Nuxt.js

**Objetivo:** Comprender qué es Server Side Rendering (SSR), cuándo usarlo y sus ventajas/desventajas, utilizando Nuxt.js para crear una aplicación con renderizado en el servidor.

## Descripción de la actividad:
### 1. Investigación Teórica:
Los estudiantes deben investigar qué es el Server Side Rendering (SSR), cómo funciona, y cuáles son las ventajas y desventajas frente al renderizado del lado del cliente (CSR). Deben entender el concepto de Nuxt.js y cómo facilita la creación de aplicaciones SSR.
El estudiante debe investigar también Quasar Framework y cómo ayuda en la creación de aplicaciones SSR con características adicionales como la creación de aplicaciones móviles o de escritorio.


### ¿Qué es el Server Side Rendering (SSR)?

El **Server Side Rendering (SSR)** es una técnica donde el servidor genera el HTML de una página antes de enviarlo al navegador. El contenido se renderiza en el servidor, lo que mejora el rendimiento percibido y el SEO.

### ¿Cómo funciona el SSR?

1. El usuario realiza una solicitud.
2. El servidor ejecuta el framework (como Nuxt.js), obtiene datos y genera el HTML final.
3. El servidor envía el HTML ya renderizado al navegador.
4. El navegador activa el JavaScript (hidrata la página) para hacerla interactiva.

### Diferencias entre SSR y CSR

| Característica | SSR | CSR |
|----------------|-----|-----|
| Renderizado inicial | En el servidor | En el navegador |
| Tiempo hasta ver contenido | Más rápido | Más lento |
| SEO | Mejor | Limitado |
| Carga en el servidor | Más alta | Más baja |
| Interactividad | Requiere hidratación | Directa tras cargar JS |

### Ventajas del SSR

* Mejor SEO.
* Mayor velocidad en el primer renderizado visible.
* Mejor rendimiento en dispositivos menos potentes.
* Correcta previsualización en redes sociales (OpenGraph, etc.).

### Desventajas del SSR

* Mayor carga sobre el servidor.
* Configuración y despliegue más complejos.
* El tiempo de respuesta puede aumentar si hay alta demanda.
* Requiere hidratación del lado del cliente.

---

## Nuxt.js y por qué facilita el SSR

**Nuxt.js** es un framework basado en Vue.js que facilita crear aplicaciones SSR, SSG o SPA sin configuraciones complejas.

### Características principales de Nuxt.js

* SSR integrado por defecto.
* Sistema de rutas automático mediante el directorio `pages/`.
* Manejo de estado, middlewares y server routes.
* Soporte para composables, layouts y metadatos SEO.
* Flujo de desarrollo rápido con `nuxi dev`.

### ¿Cómo facilita Nuxt.js el SSR?

* Renderiza páginas en el servidor usando Vue y Nitro.
* Genera HTML optimizado para cada ruta.
* Maneja hidratación automática en el cliente.
* Permite caching, prefetching y renderizado híbrido.

---

## Quasar Framework y SSR

**Quasar Framework** es un framework basado en Vue.js que permite crear:

* Aplicaciones web
* SSR
* PWA
* Apps móviles (Capacitor/Cordova)
* Apps de escritorio (Electron)

### ¿Cómo ayuda Quasar en SSR?

* Ofrece un modo SSR integrado.
* Optimiza la carga progresiva e hidratación.
* Permite usar la misma base de código para web, móvil y escritorio.
* Incluye una amplia biblioteca de componentes UI.

### Ventajas de Quasar para SSR

* Ecosistema unificado.
* Componentes optimizados.
* Proceso de compilación avanzado con optimización de bundles y tree-shaking.


### 2. Práctica de implementación con Nuxt.js:
Los estudiantes deben crear una aplicación básica en Vue.js utilizando Nuxt.js.
- **Tarea 1:** Crear una pequeña aplicación que muestre contenido estático utilizando Nuxt.js y compararlo con una versión similar utilizando solo Vue.js.
- **Tarea 2:** Explicar en qué casos usar SSR y cómo Nuxt.js mejora el rendimiento y la SEO de la aplicación.
- **Tarea 3:** Implementar una funcionalidad dinámica (p. ej., fetch de datos desde una API) utilizando el sistema de rutas y páginas de Nuxt.js.


## Tarea 1:

### Aplicación estática con Vue.js (SPA)
En una aplicación básica hecha solo con Vue (SPA), el contenido se renderiza completamente en el navegador. El servidor entrega un archivo vacío con un `<div id="app"></div>` y el navegador descarga el JavaScript para generar el contenido.

Características principales:
* Todo el renderizado ocurre en el cliente.
* La primera carga puede ser más lenta.
* SEO más limitado, porque el HTML inicial no contiene contenido real.

### Aplicación estática con Nuxt.js (SSR)
Con Nuxt.js, incluso una página estática se genera en el servidor antes de enviarse al navegador. Esto significa que el usuario recibe un HTML ya completo, con el contenido presente desde el inicio.

Características principales:
* Renderizado inicial desde el servidor.
* Mejor tiempo de carga percibida.
* Mejor SEO, porque los buscadores detectan contenido real en el HTML.
* Ruteo automático basado en la carpeta `pages/`.

### Comparación general
| Aspecto | Vue.js (SPA) | Nuxt.js (SSR) |
|--------|---------------|----------------|
| Renderizado | Cliente | Servidor |
| SEO | Limitado | Excelente |
| Tiempo hasta contenido visible | Más lento | Más rápido |
| Configuración | Más simple | Más completo y estructurado |
| Enfoque | Aplicaciones SPA | Páginas web con SEO y rendimiento |

---

## Tarea 2: 

### Casos ideales para usar SSR
* Proyectos donde el SEO es importante (blogs, ecommerce, sitios públicos).
* Sitios donde la carga inicial debe ser rápida.
* Aplicaciones donde se quiere entregar contenido visible aún en dispositivos lentos.
* Proyectos que requieren compartir enlaces con metadatos correctos (OpenGraph, redes sociales).
* Sitios que necesitan pre-renderizado de datos dinámicos antes de llegar al usuario.

### ¿Cómo mejora Nuxt.js el rendimiento?
* Pre-renderiza el contenido en el servidor, reduciendo el tiempo hasta el primer renderizado (FCP).
* Optimiza los bundles JavaScript y CSS.
* Maneja automáticamente la hidratación del contenido para hacerlo interactivo.
* Permite cargar datos antes de que la página llegue al navegador, mostrando contenido inmediato.

### ¿Cómo mejora Nuxt.js el SEO?
* Entrega HTML completamente generado, lo que los motores de búsqueda pueden indexar sin depender de JavaScript.
* Permite configurar metadatos, títulos y etiquetas para cada ruta o página.
* Mejora la accesibilidad y la estructura semántica.

---

## Tarea 3: 

Usando Nuxt.js, se puede crear una página dinámica que obtiene datos desde una API utilizando `useFetch` o `useAsyncData`.

Flujo básico:
1. Crear un archivo en `pages/`, por ejemplo `pages/posts.vue`.
2. Dentro de la página, utilizar `useFetch` para obtener datos desde una API.
3. Nuxt ejecuta este fetch en el servidor durante la primera carga (SSR).
4. El usuario recibe la página ya renderizada con los datos.
5. El cliente hidrata la página y la vuelve interactiva.

Ventajas de usar esta técnica en SSR:
* Los datos llegan ya integrados en el HTML.
* El SEO mejora porque el contenido dinámico también puede ser indexado.
* La respuesta es más rápida en la primera visita.

Ejemplo conceptual (sin renderizar):
```vue
<script setup>
const { data } = await useFetch('https://jsonplaceholder.typicode.com/posts?_limit=5')
</script>

<template>
  <div>
    <h1>Listado de Posts</h1>
    <ul>
      <li v-for="p in data" :key="p.id">{{ p.title }}</li>
    </ul>
  </div>
</template>
```

En este ejemplo:
* La API se consulta durante el SSR.
* El HTML enviado al navegador ya contiene la lista de posts.
* La página es más rápida y más apta para SEO.

---

## Conclusión general

* Nuxt.js facilita la creación de aplicaciones SSR con Vue.js.
* La versión SSR mejora el rendimiento, la carga inicial y el SEO.
* Nuxt ofrece rutas automáticas, fetch en servidor y estructura organizada.
* SSR es recomendado para sitios públicos, informativos o comerciales donde el SEO es relevante.