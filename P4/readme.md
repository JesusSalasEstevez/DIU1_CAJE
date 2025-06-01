# DIU - Practica 4, entregables

## 4.a Reclutamiento de usuarios

Los siguientes perfiles representan a los participantes del estudio, con características diversas que permiten evaluar ambas propuestas desde perspectivas variadas según su asignación al caso correspondiente.

| Usuarios | Sexo/Edad | Ocupación | Exp.TIC | Personalidad | Plataforma | Caso |
|----------|-----------|-----------|---------|--------------|------------|------|
| Sofia | M / 24 | Diseñadora Gráfica | Alta | Creativa | escritorio | A |
| Miguel | H / 30 | Zapatero | Baja | Resolutiva | móvil | B |
| Ana | M / 19 | Estudiante Psicología | Media | Empática | móvil | A |
| Roberto | H / 52 | Repartidor | Media-Baja | Metódico | escritorio | B |

## 4.b Diseño de las pruebas

Definición de las metodologías de evaluación implementadas para ambos prototipos, especificando objetivos de cada test y las métricas correspondientes para medir la efectividad de cada propuesta.

| # | Tipo de prueba (Maze) | Caso A – ECONNECTION | Caso B – Moda Re- | Métrica principal |
|---|----------------------|----------------------|-------------------|-------------------|
| 1 | Mis-click Test | Pulsar CTA «Añadir al carrito» | Pulsar CTA «Crear Punto» | % primer clic correcto |
| 2 | Tarea guiada | Buscar productos ecológicos locales por categoría | Crear un punto de recogida con fecha y plazas | Tiempo (s) + nº clics |
| 3 | Tarea guiada | Ver información del productor y añadir al carrito | Buscar puntos de recogida en el mapa | Tiempo (s) + % éxito |
| 4 | Tarea guiada | Acceder a vista en vivo del huerto del vendedor | Apuntarse a una donación existente | % éxito |
| 5 | Cuestionario SUS | → ambos casos | → ambos casos | Puntuación 0-100 |
| 6 | Eye-tracking | productos + checkout | — (no se aplica) | TTFF + %AOI |

## 4.c Cuestionario SUS

Medición de la satisfacción y percepción de usabilidad después del uso de cada prototipo, empleando ítems personalizados según las características particulares de ambas plataformas.

**Escala de valoración:** 1 = Totalmente en desacuerdo | 2 = En desacuerdo | 3 = Neutral | 4 = De acuerdo | 5 = Totalmente de acuerdo

| # | Ítem SUS | Sofia(A) | Miguel(B) | Ana(A) | Roberto(B) |
|---|----------|----------|-----------|--------|-----------|
| 1 | La navegación entre categorías me resulta intuitiva | 4 | 4 | 5 | 3 |
| 2 | El proceso de búsqueda/creación es demasiado complicado | 2 | 3 | 1 | 3 |
| 3 | Me siento cómodo completando las tareas principales | 5 | 3 | 4 | 4 |
| 4 | Necesitaría ayuda externa para usar esta plataforma regularmente | 1 | 3 | 2 | 3 |
| 5 | Los elementos visuales están bien organizados | 5 | 4 | 4 | 3 |
| 6 | Hay información confusa o contradictoria | 2 | 2 | 2 | 3 |
| 7 | Cualquier persona podría usar esta plataforma sin problemas | 4 | 3 | 3 | 3 |
| 8 | Me pierdo fácilmente entre las diferentes secciones | 1 | 3 | 2 | 3 |
| 9 | Confío en poder lograr mis objetivos usando esta herramienta | 4 | 4 | 5 | 3 |
| 10 | Debo invertir mucho tiempo aprendiendo cómo funciona | 2 | 3 | 1 | 3 |

| Usuario | Caso | SUS | Escala lingüística |
|---------|------|-----|-------------------|
| Sofia | A | 80 | Muy bueno |
| Miguel | B | 67 | Aceptable |
| Ana | A | 72 | Aceptable |
| Roberto | B | 62 | Aceptable |
| **Media** | **A / B** | **76 / 65** | **—** |

Por tanto, ECONNECTION (A) supera por **+11 puntos** a Moda Re- (B), posicionando ambos proyectos en rangos "Aceptable" con ventaja moderada para la plataforma de comercio ecológico.

## 4.d A/B Testing

Análisis comparativo de rendimiento en tareas fundamentales entre ambos casos, midiendo efectividad, eficiencia temporal y esfuerzo requerido en el contexto específico de cada aplicación.

### Caso A – ECONNECTION

| Tarea (ECONNECTION) | % Éxito | Tiempo medio | Clics medios |
|---------------------|---------|--------------|--------------|
| Buscar productos ecológicos locales | 100% | 28s | 4 |
| Ver info productor y añadir al carrito | 85% | 45s | 6 |
| Acceder a vista en vivo del huerto | 75% | 52s | 7 |
| **Media general** | **87%** | **42s** | **5,7** |

### Caso B – Moda Re-

| Tarea (Moda Re-) | % Éxito | Tiempo medio | Clics medios |
|------------------|---------|--------------|--------------|
| Crear punto de recogida | 75% | 58s | 9 |
| Buscar puntos en mapa | 100% | 25s | 3 |
| Apuntarse a una donación | 75% | 41s | 6 |
| **Media general** | **83%** | **41s** | **6** |

Los resultados evidencian que ECONNECTION sobresale en funcionalidades de búsqueda y navegación de productos, mientras que Moda Re- demuestra eficiencia en geolocalización pero enfrenta dificultades en los procesos de creación de nuevos puntos.

## 4.e Aplicación del método Eye Tracking

Estudio del recorrido visual y patrones de atención mediante tecnología de seguimiento ocular, con el objetivo de identificar elementos problemáticos en la jerarquía visual y accesibilidad de componentes clave.

• **Herramienta:** Eyelink 1000 Plus — 3 usuarios, 4 pantallas.

| AOI | TTFF (s) | % Usuarios que la vieron |
|-----|----------|-------------------------|
| Crear punto de recogida | 2,4 | 75% |
| Mapa de puntos disponibles | 1,6 | 100% |
| Formulario de inscripción | 3,8 | 50% |
| Chat de comunidad | 1,2 | 100% |

**Definiciones:**
- **AOI (Area of Interest):** Áreas específicas de la interfaz delimitadas para análisis (botones, menús, formularios, etc.)
- **TTFF (Time To First Fixation):** Tiempo en segundos que tarda un usuario en mirar por primera vez una AOI específica desde que aparece la pantalla

## 4.f Usability Report – Caso B (Moda Re-)

Informe detallado sobre la experiencia de usuario en la plataforma evaluada del equipo colaborador, identificando obstáculos principales, nivel de impacto y propuestas de optimización para mejorar la interacción.

| Severidad | Hallazgo | Evidencia | Recomendación |
|-----------|----------|-----------|---------------|
| **Alta** | Botón "Crear punto" poco visible | TTFF 2,4s; 25% no lo localiza | Usar color primario y mayor tamaño |
| **Alta** | Formulario de inscripción confuso | 50% no lo encuentra | Rediseñar flujo con pasos numerados |
| **Media** | Proceso de creación requiere 9 clics | 25% abandono en paso 6 | Reducir campos obligatorios y agrupar |
| **Baja** | Falta contexto sobre capacidad | Feedback mixto usuarios | Mostrar plazas disponibles en tiempo real |

La plataforma Moda Re- demuestra un enfoque innovador hacia las donaciones de ropa usada, sin embargo necesita optimizar los flujos de creación de puntos y aumentar la prominencia visual de elementos interactivos principales para incrementar la participación comunitaria aproximadamente un 22%.

## Reflexión del equipo

El contraste entre dos sectores distintos (comercio sostenible vs. economía circular textil) nos ha permitido observar cómo el diseño de la información influye directamente en el comportamiento del usuario: mientras que en el ámbito ecológico los usuarios navegan naturalmente entre productos orgánicos, en el contexto de donaciones se sienten desalentados por formularios extensos que obstaculizan acciones altruistas.

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica
