# Django [Volt Dashboard](https://appseed.us/generator/volt-dashboard/)

Open-source **Django Dashboard** generated by `AppSeed` on top of a modern design. **[Volt Dashboard](https://appseed.us/generator/volt-dashboard/)** is a free and open source `Bootstrap 5` Admin Dashboard featuring over 100 components, 11 example pages and 3 plugins with Vanilla JS. There are more than 100 free Bootstrap 5 components included some of them being buttons, alerts, modals, datepickers and so on.

- 👉 [Volt Dashboard Django](https://django-volt-dashboard.appseed-srv1.com/) - LIVE Demo
- 👉 [Volt Dashboard Django](https://appseed.us/product/volt-dashboard/django/) - Product page
- 👉 [Complete documentation](https://docs.appseed.us/products/django-dashboards/volt) - `Learn how to use and update the product`
  - ✅ [Set up the environment](https://docs.appseed.us/products/django-dashboards/volt#environment)
  - ✅ [Manage App users](https://docs.appseed.us/products/django-dashboards/volt#manage-app-users)
  - ✅ [Application Bootstrap Flow](https://docs.appseed.us/products/django-dashboards/volt#application-bootstrap-flow)
  - ✅ [App Routing](https://docs.appseed.us/products/django-dashboards/volt#project-routing)
  - ✅ [UI Assets and Templates](https://docs.appseed.us/products/django-dashboards/volt#ui-assets-and-templates)
  - ✅ [Set up the MySql Database](https://docs.appseed.us/products/django-dashboards/volt#set-up-the-mysql-database)
  - ✅ [Adding a new app](https://docs.appseed.us/products/django-dashboards/volt#adding-a-new-app)
  - ✅ [Static Assets for production](https://docs.appseed.us/products/django-dashboards/volt#static-assets-for-production)  
  
<br />

> Built with [Volt Dashboard Generator](https://appseed.us/generator/volt-dashboard/)

- Timestamp: `2022-06-14 01:04`
- Build ID: `e6135505-1c18-4bd5-93ed-81bca1835ed0`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Database: `sqlite`
- UI-Ready app, Django Native ORM
- `Session-Based authentication`, Forms validation

<br />

![Volt Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168843604-b026fd94-5969-4be7-81ac-5887cf0958e5.png)

<br />





## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/e6135505-1c18-4bd5-93ed-81bca1835ed0.git
$ cd e6135505-1c18-4bd5-93ed-81bca1835ed0
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

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />



## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Volt Pro is a premium Bootstrap 5 Admin Dashboard featuring over 800 components, 20 example pages and 10 fully customized plugin written in Vanilla Javascript. 

- 👉 [Django Volt PRO](https://appseed.us/product/volt-dashboard-pro/django/) - product page
- 👉 [Django Volt PRO](https://django-volt-pro.appseed-srv1.com/) - LIVE deployment

<br >

![Volt Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172672843-8c40a801-3438-4e9c-86db-38a34191fbdf.png)

<br />

---
Django [Volt Dashboard](https://appseed.us/generator/volt-dashboard/) - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
