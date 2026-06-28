Windows Setup Commands

1\. Download the project from GitHub.

cd C:\\

mkdir shuang

cd C:\\shuang

mkdir ML

cd ML

git clone https://github.com/JorgenMus/handson-ml3.git

cd handson-ml3

2\. Fix PowerShell script policy when venv activation is blocked.

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

3\. Create the virtual environment inside the project folder.

py -m venv .venv

4\. Activate the virtual environment before working.

.\\.venv\\Scripts\\Activate.ps1

5\. Check that Python is running from .venv.

python --version

python -c "import sys; print(sys.executable)"

6\. Upgrade pip after creating the environment.

python -m pip install --upgrade pip setuptools wheel

