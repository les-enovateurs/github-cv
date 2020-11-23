# Création de votre portfolio gratuit avec GitHub Page / Api
* Forkez le projet https://github.com/github/personal-website
* Rendez-vous dans le projet cloné.
* Activez GitHub Pages dans les paramétres
* Renommez le projet en <votre pseudo>.github.io
* Faites un Git clone pour télécharger le projet sur votre PC
```bash
git clone https://github.com/<nom_utilisateur>/<nom utilisateur>.github.io
```

* Accédez au dossier du projet
```bash
cd <nom utilisateur>.github.io
```

* Installation de Jekyll & Bundler
```bash
gem install jekyll bundler
```

* Installation des gems/librairies utiles pour le projet
```bash
bundle install
```

* Si environnement Windows
```bash
gem install wdm
```

* Lancement du serveur Jekyll
```bash
bundle exec jekyll serve
```

## Mettre en production les modifications
  * Préparer l'envoi du code avec un message
  ```bash
git commit -am "<message>"
  ```
  * Envoyer le code en production
  ```bash
git push  
  ```
