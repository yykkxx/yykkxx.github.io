# yykkxx.github.io

A personal website showcasing interactive 3D web experiments.

## Features

### Multi-Window 3D Demo
An interactive Three.js demonstration that synchronizes 3D wireframe cubes across multiple browser windows. Open the demo in several browser windows and watch as they work together to create a unified 3D scene.

**Try it:** [3D Demo](./3d/)

## How to Use

1. Open the [3D Demo](./3d/) page
2. Open the same link in additional browser windows
3. Arrange the windows on your screen
4. Watch as the 3D cubes synchronize across all windows
5. Move or resize windows to see the effect update in real-time

## Technical Details

- **Built with:** Three.js (r124)
- **Features:**
  - LocalStorage-based window synchronization
  - Real-time position and size tracking
  - Smooth animations with easing
  - Responsive design

## Project Structure

```
.
├── index.html          # Landing page
├── 3d/                 # Multi-window 3D demo
│   ├── index.html
│   ├── main.js
│   ├── WindowManager.js
│   └── three.r124.min.js
├── 50x.html           # Error page
└── README.md
```

## Credits

This project demonstrates creative use of browser APIs to create synchronized multi-window experiences.

## License

Feel free to use and modify for your own projects.
