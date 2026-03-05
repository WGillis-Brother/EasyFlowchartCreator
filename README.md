# Easy Flowchart Creator

A fast, lightweight, browser-based flowchart editor for troubleshooting workflows.

Build decision trees in seconds, save your work as JSON, and export clean PDFs for handoff, documentation, or field teams.

## AI Notice

This project was created with the help of AI tools.

It is shared as-is for the community to use, fork, and improve. Ongoing coding support and custom troubleshooting are not provided by the original publisher.

## Why Easy Flowchart Creator?

- Single-file app (`EasyFlowchartCreator.html`) with no backend required
- Easy node editing and drag-and-drop layout
- Visual connection building with instant delete controls
- Project save/load for ongoing work
- Print-friendly PDF export from a dark editor UI

## Highlights

### Node editing
- Add **Square/Rectangle**, **Diamond**, and **Circle/Pill** nodes
- Drag to move and use corner handles to resize
- Click node text to edit inline
- Open node context menu for **Properties**, **Copy**, and **Delete**

### Connections
- Drag the **green dot** to create a connection
- Arrowed SVG lines are drawn between nodes
- Click the **red dot** on a line to remove a connection

### Workspace controls
- Pan by dragging empty canvas space
- Zoom with mouse wheel or slider
- One-click **Fit to Screen**
- Switch canvas **Landscape / Portrait** orientation

### Output and persistence
- Save editable projects as `.flowchart.json`
- Reload projects later with full node/edge data
- Export to PDF with light-mode print styling

## Quick Start

1. Download or clone this repository.
2. Open `EasyFlowchartCreator.html` in your browser.
3. Add nodes from the **Shapes** section.
4. Connect nodes with the green connector dots.
5. Save your project or export as PDF.

## Controls

**Toolbar**
- `Save Project` — Download editable JSON
- `Load Project` — Load a previously saved flowchart JSON
- `Export PDF` — Create printable output
- `Clear All` — Reset canvas

**Shortcuts**
- `Delete` — Remove selected node
- `Ctrl/Cmd + S` — Save project
- `Ctrl/Cmd + P` — Export PDF
- `Escape` — Close properties modal

## Tech Stack

- HTML + CSS + JavaScript (vanilla)
- SVG for connector rendering
- CDN dependencies:
  - `html2canvas@1.4.1`
  - `jspdf@2.5.1`

## Project File Format

Saved projects are JSON and include:

- metadata (`app`, `version`, `format`, `schemaVersion`)
- chart `title`
- `orientation`
- canvas size (`width`, `height`)
- `nodes[]`
- `edges[]`

## Browser Support

- Latest Chromium-based browsers (Chrome, Edge)
- Firefox

## Current Version

`1.0.2`

## Roadmap Ideas

- Undo/redo history
- Multi-select and grouping
- Snap-to-grid and alignment guides
- PNG/SVG export options

## Contributing

Contributions are welcome. If you want to improve UX, add features, or polish export behavior:

1. Fork the repo
2. Create a feature branch
3. Make focused changes
4. Open a pull request with screenshots or sample output

## License

This project is licensed under the MIT License.

You can use, copy, modify, merge, publish, distribute, sublicense, and sell this software, including for commercial use.
See [LICENSE](LICENSE) for full details.
