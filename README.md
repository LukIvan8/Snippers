# Snippers
Code snippets and linux commands that I don't want to memorize or recreate


## Docker
Create local database with custom ports
```
sudo docker run --name pg --restart always -p 9876:5432 -e POSTGRES_PASSWORD=pass -e POSTGRES_USER=postgres -e POSTGRES_DB=oreo -d postgres:15.0-alpine
```
