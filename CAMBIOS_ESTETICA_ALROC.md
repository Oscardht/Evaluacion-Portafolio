# 🏛️ Inversiones D'ALROC Real Estate — Roadmap de Rediseño y Transformación Estética

**Proyecto:** Web Inmobiliaria de Bienes Raíces — Lic. Claudia Di Diomede  
**Ubicación:** Isla de Margarita, Nueva Esparta, Venezuela & El Caribe  
**Referencia Visual:** `AlRocWeb` (`DalRocWEb.png` — Altar y Arquitectura Clásica Neoclásica/Barroca de la Virgen del Valle)  
**Directriz de Diseño:** *Luminosidad Clásica, Proporción Arquitectónica, Cero Bento Grid, Cero Polimorfismo Exagerado (Glassmorphism).*  
**Fecha de Elaboración:** Septiembre 2026  

---

## 🧭 1. Diagnóstico del Estado Previo vs. Nueva Visión

### ❌ Estado Previo (Problemas Identificados)
1. **Paleta Oscura y Ciber-Lujosa Inapropiada:** Fondo negro profundo (`#0D0D0F`) con resplandores dorados intensos que evocaban una estética nocturna o de discoteca/cripto más que de una firma inmobiliaria de bienes raíces caribeña de alto prestigio.
2. **Polimorfismo y Glassmorphism Exagerado:** Uso excesivo de `backdrop-filter: blur(20px)`, fondos semitransparentes apilados, bordes brillantes de plástico y sombras difusas que restaban sobriedad y legibilidad.
3. **Estructura tipo "Bento Grid":** Bloques asimétricos desordenados (tarjetas anchas, altas y cuadradas en mosaico irregular) que fragmentaban la atención del cliente en lugar de ofrecer un recorrido sereno y distinguido.
4. **Desconexión con la Identidad Insular:** No reflejaba la luz natural, el blanco alabastro de las villas coloniales y modernas de Margarita, ni la calidez atemporal que busca un inversor de alto perfil.

### ✨ Nueva Visión Estética: Inspiración `AlRocWeb`
La obra pictórica `AlRocWeb` (representación en acuarela del santuario y altar de Nuestra Señora del Valle en Margarita) sintetiza la máxima elegancia insular:
- **Luz Diáfana y Fondos Alabastro/Mármol:** Fondos en blanco cálido, marfil y perla que transmiten pureza, amplitud, honestidad y lujo atemporal.
- **Dorado Imperial y Hoja de Oro Mate:** El dorado ya no es un resplandor de neón, sino una orfebrería sutil: molduras finas, ribetes dobles, monogramas y detalles de alta precisión.
- **Acentos Arquitectónicos Nobles:**
  - *Verde Mármol / Jade Clásico (`#2D5446`):* Evocando las columnas corintias del altar, aportando estabilidad y prestancia.
  - *Azul Celestial / Niebla Marina (`#4A728E`, `#EBF1F6`):* Evocando los frescos celestiales y la brisa del Caribe.
  - *Carbón Editorial Profundo (`#1F1C18`):* Reemplaza el negro puro para los textos, brindando una lectura de alta gama editorial.
- **Proporción y Equilibrio Arquitectónico:**
  - Sustitución de cajas tipo bento por **columnatas simétricas, arcos de medio punto y marcos con doble filete.**
  - Tarjetas sólidas en tonos marfil con micro-sombras naturales de luz solar (`box-shadow: 0 8px 30px rgba(40, 32, 20, 0.05)`).

---

## 🎨 2. Sistema Cromático y Tokens de Diseño (AlRoc Architectural Palette)

| Token | Código HEX | Rol y Significado Arquitectónico |
| :--- | :--- | :--- |
| `--color-alabastro` | `#FCFBF9` | Fondo general de la página; luz natural diáfana. |
| `--color-marfil` | `#F7F3EB` | Fondo de tarjetas, paneles y superficies elevadas. |
| `--color-crema-piedra` | `#EFE8DB` | Filetes sutiles, fondos secundarios y divisiones. |
| `--color-oro-imperial` | `#C5A85A` | Dorado principal de logotipos, monogramas e insignias. |
| `--color-oro-antiguo` | `#9B7E35` | Acentos de tipografía capitular, bordes activos y hover. |
| `--color-verde-columna` | `#2D5446` | Verde esmeralda noble de columnas arquitectónicas para llamadas de acción y sellos de confianza. |
| `--color-azul-celeste` | `#4A728E` | Acentos de alta distinción y etiquetas de ubicación marítima. |
| `--color-azul-brisa` | `#F0F5F8` | Fondos de etiquetas y píldoras secundarias. |
| `--color-carbon-editorial`| `#1F1C18` | Tipografía principal (h1, h2, h3, párrafos); máxima legibilidad. |
| `--color-gris-piedra` | `#59534B` | Párrafos secundarios, metadatos y notas legales. |
| `--border-hairline-oro` | `1px solid rgba(197, 168, 90, 0.35)` | Molduras y marcos de tarjetas con sobriedad clásica. |

---

## 📐 3. Plan de Reestructuración por Componentes

### 3.1. Barra de Navegación (Header)
- **Cambio:** Abandonar la barra negra con blur oscuro.
- **Nueva Solución:** Fondo en Marfil Lácteo (`#FCFBF9` con opacidad 0.96 y borde inferior en filete de oro fino `1px solid rgba(197, 168, 90, 0.3)`).
- **Logotipo:** El logotipo de Inversiones D'ALROC resaltado con tipografía moderna *Plus Jakarta Sans* (peso 800) en carbón editorial con la palabra *ALROC* en dorado imperial itálico.
- **Navegación:** Enlaces con tipografía equilibrada (*Plus Jakarta Sans*, peso 500), con micro-subrayado en hilo dorado al pasar el cursor.

### 3.2. Sección Hero (Historia & Bienvenida)
- **Cero Bento:** En vez de cajas flotantes desalineadas, una estructura en dos columnas con simetría clásica:
  - **Columna Izquierda:** Título monumental (*Playfair Display*), lema emblemático ("NO BUSQUES, DEJA QUE TE ENCUENTREN. CONFÍA LA VENTA DE TU PROPIEDAD A LOS EXPERTOS") enmarcado en una cartela editorial con ribete doble, insignias de prestigio, barómetro en vivo (*Live Insular Pulse*) y botones de acción en oro bruñido y verde colonial.
  - **Columna Derecha:** Marco de propiedad con silueta en **arco clásico arquitectónico** (`border-radius: 180px 180px 12px 12px`), rindiendo homenaje a los arcos ojivales y de medio punto de la referencia `AlRocWeb`.
  - **📌 Requisito de Rotación de Propiedades Reales ("Villa Exclusiva Caribeña"):** En el apartado donde actualmente figura la *"Villa Exclusiva Caribeña"*, cuando se agreguen las fotografías reales de la cartera de inmuebles, se implementará una **rotación dinámica de propiedades** (carrusel cinematográfico con efecto *crossfade* suave). Esta rotación alternará fotos reales en alta definición y actualizará en tiempo real los datos de la ficha flotante (nombre de la propiedad, ubicación exacta, metraje en m², número de suites y amenidades destacadas como vista al mar o piscina privada), manteniendo la tridimensionalidad y los reflejos de luz sin saltos.

### 3.3. Sección Galerías (Propiedades y Zonas de Alta Plusvalía)
- **Cero Bento:** Eliminar las tarjetas desproporcionadas (span 8, span 4, span 5, span 7).
- **Nueva Solución:** Cuadrícula arquitectónica simétrica y armoniosa de 4 columnas equilibradas o 2x2 regular, tarjetas enmarcadas con paspartú marfil, rótulos tipográficos en serif y detalles de plusvalía y ubicación en Isla de Margarita (Playa El Ángel, Pampatar, Playa El Agua, La Caracola).

### 3.4. Sección Servicios Premium (Opiniones & Soluciones)
- **Cero Polimorfismo Exagerado:** Eliminar las cajas oscuras con brillo neón.
- **Nueva Solución:** Tarjetas de servicio nobles, con fondo blanco alabastro puro, íconos grabados en oro imperial dentro de círculos de filigrana, y descripción de servicios (Asesoría Personalizada, Oportunidades de Inversión, Seguridad Jurídica, Acceso Exclusivo a Propiedades).

### 3.5. Sección Asesora Encargada (Lic. Claudia Di Diomede)
- **Tratamiento Dignificado y Personal:**
  - Marco de retrato distinguido para la fotografía de la Lic. Claudia Di Diomede (`ClaudiaIMG.jpeg`), con orla dorada y bisel refinado.
  - Credenciales oficiales: *Corredora de Inmuebles Certificada*, colegiatura, trayectoria en la región insular y trato jurídico personalizado.
  - Acceso directo e instantáneo a contacto vía WhatsApp business con mensaje preconfigurado.

### 3.6. Tarjeta Interactiva de Contacto y Modal
- **Tarjeta de Contacto:** Enmarcada como un tarjetón de correspondencia de alta sastrería/inmobiliaria en fondo crema cálido con sellos dorados, datos claros (WhatsApp, correo, ubicación en Porlamar/Pampatar).
- **Modal de Código QR:** Diálogo refinado en blanco hueso con el QR dorado institucional de Instagram `@inversionesdalroc.ca` y enlaces directos.

---

## 🗓️ 4. Roadmap de Fases de Implementación

### ✅ Fase 1: Fundamentos Visuales y Nueva Paleta (Inmediata)
- [x] Análisis del arte `AlRocWeb` (`DalRocWEb.png`).
- [x] Copia y resguardo de activos de identidad en el repositorio web (`img/AlRocWeb.png`).
- [x] Sustitución del esquema oscuro (`#0D0D0F`) por la paleta luminosa de alabastro, marfil, mármol y oro imperial en `estilos.css` y `seccion3.css`.
- [x] Eliminación de capas de `backdrop-filter` pesadas y efectos plásticos.
- [x] Generación de este documento maestro de cambios.

### 🔨 Fase 2: Reestructuración de Componentes y Markup (Completada con Éxito)
- [x] Rediseño del Hero con marco en arco arquitectónico para la villa destacada y relieve táctil neoclásico.
- [x] Barómetro inmobiliario en vivo (*Live Insular Pulse*) con temperatura, zonas clave y estatus activo de Margarita.
- [x] Relieve 3D táctil e interactivo (micro-tilt controlado a ±3.5° y brillo especular dinámico que sigue el cursor sin glitches ni recortes).
- [x] Consola rápida de búsqueda de inmuebles (*Hero Property Finder*) con pestañas (Comprar / Alquilar / Terrenos), filtros por zona, tipo y presupuesto.
- [x] Animaciones de scrolleo de alto rendimiento (Parallax multi-plano a 60fps, elevación de header y revelado escalonado con `IntersectionObserver`).
- [x] Indicador de scrolleo clásico con ratón animado hacia las galerías.
- [x] Corrección de la galería a formato de cuadrícula simétrica equilibrada (adiós bento).
- [x] Refactorización de la sección de servicios con tarjetas sólidas de fondo marfil y relieves sutiles.
- [x] Hero de Bienvenida Estilo Airbnb (Búsqueda Directa & Conversión): Fondo 100vh panorámico con overlay de contraste, H1 centralizado en tercio superior ("Encuentra tu hogar ideal en Margarita"), widget flotante con pestañas (Apartamentos activa, Town-House, Alquiler), barra de 3 campos (Ubicación, Calendario, Alquiler), botón CTA magenta `#FF385C` y enlace secundario "Cerca de ti >".
- [x] Brújula Flotante de Recorrido (*Scroll Compass Dock*): dial circular con cálculo de porcentaje en tiempo real y detección activa de hitos/estaciones de la página.
- [x] Nueva Estructura "La Ruta de su Inversión" (`#Ruta`): 3 estaciones estratégicas conectadas por un conducto áureo (01 Curaduría & Oportunidad, 02 Blindaje Jurídico Registral, 03 Protocolización & Rentabilidad).
- [x] Contadores numéricos dinámicos vinculados al scroll (`+15 Años`, `100% Seguridad Jurídica`, `+14.8% Plusvalía Proyectada`) mediante `requestAnimationFrame`.
- [x] Filtros interactivos por categoría en la Galería Arquitectónica (*Todas las Colecciones*, *Frente al Mar*, *Arquitectura & Lujo*, *Desarrollos & Plusvalía*).
- [x] Homogeneización de tipografías: *Playfair Display* para jerarquía monumental y *Plus Jakarta Sans* para claridad de lectura.
- [x] Eliminación de la burbuja fija flotante de la esquina (cero distracciones o estorbos al navegar).
- [x] Pop-up de Cierre al 100% de Recorrido: Se activa automáticamente cuando el indicador de scrolleo alcanza el 100%, con el título *"¿Listo para consultar acerca de tu propiedad soñada? Contáctanos a través de nuestras redes sociales o WhatsApp:"*, teniendo como centro de atención el código QR de Instagram para escanear desde dispositivos móviles e iconos de redes idénticos a los del footer.

### 🌟 Fase 2.5: Transformación de Pop-ups Interactivos, Píldora Panorámica y Estandarización de Identidad (Completada con Éxito)
- [x] **Insignia y Flyout Flotante Sacro de la Virgen del Valle (`.virgen-flyout-card` y `.virgen-floating-dock` - Margen Inferior Derecho):**
  - **Sustitución de Imagen:** Reemplazo de la silueta recortada por el gráfico completo e íntegro de la Virgen (`Ejemplo.png`).
  - **Conversión a Tarjeta Ejecutiva Compacta:** Redimensión a un ancho esbelto de 298px con diseño de tarjeta de presentación de lujo.
  - **Encabezado y Jerarquía Tipográfica Equilibrada:** Retrato de la Lcda. Claudia Di Diomede con reencuadre óptico ejecutivo (zoom abierto a `scale(1.14)`, elevación vertical y desplazamiento lateral `translate(-4%, -3%)` y `object-position: center 50%` para mayor protagonismo y visibilidad del uniforme blanco corporativo), marco y resplandor áureo. Se mantuvieron intactas las dimensiones originales exactas de la tarjeta y sus márgenes internos, aplicando únicamente un ligero incremento en las fuentes solicitadas: nombre `Lcda. Claudia Di Diomede` (`1.24rem`) e insignia `Profesional Certificado N° 2735` (`0.74rem` con ícono a `0.76rem`), preservando el kicker superior y botón de WhatsApp intactos y sin recortes de texto.
  - **Botones Interactivos de Redes Sociales Oficiales D'ALROC:** Se reemplazaron los 4 íconos inertes de especialidades por botones con hipervínculos directos a las redes sociales oficiales de la empresa: **X (Twitter)** (`https://x.com/AlrocD`), **Instagram** (`@inversionesdalroc.ca`), **Facebook** (`Inversiones D'ALROC`) y **YouTube** (`@InversionesDalroc`), conservando exactamente la paleta cromática dorada/esmeralda, dimensiones originales (35px, gap 0.7rem) y las mismas animaciones al pasar el mouse (`transform: translateY(-2px) scale(1.12)` con sombra elevada).
  - **Canal Directo de WhatsApp:** Botón de contacto estilizado con el mensaje `Conversar con la Lcda. Claudia`, apertura en nueva pestaña y mensaje preconfigurado intacto en sus medidas originales.
- [x] **Pop-up Arquitectónico Superior Izquierdo (`.top-shape-popup`):**
  - **Eliminación de Redundancia de Marca:** Se suprimió el logo duplicado en la cabecera interna, dejando el escudo oficial de Inversiones D'ALROC de forma protagónica en la pestaña inferior que asoma hacia afuera.
  - **Cabecera Monumental Clickeable:**
    - Se rodó el texto hacia la izquierda para aprovechar el ancho completo.
    - Kicker superior: `EXCLUSIVIDAD Y BLINDAJE` en tipografía *Cinzel* dorada limpia (corona retirada para máxima pureza visual).
    > [!IMPORTANT]
    > **👑 ELEMENTO DE IDENTIDAD EN RESERVA — CORONA IMPERIAL ÁUREA (`fa-solid fa-crown`):**  
    > La insignia de la corona dorada ha sido retirada del kicker superior para preservar la máxima sobriedad y legibilidad tipográfica. Se resguarda formalmente en este documento como activo institucional prioritario para ser reubicada próximamente en una sección de alta distinción (candidatos ideales: insignia de blindaje legal, sello de certificación de la Lcda. Claudia Di Diomede, tarjetas VIP de propiedades o pie de página).
    - Título principal de gran tamaño: `INVERSIONES D'ALROC` en tipografía moderna *Plus Jakarta Sans* (peso 800) con *ALROC* en cursiva dorada.
    - Lema editorial: `En la compra o venta de tu propiedad` en tipografía romana clásica *Cinzel* (peso 600) y tono neutro cálido.
    - **Navegación inteligente:** Todo el bloque de cabecera es interactivo; al cliquearlo, cierra automáticamente el menú desplegable y realiza un desplazamiento suave (*smooth scroll*) hacia el pie de página (`#pie-de-pagina`).
  - **Grilla de Especialidades & Servicios (Infonormal - Ubicación Superior):** Tarjetas de Bienes Raíces & Gestoría, Construcción & Remodelación y Turismo & Hospedaje situadas estratégicamente por encima de la fila interactiva.
  - **Píldora Panorámica Interactiva con `ImagenLarge.jpg` y Textos Rotativos Fly-In (`.top-shape-expand-row`):**
    - **Eliminación del panel verde inerte:** Se removió la tira verde vacía para evitar saturación de bloques verdes y favorecer una estética editorial limpia sobre fondo marfil.
    - **Eliminación del label verde en la píldora:** Se suprimió la etiqueta/caption verde sobre la fotografía expandida para una vista panorámica limpia y sin interferencias.
    - **Eliminación total de líneas guía y tooltips:** Se suprimió la línea vertical guía (`border-left`) y el atributo tooltip `title`, dejando un diseño diáfano, limpio y sin avisos intrusivos al pasar el cursor.
    - **Unificación Tipográfica Cinzel en Verde Esmeralda Imperial:** Todos los textos rotativos comparten de forma uniforme la misma tipografía institucional *Cinzel*, peso 800, mayúsculas sostenidas, espaciado equilibrado y color verde esmeralda imperial (`--emerald-column`), abarcando todo el ancho hasta el borde derecho:
      1. `BAHÍA DE PAMPATAR, ISLA DE MARGARITA` (con icono de ubicación).
      2. `EL HOGAR DE TUS SUEÑOS, JUNTO A NUESTRA ASESORÍA.` (con icono de hogar).
      3. `EL ENCANTO DE LA ISLA, DE LA MANO DE NOSOTROS.` (con icono de brújula).
      4. Retorna a `BAHÍA DE PAMPATAR, ISLA DE MARGARITA` en bucle fluido.
    - **Toggle Inteligente de Expansión / Contracción con Clic:**
      - Al hacer clic, la imagen se expande a lo ancho (`100%`) como píldora panorámica fija de 82px revelando la bahía completa.
      - Al volver a hacer clic, se contrae inmediatamente de nuevo al icono reducido de 54px y reactiva el bloque de textos rotativos sin quedarse bloqueada en hover.
  - **Botón de Conversión Inferior:** Botón en verde esmeralda `VER PROPIEDADES AHORA` con ancla directa a `#Galeria`, cerrando el pop-up al pulsar, y botón de llamada directa.
- [x] **Estandarización de Identidad y Nomenclatura:**
  - Estandarización unificada del título profesional a **`Lcda. Claudia Di Diomede`** en ambos pop-ups y botones de contacto.
  - Armonización cromática del botón y elementos del buscador estilo Airbnb del Hero (reemplazo de coral `#FF385C` por verde esmeralda imperial `--emerald-column` y oro).
  - Sincronización exacta y consolidación final en `index.html` (retirando el archivo temporal de pruebas `ipodnano.html` y unificando el código fuente definitivo en `index.html` y `estilos.css`).

### 🚀 Fase 3: Catálogo Inmobiliario Victoriano de Lujo (Estilo Airbnb Catalog) — COMPLETADO
- [x] **Arquitectura de Cuadrícula a 2 Columnas (`grid-template-columns: repeat(2, 1fr)`):**
  - Configuración fija de **2 propiedades por fila** en pantallas de escritorio, logrando un catálogo visual amplio, imponente y cinematográfico.
  - Adaptabilidad fluida a 1 columna en dispositivos móviles y tabletas (`@media (max-width: 820px)`).
- [x] **Enmarcado Victoriano en Verde Esmeralda Imperial & Bordes Dorados:**
  - Fondo noble de tarjetas en degradado verde heráldico imperial: `linear-gradient(165deg, #1D3D2E 0%, #142B20 100%)`.
  - Doble enmarcado artesanal: borde exterior de 2px en oro antiguo (`#B88E3E`) con filete interior dorado de 1px (`rgba(212, 176, 98, 0.45)`).
  - Preservación íntegra del fondo general de la sección `#Galeria` con fondo panorámico e iluminación cálida.
- [x] **Fotografías Panorámicas de Gran Formato con `OverallPick.png`:**
  - Contenedor multimedia expandido con remate inferior de 2px en oro antiguo y efecto de zoom suave (*scale 1.06*) en hover.
  - Integración del distintivo de selección exclusiva en el catálogo.
- [x] **Tipografía Editorial de Alto Contraste sobre Esmeralda:**
  - Migración a tipografía moderna limpia *Plus Jakarta Sans* para legibilidad óptima de datos técnicos, metrajes y ubicaciones.
  - Títulos monumentales en blanco níveo sobre *Playfair Display*, iluminándose en oro bruñido al interactuar.
  - Especificaciones con iconos dorados (`fa-ruler-combined`, `fa-bed`, `fa-square-parking`).
- [x] **Buscador Hero y Filtrado Dinámico Conectado:**
  - Conexión del buscador Airbnb superior con el catálogo: filtrado instantáneo por pestañas (*Apartamentos*, *Town-House*, *Alquiler*) y por entrada de texto en tiempo real (`applyPortfolioFilter`).
- [x] **Pop-Up / Modal Ficha Técnica Dinámica con Deep Linking:**
  - Ficha técnica completa de cada inmueble con imagen ampliada, resumen descriptivo, metraje y estatus legal.
  - Detección de fragmento URL (Hash Routing como `#villa_pampatar`): apertura y desplazamiento suave automático al cargar la página si el visitante llega desde un enlace compartido.
  - Botón de conversión directo vía WhatsApp: **`CONSULTAR POR ESTA PROPIEDAD`** con icono de WhatsApp (`fa-brands fa-whatsapp`), estilizado con degradado verde esmeralda y borde dorado.
  - Mensaje dinámico preconfigurado con el enlace exacto del inmueble:
    `Buenas Claudia, me interesa esta propiedad "{URL#inmueble}". Me podrias dar detalles para pautar una cita?`

### 📱 Fase 3.5: Optimización Responsive Móvil & Corrección de Justificación Tipográfica — COMPLETADO
- [x] **Eliminación Total de la Justificación Forzada (`text-align: justify`):**
  - **Diagnóstico:** En pantallas móviles (< 768px y < 480px), la justificación tipográfica provocaba amplios "ríos de espacio en blanco" y distorsión entre palabras debido al ancho reducido de columna.
  - **Corrección:** Se erradicaron todas las declaraciones `text-align: justify` tanto en `estilos.css` como en `seccion3.css` (incluida la regla previa forzada en `@media (max-width: 768px)`).
  - **Nuevo estándar:** Alineación natural a la izquierda (`text-align: left !important; hyphens: manual !important; word-spacing: normal;`) con interlineado holgado (`line-height: 1.6 - 1.65`) en todos los párrafos, descripciones de tarjetas, bio de la asesora, lemas y fichas técnicas.
- [x] **Balance de Metadatos y Acciones en Tarjetas Móviles:**
  - En pantallas estrechas, `.meta-specs-row` pasa de `justify-content: space-between` a `justify-content: flex-start` con `gap: 0.6rem 1.2rem`, eliminando elementos aislados o desfasados al saltar de línea.
  - Reducción armoniosa de fuentes y paddings en tarjetas para pantallas compactas `<= 480px`.
- [x] **Microtipografía y Drop-Cap Adaptativo en Ficha Técnica:**
  - Redimensión responsiva de la letra capitular (`.modal-property-body::first-letter`) de 3.2rem a 2.1rem en pantallas `<= 600px` y 1.9rem en pantallas `<= 480px`, asegurando que el texto fluya de manera uniforme sin colisionar con el margen.
- [x] **Desplazamiento Seguro de Pestañas del Buscador (`.airbnb-widget-tabs`):**
  - Ajuste a `justify-content: flex-start` con `overflow-x: auto` en móviles para prevenir que la primera pestaña quede recortada en pantallas angostas.
- [x] **Separación Vertical de la Barra Superior en Móviles:**
  - Ajuste de padding superior en la sección Hero para garantizar despeje total respecto a la pestaña retráctil de la marca.

### 📲 Fase 3.6: Arco Arquitectónico Escultural Estático & Buscador Táctil con Radiobuttons — COMPLETADO
- [x] **Arco Arquitectónico Escultural y Escudo de Isla Dinámica en Móviles (`<= 768px`):**
- [x] **Top Corner Arquitectónico Estático D'ALROC en Móviles (Abarca Espacio Completo Excepto Bordesito):**
  - **Abarca el Espacio Completo Excepto el Bordesito:** En móviles abarca la dimensión horizontal (`width: calc(100% - 14px)`) conservando el elegante remate curvo en el extremo derecho (`border-bottom-right-radius: 90px` cerrado, `100px` abierto) tal como se especificó en `ABARCAESPACIOCOMPLETO EXCEPTOBORDESITO.png` y `ELESPACIOQUEDEBERIABARCAR.png`.
  - **Comportamiento 100% Estático (Cero Persecución al Scrollear):** Anclado con `position: absolute; top: 0; left: 0;` en móviles para que permanezca en la cabecera superior y nunca persiga al usuario al hacer scroll.
  - **Cero Elementos Duplicados ni Colores Falsos:** Se eliminaron escudos duplicados artificiales. Se utiliza el componente original con sus colores genuinos de escritorio (`#FCFAF6`, `var(--gold)`).
  - **Preservación Total de la Marca de Agua de la Virgen (`Ejemplo.png`):** Integrada directamente en `.top-shape-body::before` al desplegar el menú con una opacidad del 18% en el arco inferior derecho (idéntico a PC y sin ser tapada por capas opacas).
  - **Teléfono de Contacto 100% Visible y Libre de Recortes:** El número `+58 414 790-7819` se rediseñó como cápsula/badge ejecutivo (`.top-shape-phone-link`) con fondo blanco, orla de oro (`border: 1.5px solid var(--gold)`) y tipografía en negrita esmeralda (`#1D3D2E`). Además, se amplió el padding inferior del panel a `2.8rem`, garantizando que la curva del borde dorado quede por encima y con holgura sin recortar ninguna cifra.
- [x] **Eliminación Total de Resplandores Artificiales ("Glow"):**
  - Se removieron los filtros de `drop-shadow` con halo dorado (`rgba(184, 142, 62, ...)`) y los `box-shadow` con resplandor neón tanto en la insignia flotante de la Virgen (`QUITARGLOW.png`), pastilla de WhatsApp, como en el Top Shape Popup. Ahora poseen sombras naturales, nítidas y limpias, eliminando la separación halo extraña en pantallas de teléfonos.
- [x] **Restauración Estética de la Barra de Búsqueda Hero con Comboboxes Nativos:**
  - **Armonía y Estética Original 100% Intacta:** Se restauró la estructura de 3 campos en píldora dividida (`Ubicación`, `Calendario`, `Alquiler` y botón `Buscar`).
  - **Comboboxes / Selectores Táctiles Integrados:** En lugar de inputs de texto libre que abrían el teclado y causaban zooms o textos arbitrarios, se implementaron elementos `<select class="field-input field-select">` con las zonas (`Pampatar`, `Costa Azul`, `Playa El Ángel`, `La Caracola`, `Juan Griego`).
  - **Cero Teclado, Cero Zoom, Cero Descuadre:** Al tocar el campo se despliega el menú nativo del dispositivo sin activar el teclado en pantalla y sin alterar el layout visual de la barra.
  - **Tipografía Delicada y Proporcional (Letras de Adentro Reducidas):** Reducción de la escala tipográfica de los textos y placeholders interiores a `0.82rem` (y `0.80rem` en móviles) con labels de `0.72rem`, otorgando un acabado visual mucho más estilizado, sutil y proporcionado.
- [x] **Unificación Tipográfica del Pie de Página con Plus Jakarta Sans:**
  - Aplicación de *Plus Jakarta Sans* en el pie de página (`.footer`, `.footer h4`, enlaces de navegación), logrando coherencia total con el Hero.

### 💎 Fase 3.7: Optimización Tipográfica, Jerarquía Móvil y Conversión de Venta — COMPLETADO
- [x] **Aprovechamiento Tipográfico Integral en Tarjetas de Servicios y VCard:**
  - **Diagnóstico:** Con base en las anotaciones de `INCREASEcertainFONTS.jpg`, existía espacio horizontal ocioso en las tarjetas de especialidad y la VCard flotante.
  - **Solución implementada:** Se incrementó la escala tipográfica de los títulos y textos descriptivos en el menú superior y en la VCard ejecutiva, llenando el espacio disponible con elegancia y máxima legibilidad sin alterar en un solo píxel las dimensiones exteriores de los contenedores ni provocar desbordamientos.
- [x] **Depuración de Comboboxes (Placeholders No Seleccionables):**
  - Las preguntas y textos guía de los selectores (`"¿En qué zona buscas?"`, `"¿Cuándo deseas visitar?"`, `"¿Cuántas habitaciones?"`) se blindaron con los atributos `value="" disabled selected hidden`. De este modo actúan como etiquetas guía informativas y el usuario no puede seleccionarlas por error como valores de búsqueda.
- [x] **Escalado Táctil y Ergonomía Visual en Móviles para Comboboxes:**
  - En la vista móvil (`@media (max-width: 600px)`), se amplió sustancialmente la escala de los comboboxes para evitar forzar la vista: etiquetas elevadas a `1.18rem` con contraste reforzado, textos de selección a `1.35rem` y opciones nativas forzadas a `16px` para prevenir zoom intrusivo de iOS/Android.
- [x] **Transformación del 3er Campo de Búsqueda: "Habitaciones" con Ícono de Cama:**
  - Reemplazo del término `"Alquiler"` por `"Habitaciones"` con ícono `fa-solid fa-bed`.
  - Incorporación de opciones claras de 1 a 4+ habitaciones, además de proyectos de inversión, reflejando con exactitud los parámetros del mercado inmobiliario.
- [x] **Jerarquía Visual Superior Izquierda Optimizada para Móviles:**
  - **Solo en teléfonos (`@media (max-width: 600px)`):** Se ocultó el kicker superior `"EXCLUSIVIDAD Y BLINDAJE"` para evitar redundancia y darle prioridad absoluta al nombre de la marca `INVERSIONES D'ALROC`.
  - Se incorporó un subtítulo único en tipografía romana *Cinzel*: `Exclusividad y blindaje en la compra o venta de tu propiedad.` en una sola línea equilibrada y con remates clásicos.
  - **Escritorio / PC 100% Intacto:** En computadoras de escritorio se preserva la jerarquía original completa de tres niveles (Kicker `EXCLUSIVIDAD Y BLINDAJE`, Título Monumental y Tagline editorial) sin ninguna alteración.
- [x] **Redirección y Actualización del Enlace Secundario del Hero:**
  - Sustitución de `"Cerca de ti >"` por el llamado de conversión directo:  
    `Publica tu propiedad hoy y encuentra compradores >`
  - Se conserva íntegra la misma tipografía (*Plus Jakarta Sans*), estilos, píldora translúcida en móvil y animación de subrayado progresivo en hover (`.airbnb-secondary-link::after`), enlazando directamente al ancla `#Legado` de la Sección 4.
- [x] **Depuración de la Brújula Flotante de Recorrido (*Scroll Compass Dock*):**
  - Se suprimieron los prefijos numéricos (`01 `, `02 `, `03 `, `04 `) en los labels interactivos del dock lateral derecho.
  - Ahora muestra las palabras solas con tipografía pura: **Inicio**, **Portafolio**, **Servicios**, **Asesora**.
- [x] **Exploración Tipográfica de la Marca D'ALROC (`.top-shape-title`):**
  - Migración del título institucional `INVERSIONES D'ALROC` a tipografía moderna **Plus Jakarta Sans** (peso 800), unificando su identidad con la barra de búsqueda y elementos interactivos, y preservando el acento *ALROC* en cursiva dorada.
- [x] **Aplicación de Cinzel al Subtítulo Institucional (`.top-shape-tagline` & `.tagline-mobile`):**
  - Se configuró la tipografía **Cinzel** (peso 600, espaciado clásico `0.03em`) exclusivamente para el subtítulo/lema editorial (`En la compra o venta de tu propiedad` en PC y `Exclusividad y blindaje en la compra o venta de tu propiedad.` en móvil), aportando un acabado solemne y arquitectónico de inspiración imperial.

---

### 🎨 Código Oficial de Colores del Proyecto Inversiones D'ALROC
| Nombre del Color | Código Hex | Variable CSS | Aplicación Principal |
| :--- | :--- | :--- | :--- |
| **Verde Esmeralda Imperial** | `#1D3D2E` | `--emerald-column` | Fondo de tarjetas nobles, botones principales y acentos de prestigio |
| **Verde Esmeralda Profundo** | `#142B20` | Degradado | Sombra base en degradados de tarjetas y botones victorianos |
| **Verde Mármol AlRoc** | `#2D5446` | `--emerald-medium` | Acentos arquitectónicos y estados activos |
| **Oro Antiguo Victoriano** | `#B88E3E` | `--gold` | Marcos, filigranas, bordes de tarjetas y divisores heráldicos |
| **Hoja de Oro Bruñido** | `#D4B062` | `--gold-light` | Iconos, rótulos luminosos, títulos en hover y filetes interiores |
| **Bronce Orfebre Clásico** | `#8C6820` | `--gold-dark` | Capitulares, subtítulos y grabados |
| **Pan de Oro Sagrado / Corona** | `#F3C64D` | `--vitral-gold` | Acentos de corona y orfebrería de alta jerarquía |
| **Pergamino Marfil Cálido** | `#F6F1E7` | `--bg-canvas` | Fondo arquitectónico general de secciones (mármol/pergamino) |
| **Superficie Marfil Pura** | `#FCFAF6` | `--bg-surface` | Superficie pura interior de modales y cajas claras |

---

### 💼 Fase 4: Sección 4 — Formulario de Captación y Consignación ("Vende tu Propiedad")
**Objetivo:** Canalizar y convertir a propietarios e inversionistas que desean comercializar su inmueble a través de Inversiones D'ALROC y la Lcda. Claudia Di Diomede.

- [x] **Enlace Directo desde el Hero:** Acceso inmediato mediante `Publica tu propiedad hoy y encuentra compradores >` apuntando a la Sección 4 (`#Legado`).
- [ ] **Estructura del Formulario Neoclásico Editorial:**
  - Diseño en tarjeta marfil con filetes en oro bruñido y remates arquitectónicos.
  - Campos esenciales de captación sin fricción:
    1. **Nombre y Apellido del Propietario / Representante.**
    2. **Teléfono / WhatsApp de Contacto.**
    3. **Tipo de Propiedad:** Villa / Casa, Apartamento, Town-House, Terreno / Parcela, Local Comercial.
    4. **Ubicación en Isla de Margarita:** (Pampatar, Playa El Ángel, Costa Azul, Jorge Coll, Playa El Agua, Porlamar, Juan Griego, etc.).
    5. **Dimensiones Aproximadas (m²)** y número de habitaciones/baños.
    6. **Rango de Precio Estimado o Solicitud de Avalúo Legal.**
    7. **Observaciones / Amenidades Destacadas** (piscina, vista al mar, pozo de agua, planta eléctrica).
- [ ] **Botón de Conversión WhatsApp Final:**
  - Una vez completados los datos, el botón de acción principal se habilita con el llamado:  
    `ENVIAR FORMULARIO Y HABLAR CON LA LCDA. CLAUDIA PARA EMPEZAR A VENDER SU PROPIEDAD`
  - Al pulsar, compila la información en un mensaje formal estructurado con emojis institucionales hacia el WhatsApp `+58 414 790-7819`.

---

### ✈️🏛️ Propuestas Arquitectónicas: Sección 3 vs. Sección 4 & "Hospedaje y Boletería"
Actualmente el proyecto cuenta con dos secciones intermedias preparadas en el markup:
- **Sección 3:** `<section class="Opiniones" id="Opiniones">`
- **Sección 4:** `<section class="Legado" id="Legado">` (hacia donde apunta el botón *"Publica tu propiedad hoy y encuentra compradores >"*).

Para integrar con éxito los servicios de **Turismo, Hospedaje y Boletería** sin descuidar el nicho de Bienes Raíces y Venta de Propiedades, se plantean las siguientes alternativas:

#### 🌟 Opción Recomendada: Sección 3 Bimodal (Hospedaje & Boletería) + Sección 4 (Consignación & Asesora)
1. **Sección 3 (`#Opiniones` -> Renombrable a `#Experiencias` o `#Turismo`): "Estadías Exclusivas & Concierge de Viajes":**
   - **Tarjeta A — Hospedaje Vacacional VIP en Margarita:** Alquileres temporales en villas y apartamentos de lujo frente al mar.
   - **Tarjeta B — Boletería & Traslados Ejecutivos:** Emisión de boletos aéreos y marítimos (ferry / vuelos nacionales e internacionales a Porlamar), recepción VIP y chofer privado en la isla.
   - **Botón de Acción:** *"Cotizar Estadía o Vuelo con Concierge D'ALROC"*.
2. **Sección 4 (`#Legado`): "Consignación de Propiedades & Blindaje con la Lcda. Claudia Di Diomede":**
   - Abarca el formulario de captación para vendedores conectado a WhatsApp (`ENVIAR FORMULARIO Y HABLAR CON LA LCDA. CLAUDIA PARA EMPEZAR A VENDER SU PROPIEDAD`).
   - Acompañado del perfil de respaldo legal de la Lcda. Claudia (trayectoria, colegiatura y sello de blindaje inmobiliario).

#### 💡 Opción Alternativa: Pestañas / Selector Interactivo en Sección 4
- Si la Sección 3 se reserva para testimonios o proyectos de construcción, la Sección 4 puede tener un interruptor de dos vistas:
  - **Pestaña 1: "Quiero Vender mi Propiedad"** (Formulario de consignación).
  - **Pestaña 2: "Hospedaje & Boletería Vacacional"** (Solicitud de fechas de viaje, personas y reservas de vuelos/alojamiento temporal).

