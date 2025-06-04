# Color Recognition and Stage-Based Control (UGOT)

## 🇬🇧 What does this code do?

This code gives the **UGOT robot** two combined modes:

1. **Color recognition with progression**:  
   - Scans orange and purple balls using AI vision.  
   - Advances through stages (`etapa`) and gives visual/sound feedback after each detection.  
   - Lights, messages, and movement vary depending on the detected color.

2. **Keyboard control based on stage**:  
   - Uses `w`, `a`, `s`, `d` to control movement.  
   - Behavior changes depending on the current stage.  
   - Speeds, directions, and actions vary progressively.

### 🔧 Sensors and components used:
- 📷 **Camera** (AI Vision): For color recognition.
- ⌨️ **Keyboard input**: Stage-based movement control.
- 💡 **RGB LEDs**: Stage indication and feedback.
- 🔊 **Speaker**: Victory sound and feedback per color.

---

# Reconocimiento de Colores y Control por Etapas (UGOT)

## 🇪🇸 ¿Qué hace este código?

Este código otorga al **robot UGOT** dos modos combinados:

1. **Reconocimiento de colores con avance por etapas**:  
   - Escanea pelotas de color naranja y morado con visión artificial.  
   - Aumenta una variable de etapa (`etapa`) y da retroalimentación visual y sonora.  
   - Las luces, mensajes y velocidad cambian según el color detectado.

2. **Control por teclado según la etapa**:  
   - Usa `w`, `a`, `s`, `d` para controlar el movimiento.  
   - El comportamiento depende del valor de la etapa.  
   - Varían direcciones, giros y velocidades de forma progresiva.

### 🔧 Sensores y componentes utilizados:
- 📷 **Cámara** (Visión AI): Para reconocer colores.  
- ⌨️ **Entrada por teclado**: Control del movimiento según la etapa.  
- 💡 **Luces RGB**: Indicación de etapa y retroalimentación.  
- 🔊 **Altavoz**: Sonido de victoria y respuestas por color.