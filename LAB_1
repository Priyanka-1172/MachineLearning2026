from pathlib import Path

folders = [
    "data/raw",
    "data/processed",
    "notebooks",
    "src",
    "reports",
    "figures",
    "models"
]

for folder in folders:
    Path(folder).mkdir(parents=True, exist_ok=True)

Path("README.md").touch()
Path("requirements.txt").touch()
Path(".gitignore").touch()