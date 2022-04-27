# What can I do at covid line bot
* ask new case  with line bot.

* ask covid information with line bot.
# How to build covid line bot
* intall python 3.8
* make a python 3.8 ENV [how to make python ENV](https://cloud-plantain-504.notion.site/Python-1e231b44493b43e0b9596044d942470b)

    `virtualenv --python=3.8 Env38`
    
* git clone the project to Env38
    
    `cd Env38 `

    `git clone https://github.com/kid50901/LineBot_covid19info.git`
* run Env

    `Scripts\activate`
* install package

    `cd LineBot_covid19info`

    `pip install -r requirements.txt`
* get https url : you can use ngrok to change localhost or run server at heroku or bulid server by yourself.
* get LINE_CHANNEL_ACCESS_TOKEN and LINE_CHANNEL_SECRET from line Developers
* set up webhook URL at line Developers
* set up setting.py
    ```python
    ALLOWED_HOSTS = ['your host']
    ```
    ```python
    LINE_CHANNEL_ACCESS_TOKEN = 'your token'
    LINE_CHANNEL_SECRET = 'your chennel password'
    ```
* runserver
    ```
    python manage.py runserver
    ```
