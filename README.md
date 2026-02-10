# D-D-Campaign-Notes — Template

This repository is a blank template for organizing D&D (or tabletop) campaign notes.
Use the folders and templates to record sessions, NPCs, locations, items, and player characters.

How to use
- Copy this repository to start a new campaign.
- Fill in templates in the `templates/` directory and keep organized content in `sessions/`, `characters/`, `npcs/`, `locations/`, and `items/`.

This file lists the structure of the template repository:

- README.md
- .gitignore
- LICENSE
- CONTRIBUTING.md
- templates/
  - session-template.md
  - character-template.md
  - npc-template.md
  - location-template.md
  - item-template.md
- sessions/ (empty, for notes)
- characters/ (empty, for filled character files)
- npcs/ (empty)
- locations/ (empty)
- items/ (empty)
- docs/ (optional)

How to create the public, cloneable repository (two options)

1) Create locally and push to GitHub (manual flow)

- Create a new repo on GitHub (name it e.g. `D-D-Campaign-Notes-Template`) and make it Public.
- Locally:

```bash
# clone your empty repo (or create locally and add remote)
git clone git@github.com:<your-username>/<repo-name>.git
cd <repo-name>

# copy the template files into the folder (or save these files)
git add .
git commit -m "Initial template commit: campaign notes structure"
git push -u origin main
```

2) Use GitHub CLI (creates repo on GitHub and pushes the current directory)

From a directory containing the files above:
