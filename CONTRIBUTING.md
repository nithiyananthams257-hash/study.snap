# Contributing to Snap & Study

Thank you for your interest in contributing to Snap & Study!

## Development Setup

1. Fork and clone the repository.
2. Create and activate a Python 3.10+ virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt -r requirements-dev.txt
   ```
4. Copy `.env.example` to `.env` and configure your `GEMINI_API_KEY`.
5. Run the Streamlit app:
   ```bash
   streamlit run app/Home.py
   ```

## Pull Request Guidelines

- Ensure code passes `ruff check .` and `black --check .`.
- Add tests for new features in the `tests/` directory.
- Use Conventional Commits (e.g. `feat:`, `fix:`, `docs:`, `refactor:`).
