# UTM-CFlex2024A Práctica 1.1

<!-- badges: start -->

<!-- badges: end -->

Práctica 1.1 Perceptrón.

## Requiremientos

- [Anaconda](https://www.anaconda.com/download/) >= 4.x
- [git](https://git-scm.com/) >= 2.x
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0:
    Esto puede ser instalado con `pip` o `conda` dependiendo cómo tú manejas tus paquetes de Python:

``` bash
pip install cookiecutter
```
o

conda install -c conda-forge cookiecutter

Crear un nuevo proyecto

En el directorio en el que quieras guardar tu proyecto generado:


cookiecutter https://github.com/christiane-millan/test-plantilla-cflex


Estructura de directorios y archivos resultantes

````
{{ cookiecutter.project_slug }}
    ├── data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-cmillanh-initial-data-exploration`.
    │
    ├── .gitignore         <- Files to ignore by `git`.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    └── README.md          <- The top-level README for developers using this project.
````