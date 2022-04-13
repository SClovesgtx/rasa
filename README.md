# Instalação

```
pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple --use-feature=2020-resolver

pip3 install -U "rasa[spacy]"
python3 -m spacy download pt_core_news_lg
```

# Comandos Rasa

Para iniciar com configurações padrões:

```rasa init --no-prompt```

Para treinar novo modelo:

```rasa train```

Para rodar o rasa-x:

```rasa x```
