# devops-intern-assessment

## CI/CD with GitHub Actions
This repo contains a simple Python project with:
- `main.py`: sample app
- `tests/test_sample.py`: sample unit test
- `.github/workflows/ci.yml`: CI/CD pipeline

### Pipeline steps
1. Install dependencies (from `requirements.txt`)
2. Run tests (`pytest`) a simple addtion python code
3. Deploy step (mock → just echoes "Deploying...")
