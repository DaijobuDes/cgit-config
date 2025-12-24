# cgit-config

My own configuration on setting up cgit + nginx

## Setting up

Assuming you have docker installed, run this command and it will build
the container and runs it after.

```sh
docker compose up -d
```

## Self-hosting your repositories

Inside `repositories` folder, clone your repositories with the `--bare` parameter. Example below

```sh
cd repositories
git clone git@github.com:DaijobuDes/cgit-config.git --bare
```
