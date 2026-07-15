# STL → VTT Art Lab

A beginner-friendly guide for turning collected STL miniatures into readable, stylized character art for virtual tabletops with Blender.

The workflow is intentionally small and repeatable:

1. Import and inspect the STL.
2. Assign broad materials with face selection.
3. Frame the model with an orthographic camera.
4. Shape it with a Sun and an Area Light.
5. Add restrained Ambient Occlusion and Freestyle linework.
6. Export a transparent PNG.
7. Do a light cleanup pass and save the scene as a reusable template.

## Open the guide

Open [index.html](index.html) in a browser. It is a self-contained static page with:

- Linked sections and a responsive contents menu
- A learning path organized around visual decisions
- Expandable troubleshooting answers
- Lesson completion buttons saved in the browser
- Checklists for post-processing and final export

No build step or external dependency is required.

## Project files

- `index.html` — the polished public guide
- `docs/advanced/index.html` — optional advanced techniques hub
- `docs/advanced/*.html` — focused pages for materials, lighting, backgrounds, paint, shading, compositing, kitbashing, templates, and alternate tools
- `notes.md` — ongoing discoveries, Blender-version-specific notes, and future screenshot ideas
- `README.md` — project purpose and quick start

The guide is designed to grow with screenshots of Material Properties, Linked Flat Faces, Camera Properties, Eevee/AO, and Freestyle when those examples are available.

The advanced pages are deliberately separate. They are optional next steps after the basic workflow, not prerequisites for getting a usable render.
