# IA_project

## Version de Python
Veillez à avoir une version python <= 3.10.
Si ce n'est pas le cas, installez une version compatible.

🖥️ Windows : [Télécharger Python 3.10](https://www.python.org/downloads/release/python-3100/)

🍎 macOS :
```bash
brew install python@3.10
```

🐧 Linux :
```bash
sudo apt update
sudo apt install python3.10 python3.10-venv python3.10-dev
```

## Mis en place d'un environnement virtuel (si votre version Python > 3)
🖥️ Windows : 
```bash
py -3.10 -m venv .venv
.venv\Scripts\activate
```

🍎 macOS :
```bash
/opt/homebrew/opt/python@3.10/bin/python3 -m venv .venv
source .venv/bin/activate
```

🐧 Linux :
```bash
python3.10 -m venv .venv
source .venv/bin/activate
```

## Lancer l'installation des dépendances
Installez les dépendances via les commandes suivantes :
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## Télécharger les datasets (amélioration)
[Dataset de reconnaissance d'expressions faciales](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)