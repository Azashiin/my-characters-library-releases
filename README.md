# WorldIndex Studio

**Créez et organisez vos univers, puis partagez vos créations.**

WorldIndex réunit un **Studio Windows pour construire ses univers** et un **site pour les publier, découvrir ceux des autres et échanger autour des créations**.

[**Télécharger la dernière version**](https://github.com/Azashiin/my-characters-library-releases/releases/latest) · [**Explorer WorldIndex**](https://my-characters-library-albui.asashiin.chatgpt.site) · [Guide du site](https://my-characters-library-albui.asashiin.chatgpt.site/guide)

## Créer et organiser dans le Studio

Le Studio fonctionne hors ligne avec une bibliothèque locale. Il permet de :

- Construire des univers et organiser leurs continents, pays, régions, villes et villages.
- Écrire des récits et construire une chronologie, avec des événements liés aux lieux et aux histoires.
- Créer des fiches de personnages, d’objets et de magies, et les rattacher à un univers.
- Organiser les illustrations, les galeries, les tags et les notes de travail.
- Personnaliser les cadres décoratifs et importer ou exporter ses créations.

Une connexion permet de retrouver son profil et de partager les présentations choisies sur le site. Les univers commencent en privé ; les notes de travail, les prompts, les paramètres et les originaux restent dans la sauvegarde privée.

## Publier et découvrir sur le site

Les **univers et les créations publiés sont au premier plan**. Le site permet d’explorer les fiches, de découvrir leurs auteurs et de parcourir les galeries.

Les commentaires et les discussions associées à une création prolongent la découverte. Les favoris, le suivi de créateurs et les notifications permettent de retrouver les publications et les échanges qui vous intéressent.

Les cadres sont des **décorations de présentation** : une image avec son cadre n’est jamais ajoutée à la galerie d’un personnage, d’un objet ou d’une magie. Les modèles dont l’auteur autorise le téléchargement se partagent au format `.myframe`.

Les indices de génération par IA sont recherchés automatiquement dans les métadonnées des fichiers. Un badge **« IA probable »** peut être contesté par l’auteur pour revue. L’absence d’indice ne certifie pas une origine humaine ; cette analyse ne reconnaît pas les pixels d’une image dont les métadonnées ont été retirées.

## Version actuelle : 4.0.2

Le Studio reprend l’identité visuelle du site : **bleu nuit, ardoise et ivoire**, navigation sombre, panneaux clairs, titres, boutons et formulaires harmonisés. Les univers, les fiches, les galeries, les paramètres, le compte et l’icône Windows suivent cette identité.

[Consulter les changements de la version 4.0.2](https://github.com/Azashiin/my-characters-library-releases/releases/tag/v4.0.2)

## Installer ou mettre à jour

**Windows 10 22H2 ou Windows 11, 64 bits.**

1. Ouvrez la [dernière version](https://github.com/Azashiin/my-characters-library-releases/releases/latest) et téléchargez le fichier `.exe`.
2. Fermez le Studio puis lancez l’installateur.
3. Suivez les étapes de l’assistant. La bibliothèque existante est conservée.

À partir de Studio 3.7, les mises à jour se trouvent dans **Paramètres & cadres → Mises à jour du Studio**. Le logiciel recherche les nouvelles versions au démarrage et vous laisse choisir quand les télécharger et les installer.

**Si une ancienne version se ferme sans installer sa mise à jour**, téléchargez et lancez manuellement l’installateur actuel une première fois.

Les créations locales sont conservées dans `%APPDATA%\MyCharactersLibrary\Library3`. Pour sauvegarder cette bibliothèque, quittez le Studio puis copiez le dossier complet.

## Fichiers proposés dans les versions

| Fichier | Utilité |
| --- | --- |
| `.exe` | Installateur Windows 64 bits. |
| `.exe.sha256` | Empreinte SHA-256 de l’installateur. |
| `studio-update.json` | Manifeste de mise à jour signé pour le Studio. |

Dans la page d’une version, choisissez l’installateur `.exe` parmi les fichiers **Assets**. Les archives **Source code** générées par GitHub contiennent les fichiers de ce dépôt de distribution.

Ce dépôt héberge les installateurs, les mises à jour et leur documentation. Il conserve son adresse historique `my-characters-library-releases` pour assurer la continuité des téléchargements et du système de mise à jour de WorldIndex.
