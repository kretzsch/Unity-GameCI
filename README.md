# Unity Cross Platform CI

A demonstration of a CI/CD pipeline for Unity using GitHub Actions and GameCI.

## Features
- Automated builds on every push
- Multi-platform support (Windows, WebGL)
- Build caching for faster pipelines
- Downloadable build artifacts

## Tech Stack
- Unity
- GitHub Actions
- GameCI

## Pipeline Overview
Each push to `main`:
1. Triggers a CI workflow
2. Builds the project for multiple platforms
3. Uploads artifacts for download

## Why This Matters
This setup simulates a production-ready workflow, ensuring consistent builds and reducing manual errors.

## Future Improvements
- Add automated tests
- Add deployment (itch.io / Steam)
