# Parking-garage scene

A 3D scene used in an online study, embedded in a Qualtrics survey. It's served by GitHub Pages; participants reach it through the survey link, not directly.

## What's here
- `garage.html`: the scene. It needs `?c=0` or `?c=1` and `&pid=…` in the address.
- `textures/`: pictures the scene loads. The floor photos are from Poly Haven (CC0).
- `vendor/three-0.170.0/`: three.js r0.170.0, unchanged, under its MIT licence (`LICENSE`).

## Updating
This folder is built from the study's working folder by `make_site.sh`. Change `garage.html` there, run the script, then commit and push from here.
