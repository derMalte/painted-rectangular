# painted-rectangular

A minimalist interactive webpage that recursively splits the screen into black and white rectangles.

## What it does

On load, the screen is divided in half — one black, one white — split along the **shorter side** of the window (so a landscape screen splits left/right, a portrait screen splits top/bottom).

Click any rectangle to split it into two smaller rectangles (one black, one white), again divided along the shorter side of that rectangle. You can keep clicking to subdivide indefinitely.

## Usage

No build step or dependencies required. Just open `index.html` in any modern browser.

```
open index.html
```

## Features

- Automatically orients the initial split based on the window's aspect ratio
- Each click recursively subdivides the clicked rectangle
- Split direction is always along the shorter side of the clicked element
- Hover highlight shows which rectangles are clickable
