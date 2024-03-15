# PYTHON NO WINDOWS

## INSTALAÇÃO

BASTA DIGITAR `python` NO TERMINAL E SEGUIR A INSTALAÇÃO PELA _MICROSOFT STORE_ (O GERENCIADOR DE PACOTES pip SERÁ INSTALADO JUNTO COM O PYTHON).  

## CONFIGURANÇÃO DE UM AMBIENTE VIRTUAL

```bash
python -m venv .venv ## CREATE
.venv/Scripts/activate ## ACTIVATE
```

## INSTALAÇÃO DE PACOTES

```bash
pip install matplotlib
pip install pandas
python -m pip install pandas-stubs # TYPES FOR pandas
pip install seaborn
pip install types-seaborn # TYPES FOR seaborn
pip install plotly
pip install -U kaleido # EXPORT plotly CHARTS
pip install tabulate # REQUIRED TO CONVERT DATAFRAMES TO MARKDOWN TABLES
pip install stemgraphic # STEM AND LEAF PLOTS
```

## EXTENSÕES PARA VSCODE

* [MYPY TYPE CHECKER](https://marketplace.visualstudio.com/items?itemName=ms-python.mypy-type-checker)

## GERENCIAR REQUISITOS (VERSÕES EXATAS DE PACOTES)

* BACKUP:

  ```bash
  pip freeze > requirements.txt
  ```

* RESTAURAÇÃO:

  ```bash
  pip install -r requirements.txt
  ```

## LISTAR PACOTES INSTALADOS

```bash
pip list
```
