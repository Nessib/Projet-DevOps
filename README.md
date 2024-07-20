Mise en place d'une solution de
supervision re seau base e sur DevOps

1. Pré-requis
 Administration système et réseau sous Linux
 Virtualisation : VMWare , VirtualBox

2. Objectifs
 Conception d'une architecture de supervision basée sur les containers
 Mise en place d'une architecture de supervision basée sur les containers
 Mise en place de la solution avec Jenkins

3. Conception de l'architecture
Une entreprise veut mettre en place une architecture de supervision basée sur un container Nagios
pour superviser :
Une base de donnée
Un serveur Web
Un serveur FTP
Un cluster Hadoop

4. Mise en place de l'architecture
L'entreprise décide de mettre en place l'architecture à base de containers en utilisant Docker
et Jenkins.

5. Travail demandé
 Partie 1 : Conception
Proposer une conception de l'architecture à mettre en place en spécifiant les zones et les
serveurs à déployer pour chaque zone.
Préciser à chaque fois votre choix technologique pour les services à déployer.
 Partie 2 : Virtualisation
Déployer tous les services sous forme de containers et tester le bon fonctionnement des
services.
 Partie 3 : Réseau
Tester l'accessibilité entre les serveurs et Nagios : tous les serveurs doivent se connecter à
Nagios.

Automatisation et Orchestration dans le cloud

2

 Partie 4 : Supervision
Configurer Nagios pour superviser les différents services déployés.
 Partie 5 : Sécurité
Configurer le serveur Web en lui ajoutant le module SSL pour sécuriser les accès.
 Partie 6 : Qualité de service
Mettre en place la solution heartbeat au niveau du serveur Web pour garantir sa haute
disponibilité.
