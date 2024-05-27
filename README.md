# Warning

### Do not push or commit on this branch, unless it is absolutely necessary.
### If an API/submodule must be modified, do so on its own github repository.

# How to update the submodules

### If it is the first time you check out this repo
```shell
git submodule update --init --recursive
```

### Otherwise
```shell
git submodule update --recursive --remote
```

# Dockerize the services along with the database

Execute the following command:
```shell
docker compose up --build -d
```