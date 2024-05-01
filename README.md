## Configuração do Ambiente de Desenvolvimento 

Execute o comando no terminal  

```
git clone [URL do repositório]
```

Crie o ambiente virtual

```
python -m venv .venv
```

Ative o ambiente virtual
  Windows

```
.venv\Scripts\activate
```
  Linux/Mac

```
source venv/bin/activate
```


Baixe e instale a versão mais recente do Python no site oficial: [Python Downloads](https://www.python.org/downloads/)
	A versão utilizada no projeto: 3.12.0

Após instalar o Python, abra o terminal e instale o Django (A versão utilizada no projeto: 4.2)

```
pip install django
```

Instale as dependências

```
pip install -r requirements.txt
```

Execute o servidor localmente
```
python manage.py runserver
```

Crie um app
```
python manage.py startapp nome_do_app
```



