# TaskBoard
A simple app to manage your tasks.

![Dashboard](/screenshots/dashboard.png)
![Sign up](/screenshots/sign-up.png)

## Installation

1- Clone the repository

```
git clone https://github.com/rohitiuc/taskboard
```

2- change the directory into taskboard folder

```
cd taskboard
```

3- install the dependencies by running Composer's install command

```
composer install
```

4- create an environment file

```
cp .env.example .env
```

5- edit `.env` file with appropriate credential for your database server - these parameter(`DB_USERNAME`, `DB_PASSWORD`).

6- create a database named `Agenda`

7- migrate your database

```
php artisan migrate
```

8- generate the application key.

```
php artisan key:generate
```

9- Run the server

```
php artisan serve
```

10- Now go to `http://localhost:8000` from your browser.

## Screenshots

![View Tasks](/screenshots/fullscreen-mode.png)

![Create Task](/screenshots/create-task.png)

![Create Note](/screenshots/create-note.png)

![Sign in](/screenshots/sign-in.png)

![Edit Profile](/screenshots/edit-profile.png)



## Ask a question?

If you have any question, contact me via my email:
> er.rohitiuc@gmail.com
