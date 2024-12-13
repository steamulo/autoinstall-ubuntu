# Ubuntu Autoinstall Configuration

Ce projet fournit une configuration automatisée pour l'installation d'Ubuntu, spécialement conçue pour les développeurs. Il configure automatiquement un environnement de développement complet avec les meilleurs outils et configurations.

## 🚀 Fonctionnalités

- Configuration système optimisée pour le développement
- Suite complète d'outils de développement
- Configuration shell ZSH personnalisée avec Powerlevel10k
- Environnements de développement multiples (Python, Java, Node.js)
- IDEs professionnels préconfigurés
- Optimisations système pour de meilleures performances

## 📋 Prérequis

- Une clé USB bootable avec Ubuntu Server
- Connexion Internet active pendant l'installation
- Minimum 20 Go d'espace disque
- 4 Go de RAM minimum (8 Go recommandés)

## 🛠 Composants Installés

### Outils Système
- Git, Curl, Wget
- Vim, Neovim
- Terminator
- Htop, Btop, Iotop
- Tmux
- Tree, Ripgrep, fd-find, jq
- Net-tools, Nmap, Traceroute

### Environnement de Développement
- Python (via pyenv)
  - Python 3.8.18
  - Python 3.10.13
  - Python 3.12.1
- Java (JDK & JRE)
- Node.js (via nvm)
- Docker & Docker Compose

### IDEs (via Snap)
- Visual Studio Code
- PhpStorm
- PyCharm Professional
- IntelliJ IDEA Ultimate
- GoLand

### Outils de Développement
- Postman
- Docker
- kubectl
- DBeaver CE

### Configuration Shell
- ZSH avec Oh-My-Zsh
- Thème Powerlevel10k
- Plugins ZSH utiles
  - git
  - docker
  - docker-compose
  - kubectl
  - pyenv
  - npm
  - zsh-autosuggestions
  - zsh-syntax-highlighting

### Optimisations Système
- Configuration swap optimisée
- Paramètres sysctl pour de meilleures performances
- Services TLP pour l'optimisation de la batterie
- Preload pour le chargement rapide des applications

## 🚀 Installation

1. Créez une clé USB bootable avec Ubuntu Server
2. Copiez le fichier `autoinstall.yml` à la racine de la clé USB
3. Démarrez sur la clé USB
4. Suivez le processus d'installation automatique

## ⚙️ Post-Installation

Après l'installation, votre système sera configuré avec :

- Un utilisateur `steamulo` avec les droits sudo
- Docker configuré pour une utilisation sans sudo
- Python 3.10.13 comme version par défaut
- ZSH comme shell par défaut avec une configuration optimisée

## 🔧 Personnalisation

Le fichier `autoinstall.yml` peut être modifié pour :

- Ajouter/supprimer des paquets
- Modifier les versions de Python
- Ajouter des configurations système supplémentaires
- Personnaliser les alias et la configuration ZSH

## 🔒 Sécurité

- Mot de passe par défaut : "Steamulo!"
- Il est recommandé de changer le mot de passe après la première connexion
- Les clés SSH peuvent être ajoutées post-installation

## 📝 Notes

- L'installation complète peut prendre 30-45 minutes selon votre connexion Internet
- Certains composants (comme les IDEs) nécessitent une connexion Internet pour l'activation
- La configuration est optimisée pour Ubuntu Server mais peut être adaptée pour d'autres versions

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## 📜 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
