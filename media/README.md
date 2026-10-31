# Site media

Drop files here with these exact names. Each figure stays hidden until its file exists, then appears automatically. No code changes needed. Images and videos only show if the file name matches exactly (lower-case).

## Hybrid RNG (Research, first study)

| File | Slot | Ideal content |
|---|---|---|
| `demo.mp4` + `demo-poster.jpg` | 03 Hardware demonstration | Done: narrated lab video (H.264, 608×1080 portrait, 27 MB). |
| `pendulum-hardware.jpg` | Fig. 1 | The physical double pendulum with both rotary encoders visible. Plain background, even light, landscape 4:3, ~1600 px wide, under 400 KB. |
| `phase-portrait.png` | Fig. 2 | Phase portrait with labelled axes and units (e.g. θ₁ vs ω₁). If it's from encoder data, change the caption to "Measured phase portrait" in index.html. |

## Collective cell mechanics (Research, second study)

| File | Slot | Ideal content |
|---|---|---|
| `cell-sim.mp4` | Fig. 3 (full width, loops silently) | Your single best simulation clip: 8–15 s, silent, H.264 MP4, 1280 px wide max, under ~8 MB. Ideally shows the system going from disorder to coordinated motion or spreading. Avoid UI chrome (crop out Streamlit sidebars). |
| `cell-sim.png` | Fig. 4 | A still frame with Voronoi contacts visible; colour agents by something meaningful (heading, speed or strain) and include a colour bar. 4:3, ~1600 px wide. |
| `vicsek-validation.png` | Fig. 5 | Order parameter vs. noise from your model, with the Vicsek et al. (1995) reference behaviour overlaid. Labelled axes, legend, error bars if you have them. |

Axolotl microscopy images belong to the lab: get Dr. Lynch's OK before posting any experimental (unpublished) images or data.

## Format rules

- Video: H.264 MP4 (not HEVC/.mov), silent unless narrated, under ~10 MB each. GitHub rejects files over 100 MB.
- Plots: export at 2× resolution (~1600 px wide), dark or transparent background, fonts large enough to read on a phone.
- Keep raw footage and originals outside this folder.
