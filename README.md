# [Argon Tailwind Django](https://appseed.us/product/argon-dashboard-tailwind-pro/django/) `PRO`

Premium **Django Dashboard** provided by `AppSeed` op top of a modern design. 
Designed for those who like bold elements and beautiful websites, **[Argon UI Dashboard](https://appseed.us/product/argon-dashboard-tailwind-pro/django/django/)** is ready to help you create stunning websites and webapps. **Argon UI Dashboard** is built with over 100+ frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining - Designed by [Creative-Tim](https://www.creative-tim.com/?AFFILIATE=128200).

- 👉 [Argon Tailwind Django PRO](https://appseed.us/product/argon-dashboard-tailwind-pro/django/) - `product page`
- 👉 [Argon Tailwind Django PRO](https://django-argon-tailwind-pro.onrender.com/) - `LIVE Demo`

<br />

> Features

- ✅ Design: [Argon Dashboard](https://www.creative-tim.com/product/argon-dashboard-pro-tailwind?AFFILIATE=128200) by `Creative-Tim`
- ✅ Styling: `Tailwind CSS`
- ✅ `Up-to-date dependencies`
- ✅ `Session-Based authentication`, Forms validation
- ✅ `Admin Section` Styled (reserved for superusers)
- ✅ `Docker`
- 🚀 `CI/CD` flow via `Render`


![Argon Tailwind Django - Premium Django Starter.](https://user-images.githubusercontent.com/51070104/228897490-b4b679c1-1342-41fd-badd-034e8b74570b.jpg)

<br /> 

## Start with `Docker`

> **Step 1** - Download the code from the official [product page](https://appseed.us/product/argon-dashboard-tailwind-pro/django/) (requires a purchase)

```bash
$ unzip django-argon-dashboard-tailwind-pro.zip
$ cd django-argon-dashboard-tailwind-pro
```

<br /> 

> **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## Manual Build

> **Step 1** - Download the code from the official [product page](https://appseed.us/product/argon-dashboard-tailwind-pro/django/) (requires a purchase)

```bash
$ unzip django-argon-dashboard-tailwind-pro.zip
$ cd django-argon-dashboard-tailwind-pro
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Create Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Create Superuser

```bash
$ python manage.py createsuperuser
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## Codebase Structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                            
   |    |-- settings.py                   # Project Configuration  
   |    |-- urls.py                       # Project Routing
   |
   |-- home/
   |    |-- views.py         # APP Views 
   |    |-- urls.py          # APP Routing
   |    |-- models.py        # APP Models 
   |    |-- tests.py         # Tests  
   |  
   |-- templates/
   |    |-- includes/        # HTML chunks and components   
   |
   |-- static/
   |    |-- CSS, JS, Images  # CSS files, Javascripts files   
   |
   |-- requirements.txt      # Project Dependencies
   |
   |-- env.sample            # ENV Configuration (default values)
   |-- manage.py             # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## Customize CSS

- Edit the `static/assets/scss/styles.css`
- Regenerate the CSS using `NPM` or `Yarn`

```bash
$ npm i            # Install modules
$ npm run build    # Recompile SCSS to CSS
$ npm run min-css  # Minify CSS
$ // OR 
$ yarn             # (via Yarn) Install modules
$ yarn build       # (via Yarn) Recompile SCSS to CSS
$ yarn min-css     # (via Yarn) Minify CSS
```

<br />

---
[Argon Tailwind Django](https://appseed.us/product/argon-dashboard-tailwind-pro/django/) `PRO` - Free starter provided by **[AppSeed](https://appseed.us/)**.
