```
clj -M --main cljs.main --compile hello-world.core --repl
```
```
clj -M --main cljs.main --repl-opts "{:launch-browser false}" --compile hello-world.core --repl
```   
```   
(require '[hello-world.core :as hello] :reload)
```   
```   
(hello/average 20 13)
```   
```   
clj -M -m cljs.main --help
```   
```   
clj -M -m cljs.main --optimizations advanced -c hello-world.core
```   
```   
clj -M -m cljs.main --serve
```   
