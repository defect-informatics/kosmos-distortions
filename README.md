# Kosmos bond-distortion trajectories

Per-start relaxation movies for the [Kosmos defect library](https://defect-informatics.github.io/kosmos/).

Each compressed JSON file (`snbtraj/<mp-id>/<defect>.jsongz`) holds the saved optimizer frames, the recorded energy and force curves and the sample indices of one bond-distortion start stored on Eagle. Integer coordinate deltas keep the published coordinate precision; the site rebuilds the geometry at each frame.

The website fetches these files from a pinned revision of this repository. Truncated or inconsistent source files are excluded and listed in `manifest.json`; no geometry is interpolated or borrowed.
