# Comandos básicos para Conda  
* [x] Configuración de un ambiente virtual
* [x] Otros

----
# Configuración de un ambiente virtual

1. Crear un ambiente virtual
```bash
conda create --name myenv
```
1.1  Crear un ambiente a partir de un archivo

```bash
conda env create --file environment.yml
```
2. Instalar paquetes
```bash
conda install numpy
```
----

# Otros

* Ver la lista de ambientes 
```bash
conda list env
```
* Cambiar la versión de Python
```bash
conda install python=3.5.0
```

* Ver versión de python 
```bash
python -V 
```
* Actualizar a la última versión de python
```bash
conda update python
```




 
