# Hydraulic System Simulation & Automated Testing Tool

## Descripción del Proyecto
Simulador en Python diseñado para modelar el comportamiento hidrodinámico y calcular pérdidas de presión en sistemas de tuberías industriales. Este proyecto integra principios de mecánica de fluidos con prácticas de desarrollo de software como pruebas unitarias automatizadas.

## Características Técnicas
* **Cálculo de Mecánica de Fluidos:** Implementación de fórmulas para el Número de Reynolds, fricción en tuberías (PVC Schedule 80, HDPE) y coeficientes de accesorios.
* **Validación Automatizada (QA):** Suite de pruebas unitarias con **Pytest** para asegurar la precisión decimal de los cálculos físicos.
* **Diseño Modular:** Funciones separadas para escalabilidad y mantenimiento del código.

## Tecnologías Utilizadas
* Python 3.x
* Pytest (Framework de pruebas)
* Git & GitHub (Control de versiones)

## Cómo ejecutar las pruebas
Para validar la lógica del simulador, ejecutar en la terminal:
```bash
pytest test_water_flow.py -v