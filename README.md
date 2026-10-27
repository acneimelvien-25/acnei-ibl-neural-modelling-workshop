# ACNEI-IBL Neural Modelling Workshop

A collaborative GitHub workspace for the ACNEI-IBL Neural Modelling Workshop, designed to support five different project teams working on distinct modelling tasks while sharing one repository for version control, collaboration, and file uploads.

## Workshop purpose

This repository provides a structured environment where students or research teams can:

- work independently within their own team folder
- collaborate through GitHub pull requests and code review
- upload notebooks, scripts, datasets, reports, and results
- share progress across all five project teams in one central location
- maintain a clear and reproducible project history

## Overview of the five teams

Each team works on a different project or analytical track within the workshop. The repository is structured so that every team has a dedicated workspace while still benefiting from a unified collaboration environment.

- Team 01
- Team 02
- Team 03
- Team 04
- Team 05

## Repository structure

```text
acnei-ibl-neural-modelling-workshop/
├── README.md
├── CONTRIBUTING.md
├── LICENSE
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
└── .gitignore
```

## Team workflow

Each team should work in its own folder:

- `teams/team-01/`
- `teams/team-02/`
- `teams/team-03/`
- `teams/team-04/`
- `teams/team-05/`

Each team folder can contain a standard structure like:

```text
teams/team-01/
├── README.md
├── data/
├── notebooks/
├── scripts/
├── results/
├── reports/
├── notes/
└── figures/
```

## Recommended project lifecycle

1. Define the project objective and research question.
2. Prepare or clean the dataset.
3. Build and test the modelling approach.
4. Run evaluations and compare model performance.
5. Save outputs in `results/` or `reports/`.
6. Write a summary of findings and next steps.
7. Open a pull request for review and feedback.

## Accepted file types

Teams may upload many kinds of project material, including:

- Jupyter notebooks (`.ipynb`)
- Python scripts (`.py`)
- R scripts (`.R`)
- SQL scripts (`.sql`)
- CSV and JSON data files
- figures and plots
- model outputs
- documentation files (`.md`)
- presentation slides

## Collaboration rules

- Keep each team’s work in its own folder.
- Use clear and descriptive filenames.
- Update the `README.md` inside each team folder as the project evolves.
- Use GitHub branches for isolated work.
- Submit pull requests for review before merging significant changes.
- Avoid overwriting another team’s files.
- Store final outputs in `results/`, `reports/`, or `figures/`.

## Contribution workflow

To contribute to the workshop repository:

1. Clone the repository.
2. Create a branch for your work.
3. Add or modify files inside your assigned team folder.
4. Commit with a clear and descriptive message.
5. Push the branch to GitHub.
6. Open a pull request and request review.

See `CONTRIBUTING.md` for more details.

## Documentation

Additional workshop documentation is stored in the `docs/` folder.

- `docs/workshop-overview.md` — overview of the workshop structure, goals, and collaboration flow

## Goals for the workshop

This repository is intended to help teams:

- build and compare neural modelling approaches
- collaborate in a reproducible environment
- document and share results clearly
- produce workshop outputs that are easy to review and discuss

## License

This project is licensed under the MIT License.

---

This repository provides a shared, scalable foundation for collaborative modelling work across five project teams in the ACNEI-IBL workshop.
