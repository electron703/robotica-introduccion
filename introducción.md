# 🤖 Introducción a la Robótica

## 1. ¿Qué es un robot?

Un robot es una máquina capaz de percibir su entorno, procesar información y actuar en consecuencia para cumplir una tarea.

👉 En términos simples:
- Recibe información (sensores)
- Decide qué hacer (controlador)
- Actúa (motores o actuadores) 

📌 Ejemplos:
- Robots industriales (líneas de producción)
- Robots domésticos (aspiradoras automáticas)
- Robots de exploración (espaciales o submarinos)
- Robots educativos y de competición 

## 2. Robots de competición
En el ámbito educativo, la robótica suele trabajarse a través de competencias, donde los robots deben cumplir objetivos específicos.
⚔️ Robot Sumo
    • Dos robots luchan dentro de un ring 
    • Objetivo: empujar al oponente fuera del área 
    • Requiere: fuerza, estrategia y sensores 
🏁 Robot de Carreras (Seguidor de línea)
    • Sigue una línea en el suelo 
    • Gana el más rápido 
    • Requiere: precisión y velocidad 
⚽ Robot Fútbol
    • Robots juegan en equipos 
    • Deben detectar la pelota y el arco 
    • Requiere: coordinación y control 
🧠 Otros tipos
- Laberinto (resolver caminos)
- Mini desafíos de precisión 
- Robots autónomos o controlados por radio (RC)
- 
## 3. Diagrama de bloques de un robot

Un robot se puede representar mediante el siguiente esquema:

    [Sensores] → [Controlador] → [Actuadores]
         ↑                           ↓
         └──── Retroalimentación ────┘
         
Esto responde al concepto de sistema automático con control.

Explicación:
- Sensores: Detectan información del entorno
- Controlador: Procesa la información (decide)
- Actuadores: Ejecutan la acción 
    
Diagráma de bloques de un robot de carreras:
<img width="985" height="786" alt="imagen" src="https://github.com/user-attachments/assets/d2ac9947-a93e-4da8-8704-b2ed6d11c4ea" />



## 4. Partes principales de un robot
🔍 Sensores (Entrada)
Permiten que el robot "perciba"
Ejemplos:
    • Sensores infrarrojos (IR) 
    • Sensores ultrasónicos 
    • Sensores de línea 
    • Encoders (posición/velocidad) 
⚙️ Actuadores (Salida)
Permiten que el robot "se mueva o actúe"
Ejemplos:
    • Motores DC 
    • Servomotores 
    • Motores paso a paso 
🧠 Controlador
Es el "cerebro" del robot
Ejemplos:
    • Microcontroladores (Arduino, ESP32) 
    • Placas de desarrollo 
Funciones:
    • Leer sensores 
    • Ejecutar programas 
    • Controlar motores 
🔋 Fuente de energía
Alimenta todo el sistema
Ejemplos:
    • Baterías (LiPo, 18650, etc.) 
🧱 Estructura mecánica
Es el "cuerpo" del robot
Incluye:
    • Chasis 
    • Ruedas 
    • Soportes 
## 5. Áreas que intervienen en la robótica
La robótica es una disciplina multidisciplinaria, combina varias áreas:

| ⚡ Electrónica | ⚙️ Mecánica | 💻 Programación |
|----------------|-------------|-----------------|
| Diseño de circuitos | Diseño del chasis | Lógica de control |
| Sensores y actuadores | Transmisión de movimiento | Toma de decisiones |
| Drivers de motores | Reducción de velocidad (engranajes) | Automatización |
| Alimentación eléctrica |Materiales y resistencia  | Lenguajes (Arduino, C/C++, Python) |
|  | Diseño e impresión 3D: CAD, prototipado rápido, |  |
|  | fabricación de piezas personalizadas |  |





 



## 6. Ejemplo de funcionamiento de un robot
👉 Robot seguidor de línea:
    1. Sensores detectan la línea 
    2. Controlador interpreta la posición 
    3. Ajusta la velocidad de los motores 
    4. El robot corrige su trayectoria 
## 7. Actividad sugerida (10–15 min)
💡 Pregunta disparadora:
    • ¿Qué diferencia hay entre sensor y actuador? 
    • ¿Qué hace el controlador? 
    • ¿Por qué es importante la mecánica en un robot?
    • ¿Qué componentes serían necesitaríos para armar un robot para participar en una competencia de mini sumo? Tener en cuenta: 
        ◦ Sensores 
        ◦ Motores 
        ◦ Controlador 
        ◦ Estructura 
        ◦ Limites físicos indicados en los reglamentos (dimensiones, peso).
## 8. 📌 Ideas clave:
    • Un robot = sensores + control + acción 
    • La robótica integra varias disciplinas 
    • Las competencias son una forma práctica de aprender 
