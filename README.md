# American Civil War Battle Data

This project contains various data on the American Civil War.
See the documentation at https://readthedocs.org/projects/acw-battle-data

## Build

In the root directory of the project run,
```shell
$ python build.py
```
This will build the data in the directory, ``data``.

To build html documenation
```shell
$ cd docs/ && make html
```
and pdf documentation
```shell
$ cd docs/ && make html
```


## Prerequesites

For python dependencies create and activate a [conda](http://conda.pydata.org/docs/using/envs.html#create-a-separate-environment) environment.

```shell
conda env create -f environment.yml
```

- R
    - **dplyr**
    - **jsonlite**
    - **magrittr**
    - **pander**
    - **stringr**
    - **tidyr**
    - **RSQLite**
    - **purrr**
    - **yaml**
- pdflatex


## Licenses

- Documentation and other text: [CC-BY](http://creativecommons.org/licenses/by/4.0/).
- Code: [BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause).
