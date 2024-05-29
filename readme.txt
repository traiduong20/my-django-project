RUN sudo apt install python3-venv

RUN python3 -m venv myvenv

RUN source myvenv/bin/activate

RUN (myvenv) ~$ python -m pip install --upgrade pip

CREATE file  requirements.txt

djangogirls
├── myvenv
│   └── ...
└───requirements.txt

djangogirls/requirements.txt
Django~=3.2.10

RUN (myvenv) ~$ pip install -r requirements.txt

// python -m pip install -U --force-reinstall pip

RUN pip install django

// Create a PythonAnywhere account
name: jacki2k 
mail: traiduong.24hdev@gmail.com
pass: Trai20061992

// Creating a PythonAnywhere API token

e86f78bcbfcd50ca83aba9c0c5064e31b441e826

RUN python manage.py migrate

RUN python manage.py runserver
