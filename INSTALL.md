# Install

Copy `README.md`, the `assets/` folder and `.github/workflows/snake.yml` into `systemrot/systemrot`.

Then open **Actions → Generate contribution snake → Run workflow** once.

The workflow writes the generated SVGs directly into `assets/` on the default branch, so the README uses stable local paths and does not depend on the `output` branch.
