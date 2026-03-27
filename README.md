# GitHub Tag Analyzer

A Python project for collecting, analyzing and classifying GitHub tags and releases.

## Features
- Connects to the GitHub REST API
- Collects tag and release data from public repositories
- Classifies version tags using regex
- Stores processed results in structured JSON
- Can be extended for update checks and release monitoring

## Tech stack
- Python
- GitHub REST API
- JSON
- Regex

## Example use case
This project can be used to analyze public repositories and create structured release information for further processing.

## Project structure
- `main.py` – main script
- `utils.py` – helper functions
- `data/` – sample JSON output
- `README.md` – project documentation

## Next steps
- Add update detection for new releases
- Export results to CSV
- Improve tag normalization logic
