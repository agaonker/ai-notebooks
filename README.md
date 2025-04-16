# AI Notebooks (2025 Edition)

A collection of modern Jupyter notebooks exploring various aspects of AI, machine learning, and large language models.

## 🚀 Features

- Interactive notebooks for AI experimentation
- Modern LLM prompt engineering techniques
- Data visualization and analysis tools
- Hands-on examples with real-world applications
- Modern Python packaging with `pyproject.toml`
- Fast dependency management with `uv`

## 📋 Prerequisites

- Python 3.9+
- [uv](https://github.com/astral-sh/uv) - The fast Python package installer
- Jupyter Lab/Notebook

## 🛠️ Installation

1. Install `uv` (if not already installed):
```bash
# Using pip
pip install uv

# Or using curl
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Clone the repository:
```bash
git clone https://github.com/agaonker/ai-notebooks.git
cd ai-notebooks
```

3. Create and activate a virtual environment:
```bash
# Create virtual environment
uv venv

# Activate the environment
# On Unix/macOS:
source .venv/bin/activate
# On Windows:
.venv\Scripts\activate
```

4. Install dependencies:
```bash
uv pip install -e .
```

## 📚 Notebooks

- `open-ai-prompts.ipynb`: Advanced prompt engineering techniques and examples
- `plots-graphs-sigmoid.ipynb`: Data visualization and mathematical functions

## 🧪 Development

This project uses modern Python packaging with `pyproject.toml`. Key features:

- Dependency management with `uv`
- Code formatting with `ruff`
- Type checking support
- Modern build system with `hatchling`

To contribute:

1. Install development dependencies:
```bash
uv pip install -e ".[dev]"
```

2. Run linting:
```bash
ruff check .
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for their groundbreaking work in AI
- The Jupyter community for their excellent tools
- All contributors to this project
- The `uv` team for their fast Python package installer
