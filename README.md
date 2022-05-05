# 2048 Container

Wir erstellen einen 2048 Container.

[https://github.com/tiehuis/2048-cli](https://github.com/tiehuis/2048-cli)

** Unter examples findet ihr mögliche Lösungsvorschläge, versucht die Aufgabe zuerst ohne diese zu lösen. **


## Build

```bash
docker build --rm -t [kürzel]-2048-image:latest .
```

## Run

```bash
docker run -ti --name [kürzel]-2048-container [kürzel]-2048-image:latest
```
