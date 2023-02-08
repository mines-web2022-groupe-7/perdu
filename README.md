# Perdu sur internet

## Le cours

Lire le README de https://github.com/ue22-p22/web et setuper le cours sur son poste.

## Freebasecamp

S'inscrire sur https://www.freecodecamp.org/ et faire les 10 premiers cours de "Responsive Web Design"

## TP

1. Aller sur https://perdu.com
2. Cloner le repertoire "perdu"
3. Ouvrir le repo avec VSCode
4. Ecrire dans un fichier index.html le code qui permettra a votre naviageur d'afficher le contenue du site perdu.

### Comment visualiser le site ?

(a discuter en cours)
Plein d'option s'offre a vous.

#### 1. Via un fichier

"Ouvrir avec" depuis le fichier ou "Ouvrir le fichier ..." depuis le navigateur

#### 2. Via un un serveur web definie dans python et/ou javascript

La plupart des languages offres des outils pour permettre de "rendre" le contenue d'un dossier via "ip"

**En python** :

```bash
# On lance python en chargeant le module 'http.server'
python -m "http.server"

# Puis ouvrir sur son navigateur l'url http://localhost:8000
```

**En javascript** :

```bash
# Installation de la librairie permettant de faire cela
npm install -g http-server

# Lancement de la commande
http-server .

# Puis ouvrir sur son navigateur l'url http://localhost:8080
```

#### 3. Et sur internet ?

Il existe une infinité d'hébergeur qui propose de 'stoquer' votre site et le 'distribuer'. 

Dans le cadre de ce cours nous utiliserons https://surge.sh/ qui me semble être une solution simple (et gratuite pour notre usage).

Mission : suivre leur documentation pour installer l'outil et mettre a disposition votre version du site perdu aux yeux du monde !

### (optionnel) Pour les plus rapides

Merci de rajouter sur le site le même :

![Perdu](https://tenor.com/fr/view/confused-meme-lost-john-travolta-office-gif-7666840)