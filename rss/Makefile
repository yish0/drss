PYTHON_VERSION = 3.12
PYTHON_DIR = python
PYTHON_BIN = $(PYTHON_DIR)/bin

uv:
	which uv || (curl -LsSf https://astral.sh/uv/install.sh | sh)

setup: $(UV)
	uv venv python --python=$(PYTHON_VERSION)

clean:
	rm -rf $(PYTHON_DIR)
