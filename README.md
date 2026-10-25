# ClipCraft Studio

A local-first, browser-based video-editor prototype inspired by common template-driven editors. It is an independent implementation and is not affiliated with CapCut.

## Run

Open `index.html` in current Chrome or Edge. For best compatibility, serve the folder locally:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Implemented
- Template gallery with categories and search
- Apply templates to editable title styling and canvas ratio
- Import a local video or image and preview it in the browser
- Edit title text, size, color, weight, position and shadow
- Trim range controls and playback speed/filter adjustments
- Add/select audio file (preview/export audio mixing is not implemented yet)
- Save custom templates in localStorage
- Export canvas-rendered video in browser-supported WebM or MP4 format
- Export/import project settings JSON
- Responsive dark editing workspace

## Prototype limitations
This is a functional starter, not a complete professional nonlinear editor. It currently exports a single video/image with a text overlay; it does not yet mix audio into exports, implement true multi-clip editing/transitions, or offer server/cloud accounts. Browser codec support determines the output format, so export may be WebM even when MP4 is requested.
