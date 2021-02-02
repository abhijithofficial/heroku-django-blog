
## About DjangoBlog

This Repo presents a detailed description of the Blog "Content Managmet" System, 
. The purpose of the website is to managmet your blogs and list another users blog also.

Happy Managmnet


## Installation 
Clone 
```
git clone https://github.com/HalaAlmomanii/DjangoBlog.git
```
create python 3 virtual enviroment
``` 
virtualenv -p python3 env
```
install Blog requirments
```
pip install -r requirmenrs.txt
```
activate enviroment 
```
sourc env/bin/activate
```
DataBase
```
 python manage.py makemigrations
 python manage.py migrate
```
create admin
```
python manage.py createsuperuser
```
running Django
```
 python manage.py runserver
```

## URL

Admin URL: ``` localhost:8000/admin```
Django URL : ``` localhost:8000/```
