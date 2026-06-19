# STAD 2026 na disciplina de Modelos Lineares 

# Iniciando o ambiente

Baixe o ambiente pronto [aqui](https://github.com/Davidcms23/202601stad-lm/blob/main/environment.yml)

```bash
conda env create -f environment.yml
```

```bash
conda activate stad261
```

Ou para renomear o ambiente

```bash
conda env create -f environment.yml -n nome_ambiente
```


**Inicie o jupyter**

```bash
jupyter lab
```

## Criando um ambiente

```bash
conda create --name labest00 python=3.12
```

```bash
conda activate [nome_do_ambiente]
```

**Instale os pacotes**

```bash
conda install -c conda-forge pandas numpy scipy statsmodels jupyterlab
```
ou
```bash
conda install -c conda-forge --file requirements.txt
```

Por que usar o [conda-forge](https://conda-forge.org/docs/user/introduction/)?

## Alternativa

Usando o [micromamba](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html).

```bash
micromamba create --name stad261 python=3.12 uv -c conda-forge
```
```bash
micromamba activate stad261
```
```bash
uv pip install numpy pandas statsmodels scipy
```
```bash
uv pip install jupyterlab
```

### referência:
[Linear Models with Python, Julian J. Faraway](https://www.taylorfrancis.com/books/mono/10.1201/9781351053419/linear-models-python-julian-faraway)
