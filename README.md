# DCM Atlas: effective connectivity knowledge graph (20-paper pilot)

Interactive static site for the Dynamic Causal Modelling (DCM) effective-connectivity pilot.

- **Live site:** https://josh45244.github.io/dcm-kg-pilot/
- **Explorer:** 105 normalized regions and 306 extracted connections from 20 papers, drawn as directed arcs inside a 3D brain.
- **Corpus:** 972 DCM papers grouped into 33 condition groups.
- The brain is a procedural model built in Blender (`scripts/07_build_brain_model.py`). Region positions are approximate canonical MNI locations for display, not coordinates reported by the papers.
- No full-text PDFs or verbatim verification quotes are published here.

Rebuild: run `scripts/07_build_brain_model.py` in Blender (only when the model changes), then `python scripts/06_build_website.py`.
