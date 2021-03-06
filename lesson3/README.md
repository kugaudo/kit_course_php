```*** Setting up Lesson3 ***

1. Clone or extract this repository and navigate to lesson3:
$ cd kit_course_php/lesson3

2. Start Docker container:
$ docker-compose up -d

3. Connect to Docker container:
$ docker-compose exec php /bin/bash;

4. Ensure you are at the application root:
$ cd /app

5. Build project:
$ composer install

6. Run phonebook.php:

- To add a phonebook record use:  
$ php phonebook.php save NAME PHONENUMBER 

- To find a phonebook record use:
$ php phonebook.php read NAME


*** Some useful notes ***

Single Responsibility Principle — each class should be responsible for some atomic functionality.

Decoupling is a process when some module is split into multiple submodules according to the Single Responsibility Principle.

Delegation Pattern is an approach when we add some responsibility for decision making to a given class, where afterward, another class is called.

Mapping.csv is used for storing a mapping of user-defined names to filename-safe strings.


```

