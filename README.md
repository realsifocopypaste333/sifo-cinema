# sifocinema website

Hello

lets create very simple web cinema :)


1. clone the project

https://github.com/realsifocopypaste333/sifo-cinema

===============

2. create virt env 
 
we can use conda / mini conda

conda create --name sifocinema_env python=3.8 -y

conda activate sifocinema_env

=================================

3. navigate to the project folder

cd sifocinema


============================

4. install the modules

pip install -r  requirements.txt


if future error , please install future before it

pip install future

and try again

===================

5. create data base

python manage.py makemigrations

python manage.py migrate

python manage.py collectstatic

======================

6. create super user / admin

python manage.py createsuperuser

=========================

7. run the server

python manage.py createsuperuser

=======================

8. openwith the web browser (example = firefox, libre wolf, chromium, etc)

127.0.0.1:8000

and for editing the web open admin web

127.0.0.1:8000/admin


========================

this text license with / under creative common (cc) lincense

=========================================
