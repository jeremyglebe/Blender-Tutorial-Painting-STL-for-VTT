# STL → VTT Art Lab

A practical Blender workflow for turning STL miniatures into VTT character art using simple materials, lighting, ambient occlusion, Freestyle linework, and transparent PNG renders.

## Live Site

Open the local static site through [index.html](index.html), or visit the [GitHub repository](https://github.com/jeremyglebe/Blender-Tutorial-Painting-STL-for-VTT) for the current source.

## Who This Is For

- VTT GMs and players
- People with STL libraries
- People who want customized character art without becoming Blender experts
- Mini painters translating familiar material ideas into digital renders

## The Basic Workflow

1. Import and inspect the STL.
2. Assign broad materials with face selection.
3. Frame the model with an orthographic camera.
4. Shape it with a Sun and an Area Light.
5. Add restrained Ambient Occlusion and Freestyle linework.
6. Export a transparent PNG.
7. Do a light cleanup pass and save the scene as a reusable template.

The Basic Workflow is intentionally kept simple. Advanced techniques and quick-reference material live on separate pages so beginners can get a result without opening every node editor.

## Open the Guide

Open [index.html](index.html) in a browser. It is a self-contained static page with:

- Linked sections and a responsive contents menu
- A learning path organized around visual decisions
- Expandable troubleshooting answers
- Lesson completion buttons saved in the browser
- Checklists for post-processing and final export

No build step or external dependency is required.

## Project Files

- `index.html` — the polished public guide
- `docs/advanced/index.html` — optional advanced techniques hub
- `docs/advanced/*.html` — focused pages for materials, lighting, backgrounds, paint, shading, compositing, kitbashing, templates, and alternate tools
- `reference/index.html` — quick-reference hub
- `reference/material-recipes.html` — common material settings cookbook
- `contribute.html` — how to report Blender changes and suggest improvements
- `notes.md` — ongoing discoveries, Blender-version-specific notes, and future screenshot ideas
- `README.md` — project purpose and quick start

## Blender Version Notes

The guide documents Blender 4.x-era workflows while acknowledging that panel names and render options move between releases. See [notes.md](notes.md) for version-specific observations. If a menu moved or a setting was renamed, please [open an issue](https://github.com/jeremyglebe/Blender-Tutorial-Painting-STL-for-VTT/issues) with your Blender version and a screenshot when possible.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md), use the focused [GitHub issue forms](https://github.com/jeremyglebe/Blender-Tutorial-Painting-STL-for-VTT/issues/new/choose), or open a pull request. Material recipes, UI corrections, screenshots, troubleshooting notes, and accessibility improvements are all welcome.

The guide is designed to grow with screenshots of Material Properties, Linked Flat Faces, Camera Properties, Eevee/AO, and Freestyle when those examples are available. See [CHANGELOG.md](CHANGELOG.md) for recent additions.

The advanced pages are deliberately separate. They are optional next steps after the basic workflow, not prerequisites for getting a usable render.
