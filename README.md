# Ejecutar scripts en Linux

Existen dos formas de ejecutar los scripts:

- Ejecutarlo por sí solo con ./
- Ejecutarlo con un intérprete en concreto

## Ejecutar con un intérprete en concreto

Simplemente creamos un archivo .sh y lo ejecutamos con el comando:

```bash
sh archivo.sh
```

## Ejecutarlo por sí solo

Aquí primero tenemos que añadir en la primera línea del script, el intérprete con el que lo vamos a ejecutar (bash, python....). Por lo que el archivo tendría esta pinta:

```bash
#!/bin/bash
onedrive --synchronize
```

Ahora tendíamos que darle permisos de ejecución:

```bash
chmod a+x miscript.sh
```

Y ya podríamos ejecutarlo:

```bash
./miscript.sh
```

