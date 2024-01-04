install-os-tools:
	@echo "installing dvc, pipenv, cookiecutter, pre-commit"
	pip install dvc pipenv cookiecutter pre-commit

documentation:
	@echo "Save documentation to docs..."
	pdoc src -o docs --force
	@echo "View API documentation..."
	pdoc src --http localhost:8080

requirements:
	@echo "Installing dependencies"
	pipenv install
