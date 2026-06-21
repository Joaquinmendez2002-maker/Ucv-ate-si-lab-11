# Ucv-ate-si-lab-11
Algoritmo de Poda Alfa-beta
# Laboratorio: Minimax y Poda Alfa-Beta

## Descripción
Este proyecto implementa los algoritmos Minimax y Poda Alfa-Beta para resolver un árbol de decisión simplificado.

## Objetivo
Comparar el resultado y la eficiencia de Minimax frente a Poda Alfa-Beta.

## Instalación
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Ejecución
```bash
python -m src.main
```

## Pruebas
```bash
pytest --cov=src --cov-report=term-missing
```

## Preguntas de análisis
1. ¿Por qué Minimax y Alfa-Beta devuelven el mismo valor?
2. ¿Cuándo Alfa-Beta reduce más nodos?
3. ¿Qué ocurre si el árbol está mal ordenado?
4. ¿Cómo se aplicaría este algoritmo en ajedrez, damas o tres en raya?
```
