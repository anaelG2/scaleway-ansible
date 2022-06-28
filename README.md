Playbook Ansible webservers
=========

Playbook Ansible permettant de déployer et d'installer un serveur web NGINX sur un hôte ansible. 


Rôles
------------

  - [nginx](roles/nginx)
  - [prerequisites](roles/prerequisites/)


Prérequis
--------------

Déclaration des variables d'environnement :
  - `export ANSIBLE_PRIVATE_KEY_FILE=<SSH_KEY>`
  - `export ANSIBLE_HOST_KEY_CHECKING=False`


Utilisation
--------------

1. Configurer vos serveurs cibles via le fichier inventaire

2. Personnaliser le playbook en modifiant les valeures des fichier vars/main.yml des différents rôles

3. Déployer le playbook à l'aide la commande suivante :

    `ansible-playbook -i <HOST_FILE> playbook.yml`





