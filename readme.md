Fron:
- webpack
- react, установка  create-react-app
- react-router 
- взаимодействие с backend сервером django через axios  
Back:
- django
- django rest framework 
- swagger 
 

Для правильно работы необходимы пакеты:  
pip install djangorestframework  
pip install django-cors-headers  
pip install coreapi pyyaml  
pip install django-rest-swagger  


В терминале делаем cd вдиректорию проекта и запускаем:  
python manage.py runserver
Далее стартуем установку и запуск React+Webpack

При клонировании репозитория с Git небходимо восстановить модули:  
'npm install'  
Делаем запуск:
'npm start'  

Просмотреть API можно по:  
http://127.0.0.1:8000/api/openapi - schema openapi  
http://127.0.0.1:8000/api/swagger-ui/ - swagger-ui  
http://127.0.0.1:8000/api/categories/ - список всех категорий  
http://127.0.0.1:8000/api/dishes/?category=Салаты -  На примере запроса блюд из категории 'Салаты'  
http://127.0.0.1:8000/api/recipe/ - список всех рецептов
http://127.0.0.1:8000/api/recipe/id - id блюд