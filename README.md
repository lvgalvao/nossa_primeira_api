# Nossa primeira API

Instalando da maneira tradicional:

1) Usamos o Python 3.11.5

Utilize o Pyenv para instalar o Python 3.11.5 caso não tenha instalado.

```bash
$ pyenv install 3.11.5
```

Caso não tenha o Pyenv instalado, siga as instruções de instalação no link abaixo:

- [Pyenv Linux e Mac](https://github.com/pyenv/pyenv)
- [Pyenv Windows](https://github.com/pyenv/pyenv)

2) Crie um ambiente virtual

```bash
$ python -m venv .venv
```

3) Ative o ambiente virtual

```bash
$ source .venv/bin/activate
```

4) Instale as dependências

```bash
$ pip install -r requirements.txt
```

5) Execute o projeto

```bash
$ uvicorn main:app --reload
```

Instalando com Docker:

```
docker compose up --build
```