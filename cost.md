---
lang: es-AR
title: 'The Cost of a Cloud: Research Problems in Data Center Networks (Article)'
author:
- Albert Greenberg
- James Hamilton
- David A. Maltz
- Parveen Patel
date: Juan Ignacio Díaz # hack horrible para que se vea bien en la presentación
theme:
- Copenhagen
...


# Introducción

- ¿Cuáles son los costos de mantener un Data Center?
- ¿Cómo se pueden mitigar estos costos?

+------------------+--------------------+----------------------------------------+
| Coste Amortizado | Componente         | Sub-Componentes                         |
+:================:+:===================+:=======================================+
|      ~45%        | Servidor           | CPU, memoria, almacenamiento           |
+------------------+--------------------+----------------------------------------+
|      ~25%        | Infraestructura    | Distribución de energía y enfriamiento |
+------------------+--------------------+----------------------------------------+
|      ~15%        | Consumo Energético | Costos utilitarios                     |
+------------------+--------------------+----------------------------------------+
|      ~15%        | Red                | Enlaces, tránsito, equipo              |
+------------------+--------------------+----------------------------------------+

: **Coste por componente.**[@greenberg2008cost]


# Servidores

## Problema

- Alto precio
- Baja utilización (~10%)

## Solución

- Virtualizar:
    + Crear una _pool_ de recursos
    + Que crezcan y disminuyan dinámicamente

---

![Topología de data center](topology.png)[@greenberg2008cost]


# Infraestructura

## Componentes

- Sistema de Alimentación Ininterrumpida (SAI)
- Sistema de enfriamiento

## Reducción del Costo

- Relajar el requerimiento de alimentación ininterrumpida
- Varios Data Centers baratos


# Consumo Energético

_Power Usage Efficiency_ (PUE)

: $PUE = \frac{ Consumo Energetico Total }{ Consumo Energetico IT }$

    Eficiencia del consumo energético.

## Propuesta

- Ahorrar en enfriamiento


# Red

## Costos

- Equipamiento
- Red de Area Amplia
    + _peering_
    + enlaces entre data centers

## Reducción de costos

- Estrategias de _peering_
- Optimizar uso de la red


# Geo-Distribucion

- Diversidad geografica [@kohavi2007practical]
- Mega/micro data centers
- Coste de red


# Conclusiones

- Relacion coste/utilización
- Uso de la red
- Geo-diversificacion

## Propiedades Necesarias

- Direccionamiento independiente de ubicación
- Ancho de banda y latencia uniformes
- Seguridad


# Bibliografía
