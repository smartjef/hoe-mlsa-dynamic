# Portfolio
This project was created for the purpose of learning how to use bootsrap and how to create a website using it. This project is a simple website that is responsive and has a navbar, a jumbotron, a form, and a footer. This project was created using bootstrap and html.

The static version of this website can be found at https://smartjef.github.io/hoe-mlsa/

We then went on to create a dynamic version of this website using django. The dynamic version of this website can be found at https://sjef.azurewebsites.net/

## Setting up the project
To set up the project, you will need to have python installed on your computer. You can download python from https://www.python.org/downloads/
1. Clone the repository by typing in the following command in your terminal:
```bash
git clone https://github.com/smartjef/hoe-mlsa-dynamic.git
```
2. Change directory into the project folder by typing in the following command in your terminal:
```bash
cd hoe-mlsa-dynamic/
```
3. Assuming you have python,pip and virtualenv installed ,you will have to create a virtual environment. To do this, open your terminal and type in the following command:
```bash
virtualenv venv
``` 
or
```bash
python -m venv venv
```
or
```bash
python3 -m venv venv
```
4. Once you have created the virtual environment, you will have to activate it. To do this, type in the following command:
For Linux and Mac:
```bash
source venv/bin/activate
```
For Windows:
```bash
venv\Scripts\activate
```
5. Once you have activated the virtual environment, you will have to install the requirements. To do this, type in the following command:
```bash
pip install -r requirements.txt
```
6. Once you have installed the requirements, you will have to make migrations. To do this, type in the following command:
```bash
python manage.py makemigrations
```
7. Once you have made migrations, you will have to migrate. To do this, type in the following command:
```bash
python manage.py migrate
```
8. Once you have migrated, you will have to create a superuser. To do this, type in the following command and fill in the details:
```bash
python manage.py createsuperuser
```
9. Once you have created a superuser, you may run the server. To do this, type in the following command:
```bash
python manage.py runserver
```
- If you want to run the server on a different port, you can do so by typing in the following command:
```bash
python manage.py runserver <port number>
``` 
e.g
```bash
python manage.py runserver 7000
```
- If you want to run the server on a different ip address, you can do so by typing in the following command:
```bash
python manage.py runserver <ip address>:<port number>
```
e.g
```bash
python manage.py runserver 192.168.100.1:8000
```
To confirm, you'll see a similar output to the following:
```bash
System check identified no issues (0 silenced).
February 22, 2023 - 07:40:18
Django version 4.1.7, using settings 'portfolio.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

10. You can now login to the admin panel by going to http://127.0.0.1:8000/mlsa/ and logging in with the superuser credentials you created earlier.

## Sample Images


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ndlgg4pzazcdd6qg1uu9.png)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gl5d7myohinjg3zc0ev2.png)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/apu5gju09ugljz5a3ul2.png)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/psduw4byjxoobbmj53wo.png)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/g65h5y0n5s51eygiw4wm.png)

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9c39x4p6nmw9s94qshq9.png)

Reach out in the comments if you have any questions or suggestions. Thanks for reading.