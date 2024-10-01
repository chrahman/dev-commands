# dev-commands

## Basic Git setup commands

```$ git config --global user.name "Your Name"```

```$ git config --global user.email "you@youraddress.com"```


## Before Deploy set remote origin
```$ git remote set-url origin https://<TOKEN>@github.com/<username>/<repository>.git```

## Git commands repo
```$ git init```

```$ git add .```

```$ git commit -m "Your Commit"```

```$ git push -u origin main```

## Git commands for ignore camel case
git config core.ignorecase false

## Git Clone
```$ git clone "URL"```

```$ git checkout "branch"```


## For Packeges
```Set-ExecutionPolicy Unrestricted```

## install postgress
Download from: https://postgresapp.com/downloads.html

Goto dumpfile location and run this command:

```psql -d postgres -f sqlfile.sql ```

If default port is ```5432``` & you dont know the password for ```5432``` then start on 5433 and try this command to restore dump:

``` psql -d postgres -f sqlfile.sql -p 5433 ```

