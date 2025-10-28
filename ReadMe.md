# from your project folder
# 0) Ensure venv is available (Debian/Ubuntu)
sudo apt-get update && sudo apt-get install -y python3-venv

# 1) Create a virtual environment *inside* the project
python3 -m venv .venv

# 2) Activate it (bash/zsh)
source .venv/bin/activate

# 3) Upgrade pip & install your requirements
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
