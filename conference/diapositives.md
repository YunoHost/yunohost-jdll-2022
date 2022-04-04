---
type: slide
title: YunoHost JDLL 2022
slideOptions:
  theme: white
  transition: slide
  width: 1280
  height: 1080
  margin: 0.01
---

<img src="https://yunohost.org/_images/ynh_logo_black_300dpi.png" class="plain">

## De l'auto-hébergement<br />à l'élevage de CHATONS

### Journées du Logiciel Libre
### 2022-04-03

----

<img src="./uploads/772bfb484e4a105c48ba0f707.jpg" width="100px" class="plain"> 

`tituspijean`

---

## Sommaire

1. Introduction : reprenez le contrôle
2. YunoHost : une solution simple pour l'auto-hébergement
3. Côté administrateur <span class="fragment">($\hookleftarrow$ c'est vous !)</span>
4. Côté technique <span class="fragment">($\hookleftarrow$ promis, c'est accessible)</span>
5. Côté communauté

---

## Introduction

----


<img src="./uploads/772bfb484e4a105c48ba0f703.png" height="80%" class="plain" />
<small>Illustration par JimboJoe</small>

----

### Où stockez-vous vos données ?

* Sur papier ?
* Votre disque dur, clé USB, ...
* Fournisseurs de services (*drive, *box, *cloud)

----


<!-- .slide: data-background-image="./uploads/772bfb484e4a105c48ba0f702.jpg" data-background-size="contain" data-background-color="black" -->

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

### Envoi de données vers le nuage
<!-- .element style="color: white;" -->
*Incendie d'un centre de données d'OVH,
à Strasbourg, mars 2021*
<!-- .element style="color: white;" -->

----

![](https://doc.pijean.ovh/uploads/772bfb484e4a105c48ba0f714.jpg)

----

* (Re)possession des données
* Décentralisation
* Vie privée
* Liberté d'expression
* Auto-didactisme <!-- .element class="fragment" style="width: 100%" -->

## $\implies$ Motivations à l'auto-hébergement
<!-- .element class="fragment" style="width: 100%" -->

----

## Le matériel pour s'auto-héberger

<img src="https://yunohost.org/user/images/virtualbox.png
" height="200px" class="plain fragment" /> <img src="https://yunohost.org/user/images/raspberrypi.jpg
" height="200px" class="plain fragment" /> <img src="https://yunohost.org/user/images/computer.png
" height="200px" class="plain fragment" /> <img src="https://yunohost.org/user/images/vps.png
" height="200px" class="plain fragment" />

----

## Les logiciels à auto-héberger

|             | Alternatives libres |
| ----------- | -------- |
| Twitter | <img src="./uploads/772bfb484e4a105c48ba0f70a.png" height="50px" class="plain" /> Mastodon |
| Dropbox, GDrive, iCloud... | <img src="./uploads/772bfb484e4a105c48ba0f70e.png" height="50px" class="plain" /> Nextcloud |
| Office 365 | <img src="./uploads/772bfb484e4a105c48ba0f70c.png" height="50px" class="plain" /> Cryptpad |
| Tout système de domotique | <img src="./uploads/772bfb484e4a105c48ba0f70b.png" height="50px" class="plain" /> Home Assistant |
| Messenger, Whatsapp, Wechat... | <img src="./uploads/772bfb484e4a105c48ba0f70f.png" height="50px" class="plain" /> |
<!-- .element style="width: 90%" -->

**... chacun avec ses propres prérequis
et instructions d'installation**

---

<!-- .slide: data-background-image="https://64.media.tumblr.com/4b3b0287ca43ce1021340cd692f65f9f/tumblr_mj7iufgKNi1qghl49o1_500.gifv" -->

<img src="./uploads/772bfb484e4a105c48ba0f710.png" class="fragment plain" />

----

## Il est *nécessaire* de rendre l'administration de serveurs __simple__

----

# <img src="./uploads/772bfb484e4a105c48ba0f701.png" alt="YunoHost" style="height:1.5em;" class="plain" />, c'est quoi ?
- <img src="https://www.debian.org/logos/openlogo-nd-100.png" alt="Debian" height="50px" class="plain" /> une distribution Debian
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-wrench"></span> une interface d'administration simple
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-envelope"></span><span class="fa fa-comments"></span> des services fonctionnels dès l'installation
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-globe"></span> des noms de domaines gratuits et automatiquement configurés (`.ynh.fr`, `.nohost.me`, `.noho.st`)
- <span class="fa fa-globe"></span> vos propres noms de automatiquement configurés chez vos *registrars*.
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-cubes"></span> un grand catalogue d'applications installables en quelques clics 
<!-- .element class="fragment" style="width: 120%" -->
- <span class="fa fa-lock"></span> un portail de connexion pour les personnes inscrites
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-key"></span> un système de permissions pour contrôler les accès aux apps
<!-- .element class="fragment" style="width: 100%" -->
- <span class="fa fa-stethoscope"></span> un système de diagnostic pour surveiller tout ça
<!-- .element class="fragment" style="width: 100%" -->

----

## YunoHost, côté utilisateur/administrateur
### Une petite démo ?

https://demo.yunohost.org

---

## YunoHost, côté technique

----

### Installable en moins d'une heure

<img src="https://yunohost.org/user/images/virtualbox.png
" height="200px" class="plain" /> <img src="https://yunohost.org/user/images/raspberrypi.jpg
" height="200px" class="plain" /> <img src="https://yunohost.org/user/images/computer.png
" height="20px" class="plain" /> <img src="https://yunohost.org/user/images/vps.png
" height="200px" class="plain" />

----

### Automatisation des tâches de sysadmin

Accessibles via l'interface web ou la ligne de commande

<div style="width: 100%;">
<img src="./uploads/772bfb484e4a105c48ba0f708.png" height="600px" class="" /> <img src="./uploads/772bfb484e4a105c48ba0f709.png" height="600px" class="plain" /> 
</div>

----

### Les applications

Des fichiers de description, de configuration,
et des scripts Bash pour laisser la magie opérer.

<img src="./uploads/772bfb484e4a105c48ba0f711.png" height="600px" class="" />
<img src="./uploads/772bfb484e4a105c48ba0f713.png" height="600px" class="" />

\+ un système de tests automatisés pour aider les *packagers*

----

### Feuille de route

- YunoHost version 11 (Debian Bullseye) : en version bêta :rocket:
- L'intégration de nom de domaines *wildcard*
- Des formulaires d'inscription et des liens d'inscription de comptes utilisateurs
- Une évolution du système de *packaging* pour encore plus facilement intégrer des applications au catalogue
- ...

---

## YunoHost, côté communauté

----

### Plus de 8000 instances YunoHost

*Source: Shodan*

----

# <img src="https://yunohost.org/_images/ynh_logo_black_300dpi.png" alt="YunoHost" class="plain" style="height:2em; width=auto;" /> $\times$ <!--<span class="fragment fade-out" >vs.?</span> <span class="fa fa-heart fragment" style="color: red;"></span>--> <img src="./uploads/772bfb484e4a105c48ba0f705.png" alt="CHATONS" class="plain" style="height:2.5em; width=auto;" />

> CHATONS est le **Collectif des Hébergeurs Alternatifs, Transparents, Ouverts, Neutres et Solidaires**. Ce collectif vise à rassembler des structures proposant des services en ligne libres, éthiques et décentralisés.

`https://chatons.org/`

Une quinzaine de CHATONS tourne avec YunoHost. :rocket:

<!-- .element style="width: 90%" -->

----

### Un catalogue d'applications fourni

208 pleinement fonctionnelles sur 236 testées

<div class="fragment"> ... il y a un an ! Actuellement :

325 pleinement fonctionnelles sur 344 testées
512 dépôts de code dans notre organisation `YunoHost-Apps`

</div>

----

### Nous trouver

* Le site web de YunoHost : [yunohost.org](https://yunohost.org)
* Le forum pour les annonces et l'entraide : [forum.yunohost.org](https://forum.yunohost.org)
* Des salons sur Matrix/IRC de discussion et d'entraide pour le support, le *packaging* d'apps, le développement : [yunohost.org/chat_rooms](https://yunohost.org/fr/chat_rooms)
* La documentation : [yunohost.org/doc](https://yunohost.org/docs)

<span class="fa fa-heart" style="color: red; height=30px;"></span> contributeurs <br />(Python, UX, HTML, CSS, JS, Bash, doc ...)

----

# <span class="fa fa-heart" style="color: red; height=30px;"></span> Nos soutiens

![](https://doc.pijean.ovh/uploads/772bfb484e4a105c48ba0f700.png)

et donateurs !


----

## Dans les coulisses...

* Présentation faite avec [Reveal.js](https://revealjs.com/) sur [HedgeDoc](https://hedgedoc.org/)...
* ... que j'accède avec mon VPN avec [WireGuard](https://wireguard.com)...
* ... le tout auto-hébergé sur mon serveur [<img src="./uploads/772bfb484e4a105c48ba0f701.png" alt="YunoHost" style="height:3ex;" class="plain" />](https://yunohost.org)

---

# Avez-vous des questions ?

---

# Atelier
## Installation et découverte de <img src="./uploads/772bfb484e4a105c48ba0f701.png" alt="YunoHost" style="height:3ex;" class="plain" />
### Espace Public Numérique

*Dans un instant*
