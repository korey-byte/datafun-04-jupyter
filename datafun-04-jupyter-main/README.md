# datafun-04-jupyter
Create and Activate Project Virtual Environment

python3 -m venv .venv 
source .venv/bin/activate

Install Dependencies

pip3 -m pip install -r "requirements.txt"

Freeze Requirements

py -m pip freeze > requirements.txt

Git Add / Commit / Push

git add . 
git commit -m "initial commit" 

git push -u origin main