# 🪨 Piedra, Papel o Tijera — Juego en Python

Este proyecto es una versión mejorada del clásico juego **Piedra, Papel o Tijera**, desarrollado en Python como parte del curso *Lógica de Programación*. El juego permite al usuario competir contra el computador, registrar resultados y visualizar un resumen final.

---

## 🎮 ¿Cómo funciona?

El usuario elige entre piedra, papel o tijera, y el computador selecciona aleatoriamente una opción. El programa determina el ganador según las reglas clásicas:

- Piedra rompe tijera
- Tijera corta papel
- Papel envuelve piedra

---

## 📋 Menú de opciones

#############################################
             Piedra, papel o tijera
              [1] piedra
              [2] papel
              [3] tijera
              [0] salir
#############################################
🧠 Lógica del juego
El juego está estructurado en funciones modulares:

mostrar_menu() → Muestra las opciones disponibles.

obtener_opcion_usuario() → Valida la entrada del jugador.

obtener_opcion_computador() → Genera una elección aleatoria.

determinar_ganador() → Evalúa el resultado.

mostrar_resultado() → Muestra el resultado de la ronda.

jugar() → Controla el flujo principal del juego.

📊 Diagrama de flujo

🧪 Ejemplo de ejecución
Has elegido: papel
Computador eligió: piedra
¡Ganaste! 😊🙌

¿Quieres seguir jugando? (s/n): s
📈 Resumen final
Al finalizar el juego, se muestra un resumen con los resultados acumulados:

📊 Resumen de la partida:
Victorias: 3
Derrotas: 2
Empates: 1

🛠 Requisitos
Python 3.x
No se requieren librerías externas

📁 Estructura del proyecto
Código
ppt_mejorado/
├── main.py
├── .gitignore
└── README.md

👨‍💻 Autor
Ariel Sarmiento Estudiante de Lógica de Programación Repositorio académico: github.com/Prosarmiento
