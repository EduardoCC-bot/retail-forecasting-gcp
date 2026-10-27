# Retail Sales Forecasting on GCP

## Problema de negocio
Pronosticar ventas por tienda y producto para decidir cuánto inventario pedir (Single Period Model sobre el pronóstico).

## Arquitectura
Cloud Storage → BigQuery → Features → Vertex AI / BigQuery ML → Predicciones batch → Orquestado con Cloud Composer.
Diagrama: `docs/` (pendiente).

## Datos
Dataset público de Kaggle (pendiente de elegir). No se incluye en el repo: descárgalo en `data/raw/`.

## Cómo correrlo
Pendiente.