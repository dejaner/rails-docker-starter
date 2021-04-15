1.
```
docker-compose run --no-deps web rails new . --force --database=postgresql
```

2. (maybe)
```
docker-compose build
```

3.
```
docker-compose up
docker-compose run web rake db:create
```
