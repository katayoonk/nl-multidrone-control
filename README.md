# Internal project page

## Live page

https://katayoonk.github.io/nl-multidrone-control/

Repo: https://github.com/katayoonk/nl-multidrone-control

Static project page for the natural-language multi-drone control work.
Content tracks `PROJECT_OVERVIEW.md`.

## Preview

From `~/sde`:

```bash
python3 -m http.server 8000 --directory project-page
```

Open <http://localhost:8000>.

## Contents

- `index.html` — internal project overview
- `styles.css` — responsive page styles
- `assets/field-test-demo.mp4` — compressed web copy of the field-test video
- `assets/field-test-poster.jpg` — hero / video poster
- `assets/drone-0-camera.jpg` and `drone-1-camera.jpg` — frames from the physical drones

The page also links the Drive copy of the field-test video for sharing outside the local assets.

## Publishing

The page is marked **Internal**. Before publishing externally:

1. confirm approval for every person and location visible in the media;
2. replace the internal label and footer;
3. add final project/team names and approved contact details;
4. decide whether the ~14 MB video stays in git or is hosted only on Drive; and
5. review technical and safety claims with the flight team.
