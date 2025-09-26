# Proyecto-RunnerJS
Mis paginas web del 1er Departamental .DERS
# 🚀 Proyecto Integrador de Aplicaciones Web: RunnerJS

## Descripción del Proyecto
Este proyecto integrador combina varias prácticas de la materia para crear una solución completa: una landing page (índice) que enlaza a un juego clásico estilo "Runner" con un sistema de Leaderboard persistente.

La solución está dividida en tres componentes principales:
1.  **Landing Page:** Un índice que enlaza a todas las prácticas anteriores.
2.  **Frontend (Juego):** El juego "RunnerJS" desarrollado en HTML, CSS y JavaScript.
3.  **Backend (API de Puntuaciones):** Un servidor RESTful desarrollado con Node.js y Express para gestionar la persistencia de datos del Leaderboard.

---

## 🛠️ Arquitectura y Tecnologías

| Componente | Tecnologías | Propósito |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript | Interfaz de usuario, lógica del juego (colisiones, movimiento) y comunicación con la API. |
| **Backend** | Node.js, Express, `fs` (File System) | Manejo de peticiones HTTP (GET y POST), lectura/escritura de puntuaciones en el archivo `scores.json`, y servicio de la API en `http://localhost:3000`. |
| **Persistencia** | `scores.json` | Base de datos simple de tipo JSON para almacenar los 10 mejores puntajes. |

---

## ⚙️ Configuración y Ejecución Local

Para ejecutar el proyecto de forma local y probar la funcionalidad completa (juego y Leaderboard), sigue estos pasos:

### 1. Clonar el Repositorio
```bash
git clone [https://www.youtube.com/watch?v=eQMcIGVc8N0](https://www.youtube.com/watch?v=eQMcIGVc8N0)
cd Practica1erDeptamental/
