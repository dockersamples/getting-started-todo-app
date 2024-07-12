## A Basic Todo List App

This is a starting point for todo-list app powered with React, Node and Mongo.

## Tech Stack

![image](https://github.com/user-attachments/assets/5b75919c-f250-4c5a-b146-5754de888355)


- Frontend: React
- Backend: Node.js
- Database: Mongo DB
- Database Admin Interface: MongoExpress


## Clone the repository

```
git clone https://github.com/dockersamples/getting-started-todo-app
cd getting-started-todo-app
```

## Switch to `basic` branch


```
git checkout basic
```

## Bringing up the service containers

```
docker compose up -d
```

After the application starts, navigate to `http://localhost:3000` in your web browser.


Stop and remove the containers
```
$ docker compose down
Stopping server   ... done
Stopping frontend ... done
Stopping mongo    ... done
Removing server   ... done
Removing frontend ... done
Removing mongo    ... done
