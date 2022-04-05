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

## On a créer un repertoire Github Partagé entre les membres de l'équipe

Le repertoire est un répertoires publique et j'ai ajouté Alban et Guillaume en temps que Collaborateurs du projets et ensuite, il ont juste eu besoin de faire :
```bash
git clone https://github.com/Quentinjulien/LaravelBlog.git
```
Quand il ont fait des modifications, il ont juste à faire :
```bash
git push origin main
```

### Problèmes de droits
On a rencontrée de sproblèmes de droits sur plusieurs dossier importants et après plusieurs tentative de solutions, on a décidé de faire à la racine de notre projet :
```bash
sudo chown -R 777 . 
```
