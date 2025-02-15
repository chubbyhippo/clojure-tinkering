# weather


## Development

```shell
clj -M:fig:build
```

This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

```shell
(js/alert "Am I connected?")

```

and you should see an alert in the browser window.

To clean all compiled files:

```shell
rm -rf target/public
```

To create a production build run:

```shell
rm -rf target/public
clj -M:fig:min

```
