# LumeSeries

**Séries à la demande (Xtream) pour Android TV** — simple, rapide, pensé pour la télécommande.
Troisième app de la famille Lume, à côté de [LumeTV](https://github.com/Celtiore/lume-tv) (le direct)
et de [LumeVOD](https://github.com/Celtiore/lume-vod) (les films) : même compte Xtream, même clé de
signature, trois apps côte à côte sur le launcher.

> ⚠️ **LumeSeries ne contient aucune série ni aucun contenu.** C'est uniquement un lecteur :
> tu dois renseigner ta propre source Xtream (à laquelle tu as légalement accès).

---

## 📥 Téléchargement

➡️ **[Dernière version (Releases)](../../releases/latest)** — télécharge le fichier `LumeSeries-x.y.z.apk`.

Version actuelle : **1.0.2**.

## ✨ Fonctionnalités (v1.0.0)

- 🔑 **Connexion Xtream** (saisie guidée au premier lancement — import depuis LumeTV à venir)
- 🗂️ **Catalogue à deux colonnes** : catégories à gauche, jaquettes de la catégorie à droite,
  recherche dans les catégories et dans les séries affichées
- 📺 **Fiche série** : synopsis, genre, note, casting, saisons
- 🎞️ **Liste des épisodes** d'une saison (`S01E02 · Titre · durée`)
- ▶️ **Lecture plein écran** à la télécommande (OK = pause, ±10 s, ±60 s)
- ⏭️ **Épisode suivant automatique** dans la saison (et touche Suivant)
- 🔌 **Connexion unique respectée** : passer en arrière-plan coupe le flux, LumeTV ou LumeVOD
  peuvent reprendre (et inversement)
- 🔄 **Mises à jour intégrées** (depuis les Releases GitHub)
- Import des identifiants depuis LumeTV en un OK (1.0.2), comptes multiples et Réglages (Comptes, À propos, vérification manuelle des mises à jour).

## 🗺️ Prochainement

- Import des identifiants depuis LumeTV (sans ressaisie)
- Reprise de lecture (« Reprendre à … »)
- Affiches et synopsis enrichis (TMDB)

## 🔧 Installation

1. Sur la box : autoriser l'installation d'applications inconnues pour ton navigateur ou
   ton gestionnaire de fichiers.
2. Télécharger `LumeSeries-x.y.z.apk` depuis les Releases et l'ouvrir.
3. Au premier lancement : host, utilisateur, mot de passe Xtream (Entrée passe au champ
   suivant).

Les mises à jour suivantes sont proposées **dans l'app** au démarrage.

## 🔐 Vie privée

Aucune télémétrie. Les identifiants Xtream sont stockés chiffrés sur l'appareil, exclus des
sauvegardes cloud. Le code source vit dans le dépôt `Iptv` (monorepo LumeTV / LumeVOD / LumeSeries).
