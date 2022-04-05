# TP de Quentin JULIEN, Guillaume & Alban

## Installation de Laravel via Docker

* On installe une distrubion Linux (Ubuntu) via le Microsoft Store
* On installe Docker Desktop (qu'on relit à la distro via le menu ressources dans les paramètres)

Dans le dossier ~ de l'utisateur ubuntu, je lance ces commandes
```bash
curl -s https://laravel.build/example-app | bash
cd example-app
./vendor/bin/sail up
```

## Ajout du code

On créer ensuite les modèles :
```bash
sail php artisan make:model Post -mc     # migration et controller
sail php artisan make:model Comment -mc
sail php artisan make:model Reply -mc
```

Et ensuite, **on copie le code présent sur le  Github du professeur**

### Problèmes de droits
On a rencontrée de sproblèmes de droits sur plusieurs dossier importants et après plusieurs tentative de solutions, on a décidé de faire à la racine de notre projet :
```bash
sudo chown -R 777 . 
```
