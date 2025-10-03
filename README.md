# Internship Report - MkDocs

This project contains the internship report documentation built with MkDocs Material theme.

## Setup

1. Install MkDocs and Material theme:

```bash
pip install mkdocs mkdocs-material
```

2. Navigate to the project directory:

```bash
cd internship-report
```

3. Run the development server:

```bash
mkdocs serve
```

4. Open your browser and visit: `http://127.0.0.1:8000`

## Build

To build the static site:

```bash
mkdocs build
```

The site will be generated in the `site/` directory.

## Deploy

To deploy to GitHub Pages:

```bash
mkdocs gh-deploy
```

## Project Structure

```
internship-report/
├── docs/
│   ├── index.md              # Home page
│   ├── kgen-platform.md      # KGeN Platform documentation
│   └── team-interaction.md   # Team interaction report
├── mkdocs.yml                # Configuration file
└── README.md                 # This file
```
