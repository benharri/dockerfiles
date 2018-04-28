# mosh container

easy way to run mosh on windows without the chrome app :)

inspired by [cdrage/mosh](https://github.com/cdrage/dockerfiles/tree/master/mosh), just swapped out ubuntu for alpine base.

if you want to use your own key, mount it to /root/.ssh/

usage:

```
docker run -it --rm \
  -e TERM=xterm-256color \
  -v $HOME/.ssh:/root/.ssh \
  benharri/mosh user@server.tld
```

