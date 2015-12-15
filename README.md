# static.dinosaur.is

my public [static](https://npmjs.org/ecstatic) file server

## setup

```
# dokku apps:create static
# sudo -u dokku mkdir -p ~dokku/.data/static
# dokku docker-options:add static deploy "-v /home/dokku/.data/static:/app/data"
# dokku docker-options:add static run "-v /home/dokku/.data/static:/app/data"
```

## copy files

```
$ npm run copy my-local-file.txt
```
