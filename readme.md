#activate venv in git bash -
source ./venv/Scripts/activate

#activate venv in command prompt -
.\venv\Scripts\activate

#setup venv
python -m venv venv

#run this project
python -m uvicorn main:app --reload

#uvicorn setup
pip install uvicorn
pip install uvicorn[standard]

localhoad:port/docs for swager UI
