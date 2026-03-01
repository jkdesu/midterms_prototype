# Tokyo ↔ Manhattan — MediaPipe Prototype

A web prototype with:
- **Arrow keys** to switch city background (← Tokyo | → Manhattan | ↑ both)
- **Virtual background** (Zoom-like): Tokyo/Manhattan as background with you in front
- **Banana detection** (COCO) with bounding boxes
- **Audio**: Tokyo → grateful.mp3, Manhattan → true.mp3

## Run

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Required folders

- `banana_images/` — tokyo.png, manahttan.jpg
- `mp3_data/` — grateful.mp3, true.mp3
