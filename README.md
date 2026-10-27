# ACNEI-IBL Neural Modelling Workshop

This repository is a collaborative workspace for the ACNEI-IBL Neural Modelling Workshop. It is designed for 5 project teams to work together on separate tasks, share results, and upload their modelling work in a single central place.

## Goals

- Support 5 different project teams
- Keep each team's work organised in its own folder
- Encourage collaborative development using Git and GitHub
- Allow teams to upload notebooks, scripts, reports, and results
- Make it easy to review, merge, and discuss work between teams

## Repository structure

```text
acnei-ibl-neural-modelling-workshop/
├── README.md
├── CONTRIBUTING.md
├── docs/
│   └── workshop-overview.md
├── teams/
│   ├── README.md
│   ├── team-01/
│   │   └── README.md
│   ├── team-02/
│   │   └── README.md
│   ├── team-03/
│   │   └── README.md
│   ├── team-04/
│   │   └── README.md
│   └── team-05/
│       └── README.md
└── LICENSE
```

## Team workflow

Each team should work inside their own folder:

- `teams/team-01/`
- `teams/team-02/`
- `teams/team-03/`
- `teams/team-04/`
- `teams/team-05/`

Recommended project layout inside each team folder:

```text
teams/team-01/
├── README.md
├── data/
├── notebooks/
├── scripts/
├── results/
├── reports/
└── notes/
```

## How to upload work

1. Clone the repository.
2. Create a branch for your team or for your project.
3. Add your files inside the correct `teams/team-XX/` folder.
4. Commit your changes with a clear message.
5. Push to GitHub.
6. Open a pull request for review.

## Suggested file types

Teams can upload:

- Python notebooks (`.ipynb`)
- Scripts (`.py`, `.R`, `.sql`)
- Model outputs and figures
- CSV or JSON datasets
- Markdown reports
- Documentation notes
- Results summaries

## Collaboration guidelines

- Keep each team's files separate.
- Use descriptive names for scripts and outputs.
- Add a short README in each team folder explaining the project.
- Use pull requests to share work and review changes.
- Write commit messages that explain what was updated.
- Do not overwrite another team’s files.

## Recommended project process

- Define the research question
- Prepare and clean data
- Build and test the model
- Evaluate performance
- Save results and visualisations
- Write a short final summary

## Getting started

Use the `teams/README.md` file as the main collaboration guide for all five teams.

If you want a cleaner project structure for the workshop, you can later add:

- `datasets/`
- `notebooks/`
- `templates/`
- `assignments/`
- `slides/`
- `meeting-notes/`

## License

This project is licensed under the MIT License.

---

This repository is intended to provide a simple, scalable foundation for collaborative workshop work across multiple teams.
