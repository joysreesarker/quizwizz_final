1. Change the working directory

```bash
cd web_quiz
```

2. Install virtual environment (command prompt)

```bash
pip install virtualenv
```

3. Create virtual environment - "venv"

```bash
virtualenv venv
```

4. Activate virtual environment

```bash
cd venv
cd Scripts
activate
```

5. Back to root

```bash
cd ..
cd ..
```

6. Install requirements

```bash
pip install -r requirements.txt
```

7. Database migration

```bash
python manage.py migrate
```

8. Create super user

```bash
python manage.py createsuperuser
```

> Fillup user details:
>
> - userName
>
> - email
>
> - password (hidden field)

9. Run the server in localhost

```bash
python manage.py runserver
```
We can find our website in [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

10. To run this website in local network find the device IP (YOUR IP:PORT)

```bash
python manage.py runserver 192.168.0.1:8000
```
