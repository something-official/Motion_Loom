# Motion Loom

Motion Loom makes animation timing tangible. Each thread follows a different easing curve, leaving a temporary trail that shows how velocity changes over time. It is a practical bridge between CSS transitions, JavaScript requestAnimationFrame, and the performance budget of interactive interfaces.

## Run locally

This is a dependency-light static project. Serve this directory over localhost with any static server, then open the displayed URL in a modern browser. For example:

```bash
python3 -m http.server 4173
```

Open http://127.0.0.1:4173 and try the controls described in the page.

## What to study

- Animating with requestAnimationFrame
- Comparing linear, smoothstep, and spring-like easing
- Using controls to expose animation parameters
- Respecting reduced-motion preferences
- Rendering only what the user needs to see

## Browser notes

The project uses ordinary HTML, CSS, and JavaScript with no build step or runtime package dependency. The visual system is drawn with Canvas 2D perspective primitives so it remains easy to clone and inspect.

## License

Released under the MIT License. See [LICENSE](LICENSE).
