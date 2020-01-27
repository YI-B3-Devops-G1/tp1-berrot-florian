<<<<<<< HEAD
# tp1-berrot-florian
=======
# B3 Devops - TP 1
## Info
mail: florian.berrot@ynov.com
github_username: Flours06

## But du projet
Installer Vagrant pour automatiser la création d'une VM  
Configurer des fichiers de vagrant.

## Prerequisites
- [Vagrant](https://www.vagrantup.com/downloads.html)
- [VirtualBox 6.0](https://www.virtualbox.org/wiki/Download_Old_Builds)
- git
- git bash


## VM config
Installation de la Virtual Box avec la version **6.0.1**
Sous Ubuntu 64x avec 1GB de RAM

## Librairies
```bash
nodejs@12
openssh-server
nginx
```
## Configuration VirtualBox
Make some configuration on network setting (SSH, HTTP, HTTPS)  

Connection to git bash  
```bash
ssh -p 2201 flo@127.0.0.1
```
## Vagrant
```bash
vagrant init (dans le dossier ou il ya vagrantFile et bootstrap.sh)
vagrant up (va run le fichier boostrap.sh)
```
>>>>>>> init vagrant project
