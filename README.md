Fraud & Risk Intelligence Model

Predictive Analytics Case Study (QA Dataset)

📌 Project Overview

Un cliente del sector on-demand delivery nos solicitó el diseño de un modelo analítico que le permitiera identificar, anticipar y priorizar posibles fraudes dentro de su operación, con foco en tres actores clave:

Riders (repartidores)

Users (clientes)

Partners (comercios)

El objetivo principal fue detectar patrones anómalos, estimar su impacto operativo y financiero, y entregar una herramienta visual que permitiera tomar decisiones rápidas y accionables.

⚠️ Nota: Los datos presentados en este dashboard corresponden a un entorno de QA / datos simulados, utilizados exclusivamente con fines demostrativos y de validación del modelo.

🧠 Enfoque del Modelo (Business-Friendly)

El modelo se basa en un principio simple pero poderoso:

No todo fraude es igual.
Algunas señales tienen más impacto operativo y financiero que otras.

Por eso, en lugar de usar una sola métrica, se diseñó un sistema de scoring que pondera múltiples señales de riesgo según su severidad real.

🔍 Core Metric: Claim Rate (% Reclamos)

El % de reclamos es la métrica base del modelo, ya que representa órdenes que generan:

Reembolsos (Refunds)

Compensaciones (Credits)

Ambos son costos directos para la empresa y, cuando se repiten, suelen indicar abuso del sistema.

Interpretación de negocio

0% – 10% → comportamiento normal

15% – 30% → patrón irregular

+40% → alta probabilidad de fraude

+80% → anomalía crítica (auditoría inmediata)

Este indicador se analiza por actor, vertical, comercio y período.

⚖️ Fraud Risk Score — Concepto General

Para cada eje (Rider, User, Partner) se creó un Fraud Risk Score independiente, pero bajo una lógica común:

Combinar múltiples señales y asignarles un peso según su impacto real.

Este enfoque es similar al utilizado por plataformas de delivery líderes a nivel global.

Cada actor es clasificado automáticamente en:

Low Risk

Medium Risk

High Risk

🚴 Rider Risk Analysis (Operational Fraud)

El análisis de riders se enfoca en comportamientos operativos anómalos, como:

Reclamos recurrentes

Entregas extremadamente rápidas o lentas

Órdenes completadas sin pickup registrado

Reembolsos o compensaciones frecuentes

Estos patrones pueden indicar:

Manipulación de tiempos

“Fake deliveries”

Abuso del flujo operativo

👉 El score permite priorizar riders sospechosos de forma inmediata.

👤 User Risk Analysis (Financial Abuse)

En el caso de los usuarios, el fraude suele ser financiero y más difícil de detectar sin un modelo:

Abuso de reembolsos

Compensaciones repetitivas

Reclamos sobre pedidos pequeños

Patrones de monto repetido

El modelo identifica un grupo pequeño de usuarios que, aunque representan un porcentaje bajo del total, generan una parte desproporcionada del costo.

🏪 Partner Risk Analysis (Operational Impact)

Para los comercios (partners), el análisis se centra en:

Altas tasas de cancelación

Tiempos de preparación anómalos

Patrones repetitivos de ticket

Relación entre cancelaciones y reclamos

Esto permite detectar:

Manipulación de métricas

Impacto negativo en la experiencia del usuario

Riesgos operativos concentrados por vertical

📊 Validación y Consistencia

Para garantizar confiabilidad, el modelo incluye:

Métricas independientes por actor

Validaciones cruzadas entre KPIs y tablas

Segmentación por mes y nivel de riesgo

Visualizaciones consistentes entre vistas ejecutivas y operativas

El resultado es una lectura coherente del riesgo, desde el overview ejecutivo hasta el detalle granular.

🎯 Business Impact

El dashboard permite responder preguntas clave como:

¿Qué actores están generando pérdidas?

¿Dónde se concentra el fraude?

¿Qué verticales requieren intervención?

¿Cuál es el impacto financiero del abuso?

¿Dónde enfocar controles y auditorías?

Y lo más importante:

Permite actuar antes de que el problema escale.

🧩 Executive Summary

Se desarrolló un modelo de detección de fraude basado en múltiples indicadores operativos y financieros, ponderados según su impacto real.

El sistema:

Identifica comportamientos anómalos con alta precisión

Prioriza casos críticos

Reduce el ruido operativo

Facilita decisiones rápidas y accionables

Este enfoque transforma datos operativos en inteligencia de riesgo, alineando analítica avanzada con objetivos de negocio.
