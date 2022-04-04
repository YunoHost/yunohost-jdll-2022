# JDLL 2022

Le projet YunoHost était présent aux JDLL 2022, représenté par tituspijean et ljf, avec

* un stand tenu sur les deux jours ;
* une conférence pour présenter le projet ;
* un atelier pour découvrir la simplicité de son installation et utilisation (avec lapineige en support).

## Conférence

La présentation est stockée dans le dossier `conference`
 et utilise RevealJS pour convertir le fichier Markdown en diapositives.
 Une app [Hedgedoc](https://github.com/YunoHost-Apps/hedgedoc_ynh) a été utilisée pour cela.

## Atelier

L'atelier est basé sur des serveurs VPS loués pour l'occasion,
 et une petite [Custom Webapp](https://github.com/YunoHost-Apps/my_webapp_ynh) contenant le fichier `index.html` décrivant les
 étapes d'installation, stockée ici dans le dossier `atelier`.

Les serveurs VPS ont été pris chez Scaleway.

Au préalable un projet dédié a été créé, juste pour lister les serveurs facilement,
 son identifiant est indiqué dans la commande de création.

Une clé SSH est générée avec la commande suivante, la clé publique ajoutée à Scaleway et la clé privée téléversée dans le dossier de la Custom Webapp.

```
ssh-keygen -b 4096 -C "JDLL" -f id_rsa_jdll
```

Les serveurs sont lancés avec la ligne de commande suivante, répétée autant de fois que nécessaire.
 Ils peuvent aussi être créés à la main directement dans l'interface web.

```
scw instance server create type=DEV1-S zone=fr-par-1 image=debian_buster root-volume=l:20G ip=new [project-id=...]
```

La commande retourne un descriptif du serveur ainsi créé : relever l'adresse IP publique
 et la partager à l'apprenti auto-hébergeur, ainsi que l'adresse de la webapp.
