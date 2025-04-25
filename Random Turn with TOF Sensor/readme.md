# Random Turn with TOF Sensor (UGOT)  
## 🇬🇧 What does this code do?

This code makes the **UGOT Transforming Car** robot:

- Move forward if there are no obstacles within 5 cm.
- Randomly generate:
  - A number (`num`) to decide whether to turn left or right.
  - An angle (`giro`) between 10° and 100° for the turning motion.
- If an obstacle is detected, the robot also decides which way to turn and how much, using the same random values.

### 🔧 Sensors used:
- 📏 **TOF (Time-of-Flight) distance sensor**: Detects if an obstacle is closer than 5 cm.

---

# Giro Aleatorio con Sensor TOF (UGOT)  
## 🇪🇸 ¿Qué hace este código?

Este código hace que el robot **UGOT Transforming Car**:

- Avance si no hay obstáculos a menos de 5 cm.
- Genere aleatoriamente:
  - Un número (`num`) para decidir si gira a la izquierda o derecha.
  - Un ángulo (`giro`) entre 10° y 100° para realizar el giro.
- Si se detecta un obstáculo, también decide el giro con esos valores aleatorios.

### 🔧 Sensor utilizado:
- 📏 **Sensor de distancia TOF**: Detecta si hay un obstáculo a menos de 5 cm.