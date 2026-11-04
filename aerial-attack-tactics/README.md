<a id="inicio"></a>

# Manual de Tácticas de Ataque Aéreo
## Volumen I — Aeronaves de Ala Rotativa

**Regimiento de Operaciones Aero Navales (ROAN)**  
**Clan:** FEL  
**Versión:** 0.2 — Diagramas de geometría para perfiles RW  
**Plataforma:** Arma 3  
**Fecha:** 3 de noviembre de 2026  
**Estado:** Borrador doctrinal para simulación y validación de instructores

> **Ámbito de aplicación.** Manual formativo de **simulación militar en Arma 3**, elaborado para estandarizar terminología, selección de aeronaves, geometría de vuelo, coordinación de tripulaciones, criterios de seguridad y evaluación de alumnos ROAN. Los perfiles describen conceptos y ejercicios virtuales, no procedimientos de combate utilizables en operaciones reales. Las altitudes, velocidades, distancias, sistemas de armas, sensores y reacciones de amenazas deben verificarse en el **modset, mapa, configuración de IA y modelo de vuelo** efectivos de cada sesión. No se proporcionan parámetros destinados a penetrar defensas reales ni instrucciones para atacar blancos reales.

---

<a id="introduccion"></a>
# 1. Introducción

## 1.1 Propósito

Establecer una base doctrinal común para la instrucción, planeación y evaluación del empleo de helicópteros ROAN en misiones virtuales de reconocimiento armado, apoyo aéreo cercano (CAS), ataque simulado, escolta, asalto y supervivencia de aeronaves.

El manual responde, para cada situación de entrenamiento, a las preguntas: **¿qué misión?, ¿qué plataforma?, ¿qué perfil de vuelo?, ¿qué coordinación?, ¿qué riesgos?, ¿cuándo abortar? y ¿cómo evaluar?**

## 1.2 Alcance

- **Incluido:** exclusivamente **ala rotativa**, conforme al inventario oficial ROAN; perfiles y geometrías de vuelo; clasificación de amenazas y blancos virtuales; CRM; comunicaciones; ejercicios y rúbricas.
- **Reservado:** Volumen II — Aeronaves de Ala Fija. No se desarrolla en esta edición.
- **Excluido:** empleo operativo real de armamento, métodos para eludir sistemas antiaéreos reales, datos balísticos de ataque, vulnerabilidades explotables de defensas y parámetros reales para producir daños.

## 1.3 Jerarquía de referencias

1. **Catálogo ROAN:** define plataformas autorizadas y sus funciones.
2. **Doctrina pública de aviación militar:** define conceptos y terminología general.
3. **Documentación de mods:** define sistemas implementados en Arma 3.
4. **Pruebas ROAN:** establecen valores y procedimientos reproducibles en el servidor.

**Regla de prevalencia:** ninguna capacidad atribuida a la aeronave real debe considerarse disponible en Arma 3 hasta comprobarla en la versión concreta del addon.

## 1.4 Convenciones documentales

| Marca | Significado |
|---|---|
| **[DOCTRINA]** | Concepto doctrinal público de referencia. |
| **[REFERENCIA]** | Característica de la aeronave real; no equivale a comportamiento de mod. |
| **[MOD]** | Función o limitación atribuida al addon, sujeta a revisión de versión. |
| **[ROAN]** | Convención o ejercicio propuesto para el clan; requiere aprobación del instructor. |
| **[POR VALIDAR]** | Parámetro, funcionalidad o estándar pendiente de prueba. |

## 1.5 Reglas generales de seguridad de simulación

- El piloto al mando conserva la responsabilidad sobre control de vuelo y prevención de impacto contra el terreno (CFIT).
- Ninguna maniobra se considera satisfactoria si el blanco resulta alcanzado, pero la aeronave se pierde por falta de control.
- El instructor configura las amenazas y define límites ficticios de altitud, velocidad y distancia antes del ejercicio.
- Los alumnos deben anunciar **ABORT** ante pérdida de referencias, degradación de control, identificación dudosa o presencia virtual de fuerzas amigas en una zona de ataque no autorizada.
- Los perfiles ofensivos se enseñan primero con objetivos inertes y armamento deshabilitado o simulado.

[↑ Volver al inicio](#inicio) · [↑ Volver al índice](#indice)

---

<a id="indice"></a>
# 2. Contenido

- [1. Introducción](#introduccion)
- [2. Contenido](#indice)
- [3. Fundamentos de vuelo táctico](#fundamentos)
  - [3.1 Terminología de vuelo y geometría](#terminologia-vuelo)
  - [3.2 Fases de una misión simulada](#fases)
  - [3.3 Riesgo, identificación y aborto](#gestion-riesgo)
- [4. Inventario y clasificación de ala rotativa ROAN](#inventario)
  - [4.1 Inventario autorizado](#inventario-autorizado)
  - [4.2 Matriz de rol y adecuación](#matriz-roles)
  - [4.3 Responsabilidades por tripulación](#tripulacion)
- [5. Catálogo técnico de perfiles y maniobras](#catalogo)
  - [5.1 Matriz general de perfiles](#matriz-perfiles)
  - [5.2 RW-01 — Masked / Unmask Profile](#rw01)
  - [5.3 RW-02 — Bob-Up Profile](#rw02)
  - [5.4 RW-03 — Pop-Up Profile](#rw03)
  - [5.5 RW-04 — Running Fire Profile](#rw04)
  - [5.6 RW-05 — Diving Fire Profile](#rw05)
  - [5.7 RW-06 — Close-In Gun Run / Strafing](#rw06)
  - [5.8 RW-07 — Rocket Attack Profile](#rw07)
  - [5.9 RW-08 — Standoff Guided Engagement](#rw08)
  - [5.10 RW-09 — Battle Position Engagement](#rw09)
  - [5.11 RW-10 — Successive Battle Positions](#rw10)
  - [5.12 RW-11 — Defilade Position Profile](#rw11)
  - [5.13 RW-12 — Offset Attack Profile](#rw12)
  - [5.14 RW-13 — Re-Attack / Racetrack Pattern](#rw13)
  - [5.15 RW-14 — Shooter–Cover Coordination](#rw14)
  - [5.16 RW-15 — Alternating Section Profile](#rw15)
  - [5.17 RW-16 — Armed Reconnaissance / Handoff](#rw16)
  - [5.18 RW-17 — Escort Threat Response](#rw17)
  - [5.19 RW-18 — JTAC-Controlled CAS](#rw18)
  - [5.20 RW-19 — Break Contact / Egress](#rw19)
  - [5.21 RW-20 — Terrain-Masked Defensive Flight](#rw20)
  - [5.22 RW-21 — Maneuver Kill: concepto y CFIT](#rw21)
  - [5.23 RW-22 — Holding Area / Attack Position](#rw22)
- [6. Aplicación por amenaza antiaérea virtual](#amenazas)
  - [6.1 AAA de adquisición visual](#aaa)
  - [6.2 Radar y SAM de largo alcance](#sam)
  - [6.3 MANPADS / amenazas infrarrojas](#manpads)
- [7. Aplicación por tipo de blanco virtual](#blancos)
  - [7.1 Blindados y tanques](#blindados)
  - [7.2 Infantería y posiciones fortificadas](#infanteria)
- [8. Aplicación por distancia de enganche](#distancia)
  - [8.1 Standoff](#standoff)
  - [8.2 Distancia intermedia](#intermedia)
  - [8.3 Close-in](#closein)
- [9. Operaciones coordinadas y comunicaciones](#coordinacion)
- [10. Supervivencia, emergencias y abortos](#supervivencia)
- [11. Programa de entrenamiento ROAN](#entrenamiento)
  - [11.1 Progresión](#progresion)
  - [11.2 Ejercicios](#ejercicios)
  - [11.3 Rúbrica](#rubrica)
- [12. Plantilla de ficha de táctica ROAN](#plantilla)
- [13. Glosario](#glosario)
- [14. Referencias y fuentes](#referencias)
- [15. Registro de validaciones y control documental](#control)

[↑ Volver al inicio](#inicio)

---

<a id="fundamentos"></a>
# 3. Fundamentos de vuelo táctico

<a id="terminologia-vuelo"></a>
## 3.1 Terminología de vuelo y geometría

| Concepto | Definición para instrucción ROAN |
|---|---|
| **AGL** | Altura sobre el terreno inmediatamente inferior a la aeronave (*Above Ground Level*). |
| **MSL** | Altitud referida al nivel medio del mar (*Mean Sea Level*). |
| **Low-Level Flight** | Vuelo a cota reducida, conforme a límites establecidos en misión. |
| **Contour Flight** | Vuelo que sigue de forma general el relieve y sus cambios de elevación. |
| **NOE** | *Nap-of-the-Earth*: vuelo muy próximo al relieve, con atención continua al margen de seguridad y obstáculos. No significa volar sin márgenes. |
| **Terrain Masking** | Uso del relieve para interrumpir línea de visión en un escenario virtual. |
| **Unmasking** | Transición desde una zona oculta a otra desde la cual se dispone de observación. |
| **Battle Position (BP)** | Área virtual predefinida desde la que se observa, coordina o simula una acción. |
| **Holding Area (HA)** | Área de espera y coordinación previa a una fase de misión. |
| **Ingress / Egress** | Trayecto de ingreso y salida de la zona de ejercicio. |
| **Attack Axis** | Dirección general asignada para una ejecución virtual, sujeta a deconfliction. |
| **Exposure Time** | Tiempo durante el cual la aeronave queda observable para el sistema de simulación. |
| **BDA** | *Battle Damage Assessment*: evaluación de resultados en el simulador. |

**[ROAN]** Las geometrías se representarán en dos vistas: **perfil lateral** (AGL, obstáculos, energía) y **planta** (rutas, puntos, sectores, límites de seguridad). Todas las cifras exactas permanecerán como **[POR VALIDAR]** hasta probarse en el mod.

<a id="fases"></a>
## 3.2 Fases de una misión simulada

```text
BRIEFING → PRE-FLIGHT → TAXI / TAKEOFF → INGRESS → HOLD / OBSERVE
          → AUTHORIZATION → SIMULATED ACTION → EGRESS
          → RECOVERY → DEBRIEF / BDA
```

**Briefing:** identificar mapa, meteorología, carga, tripulación, zona de exclusión, amenazas virtuales y criterios de aborto.  
**Ingress:** navegar por puntos aprobados sin salir de los límites del ejercicio.  
**Hold/Observe:** confirmar posición y sector con el instructor u operador de misión.  
**Authorization:** confirmar objetivo virtual y autorización pertinente antes de cualquier acción.  
**Action:** ejecutar la geometría entrenada sin rebasar los límites del escenario.  
**Egress:** recuperar navegación, separación y estado normal de vuelo.  
**Debrief:** analizar trazado, control de vuelo, comunicaciones, identificación y seguridad.

<a id="gestion-riesgo"></a>
## 3.3 Riesgo, identificación y aborto

**Condiciones obligatorias de aborto [ROAN]:** pérdida de control, desorientación, riesgo de colisión, comunicación esencial perdida, blanco no identificado, friendly fire potencial, incumplimiento de límites de instructor o anomalía crítica de la aeronave virtual.

```text
¿Referencia de vuelo y control adecuados?
 ├─ NO → ABORT / RECOVERY
 └─ SÍ → ¿Objetivo y autorización confirmados?
          ├─ NO → HOLD / RE-IDENTIFY
          └─ SÍ → CONTINUAR EJERCICIO SEGÚN BRIEFING
```

[↑ Volver al índice](#indice)

---

<a id="inventario"></a>
# 4. Inventario y clasificación de ala rotativa ROAN

**Fuente de autoridad:** [Catálogo Operacional de Aeronaves ROAN, versión 0.2](https://github.com/lockdawn/arma3-fel-mod-manifest/tree/main/ROAN). El catálogo establece que las aeronaves no incluidas no están autorizadas de manera ordinaria.

<a id="inventario-autorizado"></a>
## 4.1 Inventario autorizado

| Aeronave | Facción catálogo | Rol principal para este manual | MOD |
|---|---|---|---|
| H-60 Series | BLUFOR | Utilidad, transporte y asalto; configuración armada condicional | [Hatchet H-60 Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605) |
| AH-1Z Viper | BLUFOR | Ataque dedicado / CAS / escolta | [AH-1Z Viper](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780) |
| AH-6M Little Bird | BLUFOR | Ataque ligero / CAS | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| MH-6M Little Bird | BLUFOR | Inserción / operaciones especiales, no ataque dedicado | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| CH-53E Super Stallion | BLUFOR | Transporte pesado / asalto anfibio | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| MH-47G Chinook | BLUFOR | Transporte pesado / asalto especial | [Pegasus Systems MH-47G](https://steamcommunity.com/sharedfiles/filedetails/?id=3805899171) |
| Mi-8MT Hip | OPFOR | Transporte / utilidad; ataque condicional según carga disponible | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| Mi-24V Hind-E | OPFOR | Ataque / transporte armado híbrido | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| Mi-28N Havoc | OPFOR | Ataque dedicado | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| Ka-52 Alligator | OPFOR | Ataque / reconocimiento armado | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |

> **Control de alcance:** AH-64 Apache y OH-58 Kiowa **no aparecen** en el inventario ROAN consultado. No se asignarán como plataformas autorizadas de ejercicios hasta que sean incorporadas formalmente al catálogo. Tampoco se asumirá que H-60/Mi-8 incluyen pods sin verificar variante y configuración.

<a id="matriz-roles"></a>
## 4.2 Matriz de rol y adecuación

**Leyenda:** ✅ rol principal · ⚠️ condicionado a variante/configuración/misión · — no corresponde.

| Plataforma | Ataque dedicado | Reconocimiento armado | CAS virtual | Escolta | Transporte/asalto | Coordinación CPG |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| AH-1Z | ✅ | ⚠️ | ✅ | ✅ | — | ✅ |
| Mi-28N | ✅ | ⚠️ | ✅ | ✅ | — | ✅ |
| Ka-52 | ✅ | ✅ | ✅ | ✅ | — | ✅ |
| AH-6M | ⚠️ | ⚠️ | ✅ | ⚠️ | — | ⚠️ |
| Mi-24V | ✅ | ⚠️ | ✅ | ✅ | ⚠️ | ✅ |
| H-60 Series | — | ⚠️ | ⚠️ | ⚠️ | ✅ | ⚠️ |
| Mi-8MT | — | ⚠️ | ⚠️ | ⚠️ | ✅ | ⚠️ |
| MH-6M | — | — | — | — | ✅ | — |
| CH-53E | — | — | — | — | ✅ | — |
| MH-47G | — | — | — | — | ✅ | — |

<a id="tripulacion"></a>
## 4.3 Responsabilidades por tripulación

| Función | Responsabilidad primaria en simulación |
|---|---|
| **Pilot / Aircraft Commander** | Control de vuelo, altura, velocidad, navegación inmediata, margen con obstáculos, autorización de aborto. |
| **Copilot / CPG / Gunner** | Observación y sensores disponibles; comunicaciones de misión según reparto CRM; identificación de blanco virtual; gestión de sistemas asignados. |
| **Flight Lead** | Briefing, ruta, separación de sección, coordinación con controlador y cambios autorizados del plan. |
| **Wingman** | Seguimiento de formación, apoyo visual, anuncio de anomalías, preservación de separación y recuperación. |
| **JTAC virtual** | Coordinación y autorización de acciones CAS dentro de reglas ficticias del escenario. |
| **Instructor / Zeus** | Configuración de amenazas, controles, límites, observación y calificación. |

**Regla [ROAN]:** el reparto definitivo depende de las funciones efectivamente implementadas por cada addon. Los procedimientos de jettison, contramedidas y gestión de armas no se asignarán a un asiento sin comprobar los controles del mod.

[↑ Volver al índice](#indice)

---

<a id="catalogo"></a>
# 5. Catálogo técnico de perfiles y maniobras

## 5.0 Método de lectura

Cada perfil incluye **nombre técnico, propósito, geometría, plataformas, flujo de ingreso/acción/salida, coordinación y criterios de evaluación**. Las geometrías son **descriptivas**, no consignas de ataque real. La ficha completa estandarizada se encuentra en el [capítulo 12](#plantilla).

**Parámetros ROAN de vuelo:** en todas las fichas, la banda **AGL**, velocidad de ejecución, separación y distancia de enganche son **[POR VALIDAR]** mediante prácticas en Arma 3; no se extrapolan valores reales. La tripulación mantendrá los márgenes de vuelo establecidos por el instructor.

<a id="matriz-perfiles"></a>
## 5.1 Matriz general de perfiles

| ID | Perfil | Tipo | Plataforma de enseñanza sugerida |
|---|---|---|---|
| RW-01 | Masked / Unmask | Observación desde cobertura | AH-1Z, Ka-52, Mi-28N |
| RW-02 | Bob-Up | Cambio vertical breve de perspectiva | AH-1Z, Ka-52 |
| RW-03 | Pop-Up | Transición ascenso/observación/recuperación | AH-1Z, Mi-28N |
| RW-04 | Running Fire | Pasada con trayectoria de avance | AH-6M, Mi-24V |
| RW-05 | Diving Fire | Pasada con descenso controlado | AH-1Z, Mi-24V |
| RW-06 | Close-In Gun Run | Pasada cercana simulada | AH-6M, AH-1Z |
| RW-07 | Rocket Profile | Familiarización con perfil de cohetes virtuales | AH-6M, Mi-24V |
| RW-08 | Standoff Guided | Sensores, asignación y disparo virtual | AH-1Z, Mi-28N, Ka-52 |
| RW-09 | Battle Position | Gestión de posición designada | AH-1Z, Mi-28N |
| RW-10 | Successive BPs | Transición entre posiciones predefinidas | Ka-52, AH-1Z |
| RW-11 | Defilade | Observación con relieve interpuesto | Todas según rol |
| RW-12 | Offset | Geometría lateral de ruta | AH-1Z, AH-6M |
| RW-13 | Re-Attack / Racetrack | Patrón de reingreso sujeto a control | AH-6M, Mi-24V |
| RW-14 | Shooter–Cover | Reparto de tareas entre aeronaves | AH-1Z, Mi-28N |
| RW-15 | Alternating Section | Alternancia y separación | AH-1Z, Ka-52 |
| RW-16 | Armed Recon / Handoff | Identificación y transferencia | Ka-52, AH-6M |
| RW-17 | Escort Threat Response | Protección de transporte virtual | AH-1Z, Mi-24V, AH-6M |
| RW-18 | JTAC CAS | Control de comunicaciones CAS | AH-1Z, Mi-28N, Ka-52 |
| RW-19 | Break Contact | Aborto y separación | Todas |
| RW-20 | Terrain-Masked Defensive | Vuelo defensivo de referencia | Todas |
| RW-21 | Maneuver Kill / CFIT | Análisis de límite de maniobra | Todas (sin armamento) |
| RW-22 | Holding Area / Attack Position | Coordinación antes de la acción | Todas según rol |

### Convención común de fases

```text
INGRESS (navegar y estabilizar)
       ↓
SETUP (identificar, comunicar, autorizar)
       ↓
SIMULATED ACTION (ejecutar geometría aprobada)
       ↓
EGRESS (restablecer vuelo y separación)
       ↓
DEBRIEF (analizar trazas y comunicaciones)
```

<a id="rw01"></a>
## 5.2 RW-01 — Masked / Unmask Profile

- **Descripción:** transición controlada entre observación oculta por relieve y observación despejada, dentro de un escenario diseñado por el instructor.
- **Geometría:** referencia topográfica cercana; AGL y velocidad fijadas en briefing, con margen positivo frente a obstáculos. Diferenciar claramente **enmascaramiento** y **aproximación a colisión**.



```text
VISTA LATERAL — MASK / UNMASK
            REFERENCIA VISIBLE ●
                               ⋮
         CRESTA      /‾‾‾‾‾‾‾‾
                    /
A ● ───────────────/ ───────────→ B ●
  OBSERVACIÓN OCULTA         OBSERVACIÓN DESPEJADA

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, Mi-28N, Ka-52; H-60 únicamente para observación y navegación de su rol.
- **Ingreso:** aproximarse a una posición de observación aprobada, sin salir de su corredor.
- **Acción:** anunciar transición, comprobar visibilidad de un marcador de entrenamiento e identificarlo sin empleo real de armamento.
- **Salida:** regresar a un sector autorizado y confirmar recuperación de referencias.
- **Evaluación:** control, identificación, disciplina de comunicaciones y no infringir límites de terreno.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw02"></a>
## 5.3 RW-02 — Bob-Up Profile

- **Descripción:** ejercicio de transición vertical breve desde posición de espera hacia línea de observación y vuelta a vuelo estabilizado.
- **Geometría:** desplazamiento vertical representado por puntos de referencia; AGL/velocidad **[POR VALIDAR]** en Arma 3.



```text
VISTA LATERAL — BOB-UP
          ● OBSERVACIÓN
          ↑
          │ ASCENSO
  ESPERA ●
          │ DESCENSO
          ↓
          ● RECUPERACIÓN ESTABILIZADA

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, Ka-52, Mi-28N, siempre que el mod permita control suficientemente preciso.
- **Ingreso:** estabilizarse en posición virtual previamente aprobada.
- **Acción:** observar un objetivo **inerte**, reportar identificación y mantener orientación de vuelo.
- **Salida:** recuperar configuración de vuelo estable y posición de seguridad.
- **Evaluación:** estabilidad, actitud, avisos de tripulación y ausencia de pérdida de control.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw03"></a>
## 5.4 RW-03 — Pop-Up Profile

- **Descripción:** secuencia conceptual de **Ingress → The Pop → Apex/Roll-In → Dive & Release (simulado) → Escape/Recovery**, empleada como ejercicio de transición de energía, orientación y coordinación.
- **Geometría:** ascenso respecto a un tramo de ingreso, transición en ápice y descenso/recuperación hacia corredor seguro. El diagrama es conceptual, **no representa un ángulo o altura de ataque recomendados**.

```text
                APEX / ROLL-IN
                       ▲
                      / \
                     /   \    RECOVERY
INGRESS ────────────/     \──────────────→ EGRESS
               THE POP       (marcador de acción virtual)

       [Altura, velocidad y distancias]
```

- **Recomendadas:** AH-1Z, Mi-28N, Ka-52; AH-6M solo en ejercicio simplificado autorizado.
- **Ingreso:** verificar punto de referencia y corredor de entrenamiento.
- **Acción:** anunciar las fases, mantener control durante la transición y confirmar un marcador en el simulador; fase *release* sin munición en la enseñanza inicial.
- **Salida:** recuperar vuelo y regresar al corredor de salida.
- **Evaluación:** continuidad de trayectoria, control de energía, respeto de límites, reconocimiento de puntos y comunicación.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw04"></a>
## 5.5 RW-04 — Running Fire Profile

- **Descripción:** perfil de referencia en el que la aeronave conserva movimiento de avance durante una pasada ficticia.
- **Geometría:** trayectoria de vuelo progresiva y delimitada; el instructor establece altitud, velocidad y corredor separado de fuerzas amigas virtuales.



```text
VISTA SUPERIOR — RUNNING FIRE
INGRESS ● ──────────────────────→ ● EGRESS
          CORREDOR DE VUELO
                    ◇ MARCADOR VIRTUAL
        (MOVIMIENTO DE AVANCE CONTINUO)

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-6M y Mi-24V; AH-1Z según carga del mod.
- **Ingreso:** alinearse con un corredor señalizado en el mapa de entrenamiento.
- **Acción:** observar y confirmar marcador objetivo; registrar la pasada con disparo deshabilitado o sobre blanco de práctica autorizado.
- **Salida:** completar recorrido hacia salida obligatoria, sin viraje improvisado hacia otros participantes.
- **Evaluación:** estabilidad de trayectoria, cumplimiento de corredor y llamada de finalización.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw05"></a>
## 5.6 RW-05 — Diving Fire Profile

- **Descripción:** pasada conceptual con segmento descendente y recuperación, utilizada para enseñar gestión de energía y riesgo de CFIT.
- **Geometría:** tramo de aproximación, cambio de actitud, segmento descendente y recuperación; valores definidos por el instructor para el mapa concreto.



```text
VISTA LATERAL — DIVING FIRE
ENTRADA ●────────────╲
                       ╲ DESCENSO
                        ●────────────→ RECUPERACIÓN
──────────────────────────────────────────────
              LÍMITE SIMULADO DE SEGURIDAD

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z y Mi-24V; otros dedicados solo tras prueba.
- **Ingreso:** confirmar altitud inicial de entrenamiento, horizonte y ruta de escape.
- **Acción:** ejecutar descenso **sin armas en las primeras sesiones** y verificar referencia virtual.
- **Salida:** completar recuperación antes del límite de seguridad marcado y anunciar estado.
- **Evaluación:** reserva de altura, control de velocidad, recuperación y decisión temprana de abortar.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw06"></a>
## 5.7 RW-06 — Close-In Gun Run / Strafing

- **Descripción:** ejercicio de pasada cercana con cañón/ametralladora **en un campo virtual segregado**; no es una recomendación de empleo real.
- **Geometría:** eje señalizado, inicio y fin de zona, límite de sobrevuelo y salida obligatoria; parámetros según validación del mod.



```text
VISTA SUPERIOR — GUN RUN / STRAFING
ENTRADA → ┌──────────────────────────┐ → SALIDA
          │  CORREDOR AUTORIZADO      │
          │           ◇ MARCADOR      │
          └──────────────────────────┘
    FUERZAS AMIGAS FUERA DEL CORREDOR

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-6M, AH-1Z y Mi-24V; Mi-28N/Ka-52 de forma condicional.
- **Ingreso:** verificar que el instructor ha declarado el campo libre de aeronaves y personal virtual aliado.
- **Acción:** ejecutar una pasada de familiarización; fuego virtual solo si ha sido expresamente habilitado.
- **Salida:** abandonar el corredor sin reingreso no autorizado.
- **Evaluación:** identificación, disciplina de línea de tiro virtual, control de aeronave y aviso de aborto.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw07"></a>
## 5.8 RW-07 — Rocket Attack Profile

- **Descripción:** familiarización con la diferencia entre control de trayectoria y representación de un lanzamiento de cohetes dentro de Arma 3.
- **Geometría:** pasada autorizada por corredor de simulación; dispersión y punto de impacto **dependen del arma virtual y del mod**.



```text
VISTA SUPERIOR — ROCKET TRAINING PROFILE
INGRESS ● ──────────→ PUNTO DE OBSERVACIÓN
                            ⋮
                       ◇ ÁREA VIRTUAL
                            ⋮
EGRESS  ● ◀─────────── RECUPERACIÓN
       (SIN REFERENCIAS BALÍSTICAS REALES)

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-6M, Mi-24V; AH-1Z, Mi-28N, Ka-52 según configuración efectiva.
- **Ingreso:** seleccionar carga de entrenamiento y confirmar área virtual exclusiva.
- **Acción:** practicar inicialmente apuntado y llamada de acción sin descarga; posteriormente, bajo supervisión, uso de blancos de tiro inertes.
- **Salida:** terminar pasada hacia área de reunión.
- **Evaluación:** control, cumplimiento de medidas de seguridad y conciencia de dispersión del simulador.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw08"></a>
## 5.9 RW-08 — Standoff Guided Engagement

- **Descripción:** ejercicio de gestión de sensores, asignación de blanco virtual y coordinación de disparo simulado desde una posición separada del objetivo.
- **Geometría:** una posición de observación de entrenamiento y un blanco virtual; **no se prescribe alcance de arma real ni distancia para derrotar AA**.



```text
VISTA SUPERIOR — STANDOFF SIMULADO
┌─────────────────────┐    ┌─────────────────────┐
│  ÁREA DE ESPERA  ●  │    │ ÁREA DEL MARCADOR   │
└─────────────────────┘    │         ◇           │
             OBSERVACIÓN   └─────────────────────┘
[SEPARACIÓN A VALIDAR EN ARMA 3]

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, Mi-28N, Ka-52 y Mi-24V cuando el mod aporte sistemas compatibles.
- **Ingreso:** establecer posición y controles de tripulación.
- **Acción:** detectar, identificar, transmitir y confirmar el blanco en interfaz; simular autorización/empleo.
- **Salida:** finalizar acción, comunicar estado de sistemas y recuperar navegación.
- **Evaluación:** manejo de interfaz del mod, identificación inequívoca y CRM.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw09"></a>
## 5.10 RW-09 — Battle Position Engagement

- **Descripción:** organización de una posición virtual de observación/empleo asignada antes de iniciar la misión.
- **Geometría:** área BP poligonal definida en Eden, con límites de entrada y salida; altura/velocidad según ejercicio.



```text
VISTA SUPERIOR — BATTLE POSITION
   HOLDING AREA ●
             │ TRÁNSITO AUTORIZADO
             ▼
     ┌───────────────────┐
     │ BP DESIGNADA  ●   │
     └───────────────────┘
                ◇ REFERENCIA VIRTUAL

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, Mi-28N, Ka-52.
- **Ingreso:** navegar a la BP asignada.
- **Acción:** identificar sectores marcados y simular trabajo de sensores.
- **Salida:** retirarse por la ruta autorizada cuando el instructor lo indique.
- **Evaluación:** precisión de navegación, conciencia de límites y disciplina de reporte.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw10"></a>
## 5.11 RW-10 — Successive Battle Positions

- **Descripción:** transición entre dos o más BP planificadas; ejercita navegación, coordinación y reposicionamiento.
- **Geometría:** BP-A → tramo de tránsito → BP-B; corredor y separaciones definidos antes del despegue.



```text
VISTA SUPERIOR — SUCCESSIVE BATTLE POSITIONS
BP A ● ───────→ BP B ● ───────→ BP C ●
      TRANSICIÓN PLANIFICADA
        ◇              ◇              ◇
      MARCADORES DE REFERENCIA
[PROGRESIÓN SEGÚN BRIEFING]

[Altitud, velocidad y distancias]
```
- **Recomendadas:** Ka-52, AH-1Z, Mi-28N.
- **Ingreso:** confirmar BP-A y rutas de tránsito.
- **Acción:** completar observación y recibir autorización de traslado.
- **Salida:** trasladarse a BP-B o recuperación final sin improvisar posiciones.
- **Evaluación:** tiempos de comunicación, seguimiento de ruta y deconfliction.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw11"></a>
## 5.12 RW-11 — Defilade Position Profile

- **Descripción:** ejercicio topográfico sobre el significado de encontrarse en una posición protegida de línea de visión por relieve.
- **Geometría:** análisis de cresta, valle y líneas de visión, sin establecer distancias de ocultamiento aplicables a defensas reales.



```text
VISTA LATERAL — DEFILADE
           /\  RELIEVE
          /    \
_________/      \___________
    ● SECTOR CON COBERTURA      ◇ REFERENCIA
        (GEOMETRÍA CONCEPTUAL)

[Altitud, velocidad y distancias]
```
- **Recomendadas:** todas; transporte solo en contexto de navegación/protección.
- **Ingreso:** situarse en una zona de observación sin obstáculos inmediatos.
- **Acción:** comparar visibilidad de marcadores desde posiciones de entrenamiento preestablecidas.
- **Salida:** regresar a un punto seguro.
- **Evaluación:** lectura de mapa y prevención de obstáculos, especialmente cables/árboles del escenario.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw12"></a>
## 5.13 RW-12 — Offset Attack Profile

- **Descripción:** estudio de una ruta no colineal con el eje final del ejercicio; prioridad en orientación y navegación.
- **Geometría:** segmento de tránsito, punto de cambio de rumbo y tramo final fijados en Eden.



```text
VISTA SUPERIOR — OFFSET
              ◇ REFERENCIA
              │ EJE CENTRAL
INGRESS ● ─ ─┼─ ─ ─ ─ ─ ─ →
            \ │
             \─────────────→ EGRESS DESPLAZADO
       (DESPLAZAMIENTO LATERAL)

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, AH-6M, Mi-24V.
- **Ingreso:** localizar waypoint de cambio sin entrar en sectores restringidos.
- **Acción:** realizar transición controlada y confirmar el marcador virtual.
- **Salida:** continuar a recuperación por corredor planificado.
- **Evaluación:** navegación, coordinación y control del rumbo.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw13"></a>
## 5.14 RW-13 — Re-Attack / Racetrack Pattern

- **Descripción:** circuito de entrenamiento de pasadas sucesivas, con autorización independiente para cada vuelta.
- **Geometría:** patrón cerrado de entrenamiento fuera de áreas ocupadas por fuerzas amigas virtuales; altura y separación fijadas por instructor.



```text
VISTA SUPERIOR — RE-ATTACK / RACETRACK
       ┌──────────────────────────┐
       ↑                          ↓
    RETORNO                   OBSERVACIÓN
       ↑                          ↓
       └──────────────────────────┘
   (NUEVA PASADA SOLO CON AUTORIZACIÓN)

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-6M, Mi-24V; otros solo si hay margen de maniobra validado.
- **Ingreso:** incorporarse al circuito en punto designado.
- **Acción:** completar una pasada, comunicar resultado y esperar nueva autorización.
- **Salida:** abandonarlo por salida establecida al finalizar o abortar.
- **Evaluación:** conciencia de tráfico, respeto del circuito y control de reingresos.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw14"></a>
## 5.15 RW-14 — Shooter–Cover Coordination

- **Descripción:** ejercicio de asignación de funciones entre dos helicópteros de ataque, centrado en comunicaciones y conciencia mutua.
- **Geometría:** áreas separadas y rutas independientes aprobadas; separación **[POR VALIDAR]** según servidor y visualización.



```text
VISTA SUPERIOR — SHOOTER / COVER
AERONAVE A ● ──────→ ◇ MARCADOR
              SHOOTER (SIMULADO)
AERONAVE B ● ──────→ ● OBSERVACIÓN
              COVER / APOYO
         COMUNICACIONES A ↔ B

[Altitud, velocidad y distancias]
```
- **Recomendadas:** parejas AH-1Z, Mi-28N o Ka-52.
- **Ingreso:** establecer indicativos y responsabilidades.
- **Acción:** un elemento realiza una acción virtual sobre marcador; el segundo informa tráfico, límites y anomalías desde su sector.
- **Salida:** intercambio de estado y recuperación coordinada.
- **Evaluación:** reparto inequívoco, no interferencia y prevención de colisión.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw15"></a>
## 5.16 RW-15 — Alternating Section Profile

- **Descripción:** alternancia de tareas de observación/acción entre dos aeronaves, sin solapamiento de corredores.
- **Geometría:** zonas de espera y de trabajo separadas y demarcadas por el instructor.



```text
SECUENCIA TEMPORAL — ALTERNATING SECTION
           T1             T2             T3
ELEMENTO A [ACTIVO]       [ESPERA]       [ACTIVO]
ELEMENTO B [ESPERA]       [ACTIVO]       [ESPERA]
                   ↕ RELEVO COORDINADO
[CORREDORES SEGREGADOS]

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z y Ka-52; Mi-28N según escenario.
- **Ingreso:** sección se incorpora a puntos asignados.
- **Acción:** alternar de forma explícita la condición de elemento activo e inactivo.
- **Salida:** reunión y recuperación con separación confirmada.
- **Evaluación:** comunicación de relevos, identificación de líder y ausencia de entradas simultáneas no autorizadas.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw16"></a>
## 5.17 RW-16 — Armed Reconnaissance / Target Handoff

- **Descripción:** localización, identificación y transferencia de información de un contacto virtual, priorizando exactitud sobre velocidad.
- **Geometría:** ruta de reconocimiento con puntos de informe y sectores observables.



```text
FLUJO — ARMED RECON / HANDOFF
OBSERVADOR ●
    │ IDENTIFICACIÓN VIRTUAL
    ▼
REPORTE ────────────────→ RECEPTOR ●
                              │ CONFIRMA
                              ▼
                        ◇ MARCADOR

[Altitud, velocidad y distancias]
```
- **Recomendadas:** Ka-52; AH-6M y otros dedicados según sensores implementados.
- **Ingreso:** establecer área de búsqueda aprobada.
- **Acción:** observar objeto, describirlo y transmitir ubicación de mapa sin activar armamento.
- **Salida:** abandonar sector tras acuse de recibo del elemento receptor.
- **Evaluación:** reporte coherente, comprobación de coordenadas virtuales y no confundir contactos.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw17"></a>
## 5.18 RW-17 — Escort Threat Response

- **Descripción:** coordinación de escolta de un convoy o transporte de helicópteros en misión virtual, con énfasis en separación y reacción a un evento de amenaza guionizada.
- **Geometría:** corredor de convoy, rutas paralelas o puntos de espera definidos por misión; no se fijan posiciones de combate reales.



```text
VISTA SUPERIOR — ESCORT RESPONSE
ESCOLTA A ● ───────────────→
TRANSPORTE ● ─────────────→ LZ
ESCOLTA B ● ───────────────→
             │ AVISO VIRTUAL
             ▼
       REAGRUPACIÓN / RUTA ALTERNATIVA

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, AH-6M, Mi-24V para escolta; H-60, MH-47G, CH-53E, Mi-8MT para transporte.
- **Ingreso:** comprobar ruta del convoy, restricciones de sobrevuelo y canales de radio.
- **Acción:** ante amenaza de prueba, informar ubicación, mantener separación y ejecutar cambio de misión autorizado por instructor.
- **Salida:** recuperar formación o dirigirse a un punto de reunión seguro.
- **Evaluación:** continuidad de escolta, comunicaciones y prevención de fuego amigo virtual.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw18"></a>
## 5.19 RW-18 — JTAC-Controlled CAS

- **Descripción:** ejercicio de apoyo aéreo cercano controlado por un JTAC simulado, centrado en reconocimiento de instrucciones y verificación del objetivo.
- **Geometría:** áreas de espera, límites de operación y sectores de fuerzas amigas definidos por editor; no se derivan ejes reales de ataque.



```text
FLUJO — JTAC-CONTROLLED CAS (SIMULACIÓN)
JTAC ● ──→ IDENTIFICACIÓN Y AUTORIZACIÓN
                         │
                         ▼
TRIPULACIÓN ● ─────→ CONFIRMACIÓN
                         │
                         ▼
                    ◇ BLANCO INERTE
                         │
                         ▼
                 REPORTE DE FINALIZACIÓN

[Altitud, velocidad y distancias]
```
- **Recomendadas:** AH-1Z, Mi-28N, Ka-52, Mi-24V, AH-6M según misión.
- **Ingreso:** establecer contacto y confirmar área de espera.
- **Acción:** repetir información esencial, identificar marca virtual y esperar autorización explícita. Usar lanzamiento simulado en la fase básica.
- **Salida:** notificar finalización, estado y salida de zona.
- **Evaluación:** lectura correcta, identificación, disciplina de radio y acatamiento de **ABORT**.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw19"></a>
## 5.20 RW-19 — Break Contact / Emergency Egress

- **Descripción:** interrupción de actividad y salida ordenada de una zona virtual ante una condición insegura o cambio de misión.
- **Geometría:** retorno hacia zonas de recuperación previamente señalizadas; prioridad a altura mínima segura y control.



```text
VISTA SUPERIOR — EMERGENCY EGRESS
            ● PUNTO DE EJERCICIO
            │
            ├────────→ CORREDOR A
            │
            └────────→ CORREDOR B
                         │
                         ▼
                 ● RECUPERACIÓN

[Altitud, velocidad y distancias]
```
- **Recomendadas:** todas las aeronaves.
- **Ingreso:** iniciar en un escenario con uno o varios disparadores de seguridad simulados.
- **Acción:** reconocer evento, comunicar **ABORT** y abandonar la actividad planificada.
- **Salida:** dirigirse a zona segura o alterno y reportar condición.
- **Evaluación:** tiempo de decisión, control y no persistir en objetivos tras aborto.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw20"></a>
## 5.21 RW-20 — Terrain-Masked Defensive Flight

- **Descripción:** instrucción de conciencia del relieve y continuidad de vuelo al cambiar la visibilidad de objetos en un escenario virtual.
- **Geometría:** corredor con elevaciones, obstáculos y puntos de escape claramente editados. La línea de visión **no equivale** a una garantía de protección contra sensores reales.



```text
VISTA LATERAL — TERRAIN-MASKED FLIGHT
                 /\  RELIEVE
           _____/  \_____
INICIO ● ────────────────→ ● RECUPERACIÓN
       MARGEN POSITIVO ANTE OBSTÁCULOS
[ALTURAS Y VELOCIDADES POR VALIDAR]

[Altitud, velocidad y distancias]
```
- **Recomendadas:** todas, con ejercicios distintos para ataque y transporte.
- **Ingreso:** reconocer ruta, obstáculos y mínimos establecidos.
- **Acción:** navegar a referencias ficticias mientras se observan cambios de línea de visión con marcadores estáticos.
- **Salida:** alcanzar recuperación sin CFIT.
- **Evaluación:** márgenes de seguridad, lectura topográfica y estabilidad.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw21"></a>
## 5.22 RW-21 — Maneuver Kill: concepto y CFIT

- **Descripción:** **Maneuver Kill** se utiliza aquí como término pedagógico de simulación para analizar situaciones en las que una maniobra extrema causa pérdida de control o colisión contra terreno (**CFIT, Controlled Flight Into Terrain**). No se enseñan métodos para provocar accidentes a otra aeronave ni para eludir misiles reales.
- **Geometría:** ruta de obstáculos diseñada por instructor, con elevaciones y límites conservadores; **sin armamento ni amenaza activa** en fase inicial.



```text
VISTA LATERAL — CFIT PREVENTION
AERONAVE ● ────────→ RECUPERACIÓN CONTROLADA
          \
           \     X IMPACTO (ERROR)
            \    │
───────────────────┴──────────────── TERRENO
    OBJETIVO: NO IMPACTAR CON EL TERRENO

[Altitud, velocidad y distancias]
```
- **Recomendadas:** todas; especial atención a transportes pesados por su dinámica de vuelo distinta.
- **Ingreso:** establecer estado estable y comunicar referencias.
- **Acción:** reconocer que una trayectoria se vuelve insegura y decidir **ABORT / RECOVERY**, sin perseguir una maniobra extrema.
- **Salida:** recuperarse sin pérdida de control y regresar a la zona de seguridad.
- **Evaluación:** elección temprana de evitar terreno, recuperación y márgenes de altura; una colisión invalida el ejercicio incluso si se “evitó” un contacto virtual.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

<a id="rw22"></a>
## 5.23 RW-22 — Holding Area / Attack Position

- **Descripción:** separación entre zona de espera (**HA**) y posición de trabajo (**AP/BP**) para control del flujo de la misión.
- **Geometría:** áreas demarcadas, rutas de transferencia y puntos de reporte; valores de AGL y velocidades establecidos por instructor.



```text
VISTA SUPERIOR — HOLDING / ATTACK POSITION
┌─────────────────────┐
│  HOLDING AREA  ●    │
└──────────┬──────────┘
           │ AUTORIZACIÓN
           ▼
   ATTACK POSITION ●
           │
           ▼
     ◇ REFERENCIA VIRTUAL

[Altitud, velocidad y distancias]
```
- **Recomendadas:** todas, adaptando la AP a una zona de observación o inserción según rol.
- **Ingreso:** entrar al holding y verificar tráfico.
- **Acción:** recibir autorización para cambiar de zona y comunicar disponibilidad.
- **Salida:** retornar al holding o dirigirse a recuperación tras finalizar.
- **Evaluación:** orden de salida, gestión de tráfico y no invadir zonas activas.

[↑ Volver al catálogo](#catalogo) · [↑ Volver al índice](#indice)

---

<a id="amenazas"></a>
# 6. Aplicación por amenaza antiaérea virtual

**Principio [ROAN]:** la amenaza modifica la **decisión de continuar o abortar** la misión y el diseño del ejercicio; no convierte todas las aeronaves armadas en plataformas de supresión antiaérea. Las características de detección y guiado de la IA deben verificarse en Arma 3.

<a id="aaa"></a>
## 6.1 AAA de adquisición visual (ej. ZU-23 virtual)

- **Caracterización:** amenaza simulada de adquisición visual, con comportamiento dependiente de scripts, skill de IA, escenario y línea de visión del motor.
- **Ejercicios asociados:** [RW-01](#rw01) (visibilidad), [RW-11](#rw11) (relieve), [RW-19](#rw19) (aborto).
- **Plataformas de formación:** AH-1Z, Mi-28N, Ka-52 y AH-6M para escenarios con armas desactivadas; transportes solo para evasión/ruptura de misión.
- **Flujo pedagógico:** identificar el tipo de amenaza en briefing → comprobar si misión sigue autorizada → simular detección/reporte → ejecutar **ABORT** o desvío aprobado → debrief.
- **Restricción:** no se incluyen procedimientos para neutralizar físicamente un ZU-23 real.

<a id="sam"></a>
## 6.2 Radar / SAM de largo alcance

- **Caracterización:** escenario virtual de amenaza de largo alcance; las limitaciones del mod no deben confundirse con capacidades de radares reales.
- **Principio:** un helicóptero no debe asumir una misión **SEAD/DEAD** por el simple hecho de ir armado.
- **Ejercicios asociados:** [RW-16](#rw16) (reporte), [RW-19](#rw19) (aborto), [RW-22](#rw22) (holding y cambio de orden).
- **Plataformas:** aeronaves de ataque para reconocimiento/reportes ficticios; transportes para navegación por ruta alternativa establecida.
- **Flujo pedagógico:** aviso de amenaza → comunicar → detener acción ofensiva → recibir nuevo plan → recuperación y lecciones aprendidas.

<a id="manpads"></a>
## 6.3 MANPADS / amenazas de guiado infrarrojo

- **Caracterización:** amenaza virtual con detección y reacción definidas por el mod/IA; no se asumirán capacidades de búsqueda térmica reales.
- **Ejercicios asociados:** [RW-19](#rw19) (interrupción), [RW-20](#rw20) (conciencia del relieve), [RW-21](#rw21) (CFIT y control).
- **Plataformas:** todas, especialmente tripulaciones de asalto/transporte.
- **Flujo pedagógico:** alerta guionizada → comunicación de emergencia → gestión de vuelo dentro de límites → salida del ejercicio → debrief.
- **Verificación [MOD]:** disponibilidad real de avisos, flares y automatismos de cada aeronave, sin generalizar entre addons.

[↑ Volver al índice](#indice)

---

<a id="blancos"></a>
# 7. Aplicación por tipo de blanco virtual

<a id="blindados"></a>
## 7.1 Blindados y tanques (AT / Anti-Tank)

- **Objetivo académico:** diferenciar identificación, clasificación y reporte de vehículos virtuales; demostrar manejo seguro de los sensores disponibles.
- **Plataformas principales:** AH-1Z, Mi-28N, Ka-52, Mi-24V; AH-6M solo si su armamento implementado lo permite.
- **Perfiles a estudiar:** [RW-08](#rw08) (gestión de sensores), [RW-09](#rw09) (BP), [RW-16](#rw16) (handoff).
- **Flujo:** localizar marcador vehicular → identificar modelo virtual → comunicar → confirmar autorización del instructor → realizar interacción simulada → BDA en debrief.
- **Métrica de formación:** identificación correcta, tiempo de comunicación, errores de atribución y disciplina de vuelo; no se enseña ubicación óptima de impacto contra blindajes reales.

<a id="infanteria"></a>
## 7.2 Infantería desplegada y posiciones fortificadas

- **Objetivo académico:** comprobar deconfliction y prevención de fuego amigo virtual en un escenario con unidades amigas y enemigas diferenciadas.
- **Plataformas de estudio:** AH-1Z, AH-6M, Mi-24V, Mi-28N, Ka-52.
- **Perfiles a estudiar:** [RW-04](#rw04), [RW-05](#rw05), [RW-06](#rw06), [RW-07](#rw07), [RW-18](#rw18).
- **Flujo:** recibir clasificación de objetivos → identificar sector amigo → repetir instrucciones del JTAC → simulación de acción → salida y BDA.
- **Métrica de formación:** ausencia de fuego amigo, identificación positiva, cumplimiento de instrucciones y seguridad de vuelo.

[↑ Volver al índice](#indice)

---

<a id="distancia"></a>
# 8. Aplicación por distancia de enganche

> **Criterio:** las categorías describen **distancia relativa del escenario**, no umbrales tácticos universales. En Arma 3 cada aeronave/arma/mod exige medición propia.

<a id="standoff"></a>
## 8.1 Larga distancia — Standoff

- **Concepto:** separación entre posición de observación simulada y objetivo, dentro del alcance que efectivamente implemente el arma virtual.
- **Perfiles asociados:** [RW-08](#rw08), [RW-09](#rw09), [RW-16](#rw16).
- **Plataformas:** AH-1Z, Mi-28N, Ka-52, Mi-24V condicionado.
- **Validación:** distancia de adquisición *en el juego*, controles de sensores, limitaciones de interfaz, BDA del simulador.

<a id="intermedia"></a>
## 8.2 Distancia intermedia

- **Concepto:** categoría de ejercicio entre posiciones de observación relativamente lejanas y pasadas cercanas, determinada por mapa y diseño de misión.
- **Perfiles asociados:** [RW-03](#rw03), [RW-09](#rw09), [RW-12](#rw12).
- **Plataformas:** ataque dedicado y ataque ligero de acuerdo con maniobrabilidad comprobada.
- **Validación:** seguridad de maniobra, geometría y consistencia entre sesiones.

<a id="closein"></a>
## 8.3 Corta distancia — Close-In

- **Concepto:** reconocimiento de perfiles en pasada y riesgo de maniobra en un polígono de tiro **exclusivamente virtual**.
- **Perfiles asociados:** [RW-04](#rw04), [RW-05](#rw05), [RW-06](#rw06), [RW-07](#rw07).
- **Plataformas:** AH-6M, AH-1Z y Mi-24V principalmente.
- **Validación:** distancia segregada de terceros, límites de circuito, control y reconocimiento de abortos.

[↑ Volver al índice](#indice)

---

<a id="coordinacion"></a>
# 9. Operaciones coordinadas y comunicaciones

## 9.1 Organización sugerida de sección

| Elemento | Función ROAN en ejercicio |
|---|---|
| **LEAD** | Responsable de ruta, reporte al controlador y autorizaciones de movimiento. |
| **TWO / WINGMAN** | Mantiene separación, informa estado y apoya vigilancia de seguridad. |
| **PILOT** | Control y navegación inmediata de la aeronave. |
| **CPG / COPILOT / GUNNER** | Sensores e identificación, listas y radio delegada según disponibilidad. |
| **JTAC / CONTROL** | Autoriza o cancela acciones ficticias y advierte de restricciones en el campo. |

## 9.2 Formato de comunicaciones de entrenamiento

```text
ROAN LEAD: "Control, ROAN Uno en HOLD ALFA, dos aeronaves, listo para instrucciones."
CONTROL:   "ROAN Uno, mantenga HOLD ALFA. Tráfico activo en sector BRAVO."
ROAN LEAD: "Mantengo HOLD ALFA, ROAN Uno."
CPG:       "Marcador identificado. Sector amigo verificado."
CONTROL:   "ROAN Uno, ejercicio cancelado. ABORT, retorno a BASE."
ROAN LEAD: "ABORT recibido; retorno a BASE. ROAN Uno."
```

## 9.3 Principios CRM

- Una sola interpretación inequívoca de instrucciones críticas.
- Confirmación verbal de cambio de modo y sistemas del mod cuando sea aplicable.
- Avisos tempranos: obstáculos, tráfico, pérdida de referencia, confusión de sector, dudas de identificación.
- Piloto y operador no disputan control; el piloto al mando declara el procedimiento de transferencia antes del vuelo.
- El procedimiento de **jettison** y otras emergencias se definirá por aeronave y addon en fichas complementarias, con práctica inicialmente en entorno controlado.

[↑ Volver al índice](#indice)

---

<a id="supervivencia"></a>
# 10. Supervivencia, emergencias y abortos

## 10.1 Prioridades

**AVIATE → NAVIGATE → COMMUNICATE.** Mantener control precede a continuar cualquier acción ficticia.

## 10.2 CFIT y vuelo a baja altura

El principal riesgo en escenarios ROAN de vuelo a baja cota es convertir una corrección brusca o una pérdida de referencias en impacto con terreno. Toda práctica de NOE, contour, pop-up o recuperación debe asignar un corredor despejado y un umbral de seguridad del simulador.

## 10.3 Procedimiento genérico de interrupción

```text
ANOMALÍA / AMENAZA GUIONIZADA / DUDA DE IDENTIFICACIÓN
                         ↓
                   DECLARAR ABORT
                         ↓
              PRIORIZAR CONTROL DE VUELO
                         ↓
          SALIR DEL EJERCICIO POR RUTA SEGURA
                         ↓
             REPORTAR ESTADO Y REGRESAR
                         ↓
                  DEBRIEF / LECCIONES
```

## 10.4 Notas sobre defensas y contramedidas [MOD]

Las contramedidas, alertas RWR/MAWS, sensores IR y modelos de amenaza pueden diferir radicalmente entre aeronaves, versiones y servidores. ROAN deberá comprobar controles, indicadores, disponibilidad y efectos virtuales antes de aprobar una instrucción específica.

[↑ Volver al índice](#indice)

---

<a id="entrenamiento"></a>
# 11. Programa de entrenamiento ROAN

<a id="progresion"></a>
## 11.1 Progresión curricular

| Fase | Competencia | Práctica | Requisito de aprobación |
|---|---|---|---|
| **I. Tactical Flight** | AGL/MSL, contour, NOE conceptual, lectura del terreno | Corredores de navegación y obstáculos ficticios | Sin CFIT, navegación y márgenes respetados |
| **II. Attack Geometry** | Ingress, holding, BP, eje y egress | Identificación de waypoints y control | Ruta y reportes correctos |
| **III. Individual Profiles** | Pop-up, running, diving, standoff como conceptos | Pasadas sin armamento y blancos inertes | Estabilidad y abortos oportunos |
| **IV. Threat Environment** | Reconocimiento de AAA, SAM y MANPADS virtuales | Alertas guionizadas y desvíos | Decisiones y reportes apropiados |
| **V. Two-Ship** | Lead/wingman, shooter/cover | Parejas con sectores segregados | Separación y coordinación |
| **VI. CAS Coordination** | Interacción JTAC y prevención de fuego amigo | Marcadores y autorizaciones simuladas | Identificación y readback correctos |
| **VII. Combined Exercise** | Integración de competencias | Misión evaluada en Arma 3 | Rúbrica integral aprobada |

<a id="ejercicios"></a>
## 11.2 Ejercicios iniciales propuestos

### RW-TRN-01 — Terrain Awareness

- **Plataformas:** AH-1Z, H-60, Mi-8MT según nivel.
- **Escenario:** corredor con colinas, árboles y balizas visuales; amenazas desactivadas.
- **Objetivo:** distinguir contour/NOE conceptual, mantener control y anunciar obstáculos.
- **Criterios:** completar ruta aprobada, sin colisiones ni desviaciones peligrosas.

### RW-TRN-02 — Masked Observation

- **Plataformas:** AH-1Z, Mi-28N, Ka-52.
- **Escenario:** cresta con marcadores virtuales visibles desde puntos seleccionados.
- **Objetivo:** describir cambios de línea de visión sin disparo.
- **Criterios:** posicionamiento correcto, control y reportes claros.

### RW-TRN-03 — Pop-Up Geometry

- **Plataformas:** AH-1Z / Mi-28N / Ka-52.
- **Escenario:** valle y marcador objetivo; armamento desactivado.
- **Objetivo:** reconocer verbalmente **Ingress → Pop → Apex/Roll-In → Recovery → Egress**.
- **Criterios:** transiciones estables, margen con terreno y llegada a salida autorizada.

### RW-TRN-04 — CAS Communications

- **Plataformas:** ataque dedicado, CPG + piloto cuando corresponda.
- **Escenario:** JTAC, marcadores de objetivo y unidades amigas virtuales.
- **Objetivo:** readback, identificación y respuesta a **ABORT**.
- **Criterios:** cero confusiones de sector y acatamiento de orden de interrupción.

### RW-TRN-05 — Escort & Coordination

- **Plataformas:** AH-6M / AH-1Z como escolta; H-60 / MH-47G / Mi-8MT como transporte.
- **Escenario:** convoy terrestre o traslado aéreo a LZ.
- **Objetivo:** mantener comunicación, sectores y separación al producirse un evento guionizado.
- **Criterios:** ninguna colisión, comunicaciones completas y retorno ordenado.

### RW-TRN-06 — Defensive Abort / CFIT Prevention

- **Plataformas:** todas, con ajustes de dificultad según masa y AFM.
- **Escenario:** vuelo bajo con puntos de emergencia; sin armamento.
- **Objetivo:** reconocer una situación insegura y abortar sin impacto.
- **Criterios:** recuperación segura y reporte preciso.

<a id="rubrica"></a>
## 11.3 Rúbrica básica de evaluación

**Escala ROAN:** Excelente (4), Bien (3), Suficiente (2), Deficiente (1). **Puntaje máximo:** 28. **Aprobación provisional sugerida:** 21/28 y ninguna falta crítica. Sujeta a aprobación del mando ROAN.

| Núm. | Criterio de evaluación | Excelente (4) | Bien (3) | Suficiente (2) | Deficiente (1) | Puntuación |
|---|---|---|---|---|---|---|
| 1 | Control de aeronave | Control estable continuo | Correcciones menores | Correcciones frecuentes | Pérdida de control | — |
| 2 | Gestión de altura y obstáculos | Márgenes consistentes | Incidencias menores | Advertencias repetidas | CFIT o colisión | — |
| 3 | Navegación y corredor | Preciso y autónomo | Un desvío menor | Requiere guía | Incumple límites | — |
| 4 | Identificación de objetivo virtual | Positiva e inequívoca | Duda resuelta | Requiere asistencia | Identificación errónea | — |
| 5 | Comunicaciones / CRM | Concisas y completas | Omisión menor | Readbacks incompletos | Interferencia o confusión grave | — |
| 6 | Cumplimiento del procedimiento | Todas las fases | Falla secundaria | Varias fases incompletas | Omite fases esenciales | — |
| 7 | Aborto y recuperación | Oportuno y seguro | Ligero retraso | Requiere instrucción | Ignora ABORT o actúa inseguro | — |

**Faltas críticas [ROAN]:** colisión evitable, fuego amigo virtual, ejecución fuera del polígono, incumplimiento intencional de ABORT, maniobra sin control o pérdida evitable de aeronave.

[↑ Volver al índice](#indice)

---

<a id="plantilla"></a>
# 12. Plantilla de ficha de táctica ROAN

> Utilizar esta estructura para nuevas tácticas, revisiones o fichas ampliadas por plataforma. Los campos cuantitativos se llenarán **solo con resultados de pruebas en Arma 3**, especificando mod, versión y configuración de dificultad.

```text
CÓDIGO Y NOMBRE TÉCNICO
Versión de la ficha:
Tipo / familia:
Objetivo formativo:

1. DESCRIPCIÓN
   Concepto y finalidad en simulación.

2. GEOMETRÍA DE VUELO
   Vista lateral / vista en planta.
   Banda AGL ROAN: [POR VALIDAR]
   Banda de velocidad ROAN: [POR VALIDAR]
   Corredor y puntos: [POR VALIDAR]
   Configuración AFM / estándar: [POR VALIDAR]

3. PLATAFORMAS ROAN
   Recomendadas:
   Condicionales:
   No recomendadas:

4. PROCEDIMIENTO DE ENTRENAMIENTO
   Ingress:
   Setup / confirmaciones:
   Acción virtual:
   Recovery / Egress:

5. TRIPULACIÓN Y CRM
   Piloto:
   Copiloto / CPG / operador:
   Lead / wingman / JTAC:

6. CONDICIONES DE ABORTO

7. ERRORES FRECUENTES

8. EJERCICIO Y CALIFICACIÓN
   Identificador de práctica:
   Mapa y dificultad:
   Estándares observables:

9. VALIDACIÓN
   Fecha de prueba:
   Mod / versión:
   Instructor responsable:
   Estado: [POR VALIDAR / APROBADO / RETIRADO]
   Evidencia / replay:
```

[↑ Volver al índice](#indice)

---

<a id="glosario"></a>
# 13. Glosario

| Sigla / término | Significado |
|---|---|
| **AAA** | Anti-Aircraft Artillery / artillería antiaérea. |
| **AGL** | Above Ground Level / altura sobre el terreno. |
| **AP** | Attack Position / posición de ataque designada. |
| **AT / ATGM** | Anti-Tank / Anti-Tank Guided Missile. |
| **BDA** | Battle Damage Assessment. |
| **BP** | Battle Position. |
| **CAS** | Close Air Support / apoyo aéreo cercano. |
| **CFIT** | Controlled Flight Into Terrain / impacto contra terreno con aeronave bajo control. |
| **CPG** | Copilot/Gunner. |
| **CRM** | Crew Resource Management / gestión de recursos de tripulación. |
| **DEAD** | Destruction of Enemy Air Defenses. |
| **Egress** | Ruta o fase de salida. |
| **FLIR** | Forward Looking Infrared. |
| **HA** | Holding Area. |
| **Ingress** | Ruta o fase de entrada. |
| **ISR** | Intelligence, Surveillance and Reconnaissance. |
| **JTAC** | Joint Terminal Attack Controller. |
| **LZ** | Landing Zone. |
| **MANPADS** | Man-Portable Air-Defense System. |
| **MAWS** | Missile Approach Warning System. |
| **MSL** | Mean Sea Level. |
| **NOE** | Nap-of-the-Earth. |
| **RWR** | Radar Warning Receiver. |
| **SAM** | Surface-to-Air Missile. |
| **SEAD** | Suppression of Enemy Air Defenses. |
| **Standoff** | Empleo/observación desde una posición relativamente alejada del blanco. |
| **Unmask** | Salir de una posición de ocultamiento respecto a línea de visión. |

[↑ Volver al índice](#indice)

---

<a id="referencias"></a>
# 14. Referencias y fuentes

## 14.1 Inventario y mods (fuente rectora)

- [FEL — Catálogo Operacional de Aeronaves ROAN](https://github.com/lockdawn/arma3-fel-mod-manifest/tree/main/ROAN), versión 0.2 consultada para esta edición.
- [Hatchet H-60 Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605).
- [AH-1Z Viper](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780).
- [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117).
- [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103).
- [Pegasus Systems MH-47G](https://steamcommunity.com/sharedfiles/filedetails/?id=3805899171).
- [ACE3](https://steamcommunity.com/workshop/filedetails/?id=463939057).
- [Hatchet Interaction Framework](https://steamcommunity.com/sharedfiles/filedetails/?id=2941986336).

## 14.2 Doctrina y terminología pública

- U.S. Army, **FM 3-04 — Army Aviation**; consultar la edición vigente en las bibliotecas doctrinales del Ejército de EE. UU.: [Army Publishing Directorate](https://armypubs.army.mil/).
- U.S. Army, documentación doctrinal pública de aviación: [Aviation Digest](https://www.lineofdeparture.army.mil/Journals/Aviation-Digest/).
- U.S. Marine Corps, **MCRP 3-20.4, MTTP for Aviation Urban Operations**: [publicación pública (PDF)](https://www.marines.mil/Portals/1/Publications/MCRP%203-20.4%20MTTP%20for%20Aviation%20Urban%20Operations--22%20Feb%202022.pdf).
- U.S. Marine Corps, portal público de publicaciones: [Marines Publications](https://www.marines.mil/News/Publications/).

## 14.3 Referencias técnicas de aeronaves reales

- [Bell — AH-1Z Viper](https://www.bellflight.com/products/bell-ah-1z).
- [Boeing — AH-6 Little Bird](https://www.boeing.com/defense/military-rotorcraft/ah-6-little-bird).
- [Boeing — H-47 Chinook](https://www.boeing.com/defense/military-rotorcraft/h-47-chinook).
- [USSOCOM — publicaciones oficiales](https://www.socom.mil/).
- [Rostec — portal corporativo](https://rostec.ru/en/).

**Nota metodológica:** las referencias doctrinales son **bibliografía conceptual**, no una certificación de que cada etiqueta de este catálogo sea una maniobra oficial universal. Algunas son **categorías de ejercicio ROAN**, combinaciones de tareas o patrones de entrenamiento, y así deben interpretarse.

[↑ Volver al índice](#indice)

---

<a id="control"></a>
# 15. Registro de validaciones y control documental

## 15.1 Pendientes priorizados para edición 0.2

| ID | Validación requerida | Plataforma | Estado |
|---|---|---|---|
| VAL-01 | Comportamiento AGL/velocidad y AFM en entrenamiento | AH-1Z, H-60 | Pendiente |
| VAL-02 | Sensores y asiento operador efectivamente disponibles | AH-1Z, Mi-28N, Ka-52 | Pendiente |
| VAL-03 | Armamento y variantes de carga del addon | AH-6M, Mi-24V, Mi-8MT, H-60 | Pendiente |
| VAL-04 | Sistemas de alertas y contramedidas en servidor | Todos los armados | Pendiente |
| VAL-05 | Reproducción de geometrías de vuelo | AH-1Z, Mi-28N, Ka-52 | Pendiente |
| VAL-06 | Sistema de comunicaciones JTAC y reparto CRM | Todos los biplaza | Pendiente |
| VAL-07 | Revisión de maniobras y nomenclatura con instructores | Todos | Pendiente |
| VAL-08 | Formalizar rúbricas, mínimos y faltas críticas | Academia ROAN | Pendiente |

## 15.2 Historial de versiones

| Versión | Fecha | Cambios |
|---|---|---|
| **0.1** | **03/11/2026** | Primera versión integral; inventario ROAN validado contra catálogo 0.2, 22 fichas iniciales, escenarios AA/objetivos/distancia, procedimientos generales, entrenamiento, rúbrica, glosario y referencias. |

## 15.3 Control del documento

| Campo | Valor |
|---|---|
| Documento | Manual de Tácticas de Ataque Aéreo — Volumen I |
| Organización | Regimiento de Operaciones Aero Navales — FEL |
| Versión | 0.1 |
| Estado | Borrador para validación académica ROAN |
| Plataforma | Arma 3 |
| Alcance | Ala rotativa únicamente |
| Documento rector | Catálogo Operacional de Aeronaves ROAN v0.2 |
| Siguiente revisión | Tras pruebas de mods, ejercicios y aprobación del mando ROAN |

[↑ Volver al índice](#indice) · [↑ Volver al inicio](#inicio)
