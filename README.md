
# Versão do Python

Para python3.6, usar rasa==0.1.1

# Instalação rasa

Para a versão do python3.6:

```
pip3 install rasa==0.1.1
pip3 install -U "rasa[spacy]"
python3 -m spacy download en_core_web_md
```

# Instalação Rasa X (espere muitos erros)

```pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple```

## Erro Failed building wheel for xmlsec

```sudo apt-get install libxml2-dev libxmlsec1-dev libxmlsec1-openssl```

## Instalação pip muito demorada: This is taking longer than usual.

Em um dos momentos que precisei instalar, tive que usar:

```pip install --use-deprecated=legacy-resolver --user rasa-x --extra-index-url https://pypi.rasa.com/simple```

Fazer downgrade do pip. Ler mais sobre [aqui](https://forum.rasa.com/t/pip-takes-long-time/39274/3).

Segue versão que deu certo:

```pip install --upgrade pip==20.2```

# Comandos Rasa

Para iniciar com configurações padrões:

```rasa init --no-prompt```

Para treinar novo modelo:

```rasa train```

Para rodar o rasa-x:

```rasa x```
