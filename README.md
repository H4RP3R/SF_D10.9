##  Запуск

```
git clone https://github.com/H4RP3R/SF_D10.9.git
cd SF_D10.9
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py loaddata cars.xml
python manage.py runserver
```
