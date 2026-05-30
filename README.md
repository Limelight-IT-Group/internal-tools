# Internal Tools

## Overview
Internal operational tooling, dashboards and utilities for Limelight IT Group.

## Purpose
Houses tools built for internal use — the outreach pipeline app, reporting dashboards, client trackers and operational utilities. Not for external distribution. Production-grade internal tooling lives here once it has graduated from `ai-labs` or `automation`.

## Structure
```
internal-tools/
├── outreach-pipeline/   # Lead scoring and outreach management app
├── dashboards/          # Internal reporting and analytics dashboards
├── utilities/           # Standalone utility scripts and helpers
├── docs/                # Internal documentation and runbooks
├── .gitignore
└── README.md
```

## Usage
Each tool has its own README inside its subdirectory. General setup:
```bash
cd <tool-directory>
pip install -r requirements.txt
python3 main.py
```

## Standards
- All tools must have a README inside their subdirectory
- No client data committed to the repo
- Secrets via environment variables only
- Python 3.10+ required unless stated otherwise
- Commit messages follow Conventional Commits

## License
MIT License — Copyright (c) 2026 Limelight IT Group