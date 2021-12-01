# todo-dotnet6
This is todo app on .NET 6

- Demo Url: https://todo-dotnet6.herokuapp.com/swagger

# Heroku setup

- Add .NET 6

```bash
> heroku buildpacks:set https://github.com/jincod/dotnetcore-buildpack -a todo-dotnet6
> heroku buildpacks
```

- Add Postgres

```bash
> heroku addons:create heroku-postgresql:hobby-dev -a todo-dotnet6
```

- Tail logs

```bash
> heroku logs --tail -a todo-dotnet6
```