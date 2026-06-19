# 🐛 Bug Smash
Backend contra Frontend en un duelo a dos jugadores sobre una hoja de cuaderno. El que pierde se come el ticket. 😅

## ✨ Características
- Juego de lucha local para 2 jugadores (P1 "Backend" vs P2 "Frontend").
- Estética dibujada a mano: papel cuadriculado, trazos temblorosos y tipografía manuscrita.
- Renderizado completamente en `<canvas>` con primitivas vectoriales generadas en código (sin imágenes).
- Mecánicas de pelea: golpes, smash (mantener), ataque especial y escudo.
- Un solo archivo `index.html` autocontenido, sin dependencias.

## 🚀 Cómo jugar / ejecutar
```bash
open index.html
```
O sírvelo desde cualquier servidor estático:
```bash
python3 -m http.server
# luego abre http://localhost:8000
```

## 🎮 Controles
**P1 Backend**
- A / D: mover · W: saltar · S: bajar
- F: golpe (mantener = smash) · G: especial · Q: escudo

**P2 Frontend**
- ← / →: mover · ↑: saltar · ↓: bajar
- , : golpe · . : especial · / : escudo

## 🛠️ Tecnología
- JavaScript puro (vanilla) + Canvas 2D API.
- Dibujo procedural con efecto "hand-drawn" hecho a mano.
- HTML/CSS, sin frameworks ni build.

## 📦 Parte de mi colección de juegos
Uno más de mis proyectos de juegos hechos por hobby. 🎮
