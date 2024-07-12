## A Basic Todo List App

This is a starting point for todo-list app powered with React, Node and Mongo.

## Tech Stack

- Frontend: Ract
- Backend: NodeJS
- Database: Mongo
- Database Admin Interface: Mongo Express


## Deploy with docker compose

Clone the repo, switch to basic branch and run the following command:

```
$ docker compose up -d
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
