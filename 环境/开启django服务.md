    [root@bishe ~]# 
    [root@bishe ~]# conda env list
    [root@bishe ~]# source activate django-learning
    (django-learning) [root@bishe ~]# 
    (django-learning) [root@bishe ~]# 
    (django-learning) [root@bishe ~]# cd ~
    (django-learning) [root@bishe ~]# ls
    anaconda3                        mysql57-community-release-el7-11.noarch.rpm
    Anaconda3-5.1.0-Linux-x86_64.sh  mysql57-community-release-el7-11.noarch.rpm.1
    django-projects                  original-ks.cfg
    (django-learning) [root@bishe ~]# cd django-projects/
    (django-learning) [root@bishe django-projects]# ls
    HelloWorld
    (django-learning) [root@bishe django-projects]# cd HelloWorld/
    (django-learning) [root@bishe HelloWorld]# ls
    db.sqlite3  HelloWorld  manage.py
    (django-learning) [root@bishe HelloWorld]# python manage.py runserver 0.0.0.0:8000
    Performing system checks...

    System check identified no issues (0 silenced).

    You have 14 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
    Run 'python manage.py migrate' to apply them.

    March 15, 2018 - 11:24:01
    Django version 2.0.3, using settings 'HelloWorld.settings'
    Starting development server at http://0.0.0.0:8000/
    Quit the server with CONTROL-C.
    [15/Mar/2018 11:24:54] "GET / HTTP/1.1" 200 16348
    [15/Mar/2018 11:24:54] "GET /static/admin/css/fonts.css HTTP/1.1" 200 423
    [15/Mar/2018 11:24:55] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 200 81348
    [15/Mar/2018 11:24:55] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 200 80304
    [15/Mar/2018 11:24:55] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 200 82564
    Not Found: /favicon.ico
    [15/Mar/2018 11:24:56] "GET /favicon.ico HTTP/1.1" 404 1978
