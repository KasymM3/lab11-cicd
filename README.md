# lab11-cicd

Small Flask app for Practice 11: GitHub Actions CI/CD, tests, secret scanning and GHCR.

Endpoints: `/`, `/healthz`, `/version`.

Run locally (PowerShell):

```powershell
py -m pip install -r requirements-dev.txt
py -m pytest -q
py app.py
```

The CI workflow must be added on the `ci` branch via `.github/workflows/ci.yml`.
