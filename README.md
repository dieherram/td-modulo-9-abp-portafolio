# Diego Hernández — Full Stack JavaScript · UX/UI

**[Ver el portafolio en línea →](https://dieherram.github.io/td-modulo-9-abp-portafolio/)**

Desarrollador Full Stack con formación en Marketing y Diseño UX/UI. Construyo productos digitales completos: la interfaz, la API que la sostiene y las decisiones de producto detrás de ambas. Este repositorio es mi portafolio y también su código fuente.

Si estás revisando perfiles, esto es lo que necesitas saber en un minuto:

| | |
|---|---|
| **Busco** | Desarrollo frontend / full stack, con componente UX/UI |
| **Hago** | Interfaces responsivas y accesibles, APIs con Express, diseño de experiencia |
| **Con** | JavaScript, React, Node.js, PostgreSQL, Bootstrap, JWT, UX/UI |
| **Base** | Formación en Marketing — hablo el idioma del negocio, no solo el del código |
| **Contacto** | [LinkedIn](https://linkedin.com/in/diego-hernandez-ramos) · [GitHub](https://github.com/dieherram) · [CV en PDF](./assets/cv-diego-hernandez.pdf) |

---

## Proyectos

Cada proyecto incluye su código fuente. Las capturas son de las aplicaciones reales, no de maquetas.

### Mi Pokédex
Consumo de API pública con persistencia y visualización de datos.
Aplica **JavaScript, Bootstrap y la PokéAPI**. Busca y registra Pokémon, guarda el estado en el navegador y grafica las estadísticas base de cada uno: una API de terceros convertida en información que el usuario puede leer y comparar.

| Vista principal | Búsqueda | Estadísticas |
| --- | --- | --- |
| ![](./assets/images/01%20Mi%20Pokedex.jpg) | ![](./assets/images/02%20Mi%20Pokedex.jpg) | ![](./assets/images/03%20Mi%20Pokedex.jpg) |

[Código fuente](https://github.com/dieherram/td-modulo-3-4-abp-pokedex)

### Alky Wallet
Simulador de billetera digital con autenticación y movimientos.
**HTML5, CSS3 y JavaScript.** Login, depósitos, transferencias e historial, con validaciones de formulario en cada paso. El reto no era el CRUD sino que el flujo se sintiera claro: cada acción tiene su estado de carga, su error y su confirmación.

| Login | Dashboard | Historial |
| --- | --- | --- |
| ![](./assets/images/01%20Alky%20Wallet.jpg) | ![](./assets/images/02%20Alky%20Wallet.jpg) | ![](./assets/images/03%20Alky%20Wallet.jpg) |

[Código fuente](https://github.com/dieherram/td-modulo-2-abp-alky-wallet)

### Cócteles con React
Consumo de API con arquitectura de componentes.
**React y Bootstrap.** Búsqueda, filtrado por categoría y selección al azar sobre una API pública, resuelto con componentes reutilizables. Demuestra el salto de escribir lógica en cada vista a componer una interfaz que se extiende sin duplicarse.

| Inicio | Filtrado | Detalle |
| --- | --- | --- |
| ![](./assets/images/01%20Cocteles%20con%20React.jpg) | ![](./assets/images/02%20Cocteles%20con%20React.jpg) | ![](./assets/images/03%20Cocteles%20con%20React.jpg) |

[Código fuente](https://github.com/dieherram/dl-react-i-consumo-de-apis-con-react)

### Mamma Mia!
E-commerce completo con estado global.
**React, React Router y Context API.** Catálogo, detalle de producto y carrito. El estado global vive en Context y la navegación en el router: la misma arquitectura que exige un catálogo real, donde el carrito tiene que sobrevivir a la recarga de la página.

| Catálogo | Detalle | Carrito |
| --- | --- | --- |
| ![](./assets/images/01%20Mamma%20Mia.jpg) | ![](./assets/images/02%20Mamma%20Mia.jpg) | ![](./assets/images/03%20Mamma%20Mia.jpg) |

[Código fuente](https://github.com/dieherram/dl-react-ii-trabajo-practico)

### Soft Jobs API
Backend con autenticación y control de acceso.
**Node.js, Express, JWT y PostgreSQL.** API de empleos junior: registro, login, contraseñas encriptadas y middlewares que separan lo público de lo que exige un token. Es el proyecto que mejor muestra cómo diseño el backend —no qué stack uso, sino dónde pongo las fronteras.

| Documentación | Autenticación | Control de acceso |
| --- | --- | --- |
| ![](./assets/images/01%20Soft%20Jobs%20API.jpg) | ![](./assets/images/02%20Soft%20Jobs%20API.jpg) | ![](./assets/images/03%20Soft%20Jobs%20API.jpg) |

[Código fuente](https://github.com/dieherram/dl-backend-con-node-y-express-autenticacion-y-autorizacion-de-usuarios-con-jwt)

---

## Caso de estudio: de Vanilla JS a React

Uno de los proyectos anteriores lo resolví manipulando el DOM y duplicando lógica entre vistas. Rehacerlo en React no fue un cambio de sintaxis: fue un cambio de forma de pensar la interfaz.

| Vanilla JS | React |
| --- | --- |
| Cada vista carga y filtra sus datos | Un único flujo de datos, unidireccional |
| Lógica de búsqueda repetida en varias páginas | Componentes reutilizables: buscador, filtros, tarjeta, detalle |
| El estado vive en variables sueltas | Estado centralizado y predecible |
| Agregar un filtro = tocar tres archivos | Agregar un filtro = un componente nuevo |

**Resultado:** 5 páginas independientes colapsan en 1 vista principal con 4 componentes reutilizables y alrededor de **90% menos duplicación funcional**.

El aprendizaje que me llevé: en React el problema ya no es *cómo* actualizo la pantalla, sino *dónde vive el estado*. Esa pregunta es la misma que aparece al diseñar una API.

→ [Leer el análisis en el portafolio](https://dieherram.github.io/td-modulo-9-abp-portafolio/#caso-estudio)

---

## Qué aporto a un equipo

- **Frontend con criterio de producto.** No solo interfaces que funcionan: interfaces que se sostienen en móvil, se pueden leer con teclado y siguen siendo legibles con un lector de pantalla.
- **Backend con límites claros.** APIs en Express con autenticación, validación y separación de responsabilidades.
- **Perfil de Marketing.** Puedo conectar una necesidad de negocio con una decisión de interfaz, y medir si funcionó. Es la diferencia entre entregar una pantalla y entregar un producto.

## Tecnologías

`JavaScript` `React` `React Native` `Node.js` `Express` `PostgreSQL` `HTML5` `CSS3` `Bootstrap` `REST APIs` `JWT` `UX/UI` `Git`

---

## Cómo está construido este sitio

Sitio estático: **HTML, CSS y JavaScript sin build**. Bootstrap 5.3 y dos familias tipográficas de Google Fonts son las únicas dependencias externas. Se despliega en GitHub Pages, así que el repositorio es exactamente lo que está en producción.

Tres decisiones que no son obvias:

**Las imágenes se sirven a la medida.** Las 15 capturas pesan 2,8 MB en JPG. El atributo `sizes` declaraba la tarjeta en 502 px de ancho, cuando en realidad ocupa `50vw` en escritorio y `100vw` en móvil — 1920 px reales en un monitor retina. El navegador elegía un derivado de 1000 px y lo **escalaba 1,92×**: 2,8 MB entregados y una imagen más blanda que el original. Corregir la geometría y generar tres escalones reales (640 / 1280 / ancho nativo) dejó las seis escenas en **803 KB**.

**El video del hero no se descarga solo.** Pesa 4 MB, así que solo se carga si el visitante no pidió movimiento reducido, no está en ahorro de datos, la conexión supera 2 Mbps, la página ya terminó de cargar y el primer fotograma llega en 12 segundos. Si algo falla, el hero conserva su gradiente. Se pausa al salir de pantalla, al cambiar de pestaña y al abrir una galería.

## Ejecutar el proyecto

No requiere instalación ni compilación:

```bash
npx serve .
```

O abre `index.html` directamente en el navegador. Para que el video del hero funcione, conviene servirlo por HTTP en vez de abrirlo como archivo local.

## Contacto

- [LinkedIn](https://linkedin.com/in/diego-hernandez-ramos) — la vía más rápida
- [GitHub](https://github.com/dieherram) — código de todos los proyectos
- [CV en PDF](./assets/cv-diego-hernandez.pdf)

---

© 2026 Diego Hernández · Full Stack JavaScript · UX/UI · Product Thinking
