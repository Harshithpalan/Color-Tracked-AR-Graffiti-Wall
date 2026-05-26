# Color-Tracked AR Graffiti Wall (SPRAYCAM)

Hold a colored object in front of your webcam and paint on a virtual graffiti wall. HSV color tracking maps your object's position to spray strokes on the canvas.

## Features

- Real-time HSV color tracking via webcam
- Multiple track colors + custom color picker
- Spray styles: spray, thick, neon, chalk, pixel, rainbow
- Adjustable brush size, pressure, scatter, and drip
- Color sensitivity controls (hue range, brightness, saturation)
- Save PNG, undo, and clear wall
- Mouse/touch fallback painting on the wall

## Quick start

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) and allow camera access.

> **Note:** Browsers require `localhost` or HTTPS for camera access. Opening `index.html` directly via `file://` will not work.

## How to use

1. Select a **Track Color** that matches your physical object (or pick a custom color).
2. Hold the object in front of the camera until the tracker appears.
3. Move the object to paint; choose **Paint Color**, brush settings, and **Style** as needed.
4. Tune **Color Sensitivity** if tracking is too loose or strict.

## Tech

Single-page app: HTML, CSS, and vanilla JavaScript with Canvas 2D and `getUserMedia`.

## License

MIT
