# Sanity Junction — Web Demo

Démo web jouable de **Sanity Junction**, un visual novel / jeu narratif psychologique
développé avec **Ren'Py / Python**.

**Statut : Alpha / démo web**

> Cette version est une exportation web du projet Ren'Py. Le dépôt contient la version
> jouable navigateur, pas l'intégralité du projet source de développement.

🎮 **Démo en ligne :** https://sanity-junction-web.vercel.app

---

## Technologies

- **Ren'Py** (moteur de visual novel)
- **Python**
- **HTML5 / WebAssembly** via l'export web de Ren'Py
- **Vercel** (hébergement / déploiement)

## Fonctionnalités

- Visual novel jouable directement dans le navigateur
- Version alpha du jeu
- Interface Ren'Py web (chargement, sauvegardes import/export, plein écran)
- Démo accessible en ligne

---

## Lancer le projet en local

L'export web Ren'Py doit être servi via un **serveur HTTP local** (l'ouverture directe
du fichier `index.html` ne fonctionne pas à cause des restrictions des navigateurs sur
WebAssembly et les requêtes de fichiers).

Depuis la racine du projet :

```bash
py -m http.server 8000
```

Puis ouvrir dans le navigateur :

```
http://localhost:8000
```

> Astuce : si `py` n'est pas disponible, utilisez `python -m http.server 8000`.

---

## Déploiement sur Vercel

Le projet est un site statique : aucune étape de build n'est nécessaire.

| Paramètre          | Valeur            |
| ------------------ | ----------------- |
| Framework Preset   | Other             |
| Build Command      | _(vide)_          |
| Output Directory   | _(vide)_          |
| Root Directory     | racine du projet  |
| Variables d'env.   | aucune            |

---

## Pour les recruteurs

Ce projet illustre plusieurs compétences concrètes :

- **Projet narratif réalisé en équipe** (conception d'un visual novel)
- **Utilisation de Ren'Py / Python** pour le développement de jeu
- **Export web** d'un projet Ren'Py (HTML5 / WebAssembly)
- **Préparation d'une démo jouable** et testable en ligne
- **Publication sur GitHub** (versioning, structure de dépôt propre)
- **Déploiement sur Vercel**
- **Documentation projet** claire et honnête

---

## Limites actuelles

- Version **alpha** : contenu et fonctionnalités encore en évolution
- Export web relativement **lourd** (médias embarqués)
- **Chargement parfois long** au premier lancement
- Expérience **optimisée pour ordinateur** (clavier/souris, écran large)
- **Performances variables** selon le navigateur et la machine

---

## Crédits / ressources

Sanity Junction est un projet narratif développé avec Ren'Py / Python.

Les ressources utilisées dans le jeu (musiques, images, vidéos, polices, plugins)
peuvent être soumises à des droits propres à leurs auteurs respectifs. Elles sont
utilisées dans le cadre de ce projet et restent la propriété de leurs ayants droit.
En cas de question sur l'usage d'une ressource, merci de me contacter.

Moteur : [Ren'Py](https://www.renpy.org/) (version 8.5.3).

---

_Projet personnel / en équipe — Tous droits réservés, sauf mention contraire._
