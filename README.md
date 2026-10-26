# Organic 3D Viewer

A 3D molecule viewer for organic chemistry students. Type a molecule's name to see a rotatable model, switch between ball-and-stick and space-filling views, show R/S labels on stereocenters, and click atoms to measure bond lengths, angles and dihedral angles.

- 349 common organic molecules are built in and load instantly.
- Any other name is looked up on [PubChem](https://pubchem.ncbi.nlm.nih.gov/), and the 3D model is computed in the browser from PubChem's SMILES.
- Link straight to a molecule with `#name` (for example `#caffeine`) or `#cid-` plus a PubChem compound number (for example `#cid-3314`).

The whole site is the single file `index.html`. Structures are computed with a simplified force field, so measured values are close to typical experimental values but not exact.

## Lewis Structure Practice

`lewis/index.html` (live at https://lufox2021.github.io/Molecule-Viewer/lewis/) is a practice tool for general and organic chemistry students. It gives a molecule or ion's name and formula; students draw the Lewis structure (atoms, bonds, lone pairs, formal charges) and get specific feedback on electron count, octets, formal charges, expanded octets and resonance. It includes 115 problems at three levels, a Clean Up button that redraws the structure with VSEPR bond angles, a live 3D ball-and-stick model of the student's drawing, and the correct answer with all major resonance forms and a 3D model. Practice only: nothing is graded or saved.
