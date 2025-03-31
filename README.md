# 🐳 Docker Compose Collection
A simple collection of Docker Compose YAML files to quickly spin up commonly used services. 🚀

## ✨ About the Project
This project serves as a reference for setting up different development environments using Docker Compose. Currently, it includes:

* 📦 MongoDB + Express Website 🟢

* 🐘 PostgreSQL + pgAdmin 🟢

More configurations will be added in the future! ⚡

## 🚀 Getting Started

### 🔼 Stand Up the Containers

```
docker-compose -f <docker-compose-file.yml> up -d
```

Example:

```
docker-compose -f docker-compose-mongo-express.yml up -d
```

### 🔽 Shut Down the Containers

```
docker-compose -f <docker-compose-file.yml> down
```

Example:
```
docker-compose -f docker-compose-mongo-express.yml down
```

Feel free to explore, use, and contribute! 😊

