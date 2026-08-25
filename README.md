## Google Drive Link

https://drive.google.com/drive/folders/13e_ZrLS8XVh_MnUU0Y-8Z9zXaLbOCaVG?usp=sharing

## IMP COMMANDS

python3 -m venv .venv

source .venv/bin/activate

python -c "import sqlite3,os; c=sqlite3.connect('expenseflow.db'); print(c.execute(\"SELECT sql FROM sqlite_master WHERE name='expenses'\").fetchone()[0])"
