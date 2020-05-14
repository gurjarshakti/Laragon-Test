<div>

with 
<p align="center"><img src="https://laravel.com/img/logotype.min.svg" width="100"></p>
</div>


## Setting up Laragon with a Laravel App Project


If you are currently working with Laravel on windows, you will quickly realize that using development environments such as wamp or xampp can really be a real headache.
Laragon is a solution created specifically for modern development with php, includes in its installation several technologies such as, git, node, yarn, apache, nginx, ngrok, heydiSQL and composer also installers for Wordpress, drupal, symfony, and programs such as winscp, putty , notepad ++ and of course two laravel installers for zip installer and composer command installer.
All this technologies in one installer you only need to access to the official site: https://laragon.org/download/

Laragon Full Edition is the best option to install your setup, you only need to click on download link and it will open source forge page,
you must wait 5 seconds until it is downloaded automatically, once downloaded the installer is installed like any application in windows, just click and next, next, next until the process is finished.
Now you can open the laragon app, to apply all technologies you will need to add Laragon to environment path, dont worry this is a breeze with laragon, you only need to click on menu link or right click on cog icon, then “Tools/ Path variables/Add laragon to path”.

<p align="center"><img src="https://miro.medium.com/max/1050/1*zhFKQ1_I3zgfHsfO2S-GfA.png" width=""></p> 

We will end up creating a project in laravel and setting the database.
- click on “turn on button”
- click on menu link
- select quick app/laravel
- add a name for your project and click “ok” button

<img src="https://miro.medium.com/max/1050/1*s9MkL0gsyJ7pEx_97O1zSQ.png">

Now we are going to set the Database, when you use the quick app menu option, laragon makes the database with the same name as your app for you, you only need to set your credentials for database in your laravel app.

The default values for databases is:
DB_NAME=yourappname
DB_USERNAME=root
DB_PASSWORD=
laragon set database without password so, leave DB_PASSWORD key empty, now to open the app you dont need to make a “php artisan serve” command, you only need to open the laragon window and in menu select “www” option and click on your project, and thats it:

