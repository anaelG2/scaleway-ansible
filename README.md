Playbook Ansible webservers
=========

Playbook Ansible permettant de déployer et d'installer un serveur web NGINX sur un hôte ansible.


Rôles
------------

  - [nginx](roles/nginx)
  - [prerequisites](roles/prerequisites/)



Utilisation
--------------

1. Configurer vos serveurs cibles via le fichier inventory.yml

2. Personnaliser le playbook en modifiant les valeures des fichier vars/main.yml des différents rôles

3. Déployer le playbook à l'aide la commande suivante :

    `ansible-playbook -i <HOST_FILE> playbook.yml`

Role Name
=========
export ANSIBLE_PRIVATE_KEY_FILE=/home/anaelg/.ssh/id_rsa_projetannuel
export ANSIBLE_HOST_KEY_CHECKING=False
export SCW_TOKEN=87be850e-92a0-40ad-95e3-83e46b40fc03


