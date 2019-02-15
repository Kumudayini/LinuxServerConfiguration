**Configuration Summary**
1. Added **Grader** as the new User
2. Added **Catalog** as the new and gave the permission to create a new Database
3. Changed the **SSH** port from 22 to **2200** - allowed incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
4. **Cloned** the ItemCatalog project from GitHub
5. Renamed **application.py** file as **__init__.py**
6. Created a new database with the code in __init__.py file as -
engine = create_engine('postgresql://catalog:PASSWORD@localhost/catalog')
7. Added catalog.conf file to configure virtual host
8. Added catalog.wsgi to setup the Flask application
