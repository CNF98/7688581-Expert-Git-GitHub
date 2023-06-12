# Open Transport

Application web pour covoiturage. 

## Getting Started

Ces instructions permettent d'executer une copie du projet en local sur votre poste de travail pour le développement et les tests. Référez-vous à la section "Déploiement" pour les étapes à suivre pour déployer le projet en production.

### Pré-requis

Pour executer en local le projet Open Transport, vous devez au préalable installer :

```
A définir
Pour exécuter le projet Open Transport en local, vous devez effectuer les étapes suivantes :

1. Installer Python : Assurez-vous d'avoir Python installé sur votre système. Vous pouvez télécharger la dernière version de Python depuis le site officiel de Python (https://www.python.org) et suivre les instructions d'installation pour votre système d'exploitation.

2. Cloner le projet : Utilisez Git pour cloner le dépôt du projet Open Transport sur votre machine locale. Vous pouvez utiliser la commande suivante dans votre terminal :

   ```
   git clone https://github.com/nom_du_depot/Open-Transport.git
   ```

3. Installer les dépendances : Accédez au répertoire du projet cloné et installez les dépendances requises en utilisant l'outil de gestion de paquets pip. Exécutez la commande suivante dans votre terminal :

   ```
   cd Open-Transport
   pip install -r requirements.txt
   ```

   Cette commande installera toutes les dépendances spécifiées dans le fichier `requirements.txt` du projet.

4. Configurer la base de données : Le projet Open Transport peut nécessiter une base de données pour fonctionner correctement. Assurez-vous d'avoir une instance de base de données compatible (par exemple, PostgreSQL, MySQL) installée sur votre machine. Créez une base de données vide pour le projet et configurez les informations de connexion dans les fichiers de configuration appropriés du projet.

5. Lancer l'application : Une fois que toutes les dépendances sont installées et que la base de données est configurée, vous pouvez lancer l'application. Exécutez la commande suivante dans votre terminal :

   ```
   python manage.py runserver
   ```

   Cela démarrera un serveur de développement local, et vous pourrez accéder à l'application en ouvrant votre navigateur et en visitant l'URL `http://localhost:8000`.

Veuillez noter que les étapes spécifiques peuvent varier en fonction du projet Open Transport que vous souhaitez exécuter. Assurez-vous de consulter la documentation du projet pour obtenir des instructions détaillées et vérifier les exigences spécifiques avant de procéder à l'installation.

```

### Installation

Voici les étapes à suivre pour avoir un environnement de développement et de test opérationnel :


```
A définir

Pour avoir un environnement de développement et de test opérationnel, vous pouvez suivre les étapes suivantes :

1. Installer un éditeur de code : Choisissez un éditeur de code adapté à vos besoins. Certains éditeurs populaires sont Visual Studio Code, Sublime Text, Atom, ou PyCharm. Téléchargez et installez l'éditeur de code de votre choix à partir de son site officiel.

2. Installer Python : Assurez-vous d'avoir Python installé sur votre système. Téléchargez la dernière version stable de Python depuis le site officiel de Python (https://www.python.org) et suivez les instructions d'installation pour votre système d'exploitation.

3. Configurer un environnement virtuel : Il est recommandé d'utiliser un environnement virtuel pour isoler les dépendances de votre projet. Créez un nouvel environnement virtuel en utilisant l'outil venv intégré à Python. Ouvrez un terminal et exécutez les commandes suivantes :

   - Sur Windows :

     ```
     python -m venv mon_environnement
     mon_environnement\Scripts\activate
     ```

   - Sur macOS/Linux :

     ```
     python3 -m venv mon_environnement
     source mon_environnement/bin/activate
     ```

4. Cloner le projet : Utilisez Git pour cloner le dépôt du projet sur votre machine locale. Accédez au répertoire où vous souhaitez stocker le projet, puis exécutez la commande suivante dans votre terminal :

   ```
   git clone https://github.com/nom_du_depot/mon_projet.git
   ```

5. Installer les dépendances : Accédez au répertoire du projet cloné et installez les dépendances requises en utilisant l'outil de gestion de paquets pip. Exécutez la commande suivante dans votre terminal :

   ```
   cd mon_projet
   pip install -r requirements.txt
   ```

   Assurez-vous d'avoir un fichier `requirements.txt` qui répertorie toutes les dépendances nécessaires au projet.

6. Configurer les fichiers de configuration : Vérifiez si votre projet nécessite des fichiers de configuration spécifiques, tels que des fichiers d'environnement (`.env`) ou des fichiers de configuration de base de données. Assurez-vous de configurer correctement ces fichiers en fonction de vos besoins.

7. Effectuer les migrations de base de données : Si votre projet utilise une base de données, exécutez les migrations pour créer les tables nécessaires. Utilisez la commande suivante dans votre terminal :

   ```
   python manage.py migrate
   ```

8. Lancer l'application en mode de développement : Pour exécuter l'application en mode de développement, utilisez la commande suivante dans votre terminal :

   ```
   python manage.py runserver
   ```

   Cela lancera un serveur de développement local, et vous pourrez accéder à votre application dans votre navigateur en visitant l'URL `http://localhost:8000`.

Ces étapes vous permettront de mettre en place un environnement de développement et de test opérationnel pour votre projet. N'oubliez pas de consulter la documentation spécifique de votre projet pour des instructions détaillées et pour vérifier si des étapes supplémentaires sont nécessaires en fonction de ses exigences.
```

## Executer les tests

```
A définir : expliquer comment executer les tests
```


## Deployment

Voici les étapes à suivre pour déployer en production :

```
A définir
```

## Technologies :

* HTML5/CSS3
* [Boostrap](https://getbootstrap.com/)

## Contribution

Merci de lire les fichiers :
* [CONTRIBUTING.md](https://github.com/OpenClassrooms-Student-Center/7688581-Expert-Git-GitHub/blob/main/CONTRIBUTING.md)
* [CODE_OF_CONDUCT.md](https://github.com/OpenClassrooms-Student-Center/7688581-Expert-Git-GitHub/blob/main/CONTRIBUTING.md) 

## Auteurs

* **Non spécifié**

## License

Ce projet est sous la licence GNU GPL V3 - voir le fichier [LICENSE](LICENSE) pour plus de détails
