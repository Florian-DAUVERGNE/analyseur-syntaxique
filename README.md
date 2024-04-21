# Projet : Analyseur de Propositions Logiques

Ce projet est un analyseur de propositions logiques basé sur la syntaxe de logique sémantique. Il permet aux utilisateurs de saisir des formules logiques en utilisant des symboles logiques, puis de les convertir pour une évaluation.

## Installation

1. Assurez-vous d'avoir Python 3 installé sur votre système.

2. Clonez ce dépôt

    ```
    git clone git@github.com:Florian-DAUVERGNE/analyseur-syntaxique.git
    ```

 ou téléchargez les fichiers source.

![alt text]( https://bpb-us-e1.wpmucdn.com/sites.northwestern.edu/dist/b/3044/files/2021/05/github.png)


3. (Optionnel) Si vous préférez travailler dans un environnement virtuel, vous pouvez le créer en utilisant les étapes suivantes :
    ```
    python -m venv venv
    source venv/bin/activate  # Pour Linux/macOS
    .\venv\Scripts\activate   # Pour Windows
    ```

4. Installez les dépendances nécessaires en exécutant la commande suivante :
    ```
    pip install -r requirements.txt
    ```

## Utilisation

1. Exécutez le script principal en utilisant Python :
  ```
  python AnalyseurSyntaxique.py #Python
  python3 AnalyseurSyntaxique.py #Python3
  ```
2. Suivez les instructions à l'écran pour saisir votre formule logique.
3. Utilisez la commande `help` pour afficher un tableau de correspondance entre les mots-clés et les symboles logiques.

## Exemple de Formule

```
(P | Q) >> (~r = (Q & P))
```

## Structure du Projet

- `AnalyseurSyntaxique.py` : Le point d'entrée du programme. Gère l'interaction avec l'utilisateur et l'affichage des résultats.
- `Grammaire.py` : Contient le lexer et le parser PLY pour analyser les formules logiques.

## Bibliothèque
ply : https://github.com/dabeaz/ply

terminaltables : https://pypi.org/project/terminaltables/

## Lien vers l'ancien repertoire GitHub
https://github.com/Florian-DAUVERGNE/evaluateur_de_propositions
