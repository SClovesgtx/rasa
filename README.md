# Instalação rasa

```
pip3 install -U pip
pip3 install rasa
pip3 install -U "rasa[spacy]"
python3 -m spacy download en_core_web_md
```

# INstalação Rasa X (espere muitos erros)

```pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple```

# Erro Failed building wheel for xmlsec

```sudo apt-get install libxml2-dev libxmlsec1-dev libxmlsec1-openssl```

# Comandos Rasa

Para iniciar com configurações padrões:

```rasa init --no-prompt```

Para treinar novo modelo:

```rasa train```

Para rodar o rasa-x:

```rasa x```
