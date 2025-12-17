# Contributing to tedx-flow

Thank you for your interest in contributing to tedx-flow!

## Development Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tedx-flow.git
cd tedx-flow
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install development dependencies:
```bash
pip install -e ".[dev]"
```

## Running Tests

```bash
pytest tests/ -v
```

With coverage:
```bash
pytest tests/ -v --cov=tedx_flow --cov-report=html
```

## Code Style

We use:
- `black` for code formatting
- `isort` for import sorting
- `mypy` for type checking

Run all checks:
```bash
black .
isort .
mypy tedx_flow/
```

## Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run tests and linting
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Commit Messages

Follow conventional commits:
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `test:` Test changes
- `refactor:` Code refactoring
- `chore:` Maintenance tasks

## Reporting Issues

When reporting issues, please include:
- Python version
- Operating system
- Minimal reproducible example
- Expected vs actual behavior
