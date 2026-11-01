# WorldIndex Studio

**Créez et organisez vos univers, puis partagez vos créations.**

WorldIndex réunit un **Studio Windows pour construire ses univers** et un **site pour les publier, découvrir ceux des autres et échanger autour des créations**.

[**Télécharger la dernière version**](https://github.com/Azashiin/my-characters-library-releases/releases/latest) · [**Explorer WorldIndex**](https://my-characters-library-albui.asashiin.chatgpt.site) · [Guide du site](https://my-characters-library-albui.asashiin.chatgpt.site/guide)

## Créer et organiser dans le Studio

Le Studio fonctionne hors ligne avec une bibliothèque locale. Il permet de :

- Construire des univers et organiser leurs continents, pays, régions, villes et villages.
- Documenter les races, peuples, cultures, la faune et la flore, puis relier ces fiches aux personnages et aux lieux.
- Écrire des récits et construire une chronologie, avec des événements liés aux lieux et aux histoires.
- Créer des fiches de personnages, d’objets et de magies, et les rattacher à un univers.
- Organiser les illustrations, les galeries, les tags et les notes de travail.
- Retrouver toutes ses fiches avec Ctrl+K et des filtres par univers et type.
- Personnaliser les cadres décoratifs et importer ou exporter ses créations.

Une connexion permet de retrouver son profil et de partager les présentations choisies sur le site. Les univers commencent en privé ; les notes de travail, les prompts, les paramètres et les originaux restent dans la sauvegarde privée.

## Publier et découvrir sur le site

Les **univers et les créations publiés sont au premier plan**. Le site permet d’explorer les fiches, de découvrir leurs auteurs et de parcourir les galeries.

Les commentaires et les discussions associées à une création prolongent la découverte. Les favoris, le suivi de créateurs et les notifications permettent de retrouver les publications et les échanges qui vous intéressent.

Les cadres sont des **décorations de présentation** : une image avec son cadre n’est jamais ajoutée à la galerie d’un personnage, d’un objet ou d’une magie. Les modèles dont l’auteur autorise le téléchargement se partagent au format `.myframe`.

Les indices de génération par IA sont recherchés automatiquement dans les métadonnées des fichiers. Un badge **« IA probable »** peut être contesté par l’auteur pour revue. L’absence d’indice ne certifie pas une origine humaine ; cette analyse ne reconnaît pas les pixels d’une image dont les métadonnées ont été retirées.

## Version actuelle : 4.3.0

**Ctrl+K** ou **Rechercher** dans la barre supérieure ouvre une recherche dans toutes les fiches enregistrées du Studio : univers, personnages, objets, magies, races, peuples, cultures, faune, flore, lieux, récits et événements.

- Combinez les filtres **Univers** et **Type de fiche**.
- Retrouvez un nom, un nom complet ou un alias, ou choisissez **Tout le texte** pour les descriptions, récits et notes de travail.
- Consultez un extrait du passage trouvé et ouvrez directement la bonne fiche avec Entrée ou un clic.
- Les fiches privées sont incluses localement ; la corbeille est exclue et les archives sont accessibles avec une option.
- Échap ramène au travail en cours. Changer de fiche garde la confirmation des modifications non enregistrées.

[Consulter les changements de la version 4.3.0](https://github.com/Azashiin/my-characters-library-releases/releases/tag/v4.3.0)

## Écriture et présentation depuis la version 4.2


Le **Studio est l’espace d’écriture** : les textes narratifs disposent d’un éditeur visuel avec titres, gras, italique, barré, listes, citations, liens, tableaux, séparateurs, annuler/rétablir, aperçu et mode plein écran. Les prompts gardent leur saisie exacte. Les exports et sauvegardes conservent les textes et leur mise en forme.

Le **site est l’espace de présentation et de découverte**. Connectez-vous sur votre univers, une fiche ou une création et ouvrez **Personnaliser cette page** :

- Trois modèles : encyclopédie, manuscrit ou dossier illustré.
- Accents cobalt, violet ou cuivre ; police littéraire ou contemporaine ; taille de lecture et sommaire facultatif.
- Aperçu avec votre propre contenu et vos illustrations, puis vérification sur la page avant enregistrement.
- Héritage de la présentation de l’univers pour ses fiches, avec réglage individuel et réinitialisation.

Les mises en page choisies sur le site sont conservées lorsque le Studio republie les textes. Chaque auteur contrôle ses présentations ; seuls les contenus publiés sont consultables publiquement.

Les races, peuples et ethnies, cultures, faune et flore gardent leurs illustrations, crédits, appartenances et liens. Les cadres décoratifs restent séparés des galeries.

[Consulter les changements de la version 4.2.0](https://github.com/Azashiin/my-characters-library-releases/releases/tag/v4.2.0)

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
