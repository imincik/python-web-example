# Simple web app with database backend

* Initialize database
```
  curl -X POST localhost:5000/init
```

* Add new user
```
  curl -X POST --header "Content-Type: application/json" --data '{"name":"username"}' localhost:5000/users
```

* Get list of users
```
  curl localhost:5000/users
```
