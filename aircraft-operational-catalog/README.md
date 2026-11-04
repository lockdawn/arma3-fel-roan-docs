<a id="inicio"></a>

# Catálogo Operacional de Aeronaves

**Regimiento de Operaciones Aero Navales**

> **Clan:** FEL  
> **Versión:** 0.2  
> **Plataforma:** Arma 3

---

<a id="introduccion"></a>
# 1. Introducción

Este documento establece el inventario de aeronaves, plataformas e infraestructura aeronaval autorizadas para su empleo por el **Regimiento de Operaciones Aero Navales (ROAN)** dentro del clan **FEL** de **Arma 3**.

Su objetivo es funcionar como referencia operativa para pilotos, copilotos, artilleros/operadores de sistemas, instructores, líderes de misión y editores. El catálogo permite identificar qué plataformas están aprobadas, qué capacidades ofrecen, qué limitaciones deben considerarse y qué mods/dependencias son necesarios para su uso.

## 1.1 Propósito

- Establecer el inventario oficial de aeronaves autorizadas por ROAN.
- Estandarizar la selección de plataforma según el tipo de misión.
- Documentar capacidades, limitaciones, tripulación, carga, sensores y armamento.
- Mantener una referencia de mods y dependencias.
- Servir como material de consulta para entrenamiento, cursos y operaciones.
- Facilitar la creación de misiones coherentes y evitar la incorporación arbitraria de aeronaves no evaluadas.

## 1.2 Alcance

Las plataformas del documento pueden emplearse en operaciones oficiales, entrenamientos, prácticas de vuelo, cursos, misiones cooperativas, operaciones conjuntas, pruebas y edición de misiones.

## 1.3 Criterio de autorización

Una aeronave que **NO aparezca en este documento** no se considera parte del inventario autorizado de ROAN, salvo autorización específica de un oficial de FEL para una misión, entrenamiento, prueba o evaluación.

## 1.4 Criterio para los datos técnicos

Este manual distingue entre dos fuentes de información:

1. **Datos del mod:** se utilizan cuando el Workshop o la implementación documentan explícitamente una capacidad, dependencia o sistema.
2. **Datos reales de referencia:** cuando el mod no publica una cifra concreta, se emplean especificaciones de la aeronave real o de la variante más cercana. Esto es útil porque la mayoría de los addons buscan aproximarse al comportamiento real, pero **Arma 3 puede diferir** en velocidad, sensores, resistencia, carga, asientos o física.

Por lo tanto, las cifras de alcance, techo, velocidad y carga deben usarse para **planeación ROAN**, no como garantía de que el motor de Arma 3 reproduzca exactamente cada número.

## 1.5 Convenciones

- **Tripulación mínima:** personal mínimo recomendado para ejecutar la misión prevista con seguridad/funcionalidad.
- **Tripulación recomendada:** configuración ROAN que aprovecha correctamente los puestos de la aeronave.
- **Pasajeros:** personal transportado que no forma parte de la tripulación de vuelo.
- **Carga útil / payload:** carga, armas, combustible adicional o combinación que la plataforma puede transportar.
- **Sling load:** carga externa suspendida bajo un helicóptero.
- Las denominaciones BLUFOR/OPFOR se usan para ordenar el inventario y no sustituyen la facción concreta definida por cada misión.

[↑ Volver al inicio](#inicio)

---

<a id="indice"></a>
# 2. Contenido

- [1. Introducción](#introduccion)
- [2. Contenido](#indice)
- [3. Inventario general ROAN](#inventario-general)
- [4. Matriz de Empleo Operacional](#matriz-empleo)
- [5. Mods y Dependencias](#mods-dependencias)

- [6. Ala fija — BLUFOR](#ala-fija-blufor)
  - [A-10C Thunderbolt II](#a10c)
  - [C-130 E/H/J Hercules Series](#c130)
  - [F/A-18E Super Hornet](#fa18ef)
  - [F-35B Lightning II](#f35b)
  - [F-35C Lightning II](#f35c)

- [7. Ala fija — OPFOR](#ala-fija-opfor)
  - [MiG-29SM Fulcrum](#mig29sm)
  - [Su-34M Fullback](#su34m)
  - [Su-35 Flanker-E](#su35)

- [8. Ala rotativa — BLUFOR](#ala-rotativa-blufor)
  - [H-60 Series](#h60)
  - [AH-1Z Viper](#ah1z)
  - [AH-6M Little Bird](#ah6m)
  - [MH-6M Little Bird](#mh6m)
  - [CH-53E Super Stallion](#ch53e)
  - [MH-47G Chinook](#mh47g)

- [9. Ala rotativa — OPFOR](#ala-rotativa-opfor)
  - [Mi-8MT Hip](#mi8mt)
  - [Mi-24V Hind-E](#mi24v)
  - [Mi-28N Havoc](#mi28n)
  - [Ka-52 Alligator](#ka52)

- [10. Infraestructura y Operaciones Aeronavales](#infraestructura)
  - [Nimitz Experimental Build](#nimitz)
  - [LHA](#lha)
  - [Airfield Logistics](#airfield-logistics)

- [11. Glosario](#glosario)
- [12. Referencias generales](#referencias)

[↑ Volver al inicio](#inicio)

---

<a id="inventario-general"></a>
# 3. Inventario general ROAN

Vista rápida del inventario autorizado. Los roles detallados y limitaciones se encuentran en cada ficha.

## Ala fija — BLUFOR

| Modelo | Nombre | Rol principal | MOD |
|---|---|---|---|
| [A-10C](#a10c) | Thunderbolt II | CAS / Ataque | [A-10C Thunderbolt](https://steamcommunity.com/sharedfiles/filedetails/?id=2848059590) |
| [C-130 E/H/J](#c130) | Hercules Series | Transporte / Logística | [C-130 E/H/J Hercules Series](https://steamcommunity.com/sharedfiles/filedetails/?id=3122396633) |
| [F/A-18E](#fa18ef) | Super Hornet | Multirrol / Embarcado | [F/A-18E/F Super Hornet 2020](https://steamcommunity.com/sharedfiles/filedetails/?id=2131302796) |
| [F-35B](#f35b) | Lightning II | Multirrol / STOVL | [F-35B Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3517620967) |
| [F-35C](#f35c) | Lightning II | Multirrol / Embarcado | [F-35C Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3083645332) |

## Ala fija — OPFOR

| Modelo | Nombre | Rol principal | MOD |
|---|---|---|---|
| [MiG-29SM](#mig29sm) | Fulcrum | Caza / Multirrol | [Improved RHS MiG-29SM + FIR support](https://steamcommunity.com/sharedfiles/filedetails/?id=2987850906) |
| [Su-34M](#su34m) | Fullback | Strike / Interdicción | [Su-34M (UMPK)](https://steamcommunity.com/sharedfiles/filedetails/?id=3137489963) |
| [Su-35](#su35) | Flanker-E | Superioridad aérea / Multirrol | [SU-35 Flanker E](https://steamcommunity.com/sharedfiles/filedetails/?id=743108251) |

## Ala rotativa — BLUFOR

| Modelo | Nombre | Rol principal | MOD |
|---|---|---|---|
| [H-60 Series](#h60) | Black Hawk / Seahawk family | Transporte / Utilidad / Especiales | [Hatchet H-60 Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605) |
| [AH-1Z](#ah1z) | Viper | Ataque / CAS / Escolta | [AH-1Z Viper](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780) |
| [AH-6M](#ah6m) | Little Bird | Ataque ligero / CAS | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| [MH-6M](#mh6m) | Little Bird | Inserción / Operaciones especiales | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| [CH-53E](#ch53e) | Super Stallion | Transporte muy pesado / Anfibio | [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| [MH-47G](#mh47g) | Chinook | Operaciones especiales / Heavy assault | [Pegasus Systems MH-47G](https://steamcommunity.com/sharedfiles/filedetails/?id=3805899171) |

## Ala rotativa — OPFOR

| Modelo | Nombre | Rol principal | MOD |
|---|---|---|---|
| [Mi-8MT](#mi8mt) | Hip | Transporte / Utilidad | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| [Mi-24V](#mi24v) | Hind-E | Ataque / Transporte armado | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| [Mi-28N](#mi28n) | Havoc | Ataque | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| [Ka-52](#ka52) | Alligator | Ataque / Reconocimiento | [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103) |

## Infraestructura y Operaciones Aeronavales

| Nombre | Rol principal | MOD |
|---|---|---|
| [Nimitz](#nimitz) | Portaaviones Nuclear (CVN) | [Nimitz Experimental Build](https://steamcommunity.com/sharedfiles/filedetails/?id=1697731012) |
| [LHA](#lha) | Buque de Asalto Anfibio (Portahelicópteros) | [LHA](https://steamcommunity.com/sharedfiles/filedetails/?id=3596653038) |
| [Airfield Logistics](#airfield-logistics) | Plataformas / Herramientas | [Airfield Logistics](https://steamcommunity.com/sharedfiles/filedetails/?id=3048131698) |

[↑ Volver al índice](#indice)

---

<a id="matriz-empleo"></a>
# 4. Matriz de Empleo Operacional

La matriz resume para qué misiones resulta apropiada cada plataforma. No sustituye la ficha detallada.

**Leyenda:** ✅ recomendado · ⚠️ capaz/condicional · ❌ no corresponde al rol

| Aeronave | CAP | CAS | Strike | Anti-blindaje | Transporte | Logística | SOF / Inserción | SEAD/DEAD | Embarcada |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| A-10C | ❌ | ✅ | ⚠️ | ✅ | ❌ | ❌ | ❌ | ⚠️ | ❌ |
| C-130 E/H/J | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ |
| F/A-18E | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ |
| F-35B | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ (LHA) |
| F-35C | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ (CATOBAR) |
| MiG-29SM | ✅ | ⚠️ | ✅ | ⚠️ | ❌ | ❌ | ❌ | ⚠️ | ❌ |
| Su-34M | ⚠️ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅/⚠️ | ❌ |
| Su-35 | ✅ | ⚠️ | ✅ | ✅ | ❌ | ❌ | ❌ | ⚠️ | ❌ |
| H-60 Series | ❌ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ❌ | ✅ |
| AH-1Z | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅ (LHA) |
| AH-6M | ❌ | ✅ | ⚠️ | ⚠️ | ❌ | ❌ | ⚠️ | ❌ | ⚠️ |
| MH-6M | ❌ | ❌ | ❌ | ❌ | ⚠️ | ❌ | ✅ | ❌ | ⚠️ |
| CH-53E | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | ✅ (LHA) |
| MH-47G | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ | ❌ | ⚠️ |
| Mi-8MT | ❌ | ⚠️ | ⚠️ | ⚠️ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Mi-24V | ❌ | ✅ | ✅ | ✅ | ⚠️ | ❌ | ⚠️ | ❌ | ❌ |
| Mi-28N | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Ka-52 | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |

## 4.1 Selección rápida

| Necesidad | Plataformas preferentes |
|---|---|
| CAP / superioridad aérea | F/A-18E, F-35C, F-35B, Su-35, MiG-29SM |
| CAS ala fija | A-10C, F/A-18E, F-35B/C, Su-34M |
| CAS helicóptero | AH-1Z, AH-6M, Mi-24V, Mi-28N, Ka-52 |
| Transporte ligero SOF | MH-6M, H-60 |
| Transporte medio | H-60, Mi-8MT |
| Transporte pesado | MH-47G, CH-53E |
| Sling load pesado | MH-47G, CH-53E |
| Strike de largo alcance | F-35C, F/A-18E, Su-34M, Su-35 |
| Operación Nimitz | F/A-18E, F-35C |
| Operación LHA | F-35B, AH-1Z, H-60, CH-53E |

[↑ Volver al índice](#indice)

---

<a id="mods-dependencias"></a>
# 5. Mods y Dependencias

Resumen centralizado de addons principales y sus dependencias conocidas de Steam Workshop.

| MOD | Uso ROAN | Dependencias conocidas | Workshop |
|---|---|---|---|
| A-10C Thunderbolt | A-10C | Lala Peral - Vehicle Interaction System | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2848059590) |
| AH-1Z Viper | AH-1Z | Lala Peral - Vehicle Interaction System | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780) |
| Airfield Logistics | Soporte de aeródromo/cubierta | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3048131698) |
| C-130 E/H/J Hercules Series | C-130 E/H/J/J-30 | FIR AWS | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3122396633) |
| F/A-18E/F Super Hornet 2020 | F/A-18E | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2131302796) |
| F-35B Lightning | F-35B | Lala Peral - Vehicle Interaction System | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3517620967) |
| F-35C Lightning | F-35C | Lala Peral - Vehicle Interaction System | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3083645332) |
| Hatchet H-60 Pack | H-60 Series | Hatchet Interaction Framework; ACE3; CBA_A3 (transitiva) | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605) |
| Improved RHS MiG-29SM + FIR support | MiG-29SM | FIR AWS; RHSGREF; RHSAFRF; RHSSAF; RHSUSAF | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2987850906) |
| LHA | Buque anfibio | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3596653038) |
| Nimitz Experimental Build | Portaaviones | CBA_A3 | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=1697731012) |
| Pegasus Systems MH-47G | MH-47G | Hatchet Interaction Framework; ACE3; CBA_A3 (transitiva) | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3805899171) |
| RHSAFRF | Mi-8MT, Mi-24V, Mi-28N, Ka-52 | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| RHSUSAF | AH-6M, MH-6M, CH-53E | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| Su-34M (UMPK) | Su-34M | RHSAFRF; Improved RHS MiG-29SM + FIR support; FIR AWS (+ dependencias transitivas del MiG mod) | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3137489963) |
| SU-35 Flanker E | Su-35 | Sin dependencia obligatoria adicional declarada en Workshop | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=743108251) |

## 5.1 Dependencias auxiliares

| Dependencia | Workshop |
|---|---|
| ACE3 | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=463939057) |
| CBA_A3 | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=450814997) |
| FIR AWS | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=366425329) |
| Hatchet Interaction Framework | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=2941986336) |
| Lala Peral - Vehicle Interaction System | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801) |
| RHSGREF | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843593391) |
| RHSAFRF | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843425103) |
| RHSSAF | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843632231) |
| RHSUSAF | [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=843577117) |
| USAF Mod - Main | [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831) |

> **Nota ROAN:** una compatibilidad opcional (por ejemplo, un missilebox alternativo) no se considera dependencia obligatoria salvo que la misión la utilice de forma explícita.

[↑ Volver al índice](#indice)

---

<a id="ala-fija-blufor"></a>
# 6. Ala fija — BLUFOR

Esta sección contiene las aeronaves autorizadas de **Ala fija — BLUFOR**.

## Aeronaves

- [A-10C Thunderbolt II](#a10c)
- [C-130 E/H/J Hercules Series](#c130)
- [F/A-18E Super Hornet](#fa18ef)
- [F-35B Lightning II](#f35b)
- [F-35C Lightning II](#f35c)

---

<a id="a10c"></a>
## A-10C Thunderbolt II

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/520a71da-3f1e-433d-9971-1e2984bd9176" />

### Información general

Avión de ataque subsónico, bimotor y monoplaza diseñado alrededor del cañón GAU-8/A. Su función principal es el apoyo aéreo cercano (CAS), la destrucción de blindados y la permanencia prolongada sobre el área de operaciones. Su baja velocidad relativa, resistencia estructural y buena visibilidad desde cabina favorecen el trabajo coordinado con JTAC y tropas terrestres.

### Base de los datos técnicos

Las cifras de prestaciones son referencias del A-10C real. Los sistemas interactivos y la disponibilidad exacta de municiones se basan en la implementación del mod y pueden variar con su versión.

### Roles ROAN

- CAS — Close Air Support
- Ataque antiblindaje
- Interdicción táctica
- FAC(A) / coordinación aérea avanzada cuando la misión lo requiera
- Apoyo a CSAR y fuerzas terrestres en entornos permisivos o semi-permisivos

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 420 mph / 365 kt / 676 km/h |
| Velocidad de crucero | ≈ 300 kt / 556 km/h, dependiente de carga y altitud |
| Techo de servicio | ≈ 45,000 ft / 13,700 m |
| Alcance de referencia | ≈ 800 mi / 695 NM / 1,287 km sin reabastecimiento; depende del perfil |
| Autonomía | Variable según carga y perfil; optimizado para permanencia prolongada en CAS |
| Peso máximo al despegue | ≈ 51,000 lb / 23,130 kg |
| Carga bélica externa máxima | Hasta ≈ 16,000 lb / 7,260 kg |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

No es una plataforma de transporte. Su capacidad de carga corresponde a armamento, tanques externos y pods. La carga bélica real de referencia es de hasta aproximadamente 7.26 t, aunque en Arma 3 debe seleccionarse una configuración coherente con la misión.

### Armamento

Cañón **GAU-8/A Avenger de 30 mm** como arma principal. Dependiendo de la configuración del mod puede emplear misiles AGM-65 Maverick, bombas convencionales, bombas guiadas por láser/GPS, cohetes, AIM-9 para autodefensa y pods de contramedidas/ECM.

### Sensores y sistemas

El mod anuncia cabina interactiva, sistema de carga dinámica, contramedidas, RWR, navegación/moving map, designación GPS y empleo de pod electro-óptico/FLIR tipo AN/AAQ-28. La aeronave real A-10C integra aviónica digital, navegación GPS/INS, datalink y capacidad de empleo de pods de designación (TGT).

### Escenarios recomendados

- CAS sobre fuerzas amigas con JTAC o control terrestre
- Ataque contra columnas blindadas, vehículos y posiciones fortificadas
- Interdicción de convoyes y objetivos de superficie
- Misiones en las que se requiera permanecer sobre el AO y efectuar múltiples pasadas

### Escenarios no recomendados

- Superioridad aérea o CAP frente a cazas modernos
- Penetración inicial de una red SAM intacta
- Ataques a baja cota sobre zonas con alta densidad de MANPADS/AAA sin supresión previa

### Fortalezas

- Gran potencia de fuego contra objetivos terrestres
- Excelente permanencia y control a baja velocidad
- Alta resistencia al daño comparada con cazas ligeros
- Muy eficaz en coordinación con JTAC

### Debilidades

- Velocidad baja frente a cazas
- Firma y perfil poco adecuados para penetración furtiva
- Vulnerable a SAM modernos, MANPADS y AAA cuando opera bajo

### Fuerte contra

- Blindados y vehículos
- Infantería y posiciones terrestres
- Convoyes
- Objetivos de oportunidad con defensa aérea limitada

### Débil contra

- Cazas modernos
- SAM de medio/largo alcance
- MANPADS y AAA densos en vuelos bajos

### Limitaciones operativas

- Debe evitarse emplearlo como sustituto de un caza de superioridad aérea.
- En áreas con IADS activa debe operar después de SEAD/DEAD o bajo cobertura adecuada.
- La cantidad y tipo exactos de pilones/armas dependen de la versión del mod.

### MOD

[A-10C Thunderbolt](https://steamcommunity.com/sharedfiles/filedetails/?id=2848059590)

### Dependencias

- [Lala Peral - Vehicle Interaction System (VIS)](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801)
- [USAF Mod - Main](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831)

### Observaciones ROAN

- ROAN debe priorizar su empleo como plataforma CAS/antiblindaje.
- Para ataques cercanos a fuerzas amigas se recomienda control JTAC y establecimiento de ejes de ataque, altitudes y zonas de seguridad.
- No debe usarse su capacidad de carga máxima como configuración estándar: la carga debe responder al objetivo y amenazas.


[↑ Volver a Ala fija — BLUFOR](#ala-fija-blufor)  
[↑ Volver al índice](#indice)

---

<a id="c130"></a>
## C-130 E/H/J Hercules Series

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/116272ba-16fa-4181-881a-b7888ef4e32a" />

### Información general

Transporte táctico cuatrimotor turbohélice concebido para mover personal, carga y vehículos desde pistas relativamente cortas y austeras. Es una plataforma logística de largo alcance para inserción aerotransportada, transporte de suministros, MEDEVAC y apoyo a fuerzas desplegadas.

### Base de los datos técnicos

El mod cubre variantes C-130E/H/J y J-30; por ello las prestaciones se presentan por familia. Las cifras son referencias USAF y las capacidades de carga del mod se complementan con su sistema flexible de transporte.

### Roles ROAN

- Transporte táctico y logístico
- Transporte de tropas
- Lanzamiento de paracaidistas y carga
- MEDEVAC / evacuación aeromédica según configuración
- Reabastecimiento logístico entre bases

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima / de referencia | C-130E ≈ 300 kt; C-130H ≈ 318 kt; C-130J ≈ 362 kt / 417 mph |
| Techo con carga de referencia | E ≈ 19,000 ft; H ≈ 23,000 ft; J ≈ 28,000 ft con 42,000 lb de carga |
| Alcance con carga normal | E ≈ 1,000 NM; H ≈ 1,050 NM; J ≈ 1,800 NM; J-30 ≈ 1,700 NM |
| Carga útil máxima de referencia | E/H/J ≈ 42,000 lb / 19,090 kg; J-30 ≈ 44,000 lb / 19,960 kg |
| Capacidad de pallets | E/H/J: 6 pallets; J-30: 8 pallets |
| Peso máximo al despegue | Varía por variante; aproximadamente 70–79 t en la familia |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto/loadmaster) |
| Tripulación máxima | 3 (piloto, copiloto y loadmaster); personal de misión adicional según tarea |
| Pasajeros / tropas | Hasta 94 tropas |

### Capacidad de carga

El mod anuncia un sistema flexible de carga que permite combinar **infantería y vehículos**. Como referencia real, la familia maneja aproximadamente 19 t de carga útil; la variante J-30 aumenta ligeramente esa capacidad y dispone de una bodega más larga.

### Armamento

Las variantes de transporte C-130 E/H/J son normalmente **no armadas**. ROAN no debe asumir capacidad AC-130 salvo que una variante gunship sea incorporada expresamente al catálogo en el futuro.

### Sensores y sistemas

Radar meteorológico, navegación inercial/GPS y aviónica de transporte. El C-130J incorpora cabina digital y sistemas modernos de navegación/gestión de vuelo. La implementación concreta en Arma 3 depende de la variante seleccionada.

### Escenarios recomendados

- Transporte de tropas entre bases o AO distantes
- Reabastecimiento de FOB y aeródromos
- Inserción paracaidista
- Movimiento de vehículos ligeros y carga paletizada
- MEDEVAC de gran capacidad cuando el escenario lo requiera

### Escenarios no recomendados

- Entrar en un AO con defensa aérea enemiga activa sin escolta/supresión
- Aterrizar en LZ improvisadas sin longitud y superficie suficientes
- Empleo como plataforma de ataque si la variante seleccionada no lo contempla

### Fortalezas

- Gran volumen interno y flexibilidad de carga
- Buen alcance táctico
- Capacidad de operar desde pistas relativamente austeras
- Excelente plataforma logística para campañas largas

### Debilidades

- Grande, lento y poco maniobrable frente a amenazas de combate
- Firma visual/radar significativa
- Dependencia de pista para despegue y aterrizaje

### Fuerte contra

- No aplica como plataforma de combate; su fortaleza es superar distancias y restricciones logísticas

### Débil contra

- Cazas enemigos
- SAM de cualquier alcance
- MANPADS/AAA durante aproximaciones y despegues

### Limitaciones operativas

- Debe planearse una ruta segura y, en zona hostil, escolta o supresión de defensas.
- La capacidad real de asientos y vehículos en Arma 3 puede cambiar entre las variantes E/H/J/J-30 del mod.
- No se debe sobrecargar la bodega solo porque el juego permita ubicar físicamente más objetos.

### MOD

[C-130 E/H/J Hercules Series](https://steamcommunity.com/sharedfiles/filedetails/?id=3122396633)

### Dependencias

- [FIR AWS (AirWeaponSystem)](https://steamcommunity.com/workshop/filedetails/?id=366425329)

### Observaciones ROAN

- Para ROAN su rol primario es logística y transporte, no combate.
- El piloto debe confirmar variante, peso, longitud de pista y ruta antes de la operación.
- En misiones de lanzamiento aéreo debe coordinarse DZ, altitud, rumbo y señal de lanzamiento.

[↑ Volver a Ala fija — BLUFOR](#ala-fija-blufor)  
[↑ Volver al índice](#indice)

---

<a id="fa18ef"></a>
## F/A-18E Super Hornet

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/26907094-c9b2-42cf-85c2-93e1e71ea612" />

### Información general

Caza embarcado multirrol diseñado para operar desde portaaviones [CATOBAR](#nimitz). Combina superioridad aérea, escolta, ataque de precisión, CAS y supresión de defensas, por lo que constituye una de las plataformas más versátiles del inventario ROAN.

### Base de los datos técnicos

Prestaciones basadas en el F/A-18E real. El mod añade una versión actualizada con cabina y funciones interactivas; la disponibilidad exacta de armas depende de la configuración del addon.

### Roles ROAN

- CAP / superioridad aérea
- Interceptación y escolta
- CAS
- Ataque de precisión e interdicción
- SEAD / DEAD
- Operaciones embarcadas CATOBAR

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | Mach 1.8+ / aproximadamente 1,915 km/h a gran altitud |
| Velocidad de crucero | Subsónica, normalmente ≈ Mach 0.8–0.9 según carga |
| Techo de servicio | 50,000+ ft / 15,240+ m |
| Alcance de referencia USN | ≈ 1,275 NM / 2,360 km |
| Alcance de traslado | ≈ 1,660 NM / 3,070 km |
| Peso máximo al despegue | ≈ 66,000 lb / 29,940 kg |
| Carga externa | ≈ 17,750 lb / 8,050 kg en pilones externos |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

No transporta pasajeros ni carga logística. Su carga consiste en combustible externo, pods y armamento distribuido en estaciones externas.

### Armamento

Cañón **M61A2 de 20 mm** y combinaciones de AIM-9, AIM-120, AGM-88 HARM, AGM-84/SLAM/Harpoon según integración, JDAM, JSOW, Paveway, bombas convencionales y otras municiones aire-superficie. La selección exacta debe hacerse desde las opciones disponibles en el mod.

### Sensores y sistemas

Radar multimodo de combate, RWR, navegación táctica, datalink y pods de designación. En variantes modernas el radar real es APG-79 AESA; el comportamiento exacto del radar/sensores del addon debe asumirse como el que presente la versión instalada.

### Escenarios recomendados

- CAP y defensa aérea de flota
- Escolta de transportes/helicópteros
- CAS y strike desde portaaviones
- SEAD/DEAD con armamento adecuado
- Interdicción marítima o terrestre

### Escenarios no recomendados

- Misiones de transporte o logística
- Operaciones desde LHA sin infraestructura compatible CATOBAR/STOBAR
- Ataque profundo sin considerar combustible, tanker y defensa aérea enemiga

### Fortalezas

- Multirrol genuino
- Excelente compatibilidad con operaciones de portaaviones
- Buena combinación de radar, armas BVR y precisión aire-superficie
- F/A-18F permite reparto de tareas piloto/WSO

### Debilidades

- Menor alcance que plataformas dedicadas de strike de largo radio
- Carga y autonomía se reducen con configuraciones aire-aire/aire-tierra pesadas
- Operación embarcada exige disciplina de cubierta y recuperación

### Fuerte contra

- Cazas y aeronaves enemigas
- Objetivos terrestres y navales
- Emisores/radares cuando dispone de armamento SEAD
- Blancos de precisión

### Débil contra

- IADS moderna si entra sin planificación SEAD/DEAD
- Cazas con ventaja de detección/posición si el piloto pierde conciencia situacional

### Limitaciones operativas

- Para operaciones Nimitz debe respetarse el procedimiento de catapulta, patrón, marshal y apontaje definido por ROAN.
- La carga máxima teórica no equivale a una configuración óptima.

### MOD

[F/A-18E/F Super Hornet 2020](https://steamcommunity.com/sharedfiles/filedetails/?id=2131302796)

### Dependencias

- No declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma preferente de ROAN para operaciones de ala fija desde [Nimitz](#nimitz).
- Debe priorizarse una configuración acorde con el paquete de misión: CAP, CAS, SEAD o strike.
- El empleo de la variante F **SOLO** es recomendable para entrenamiento.

[↑ Volver a Ala fija — BLUFOR](#ala-fija-blufor)  
[↑ Volver al índice](#indice)

---

<a id="f35b"></a>
## F-35B Lightning II

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/efdda857-6f08-41cc-bd87-9b763cc79c45" />

### Información general

Variante STOVL del F-35 diseñada para despegues cortos y aterrizajes verticales. Está orientada a ataque de precisión, superioridad aérea, ISR y operaciones desde buques anfibios o bases con infraestructura limitada.

### Base de los datos técnicos

Prestaciones basadas en datos públicos del F-35B real; los sistemas interactivos, cámaras y carga dinámica se complementan con lo anunciado por el mod.

### Roles ROAN

- Multirrol
- CAP / defensa aérea
- Ataque de precisión
- CAS
- SEAD / DEAD
- ISR
- Operaciones STOVL desde [LHA](#lha)

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | Mach 1.6 / ≈ 1,930 km/h |
| Techo de servicio | ≈ 50,000 ft / 15,240 m |
| Alcance con combustible interno | > 900 NM / > 1,670 km |
| Radio de combate | > 450 NM / > 830 km |
| Carga de armas total de referencia | ≈ 15,000 lb / 6,800 kg |
| Peso máximo al despegue | Clase de ≈ 60,000 lb / 27,200 kg |
| Capacidad STOVL | Despegue corto y aterrizaje vertical; la carga/combustible condicionan el rendimiento vertical |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

No transporta personal. La carga corresponde a armamento interno/externo y combustible. Para mantener baja observabilidad real se prioriza armamento interno; en Arma 3 el efecto de firma depende de la simulación del mod.

### Armamento

Combinaciones aire-aire y aire-superficie: AIM-120, AIM-9 en configuraciones externas, JDAM/GBU, AGM y otras municiones según la integración del mod. La variante B real no lleva cañón interno y utiliza un pod de cañón cuando se requiere.

### Sensores y sistemas

Radar AESA, EOTS, DAS y suite de guerra electrónica/sensor fusion en la aeronave real. El mod anuncia cabina interactiva, moving map, RWR, designación/cámaras para municiones, TGP y sistema de carga/contramedidas.

### Escenarios recomendados

- Operaciones desde [LHA](#lha)
- Strike de precisión
- CAP y escolta
- SEAD/DEAD cuando la carga del mod lo permita
- Misiones donde la flexibilidad STOVL sea decisiva

### Escenarios no recomendados

- Aterrizaje vertical con combustible/carga incompatibles con la maniobra
- Operaciones logísticas o transporte
- Uso indiscriminado de hover/VTOL en zonas con amenaza terrestre

### Fortalezas

- STOVL permite operar sin catapulta
- Gran conciencia situacional y sensores
- Buena combinación aire-aire/aire-tierra
- Adecuado para operaciones anfibias

### Debilidades

- Menor alcance y carga que F-35C
- Aterrizaje vertical exige control de peso y consumo
- Hover lo vuelve vulnerable y consume combustible

### Fuerte contra

- Cazas
- Objetivos terrestres de alto valor
- Defensas aéreas y radares si se configura para SEAD/strike
- Blancos navales según armamento disponible

### Débil contra

- Amenazas de corto alcance durante hover/vertical landing
- IADS si se opera sin táctica ni armamento adecuados

### Limitaciones operativas

- STOVL no significa que cualquier peso pueda recuperarse verticalmente.
- En LHA se debe utilizar la cubierta, spawner y zonas de rearmado/reparación conforme a la misión.
- Las integraciones opcionales con USAF Missilebox no deben confundirse con dependencias obligatorias.

### MOD

[F-35B Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3517620967)

### Dependencias

- [Lala Peral - Vehicle Interaction System (VIS)](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801)
- [USAF Mod - Main](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831)

### Observaciones ROAN

- Plataforma principal de ala fija para operaciones desde [LHA](#lha).
- ROAN debe entrenar por separado despegue corto, transición y aterrizaje vertical.
- La prioridad es conservar combustible suficiente para recuperación segura.

[↑ Volver a Ala fija — BLUFOR](#ala-fija-blufor)  
[↑ Volver al índice](#indice)

---

<a id="f35c"></a>
## F-Lightning II

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/e24e8a4e-0eac-4ada-8775-61f945506541" />

### Información general

Variante naval embarcada del F-35, diseñada específicamente para catapultas y cables de apontaje. Posee mayor ala y combustible interno que el F-35B, obteniendo mejor alcance y persistencia para operaciones desde portaaviones.

### Base de los datos técnicos

Prestaciones basadas en datos públicos del F-35C real. El mod implementa la variante embarcada CATOBAR con alas mayores/plegables y tren reforzado.

### Roles ROAN

- CAP / superioridad aérea
- Ataque de precisión
- CAS
- SEAD / DEAD
- ISR
- Operaciones CATOBAR

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | Mach 1.6 / ≈ 1,930 km/h |
| Techo de servicio | ≈ 50,000 ft / 15,240 m |
| Alcance con combustible interno | > 1,200 NM / > 2,220 km |
| Radio de combate | > 600 NM / > 1,110 km |
| Carga de armas total de referencia | ≈ 18,000 lb / 8,160 kg |
| Peso máximo al despegue | Clase de ≈ 70,000 lb / 31,750 kg |
| Operación embarcada | CATOBAR; alas plegables y tren reforzado |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

No transporta pasajeros. La carga corresponde a armamento y combustible; su mayor ala y combustible le dan ventaja de alcance frente a la variante B.

### Armamento

AIM-120, AIM-9 en estaciones externas, JDAM/GBU y otras armas aire-superficie compatibles con la implementación. La configuración exacta depende del menú/pilones del mod.

### Sensores y sistemas

Radar AESA, EOTS, DAS y guerra electrónica en la plataforma real; el mod integra cabina interactiva, moving map, RWR, cámaras/targeting y gestión dinámica de carga.

### Escenarios recomendados

- CAP de flota
- Strike de largo alcance desde portaaviones
- SEAD/DEAD
- Escolta
- Ataque de precisión y reconocimiento armado

### Escenarios no recomendados

- Operación desde LHA como sustituto del F-35B
- Aterrizajes sin cable o pistas improvisadas no aptas
- Uso como plataforma logística

### Fortalezas

- Mayor alcance/persistencia que F-35B
- Optimizado para portaaviones CATOBAR
- Sensores y conciencia situacional avanzados
- Buena capacidad multirrol

### Debilidades

- Depende de catapulta/cables para ciclo embarcado completo
- Mayor tamaño que F-35B
- La carga externa compromete las ventajas de baja observabilidad real

### Fuerte contra

- Cazas
- Objetivos de alto valor
- Defensas aéreas cuando se emplea correctamente
- Blancos terrestres/navales con armamento adecuado

### Débil contra

- IADS densa si se emplea sin planificación
- Amenazas en patrón de recuperación si el carrier group no está protegido

### Limitaciones operativas

- En Nimitz debe seguirse el procedimiento CATOBAR de ROAN.
- No debe intentarse empleo STOVL: esa capacidad corresponde al F-35B.
- Mantener reservas de combustible para marshal, bolter y recuperación alterna.

### MOD

[F-35C Lightning](https://steamcommunity.com/sharedfiles/filedetails/?id=3083645332)

### Dependencias

- [Lala Peral - Vehicle Interaction System (VIS)](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801)
- [USAF Mod - Main](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831)

### Observaciones ROAN

- Junto con el F/A-18E, constituye la plataforma principal para operaciones de ala fija desde Nimitz.
- Debe entrenarse específicamente apontaje con cable y bolter.
- Su mayor radio lo hace preferible para CAP/strike a mayor distancia del carrier.

[↑ Volver a Ala fija — BLUFOR](#ala-fija-blufor)  
[↑ Volver al índice](#indice)

---

<a id="ala-fija-opfor"></a>
# 7. Ala fija — OPFOR

Esta sección contiene las aeronaves autorizadas de **Ala fija — OPFOR**.

## Aeronaves

- [MiG-29SM Fulcrum](#mig29sm)
- [Su-34M Fullback](#su34m)
- [Su-35 Flanker-E](#su35)

---

<a id="mig29sm"></a>
## MiG-29SM Fulcrum

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/207910c8-fa2f-4b43-933c-01f6eae08608" />

### Información general

Caza ligero/medio de alta maniobrabilidad modernizado para ampliar la capacidad aire-superficie del MiG-29 original. El SM combina defensa aérea, interceptación y ataque de precisión, conservando buenas prestaciones de combate cercano.

### Base de los datos técnicos

Prestaciones basadas en datos publicados de la modernización MiG-29SM/SMT como referencia. El mod mejora el MiG-29 de RHS y agrega soporte FIR, imagen térmica y capacidad de armamento ampliada.

### Roles ROAN

- CAP / superioridad aérea local
- Interceptación
- Escolta
- Ataque aire-superficie
- Interdicción táctica

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima a gran altitud | ≈ 2,400 km/h / Mach 2.25 |
| Velocidad máxima a nivel del mar | ≈ 1,500 km/h |
| Techo de servicio | ≈ 17,750 m / 58,235 ft |
| Alcance de traslado | ≈ 1,500 km sin tanques; ≈ 2,900 km con 3 tanques; > 5,000 km con tanques + 1 reabastecimiento |
| Peso máximo al despegue | ≈ 20,000 kg |
| Carga externa de referencia | ≈ 4,000 kg |
| Estaciones externas | 6 en la referencia MiG-29SM |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

No es transporte. Su carga útil se dedica a misiles, bombas, pods y tanques externos; el MiG-29SM real de referencia maneja alrededor de 4 t de armamento.

### Armamento

Cañón GSh-301 de 30 mm; R-73, R-27 y RVV-AE/R-77; Kh-29, Kh-31, Kh-25 y bombas guiadas KAB-500, además de armamento no guiado según la configuración FIR/RHS disponible.

### Sensores y sistemas

Radar de combate, sistema electro-óptico/IRST y designación montada en casco en variantes modernas. El mod anuncia soporte FIR, imagen térmica y mira láser para empleo aire-superficie.

### Escenarios recomendados

- CAP de corto/medio alcance
- Interceptación rápida
- Combate BVR y WVR
- Ataque táctico contra blancos terrestres
- Adversario OPFOR para entrenamiento aire-aire ROAN

### Escenarios no recomendados

- Strike de muy largo alcance sin tanques/reabastecimiento
- Penetración profunda con alta carga y sin apoyo
- Misiones donde se requiera gran persistencia en estación

### Fortalezas

- Muy buena maniobrabilidad
- Alta velocidad y aceleración
- Capacidad aire-aire y aire-superficie
- Amplia integración de armas mediante FIR

### Debilidades

- Menor alcance/persistencia que cazas pesados
- Carga útil inferior a Su-34/Su-35
- Dependencia fuerte del combustible en perfiles agresivos

### Fuerte contra

- Cazas y helicópteros
- Objetivos terrestres puntuales
- Radares/objetivos navales con armamento apropiado

### Débil contra

- Cazas con ventaja BVR/sensores si se lo detecta primero
- SAM de medio/largo alcance sin apoyo SEAD

### Limitaciones operativas

- Planificar combustible y tanques externos antes de misiones largas.
- La gran cantidad de dependencias debe estar presente en todos los clientes/servidor.
- Las armas disponibles dependen de la combinación exacta RHS + FIR instalada.

### MOD

[Improved RHS MiG-29SM + FIR support](https://steamcommunity.com/sharedfiles/filedetails/?id=2987850906)

### Dependencias

- [FIR AWS (AirWeaponSystem)](https://steamcommunity.com/workshop/filedetails/?id=366425329)
- [RHSGREF](https://steamcommunity.com/workshop/filedetails/?id=843593391)
- [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)
- [RHSSAF](https://steamcommunity.com/workshop/filedetails/?id=843632231)
- [RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117)

### Observaciones ROAN

- Excelente plataforma adversaria para prácticas BVR/WVR.
- ROAN debe tratar la carga FIR como parte integral de la planificación de pilones.
- Para ataque de precisión se recomienda confirmar qué sensores/municiones están funcionales en la versión del mod usada por la misión.

[↑ Volver a Ala fija — OPFOR](#ala-fija-opfor)  
[↑ Volver al índice](#indice)

---

<a id="su34m"></a>
## Su-34M Fullback

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/1efa819f-549c-4b79-9377-13d43efdf25c" />

### Información general

Avión biplaza de ataque de largo alcance derivado de la familia Su-27. Está optimizado para strike, interdicción y ataque de precisión, con gran carga útil, autonomía y una cabina lado a lado que reparte las tareas entre piloto y navegador/operador de sistemas.

### Base de los datos técnicos

Prestaciones tomadas como referencia del Su-34/Su-34E real. El mod agrega una variante Su-34 con municiones UMPK y bombas del ecosistema RHS.

### Roles ROAN

- Strike / ataque de precisión
- Interdicción
- Ataque contra infraestructura
- Ataque antiblindaje
- SEAD/DEAD según armamento disponible
- Autodefensa aire-aire

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima a nivel del mar | ≈ 1,100 km/h |
| Velocidad máxima a altitud | ≈ 1,500 km/h / Mach 1.5 |
| Techo de servicio | ≈ 15,000 m / 49,200 ft |
| Radio máximo con tanques externos | Hasta ≈ 1,700 km |
| Alcance de traslado | ≈ 4,250 km |
| Duración máxima de vuelo de referencia | Hasta ≈ 10 h, condicionada por tripulación/perfil |
| Carga de combate máxima | ≈ 8,500 kg |
| Peso normal al despegue | ≈ 39,500 kg |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 2 (piloto y operador) |
| Tripulación recomendada | 2 (piloto y operador) |
| Tripulación máxima | 2 (piloto y operador) |
| Pasajeros | 0 |

### Capacidad de carga

Puede transportar alrededor de 8.5 t de carga de combate real de referencia. La configuración del mod incluye UMPK y otras bombas/misiles provenientes de RHS/FIR.

### Armamento

Cañón interno GSh-30-1 de 30 mm; bombas guiadas/no guiadas, UMPK, misiles aire-superficie y aire-aire según integración. El mod se centra especialmente en munición UMPK y bombas RHS.

### Sensores y sistemas

Radar multimodo, navegación/ataque de largo alcance, suite de guerra electrónica y designación de blancos de la plataforma real. En el juego, la efectividad depende de las funciones heredadas de RHS/FIR y del addon.

### Escenarios recomendados

- Ataque de precisión a distancia
- Interdicción de bases, puentes, depósitos y concentraciones enemigas
- Ataques con gran carga de bombas
- Misiones OPFOR de strike a media/larga distancia

### Escenarios no recomendados

- Dogfight como función principal
- CAS muy cercano a fuerzas amigas cuando hay una plataforma más apropiada
- Operaciones desde pistas muy cortas o portaaviones

### Fortalezas

- Gran carga bélica
- Buen radio de acción
- Dos tripulantes para repartir navegación/armas
- Adecuado para ataque de precisión pesado

### Debilidades

- Grande y menos ágil que cazas puros
- Firma elevada
- Requiere protección/planificación en espacio aéreo fuertemente disputado

### Fuerte contra

- Infraestructura y objetivos de área
- Blindados y posiciones fortificadas
- Objetivos de alto valor a distancia

### Débil contra

- Cazas de superioridad aérea si entra cargado
- SAM modernos sin escolta/SEAD

### Limitaciones operativas

- Debe operar desde aeródromos adecuados.
- No se recomienda configurar el máximo de bombas si compromete combustible o maniobrabilidad.
- Las UMPK y otras armas dependen de que toda la cadena de dependencias del mod esté cargada.

### MOD

[Su-34M (UMPK)](https://steamcommunity.com/sharedfiles/filedetails/?id=3137489963)

### Dependencias

- [RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)
- [Improved RHS MiG-29SM + FIR support](https://steamcommunity.com/sharedfiles/filedetails/?id=2987850906)
- [FIR AWS (AirWeaponSystem)](https://steamcommunity.com/workshop/filedetails/?id=366425329)
- Dependencias transitivas del Improved MiG-29SM: RHSGREF, RHSSAF y RHSUSAF.

### Observaciones ROAN

- ROAN debe usarlo como plataforma de strike, no como sustituto de un caza ligero.
- En misión MP, confirmar que todos los clientes tengan la cadena completa RHS/FIR.
- Los ataques UMPK son apropiados cuando se desea mantener mayor separación de las defensas terrestres.

[↑ Volver a Ala fija — OPFOR](#ala-fija-opfor)  
[↑ Volver al índice](#indice)

---

<a id="su35"></a>
## Su-35 Flanker-E

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/d60d8a47-0f67-48b0-a67d-2e5d9804ecf9" />

### Información general

Caza pesado monoplaza de gran maniobrabilidad, autonomía y carga de armas. Está orientado principalmente a superioridad aérea y combate BVR/WVR, pero conserva una importante capacidad aire-superficie.

### Base de los datos técnicos

Prestaciones basadas en la ficha oficial de UAC para el Su-35. El mod representa el Su-35S/Flanker-E y puede simplificar algunos sensores o armas.

### Roles ROAN

- Superioridad aérea
- CAP
- Interceptación
- Escolta
- Ataque multirrol
- Adversario avanzado para entrenamiento ROAN

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima a nivel del mar | ≈ 1,400 km/h |
| Velocidad máxima a altitud | Mach 2.25 |
| Techo de servicio | ≈ 18,000 m / 59,055 ft |
| Alcance práctico a baja cota | ≈ 1,580 km |
| Alcance práctico a altitud de crucero | ≈ 3,600 km sin reabastecimiento |
| Peso máximo al despegue | ≈ 34,500 kg |
| Carga de combate máxima | ≈ 8,000 kg en 12 estaciones |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 1 (piloto) |
| Tripulación máxima | 1 (piloto) |
| Pasajeros | 0 |

### Capacidad de carga

Hasta aproximadamente 8 t de armamento externo en 12 estaciones en la aeronave real. No posee capacidad de transporte.

### Armamento

Cañón de 30 mm y amplia familia de misiles aire-aire de corto/medio/largo alcance, además de misiles aire-superficie, antirradiación/antibuque, bombas guiadas y no guiadas según integración del mod.

### Sensores y sistemas

Radar de antena en fase con detección de blancos aéreos de hasta ~350 km en condiciones ideales de referencia; puede seguir múltiples contactos y atacar varios. Integra OLS/IRST con alcance de detección de hasta ~80 km en condiciones favorables, además de guerra electrónica.

### Escenarios recomendados

- Superioridad aérea
- CAP de largo radio
- Interceptación
- Escolta de plataformas de strike
- Entrenamiento avanzado BVR/WVR contra ROAN

### Escenarios no recomendados

- Transporte/logística
- CAS lento y persistente cuando existe helicóptero/A-10
- Operaciones embarcadas en Nimitz/LHA

### Fortalezas

- Excelente maniobrabilidad y empuje vectorial
- Gran alcance
- Radar y capacidad BVR potentes
- Alta carga de armas

### Debilidades

- Gran firma física/radar frente a plataformas furtivas
- Coste de combustible/carga alto en misiones largas
- No está optimizado para operaciones embarcadas

### Fuerte contra

- Cazas y aeronaves de apoyo
- Helicópteros
- Objetivos terrestres/navales con armamento apropiado

### Débil contra

- Plataformas con ventaja de detección/stealth si no logra localizar primero
- IADS en penetración sin supresión

### Limitaciones operativas

- La distancia de detección real en Arma 3 puede ser inferior o funcionar de manera diferente a la cifra real.
- No debe considerarse invulnerable por su maniobrabilidad; la gestión BVR sigue siendo prioritaria.
- Las armas exactas dependen del addon instalado.

### MOD

[SU-35 Flanker E](https://steamcommunity.com/sharedfiles/filedetails/?id=743108251)

### Dependencias

- No declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma OPFOR ideal para pruebas de superioridad aérea.
- ROAN puede emplearlo para instrucción sobre amenazas de gran maniobrabilidad y largo alcance.
- En misiones PvE puede reservarse para adversarios de alto nivel.

[↑ Volver a Ala fija — OPFOR](#ala-fija-opfor)  
[↑ Volver al índice](#indice)

---

<a id="ala-rotativa-blufor"></a>
# 8. Ala rotativa — BLUFOR

Esta sección contiene las aeronaves autorizadas de **Ala rotativa — BLUFOR**.

## Aeronaves

- [H-60 Series](#h60)
- [AH-1Z Viper](#ah1z)
- [AH-6M Little Bird](#ah6m)
- [MH-6M Little Bird](#mh6m)
- [CH-53E Super Stallion](#ch53e)
- [MH-47G Chinook](#mh47g)

---

<a id="h60"></a>
## H-60 Series

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/775041be-6593-4fe6-8374-8345b8e1ae3f" />

### Información general

Familia de helicópteros medianos utilitarios y de operaciones especiales. El Hatchet H-60 Pack busca una experiencia de mayor fidelidad con cabina interactiva y procedimientos de arranque/operación. Dependiendo de la variante puede cubrir transporte, asalto aéreo, MEDEVAC, operaciones navales y apoyo armado.

### Base de los datos técnicos

Hatchet incluye varias configuraciones de la familia H-60. Las cifras se presentan con el UH-60M como referencia de rendimiento/carga y deben interpretarse como baseline, no como un valor idéntico para cada variante del pack.

### Roles ROAN

- Transporte táctico
- Inserción y extracción
- MEDEVAC / CASEVAC
- Operaciones especiales
- Logística y sling load
- SAR/CSAR según variante
- Operaciones aeronavales según variante

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima/crucero de referencia UH-60M | ≈ 151 kt / 280 km/h |
| Techo de servicio de referencia | ≈ 15,000 ft / 4,570 m |
| Alcance de referencia | ≈ 276 NM / 511 km; ampliable con tanques en variantes equipadas |
| Peso máximo al despegue UH-60M | ≈ 22,000 lb / 9,979 kg |
| Carga externa por gancho | Hasta ≈ 9,000 lb / 4,080 kg |
| Carga interna de referencia UH-60M | ≈ 3,190 lb / 1,447 kg en configuración militar tradicional |
| Capacidad de tropas | ≈ 11 tropas equipadas como baseline UH-60M |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 4 (piloto, copiloto y crew chiefs/artilleros cuando aplique) |
| Pasajeros | Slick 4, Pavehawk  9, Blackhawk 10, MEDEVAC 15 |

### Capacidad de carga

Como baseline UH-60M: hasta ~4.08 t en gancho externo. La carga interna y el número de asientos cambian entre UH/MH/HH/SH y según tanques, camillas o equipos de misión.

### Armamento

Depende de la variante. Puede incluir M240/M134 u otras armas de puerta y, en configuraciones armadas/DAP, armamento ofensivo adicional. No debe asumirse que toda variante H-60 posee la misma carga.

### Sensores y sistemas

El Hatchet Pack se centra en cabina interactiva y una experiencia tipo simulador. Las variantes reales pueden incluir FLIR, radar meteorológico, RWR/MAWS, GPS/INS, sistemas de navegación táctica y equipos de misión naval/especial.

### Escenarios recomendados

- Asalto aéreo
- Inserción/extracción de escuadras
- MEDEVAC
- Operaciones especiales nocturnas
- Sling load ligero/medio
- Operaciones desde [LHA](#lha) y buques cuando la variante sea compatible

### Escenarios no recomendados

- Transporte de cargas muy pesadas que requieran CH-47/CH-53
- Ataque frontal contra posiciones AA preparadas
- Operación monotripulada en prácticas ROAN de alta fidelidad

### Fortalezas

- Muy versátil
- Tamaño adecuado para LZ relativamente pequeñas
- Buena combinación de velocidad, carga y maniobrabilidad
- Hatchet permite entrenamiento de procedimientos y cabina

### Debilidades

- Carga inferior a helicópteros pesados
- Vulnerable a MANPADS/AAA
- La complejidad del Hatchet eleva la carga de trabajo de la tripulación

### Fuerte contra

- No es una plataforma de ataque primaria; en variantes armadas es eficaz contra infantería/vehículos ligeros y como escolta cercana

### Débil contra

- MANPADS
- AAA
- Armas ligeras concentradas durante hover/LZ
- Cazas enemigos

### Limitaciones operativas

- Las cifras de esta ficha son baseline UH-60M; la variante seleccionada en Eden manda sobre asientos, sensores y armamento.
- ROAN debe emplear al menos dos pilotos en entrenamiento de procedimientos Hatchet.
- Para sling load debe verificarse que la masa del objeto esté dentro del límite de la variante.

### MOD

[Hatchet H-60 Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=1745501605)

### Dependencias

- [Hatchet Interaction Framework - Stable Version](https://steamcommunity.com/workshop/filedetails/?id=2941986336)
- [ACE3](https://steamcommunity.com/workshop/filedetails/?id=463939057)
- [CBA_A3](https://steamcommunity.com/workshop/filedetails/?id=450814997) — dependencia transitiva de Hatchet/ACE

### Observaciones ROAN

- Es la familia de helicópteros de entrenamiento avanzado recomendada para ROAN cuando se desee fidelidad de cabina.
- La distribución piloto/copiloto debe seguir el manual ROAN de H-60 cuando aplique.
- Antes de una misión, el líder aéreo debe indicar la variante exacta y su función.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="ah1z"></a>
## AH-1Z Viper

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/9c1bea33-4606-4a86-a40b-34533e8479f6" />

### Información general

Helicóptero de ataque bimotor del USMC, diseñado para CAS, escolta y destrucción de blindados. Comparte arquitectura con el UH-1Y y está adaptado a operaciones expedicionarias y embarcadas.

### Base de los datos técnicos

Prestaciones basadas en datos públicos de Bell para el AH-1Z. El mod incorpora cabina interactiva, carga dinámica, moving map, RWR y sistema de daño revisado.

### Roles ROAN

- CAS
- Ataque antiblindaje
- Escolta de helicópteros de transporte
- Reconocimiento armado
- Defensa aire-aire de corto alcance contra helicópteros
- Operaciones desde [LHA](#lha)

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 200 KIAS / 370 km/h |
| Velocidad de crucero | ≈ 139 KTAS / 257 km/h |
| Techo práctico | ≈ 14,000 ft / 4,270 m |
| Radio de combate | ≈ 131 NM / 243 km |
| Alcance máximo | ≈ 310 NM / 574 km |
| Peso máximo al despegue | ≈ 18,500 lb / 8,390 kg |
| Carga útil máxima de referencia | ≈ 5,764 lb / 2,614 kg |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 2 (piloto y artillero/operador) |
| Tripulación recomendada | 2 (piloto y artillero/operador) |
| Tripulación máxima | 2 (piloto y artillero/operador) |
| Pasajeros | 0 |

### Capacidad de carga

No transporta tropas ni sling load. La carga útil está destinada a combustible, sensores y armamento.

### Armamento

Cañón M197 de 20 mm; cohetes de 70 mm; AGM-114 Hellfire y AIM-9 Sidewinder, además de otras combinaciones que permita el mod.

### Sensores y sistemas

Sistema electro-óptico/FLIR y designador láser en la plataforma real. El mod agrega cabina interactiva, dynamic loadout, moving map, RWR y contramedidas.

### Escenarios recomendados

- Escolta de UH-60/CH-47/CH-53
- CAS
- Ataque antitanque
- Protección de LZ
- Operaciones anfibias desde [LHA](#lha)

### Escenarios no recomendados

- Transporte
- Permanecer estacionario dentro del alcance de MANPADS/AAA
- Ataque contra SAM de medio/largo alcance sin apoyo

### Fortalezas

- Muy buena combinación de sensores y armamento
- Perfil estrecho y agilidad
- Capacidad antiblindaje y aire-aire limitada
- Compatible conceptualmente con operaciones [LHA](#lha)

### Debilidades

- Sin capacidad de transporte
- Vulnerable a defensa aérea de corto alcance durante hover
- Menor persistencia/carga que plataformas de ala fija

### Fuerte contra

- Blindados
- Vehículos
- Infantería y posiciones
- Helicópteros/aviones lentos con AAM

### Débil contra

- MANPADS
- AAA
- SAM de medio/largo alcance
- Cazas

### Limitaciones operativas

- Requiere coordinación estrecha piloto/artillero para aprovechar sensores.
- No debe usarse como artillería estática en hover sobre el objetivo.
- La carga exacta depende de las armas habilitadas por el mod.

### MOD

[AH-1Z Viper](https://steamcommunity.com/sharedfiles/filedetails/?id=3546703780)

### Dependencias

- [Lala Peral - Vehicle Interaction System (VIS)](https://steamcommunity.com/sharedfiles/filedetails/?id=3083512801)
- [USAF Mod - Main](https://steamcommunity.com/sharedfiles/filedetails/?id=2397360831)

### Observaciones ROAN

- Plataforma de ataque/escorta recomendada para el grupo anfibio ROAN.
- Combina especialmente bien con F-35B + [LHA](#lha) en misiones expedicionarias.
- Se recomienda vuelo NOE/terrain masking cuando el entorno lo permita.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="ah6m"></a>
## AH-6M Little Bird

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/d9c7470b-8a44-41e5-afc9-d7ff04d957e1" />

### Información general

Helicóptero ligero de ataque de operaciones especiales. Su pequeño tamaño, agilidad y baja huella logística lo hacen útil para escolta, reconocimiento armado y apoyo cercano en zonas urbanas o LZ reducidas.

### Base de los datos técnicos

Prestaciones basadas en datos USSOCOM/Boeing para la familia AH-6M/AH-6. La configuración exacta de armas corresponde a RHSUSAF.

### Roles ROAN

- CAS ligero
- Escolta
- Reconocimiento armado
- Ataque contra blancos ligeros
- Apoyo a fuerzas especiales

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima de referencia USSOCOM | ≈ 143 mph / 230 km/h |
| Velocidad máxima de crucero Boeing AH-6 | ≈ 126 kt / 233 km/h |
| Alcance de referencia | ≈ 250 mi / 402 km (USSOCOM); Boeing publica 179 NM / 332 km para AH-6 |
| Autonomía Boeing AH-6 | ≈ 2.1 h |
| Techo de servicio | Hasta ≈ 20,000 ft / 6,096 m |
| Carga de transporte | No transporta tropas en configuración AH-6M; la capacidad útil se dedica a armas/combustible |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 2 (piloto y copiloto) |
| Pasajeros | 1 elemento |

### Capacidad de carga

No es helicóptero de carga. Su capacidad útil se emplea en sistemas de armas; no debe asignársele sling load/logística.

### Armamento

Según configuración: M134 Minigun de 7.62 mm o GAU-19 de 12.7 mm, pods de cohetes de 70 mm y AGM-114 Hellfire; RHS puede ofrecer combinaciones concretas diferentes.

### Sensores y sistemas

Aviónica de operaciones especiales, navegación nocturna y miras/ópticas asociadas a armas. En RHS la funcionalidad depende de la variante y del modelo de sensores del juego.

### Escenarios recomendados

- CAS de precisión en zonas estrechas
- Escolta de MH-6/H-60
- Reconocimiento armado
- Operaciones urbanas
- Ataques rápidos desde enmascaramiento del terreno

### Escenarios no recomendados

- Ataque contra una red AA densa
- Transporte/logística
- Combate prolongado sobre un objetivo defendido

### Fortalezas

- Muy pequeño y ágil
- Excelente para LZ urbanas/reducidas
- Rápida respuesta
- Buena potencia de fuego para su tamaño

### Debilidades

- Protección y supervivencia limitadas
- Poca carga y autonomía frente a helicópteros mayores
- Muy vulnerable si queda expuesto

### Fuerte contra

- Infantería
- Vehículos ligeros
- Posiciones
- Blindados aislados si equipa Hellfire

### Débil contra

- MANPADS
- AAA
- Armas ligeras concentradas
- Helicópteros de ataque pesados/cazas

### Limitaciones operativas

- Debe evitar hover prolongado en línea de vista del enemigo.
- Tiene capacidad para 1 pasajero en la variante AH.
- La carga de misiles/cohetes debe balancearse con maniobrabilidad.

### MOD

[RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117)

### Dependencias

- RHSUSAF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Ideal para instrucción de vuelo táctico bajo y ataque ligero.
- Debe operar aprovechando velocidad, terreno y sorpresa.
- No sustituye a AH-1Z/Mi-28/Ka-52 para ataque sostenido pesado.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="mh6m"></a>
## MH-6M Little Bird

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/33630a90-50d9-4b24-8b12-39f8e0872978" />

### Información general

Variante de transporte ligero de operaciones especiales de la familia Little Bird. Está diseñada para insertar o extraer pequeños equipos en zonas donde un helicóptero mayor no podría operar con facilidad.

### Base de los datos técnicos

Prestaciones basadas en USSOCOM para el MH-6M. RHSUSAF puede variar ligeramente velocidad/asientos por configuración.

### Roles ROAN

- Inserción y extracción SOF
- Transporte ligero
- Asalto urbano
- Reconocimiento / enlace
- Operaciones en LZ extremadamente pequeñas

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 143 mph / 230 km/h |
| Alcance | ≈ 250 mi / 402 km |
| Techo de servicio de referencia | ≈ 18,700–20,000 ft / 5,700–6,100 m según fuente/configuración |
| Capacidad de pasajeros | Hasta 6 operadores en bancos externos |
| Carga logística | Muy limitada; no es plataforma de carga pesada |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 2 (piloto y copiloto) |
| Pasajeros | ≈ 7 elementos |

### Capacidad de carga

Su principal 'carga' son hasta seis operadores externos. No se recomienda para sling load ni para suministros pesados.

### Armamento

La variante MH es principalmente de transporte; puede disponer de armas ligeras/autoprotección según configuración de RHS, pero no debe asumirse la misma carga que AH-6M.

### Sensores y sistemas

Navegación y equipamiento de operaciones especiales optimizado para vuelo nocturno y a baja cota. La simulación exacta depende de RHS.

### Escenarios recomendados

- Inserción/extracción de equipos pequeños
- Operaciones urbanas
- Techos, claros y LZ reducidas
- Movimientos rápidos de SOF

### Escenarios no recomendados

- Mover escuadras grandes
- MEDEVAC masivo
- Carga externa pesada
- Entrar en una LZ con fuego AA sostenido

### Fortalezas

- Huella muy pequeña
- Gran agilidad
- Puede colocar tropas en lugares inaccesibles para helicópteros medianos
- Excelente para SOF

### Debilidades

- Solo 6 pasajeros
- Tripulantes/pasajeros externos están muy expuestos
- Poca autonomía/carga comparada con H-60/CH-47

### Fuerte contra

- No aplica como plataforma de combate primaria; su fortaleza es la inserción precisa y rápida

### Débil contra

- Armas ligeras
- MANPADS
- AAA
- Cualquier fuego concentrado durante inserción

### Limitaciones operativas

- El equipo transportado debe ser pequeño y ligero.
- No mantener hover innecesario sobre la LZ.
- La aproximación debe priorizar enmascaramiento y exposición mínima.

### MOD

[RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117)

### Dependencias

- RHSUSAF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma preferente para inserciones de 2–6 operadores.
- Puede combinarse con AH-6M como pareja transporte/escort.
- La extracción debe planearse con señal, rumbo y punto de escape antes de entrar.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="ch53e"></a>
## CH-53E Super Stallion

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/b8fcc3a1-186a-4182-8b79-6b053d68999f" />

### Información general

Helicóptero pesado de tres motores del USMC, concebido para transportar tropas, vehículos, artillería y suministros desde buques anfibios hacia tierra. Es una de las plataformas de mayor capacidad de carga de ROAN.

### Base de los datos técnicos

Prestaciones basadas en documentación USMC/NAVAIR del CH-53E. Los valores de carga varían mucho con temperatura, altitud y perfil; se muestran cifras de planificación y máximos publicados.

### Roles ROAN

- Heavy lift
- Transporte anfibio ship-to-shore
- Logística pesada
- Sling load pesado
- Asalto aéreo
- MEDEVAC de gran capacidad

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 150 kt / 278 km/h |
| Velocidad de crucero | ≈ 130 kt / 241 km/h |
| Alcance de referencia | ≈ 480–540 NM / 890–1,000 km según configuración |
| Radio de misión pesado de referencia | ≈ 110 NM con carga externa en condiciones definidas por USMC |
| Techo de servicio aproximado | ≈ 18,500 ft / 5,640 m |
| Peso máximo bruto | ≈ 73,500 lb / 33,340 kg en documentación USMC |
| Carga interna útil de referencia | ≈ 13,200 lb / 5,987 kg |
| Carga externa | Hasta ≈ 36,000 lb / 16,330 kg como capacidad máxima publicada; la carga operativa depende fuertemente de condiciones |
| Pasajeros | ≈ 30 elementos |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 2 (piloto y copiloto) |
| Pasajeros | ≈ 24 elementos |

### Capacidad de carga

Especialista en carga pesada. Puede transportar internamente pallets/equipos y externamente vehículos/cargas de varias toneladas. Para ROAN debe usarse un margen conservador, especialmente en mapas de gran altitud o clima caliente.

### Armamento

Hasta tres ametralladoras GAU-21 calibre .50 como kit defensivo en la aeronave real; RHS puede representar una configuración específica.

### Sensores y sistemas

GPS, FLIR, ANVIS-HUD, radios UHF/VHF/HF, IFF y sistemas de autoprotección como DIRCM/AAR-47/ALE-47/APR-39 en configuraciones modernas.

### Escenarios recomendados

- Transporte de cargas que exceden H-60
- Movimiento ship-to-shore desde [LHA](#lha)
- Sling load de vehículos/equipos pesados
- Asalto aéreo de gran volumen
- Logística de campaña

### Escenarios no recomendados

- LZ urbanas pequeñas
- Misiones donde solo se transporten pocos pasajeros
- Entrar sin escolta en zonas con defensa aérea activa

### Fortalezas

- Enorme capacidad de carga
- Autonomía elevada
- Apto para operaciones anfibias
- Puede mover equipo que otros helicópteros no pueden

### Debilidades

- Muy grande
- LZ y cubierta requieren espacio
- Alto consumo y menor agilidad
- Objetivo visible para amenazas AA

### Fuerte contra

- No es plataforma ofensiva; su ventaja es el transporte estratégico/táctico de cargas muy pesadas

### Débil contra

- MANPADS
- AAA
- SAM
- Cazas
- Obstáculos/LZ confinadas

### Limitaciones operativas

- Aplicar margen de peso: temperatura y elevación reducen notablemente la carga real.
- No usar cifras máximas como carga habitual.
- Coordinar cuidadosamente deck handling y LZ por tamaño/rotor.

### MOD

[RHSUSAF](https://steamcommunity.com/workshop/filedetails/?id=843577117)

### Dependencias

- RHSUSAF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- ROAN debe reservarlo para cargas o movimientos que justifiquen su tamaño.
- Es especialmente útil en combinación con [LHA](#lha) para operaciones anfibias.
- La escolta AH-1Z es recomendable en zonas hostiles.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="mh47g"></a>
## MH-47G Chinook

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/b5afbf79-fee4-4df2-9aad-2fbf7883adad" />

### Información general

Variante de operaciones especiales del Chinook con navegación avanzada, capacidad de reabastecimiento en vuelo, sensores/autoprotección y mayor alcance para infiltración/exfiltración clandestina. Está diseñado para heavy assault, resupply y sling load en apoyo a SOF.

### Base de los datos técnicos

Prestaciones basadas en USSOCOM/Boeing para MH-47G/H-47. El mod incluye MH-47G Block I y II con alta fidelidad Hatchet, MFD y CDU interactivos.

### Roles ROAN

- Infiltración/exfiltración SOF
- Heavy assault
- Transporte de largo alcance
- Sling load
- Reabastecimiento
- Operaciones nocturnas y de baja cota

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima USSOCOM | ≈ 195 mph / 314 km/h |
| Velocidad de crucero USSOCOM | ≈ 132 mph / 212 km/h |
| Alcance sin reabastecimiento | ≈ 604 mi / 972 km |
| Techo de servicio de referencia H-47 | ≈ 20,000 ft / 6,096 m |
| Carga útil de referencia H-47 | ≈ 27,700 lb / 12,565 kg; depende de combustible/equipos SOF |
| Sling load de referencia | Centro hasta ≈ 26,000 lb / 11,793 kg en familia Chinook |
| Reabastecimiento en vuelo | Sí en MH-47G real; permite extender significativamente el alcance |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 6 (piloto, copiloto, flight engineer/crew chief y artilleros) |
| Pasajeros | ≈ 28 elementos |

### Capacidad de carga

Comparte gran capacidad de carga del Chinook, pero el equipo y combustible adicional de operaciones especiales pueden reducir el payload disponible. Es apto para sling load pesado.

### Armamento

M134 Minigun y M240 de 7.62 mm para defensa, según configuración real; el mod puede implementar puestos concretos.

### Sensores y sistemas

El MH-47G real integra navegación de precisión, sensores de vuelo nocturno/FLIR, autoprotección, comunicaciones y reabastecimiento en vuelo. Pegasus/Hatchet anuncia cabina de alta fidelidad, MFD, CDU y procedimientos interactivos.

### Escenarios recomendados

- SOF a larga distancia
- Infiltración nocturna
- Rescate/CSAR complejo
- Heavy assault
- Sling load en terreno difícil
- Misiones donde se requiera entrenamiento de cabina avanzado

### Escenarios no recomendados

- Misiones simples que no justifican su complejidad
- LZ extremadamente confinadas
- Ataque frontal sin escolta

### Fortalezas

- Muy largo alcance
- Gran carga
- Capacidad SOF y reabastecimiento en vuelo
- Alta fidelidad del mod para entrenamiento

### Debilidades

- Complejo de operar
- Grande y visible
- Carga útil puede reducirse por combustible/equipos adicionales

### Fuerte contra

- No es ataque primario; su fortaleza es la movilidad SOF de largo alcance y heavy lift

### Débil contra

- MANPADS
- AAA
- SAM
- Cazas
- LZ pequeñas/obstáculos

### Limitaciones operativas

- La tripulación ROAN debe estar familiarizada con Hatchet antes de una operación compleja.
- Planificar combustible, carga y altura de densidad; no sumar máximos teóricos.
- Requiere más coordinación interna que CH-47F RHS.

### MOD

[Pegasus Systems MH-47G](https://steamcommunity.com/sharedfiles/filedetails/?id=3805899171)

### Dependencias

- [Hatchet Interaction Framework - Stable Version](https://steamcommunity.com/workshop/filedetails/?id=2941986336)
- [ACE3](https://steamcommunity.com/workshop/filedetails/?id=463939057)
- [CBA_A3](https://steamcommunity.com/workshop/filedetails/?id=450814997) — dependencia transitiva de Hatchet/ACE

### Observaciones ROAN

- Es la opción ROAN de Chinook de alta fidelidad y operaciones especiales.
- Se recomienda crew completo en operaciones oficiales.

[↑ Volver a Ala rotativa — BLUFOR](#ala-rotativa-blufor)  
[↑ Volver al índice](#indice)

---

<a id="ala-rotativa-opfor"></a>
# 9. Ala rotativa — OPFOR

Esta sección contiene las aeronaves autorizadas de **Ala rotativa — OPFOR**.

## Aeronaves

- [Mi-8MT Hip](#mi8mt)
- [Mi-24V Hind-E](#mi24v)
- [Mi-28N Havoc](#mi28n)
- [Ka-52 Alligator](#ka52)

---

<a id="mi8mt"></a>
## Mi-8MT Hip

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/5eda0712-691b-464d-b619-55fb17c81908" />

### Información general

Helicóptero medio multipropósito ampliamente empleado para transporte de tropas, carga, asalto aéreo y apoyo armado. Es robusto, relativamente sencillo y puede operar desde zonas no preparadas.

### Base de los datos técnicos

Prestaciones basadas en referencias de la familia Mi-8MT/Mi-8MTV. RHS puede ofrecer subvariantes con armamento, asientos o tanques diferentes.

### Roles ROAN

- Transporte de tropas
- Inserción/extracción
- Logística
- MEDEVAC según variante
- Apoyo armado según configuración

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 250 km/h |
| Velocidad de crucero | ≈ 220–230 km/h |
| Alcance de referencia | ≈ 500 km con combustible estándar; aumenta con tanques auxiliares |
| Techo de servicio | ≈ 5,000 m como referencia operativa |
| Peso máximo al despegue | ≈ 13,000 kg |
| Carga interna/externa | Hasta ≈ 4,000 kg |
| Tropas | Hasta ≈ 24 en configuraciones Mi-8MT tradicionales |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y copiloto) |
| Tripulación máxima | 4 (piloto, copiloto y artillero) |
| Pasajeros | ≈ 14 elementos |

### Capacidad de carga

Puede transportar aproximadamente 4 t internamente o en gancho externo en configuraciones de referencia. En RHS debe verificarse el límite concreto de sling load de la variante.

### Armamento

Algunas variantes pueden portar ametralladoras, pods de cohetes S-8/S-5, pods de cañón y otras armas. La configuración de transporte puede ir desarmada.

### Sensores y sistemas

Aviónica de navegación convencional, radios y equipos de autoprotección según subvariante. RHS representa distintas versiones soviéticas/rusas con niveles diferentes de equipamiento.

### Escenarios recomendados

- Transporte OPFOR
- Asalto aéreo
- Logística
- Sling load medio
- Escenarios de fuerzas rusas convencionales

### Escenarios no recomendados

- CAS pesado como función primaria
- Operación sin escolta en zonas con defensa AA
- Carga que exceda ~4 t

### Fortalezas

- Robusto y versátil
- Buena capacidad de tropas/carga
- Puede operar desde LZ austeras
- Amplia variedad de configuraciones

### Debilidades

- Firma grande
- Velocidad moderada
- Protección/sensores varían mucho por versión

### Fuerte contra

- En variantes armadas: infantería, posiciones y vehículos ligeros

### Débil contra

- MANPADS
- AAA
- Cazas
- SAM

### Limitaciones operativas

- Confirmar la variante RHS antes de asumir armamento o número de asientos.
- No confundir Mi-8MT con Mi-17 moderno: capacidades pueden solaparse, pero no son idénticas.
- Planificar salida inmediata de la LZ en ambiente hostil.

### MOD

[RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)

### Dependencias

- RHSAFRF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Útil como plataforma OPFOR de transporte general.
- ROAN puede usarlo para prácticas de adaptación a cabinas/handling distintos a BLUFOR.
- En misiones mixtas, identificar claramente callsign y variante para evitar confusión con Mi-17.

[↑ Volver a Ala rotativa — OPFOR](#ala-rotativa-opfor)  
[↑ Volver al índice](#indice)

---

<a id="mi24v"></a>
## Mi-24V Hind-E

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/6169234d-d299-4e08-8dd5-832e63756d05" />

### Información general

Helicóptero de ataque pesado con una característica poco común: conserva una cabina de transporte para un pequeño grupo de tropas. Está concebido para apoyo de fuego, ataque antiblindaje, escolta y asalto armado.

### Base de los datos técnicos

Prestaciones basadas en referencias militares del Mi-24V. RHS puede ajustar masa, munición y asientos.

### Roles ROAN

- CAS
- Ataque antiblindaje
- Escolta
- Reconocimiento armado
- Transporte limitado de tropas
- Asalto armado

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 310 km/h |
| Velocidad de crucero | ≈ 260 km/h |
| Alcance máximo de referencia | ≈ 750 km |
| Radio táctico de referencia | ≈ 160 km según carga/perfil |
| Techo de servicio | ≈ 4,500 m |
| Peso máximo al despegue | ≈ 12,500 kg |
| Carga externa/armamento | Hasta ≈ 2,400 kg de referencia |
| Tropas | Hasta 8 |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 1 (piloto) |
| Tripulación recomendada | 2 (piloto y operador/artillero) |
| Tripulación máxima | 2 (piloto y operador/artillero) |
| Pasajeros | ≈ 8 elementos |

### Capacidad de carga

Puede transportar hasta 8 soldados además de su armamento. Esa combinación reduce rendimiento y no convierte al Hind en sustituto de Mi-8/Mi-17.

### Armamento

Ametralladora Yak-B de 12.7 mm en torreta en Mi-24V, misiles antitanque Shturm-V, pods de cohetes y otras cargas no guiadas/cañones según configuración RHS.

### Sensores y sistemas

Mira/óptica para operador, sistemas de navegación y autoprotección de la época. Las capacidades nocturnas y de adquisición son inferiores a helicópteros modernos como Mi-28N/Ka-52.

### Escenarios recomendados

- CAS y antiblindaje
- Escolta de Mi-8/Mi-17
- Ataque de posiciones
- Inserción armada pequeña
- Escenarios soviéticos/rusos

### Escenarios no recomendados

- ISR nocturno avanzado
- Hover prolongado contra MANPADS
- Transportar tropas cuando se necesita gran capacidad

### Fortalezas

- Velocidad alta para helicóptero de ataque
- Blindaje considerable
- Combina fuego y pequeña capacidad de tropas
- Buena potencia contra blindados

### Debilidades

- Grande y menos ágil en hover que plataformas más modernas
- Sensores antiguos
- La doble función ataque/transporte obliga a compromisos

### Fuerte contra

- Blindados
- Vehículos
- Infantería
- Posiciones fortificadas

### Débil contra

- MANPADS
- AAA
- SAM
- Cazas
- Helicópteros modernos con mejor sensor/armas si detectan primero

### Limitaciones operativas

- Las 8 plazas no deben justificar sobrecargar una misión de ataque con pasajeros innecesarios.
- Aprovechar ataques en pasada y terreno; evitar hover estático.
- Confirmar misil/pod exacto de la clase RHS.

### MOD

[RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)

### Dependencias

- RHSAFRF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma híbrida útil para entrenamiento de doctrina OPFOR.
- En ROAN puede cubrir ataque y una extracción de emergencia pequeña, pero su rol primario seguirá siendo combate.
- Para tropas regulares, Mi-8/Mi-17 son más apropiados.

[↑ Volver a Ala rotativa — OPFOR](#ala-rotativa-opfor)  
[↑ Volver al índice](#indice)

---

<a id="mi28n"></a>
## Mi-28N Havoc

### Imagen

<img width="1448" height="1086" alt="image" src="https://github.com/user-attachments/assets/0092d0f7-4cf6-45fd-9e3c-c954c6a5cae9" />

### Información general

Helicóptero de ataque pesado biplaza, diseñado para destruir tanques, vehículos, infantería y objetivos aéreos lentos de día o noche. Prioriza blindaje, supervivencia y potencia de fuego.

### Base de los datos técnicos

Prestaciones basadas en información pública de Rostec/Russian Helicopters para Mi-28N/NE. RHS puede variar armamento y sensores disponibles.

### Roles ROAN

- Ataque antiblindaje
- CAS
- Escolta
- Reconocimiento armado
- Ataque nocturno

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 300 km/h |
| Velocidad de crucero | ≈ 270 km/h como referencia |
| Techo dinámico | ≈ 5,600 m |
| Alcance de referencia | ≈ 435 km; ferry puede superar 1,000 km con configuración adecuada |
| Carga externa de armas | ≈ 2,300 kg como orden de magnitud |
| Tripulación | 2 |
| Capacidad de pasajeros | 3 en misión normal |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 2 (piloto y operador/artillero) |
| Tripulación recomendada | 2 (piloto y operador/artillero) |
| Tripulación máxima | 2 (piloto y operador/artillero) |
| Pasajeros | 3 elementos |

### Capacidad de carga

No transporta carga. La capacidad externa está dedicada a armas y tanques/pods compatibles.

### Armamento

Cañón móvil 2A42 de 30 mm; misiles antitanque Ataka-V y otras familias según variante; cohetes S-8/S-13; posibilidad de armas aire-aire de corto alcance y bombas/pods en algunas configuraciones.

### Sensores y sistemas

Sistema de puntería/observación día-noche, navegación y autoprotección. Las versiones avanzadas integran radar/sensores mejorados; utilizar solo las funciones efectivamente presentes en la clase RHS.

### Escenarios recomendados

- Ataque antitanque
- CAS
- Escolta de transportes rusos
- Operaciones nocturnas
- Defensa contra helicópteros/objetivos lentos

### Escenarios no recomendados

- Transporte
- Penetración contra SAM de medio/largo alcance
- Hover expuesto en entornos MANPADS

### Fortalezas

- Blindaje y supervivencia
- Cañón potente
- Gran capacidad antiblindaje
- Operación día/noche

### Debilidades

- Pocos pasajeros
- Grande y detectable
- Menos rápido que ala fija ante amenazas SAM

### Fuerte contra

- Tanques
- IFV/APC
- Infantería
- Posiciones
- Helicópteros/objetivos lentos

### Débil contra

- SAM
- MANPADS si se expone
- AAA pesada
- Cazas

### Limitaciones operativas

- Priorizar stand-off con ATGM y exposición corta.
- No entrar en zona de SAM solo por disponer de blindaje.
- La capacidad exacta de radar/FLIR depende de RHS.

### MOD

[RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)

### Dependencias

- RHSAFRF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Helicóptero de ataque OPFOR pesado para escenarios modernos.
- Útil para comparar procedimientos de piloto/operador con AH-1Z.
- Debe operar con reconocimiento y rutas de enmascaramiento.

[↑ Volver a Ala rotativa — OPFOR](#ala-rotativa-opfor)  
[↑ Volver al índice](#indice)

---

<a id="ka52"></a>
## Ka-52 Alligator

### Imagen

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/fda09f51-2746-4977-a1b5-a657a80a88d1" />

### Información general

Helicóptero de ataque/reconocimiento de rotores coaxiales y cabina biplaza lado a lado. Su configuración le proporciona alta maniobrabilidad y capacidad para operar en condiciones exigentes, además de coordinación de grupos de helicópteros.

### Base de los datos técnicos

Prestaciones basadas en datos públicos de Rostec para Ka-52. RHS puede simplificar sensores/armamento.

### Roles ROAN

- Ataque antiblindaje
- CAS
- Reconocimiento armado
- Designación/coordinación de blancos
- Escolta
- Ataque contra helicópteros/objetivos lentos

### Características técnicas

| Característica | Valor |
|---|---|
| Velocidad máxima | ≈ 300 km/h |
| Velocidad de crucero | ≈ 260 km/h |
| Techo de vuelo | Más de 5,000 m; referencia práctica ≈ 5,500 m |
| Techo estático | ≈ 4,000 m |
| Alcance práctico de referencia | ≈ 460 km; ferry puede rondar 1,100 km según configuración |
| Peso máximo al despegue | ≈ 10,800 kg como referencia |
| Carga de combate | ≈ 2,000 kg |
| Puntos de suspensión | 6 |

### Tripulación y pasajeros

| Configuración | Cantidad / criterio |
|---|---|
| Tripulación mínima | 2 (piloto y operador/artillero) |
| Tripulación recomendada | 2 (piloto y operador/artillero) |
| Tripulación máxima | 2 (piloto y operador/artillero) |
| Pasajeros | 0 |

### Capacidad de carga

No transporta personal. Hasta aproximadamente 2 t de carga de combate en seis puntos externos según datos publicados.

### Armamento

Cañón 2A42 de 30 mm, misiles guiados antitanque, cohetes no guiados, misiles aire-aire y bombas/tanques externos según configuración.

### Sensores y sistemas

Suite día/noche, navegación, electro-óptica y sistemas de autoprotección. El Ka-52 real está concebido también para reconocimiento y designación/coordinación de blancos.

### Escenarios recomendados

- Ataque antiblindaje
- Reconocimiento armado
- CAS
- Escolta
- Operaciones en terreno montañoso o donde la maniobrabilidad sea útil

### Escenarios no recomendados

- Transporte
- Hover expuesto frente a MANPADS/AAA
- Penetración en IADS sin supresión

### Fortalezas

- Excelente maniobrabilidad por rotores coaxiales
- Cabina lado a lado facilita coordinación
- Cañón/ATGM potentes
- Buena función de reconocimiento/ataque

### Debilidades

- Sin capacidad de transporte
- Perfil de ataque sigue siendo vulnerable a AA
- Complejidad de coordinación de sensores/armas

### Fuerte contra

- Blindados
- Vehículos
- Infantería
- Helicópteros y objetivos aéreos lentos

### Débil contra

- MANPADS
- AAA
- SAM
- Cazas

### Limitaciones operativas

- La capacidad de sensores del Ka-52 real no implica que todas las funciones estén modeladas en RHS.
- Usar terreno y alcance de misiles, no hover sobre la línea de frente.
- La configuración de 2 t es máxima de referencia, no carga obligatoria.

### MOD

[RHSAFRF](https://steamcommunity.com/workshop/filedetails/?id=843425103)

### Dependencias

- RHSAFRF no declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma OPFOR recomendada para ataque/reconocimiento avanzado.
- Puede emplearse como amenaza de alto nivel en ejercicios ROAN.
- Su disposición de tripulación lado a lado cambia la coordinación respecto a AH-1Z/Mi-28.

[↑ Volver a Ala rotativa — OPFOR](#ala-rotativa-opfor)  
[↑ Volver al índice](#indice)

---

<a id="infraestructura"></a>
# 10. Infraestructura y Operaciones Aeronavales

Esta sección reúne las plataformas y herramientas autorizadas para soportar operaciones embarcadas y de aeródromo de ROAN.

## Elementos

- [Nimitz](#nimitz)
- [LHA](#lha)
- [Airfield Logistics](#airfield-logistics)

---

<a id="nimitz"></a>
## Nimitz

### Imagen

<img width="1672" height="941" alt="Imagen de ChatGPT 3 nov 2026, 10_22_26 p m-2" src="https://github.com/user-attachments/assets/720a7a3c-aa36-46a8-a4af-4a6f86cfa4b5" />

### Tipo

Portaaviones CATOBAR / infraestructura aeronaval

### Información general

Versión experimental del USS Nimitz para Arma 3. El propio Workshop la describe como una rama de desarrollo con cambios nuevos y no probados, destinada a usuarios que aceptan una experiencia 'bleeding edge'. Permite recrear operaciones de ala fija embarcada con catapultas y cables de apontaje.

### Capacidades principales

- Cubierta de vuelo para operaciones de ala fija y helicópteros.
- Catapultas para lanzamiento de aeronaves compatibles.
- Cables de apontaje/arresting gear para recuperación.
- Elementos de cubierta, estacionamiento y operación aeronaval.
- Integración especialmente adecuada con F/A-18E y F-35C del catálogo ROAN.

### Escenarios recomendados

- Prácticas de apontaje y despegue por catapulta
- Operaciones de carrier air wing
- CAP/strike desde mar
- Entrenamiento de procedimientos de cubierta

### Limitaciones operativas

- Es una build experimental: pueden existir bugs de catapulta, cables o scripts.
- No debe asumirse compatibilidad perfecta con cada aeronave sin prueba previa.
- Para eventos oficiales conviene validar la versión del mod antes de publicar la misión.

### MOD

[Nimitz Experimental Build](https://steamcommunity.com/sharedfiles/filedetails/?id=1697731012)

### Dependencias

- [CBA_A3](https://steamcommunity.com/workshop/filedetails/?id=450814997)

### Observaciones ROAN

- ROAN debe tratarlo como la plataforma principal para F/A-18E y F-35C.
- Se recomienda mantener procedimientos estandarizados de taxi, catapulta, patrón y apontaje.
- Airfield Logistics puede complementar el movimiento de aeronaves en cubierta, sujeto a compatibilidad.

[↑ Volver a Infraestructura](#infraestructura)  
[↑ Volver al índice](#indice)

---

<a id="lha"></a>
## LHA

### Imagen

<img width="1672" height="941" alt="Imagen de ChatGPT 3 nov 2026, 10_22_25 p m-1" src="https://github.com/user-attachments/assets/49adae23-bb99-4792-94f6-4890d165f33e" />

### Tipo

Landing Helicopter Assault / buque anfibio con cubierta de vuelo

### Información general

Buque de asalto anfibio basado en la clase America y con una configuración cercana al USS Bougainville (LHA-8). Incluye cubierta ampliada, dos elevadores de borde y well deck, y está pensado como base de operaciones para un Marine Air Ground Task Force.

### Capacidades principales

- Spawner de aeronaves con seis pads; el autor cita compatibilidad con F-35B y AH-1Z de Peral, entre otros.
- Spawner/lanzador de botes en dos bahías.
- Spawner de vehículos en well deck con seis pads.
- La cubierta funciona como zona de rearmado y reparación para aeronaves configuradas.
- Mangueras de reabastecimiento de combustible en cubierta.
- Cuatro torretas de defensa aérea NATO del juego base.
- Número de identificación del buque editable en Eden.
- Briefing room, puente, torre de observación, medical bay y vehicle bay.

### Escenarios recomendados

- Operaciones F-35B STOVL
- Operaciones de helicópteros H-60/AH-1Z/CH-53
- Asalto anfibio
- Base avanzada aeronaval
- Entrenamiento de deck operations

### Limitaciones operativas

- El autor lo identifica como WIP; funciones adicionales siguen en desarrollo.
- Las aeronaves compatibles con spawner/rearm/repair dependen de configuración del mod.
- No sustituye a un carrier CATOBAR para F/A-18E o F-35C.

### MOD

[LHA](https://steamcommunity.com/sharedfiles/filedetails/?id=3596653038)

### Dependencias

- No declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Plataforma ROAN preferente para F-35B y helicópteros en operaciones anfibias.
- F-35C/F/A-18E deben mantenerse en Nimitz salvo pruebas específicas.
- Planificar segregación entre spots de helicópteros y operaciones STOVL.

[↑ Volver a Infraestructura](#infraestructura)  
[↑ Volver al índice](#indice)

---

<a id="airfield-logistics"></a>
## Airfield Logistics

### Imagen

<img width="1672" height="941" alt="Imagen de ChatGPT 3 nov 2026, 10_22_28 p m-3" src="https://github.com/user-attachments/assets/0a920e62-e7da-4b6c-9770-2a647b744ae0" />

### Tipo

Soporte de tierra y cubierta para aeronaves

### Información general

Mod de apoyo que agrega tractores de remolque y activos de aeródromo para mover y organizar aeronaves en bases y cubiertas. Está orientado a mejorar el handling de aeronaves en tierra y la ambientación/operación logística.

### Capacidades principales

- Tractores de remolque A/S32A y B-600.
- Capacidad de remolcar aviones y helicópteros en tierra y en entorno marítimo/cubierta.
- Forklifts capaces de levantar y mover objetos compatibles.
- Aircraft Carrier Crash Crane para mover o retirar aeronaves.
- Helicopter dollies remolcables.
- Generador de luz remolcable.
- Módulo 'attach to forklift' para habilitar objetos adicionales.

### Escenarios recomendados

- Organización de parking y cubierta
- Remolque de aeronaves sin encender motores
- Mantenimiento/ambientación de base aérea
- Recuperación de aeronaves que bloqueen cubierta
- Logística visual y funcional en Nimitz/LHA

### Limitaciones operativas

- No todos los aviones de terceros son necesariamente towable sin compatibilidad adicional.
- La grúa/forklift tiene listas y límites de objetos compatibles.
- No debe usarse para mover aeronaves durante fases activas de despegue/aterrizaje.

### MOD

[Airfield Logistics](https://steamcommunity.com/sharedfiles/filedetails/?id=3048131698)

### Dependencias

- No declara dependencias obligatorias adicionales en Steam Workshop.

### Observaciones ROAN

- Recomendado para misiones con operaciones de cubierta detalladas.
- El instructor/Zeus debe probar previamente compatibilidad con cada addon de aeronave.
- No es un portaaviones: complementa aeródromos, Nimitz y LHA.

[↑ Volver a Infraestructura](#infraestructura)  
[↑ Volver al índice](#indice)

---

<a id="glosario"></a>

# 11. Glosario

| Término | Significado |
|---|---|
| AAA | Anti-Aircraft Artillery |
| BVR | Beyond Visual Range |
| CAP | Combat Air Patrol |
| CAS | Close Air Support |
| CASEVAC | Casualty Evacuation |
| CATOBAR | Catapult Assisted Take-Off But Arrested Recovery |
| CSAR | Combat Search and Rescue |
| DEAD | Destruction of Enemy Air Defenses |
| FAC(A) | Forward Air Controller (Airborne) |
| FLIR | Forward Looking Infrared |
| IADS | Integrated Air Defense System |
| ISR | Intelligence, Surveillance and Reconnaissance |
| JTAC | Joint Terminal Attack Controller |
| LHA | Landing Helicopter Assault |
| LZ | Landing Zone |
| MANPADS | Man-Portable Air-Defense System |
| MEDEVAC | Medical Evacuation |
| NOE | Nap-of-the-Earth |
| RWR | Radar Warning Receiver |
| SAM | Surface-to-Air Missile |
| SEAD | Suppression of Enemy Air Defenses |
| SOF | Special Operations Forces |
| STOVL | Short Take-Off and Vertical Landing |
| TGP | Targeting Pod |
| VTOL | Vertical Take-Off and Landing |
| WSO | Weapon Systems Officer |
| Sling Load | Carga externa suspendida bajo un helicóptero |

[↑ Volver al índice](#indice)

---

<a id="referencias"></a>

# 12. Referencias generales

Las páginas de Steam Workshop enlazadas en cada ficha son la referencia principal para **mods y dependencias**. Para prestaciones no documentadas por los addons se utilizaron datos reales publicados por fabricantes, fuerzas armadas y organismos oficiales, entre ellos:

- **U.S. Air Force**
  - [A-10C Thunderbolt II — Fact Sheet](https://www.af.mil/About-Us/Fact-Sheets/Display/Article/104490/a-10c-thunderbolt-ii/)
  - [C-130 Hercules — Fact Sheet](https://www.af.mil/About-Us/Fact-Sheets/Display/Article/1555054/c-130-hercules/)

- **U.S. Navy / NAVAIR / USMC**
  - [F/A-18A-D Hornet and F/A-18E/F Super Hornet — U.S. Navy Fact File](https://www.navy.mil/Resources/Fact-Files/Display-FactFiles/Article/2383479/fa-18a-d-hornet-and-fa-18ef-super-hornet-strike-fighter/)
  - [CH-53E Super Stallion — U.S. Navy Fact File](https://www.navy.mil/Resources/Fact-Files/Display-FactFiles/Article/2166570/ch-53e-super-stallion/ch-53e-super-stallion/)

- **Lockheed Martin / Sikorsky**
  - [F-35 Lightning II — Fast Facts](https://www.f35.com/content/dam/lockheed-martin/aero/f35/documents/F-35%20Fast%20Facts%20-%20March%202021.pdf)
  - [UH-60M Black Hawk — Technical Brochure](https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/black-hawk/sikorsky-UH60M-brochure.pdf)

- **Boeing**
  - [AH-6 Little Bird](https://www.boeing.com/defense/military-rotorcraft/ah-6-little-bird)
  - [H-47 Chinook](https://www.boeing.com/defense/military-rotorcraft/h-47-chinook)

- **U.S. Special Operations Command (USSOCOM)**
  - [USSOCOM 2026 Fact Book — AH-6M, MH-6M y MH-47G](https://www.socom.mil/FactBook/2026%20Fact%20Book.pdf)

- **Bell**
  - [AH-1Z Viper — Official Specifications](https://www.bellflight.com/products/bell-ah-1z)

- **United Aircraft Corporation (UAC)**
  - [Su-34 — Official Specifications](https://uacrussia.ru/en/aircraft/lineup/lineup/su-34/)
  - [Su-35 — Official Specifications](https://uacrussia.ru/en/aircraft/lineup/lineup/su-35/)

- **Rostec / Russian Helicopters**
  - [Ka-52 Alligator y Mi-28NE — Russian Military Helicopters](https://rostec.ru/en/media/pressrelease/rosoboronexport-to-showcase-upgraded-russian-military-helicopters-at-helirussia-2022/)
  - [Mi-8/17 Family — Helicopter of 100 Professions](https://rostec.ru/en/media/news/helicopter-of-100-professions-eight-facts-about-the-mi-8/)

- **Ministry of Defence & Armed Forces of the Czech Republic**
  - [Mi-24 / Mi-24V Hind — Technical Data](https://acr.mo.gov.cz/en/armed-forces/equipment/air-force/helicopters/mil-mi-24---nato-code%3A-hind-38157/)

## 12.1 Criterio de uso de cifras

Los valores de carga, techo, alcance y velocidad pueden cambiar por:

- Variante específica del avión/helicóptero.
- Peso real de despegue.
- Combustible.
- Configuración de armas.
- Temperatura y altitud.
- Daños.
- Modelo de vuelo de Arma 3.
- Advanced Flight Model.
- Versión del mod.

Por ello, antes de una operación que dependa de un límite exacto —por ejemplo sling load cercano al máximo o recuperación vertical del F-35B— se recomienda realizar una prueba en el mismo modset y mapa de la misión.

---

# Control del documento

| Campo | Valor |
|---|---|
| Documento | Aeronaves Autorizadas ROAN |
| Versión | 0.2 |
| Estado | Versión funcional completa |
| Fecha | 29 de septiembre de 2026 |
| Organización | Regimiento de Operaciones Aero Navales |
| Plataforma | Arma 3 |

[↑ Volver al índice](#indice)  
[↑ Volver al inicio](#inicio)
