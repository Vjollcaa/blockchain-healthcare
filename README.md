# Electronic Health Record (EHR) with blockchain

Basic dashboard app with Admin LTE template and Flask Admin has:

- User Registration
- Login as general or admin user
- Roles management
- Create form in modal window by default
- Inline editing enabled by default
- Skins and  layout customization
- Dashboard, charts, chat and calendar examples
 
Utilities: 

  - AdminLTE Bootstrap template
  - Flask-Security
  - Flask-Admin
  - A lot of Charts libraries
  - SQLite


### How to use

- Clone or download the git repository.
    ```sh
    $ git clone https://github.com/Vjollcaa/blockchain-healthcare.git
    ```
- Create and activate a virtual environment:
    ```sh
    $ virtualenv venv
    $ . . venv/bin/activate
    ```
- Install the requirements inside the app folder
    ```sh
    $ pip install -r requirements.txt
    ```
- Run the application

- On a different terminal session, start a blockchain node server
    ```sh
    $ set FLASK_APP=node_server.py
    $ flask run --port 8000
    ```
- The first execution will create automatically a sample sqlite database.
- Open your favorite browser and type
    ```
    localhost:5000/admin
    ```
    then just log in with the default user or register one. 

