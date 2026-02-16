# 🎾 YOLO para Tenis (baseline → mejoras)

Repositorio para entrenar un modelo YOLO de detección en tenis con un enfoque iterativo:
1) **Baseline** con dataset público → métricas + demo (GIF)
2) **Dataset propio** anotado en CVAT → reentrenar y comparar mejoras
3) **Escalado de modelo** si compensa (yolov8n → yolov8s/m)

## Estructura del proyecto
- `scripts/`: comandos reproducibles (entrenar / predecir / generar GIF)
- `notes/experiments.md`: registro de experimentos y mejoras
- `models/`: demos (GIF) y artefactos ligeros
- `data/`: datasets (NO se suben al repo)
- `runs/`: salidas de entrenamiento/inferencia (NO se suben al repo)

## Objetivo
Construir un modelo útil y demostrable, documentando mejoras con métricas y ejemplos visuales.