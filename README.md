# photoprism-scroll-bug-reproducer

Generate images with bash:

```
for i in $(seq 1 500) ; do convert -size 100x100 -blur 0x100 plasma:fractal "rnd_$i.jpg" ; done
```

Test:

```
docker-compose up --detach
```
