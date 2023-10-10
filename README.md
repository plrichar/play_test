# play_test
- name: crée un fichier
  hosts: all
  tasks:
  - name: crée le fichier toto
    mkdir /etc/toto
