## Pré-requisitos

Certifique-se de ter as seguintes instalações:

- [Python 3.x](https://www.python.org/downloads/) (testado na versão `3.11.2`)
  - [ChromeDriver](https://chromedriver.chromium.org/downloads) (Google Chrome)  
  - [Geckodriver](https://github.com/mozilla/geckodriver/releases/latest) (Firefox)  
---

## Ambiente Virtual

Comando para criar um ambiente virtual e isolar as dependências do projeto:

```bash
python -m venv nome_do_ambiente
```
---

## Pós ativação

```bash
pip install -r requirements.txt
```
---

## Executando os Testes

Para executar todos os testes estando na pasta raiz:

Copiar código
```bash
behave
```

Para executar um arquivo de teste específico na pasta raiz:


Copiar código
```bash
behave features\login.feature
```