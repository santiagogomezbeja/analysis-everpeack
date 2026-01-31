# EverPeak Retail Analysis – Sprint 6

Este repositorio contiene el análisis realizado durante el Sprint 6 del caso EverPeak–SilverBasket.

El dataset `everpeak_retail` incluye 2,000 órdenes de clientes con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del retail. :contentReference[oaicite:2]{index=2}

## 📂 Contenido del repositorio

- `notebooks/everpeak_analysis.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/everpeak_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Generar insights para el equipo de Estrategia e Integración de EverPeak

## Datasets utilizados
- plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

## Etapas del análisis realizadas
- Exploraracion.
- Limpieza.
- Analisis.
- Construccion de perfil estadístico de los clientes.
- Deteccion de comportamientos atípicos.
- Creacion de segmentos de clientes.
