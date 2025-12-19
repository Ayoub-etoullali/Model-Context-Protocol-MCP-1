# Command Line Interface (CLI)

## Code
cd src
source .venv/bin/activate

### WSL
#### Update your package list and upgrade existing packages
sudo apt update && sudo apt upgrade -y
#### Install essential tools
sudo apt install -y git curl build-essential python3-pip python3-venv

### Inspector
uv run mcp dev mcp-server-example.py

### Run
uv run mcp-server-example.py

## Commit 
git add .
git commit -m "ava"
git push

