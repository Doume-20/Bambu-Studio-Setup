# Quick Start - Bambu Studio

Guide de démarrage rapide pour l'utilisation de Bambu Studio avec l'imprimante A1 Mini.

---

## 1. Installation et Premier Lancement

### Téléchargement
1. Rendez-vous sur le site officiel de Bambu Lab : [https://bambulab.com/en/download/studio](https://bambulab.com/en/download/studio)
2. Téléchargez la version **Windows**
3. Installez le logiciel en suivant les instructions (double-cliquez sur le fichier .exe téléchargé)

### Configuration Initiale
Au premier lancement de Bambu Studio :

1. **Langue** : Sélectionnez **Français** dans le menu déroulant
2. **Modèle d'imprimante** : Choisissez **Bambu Lab A1 mini**
3. **Filaments** : Sélectionnez les profils suivants :
   - **PLA Bambu Lab**
   - **PETG Bambu Lab**
4. **Unités** : Sélectionnez **mm/g** (millimètres/grammes)
5. **Thème** (optionnel) : Si vous préférez un thème sombre, allez dans les paramètres et activez le **Mode Sombre**

Cliquez sur **Terminer** pour finaliser la configuration.

---

## 2. Import et Préparation du Modèle 3D

### Où Trouver des Modèles 3D ?
Vous pouvez télécharger des modèles gratuits sur ces plateformes :
- **MakerWorld** : [https://makerworld.com](https://makerworld.com) (plateforme officielle Bambu Lab)
- **Printables** : [https://www.printables.com](https://www.printables.com)
- **Thingiverse** : [https://www.thingiverse.com](https://www.thingiverse.com)

### Importer un Fichier STL
1. Cliquez sur **Fichier** → **Importer** → **Importer STL/OBJ/AMF/3MF**
2. Sélectionnez votre fichier (format .STL, .OBJ, .3MF, etc.)
3. Le modèle apparaît sur le plateau virtuel

### Manipulations de Base

#### Déplacer le Modèle
- Sélectionnez l'outil **Déplacer** dans la barre d'outils gauche
- Cliquez et glissez le modèle pour le repositionner sur le plateau

#### Rotation
- Sélectionnez l'outil **Rotation**
- Utilisez les cercles de rotation pour orienter le modèle selon vos besoins
- **Astuce** : Orientez les surfaces plates vers le bas pour une meilleure adhérence

#### Mise à l'Échelle
- Sélectionnez l'outil **Échelle**
- Modifiez la taille en pourcentage ou en dimensions exactes (mm)
- Verrouillez les proportions pour conserver les dimensions d'origine

#### Duplication
- Clic droit sur le modèle → **Ajouter une instance**
- Ou utilisez le raccourci **Ctrl+D**

### Optimiser l'Orientation
Pour de meilleurs résultats d'impression :
- Placez les surfaces plates au contact du plateau
- Minimisez les porte-à-faux (surfaces inclinées à plus de 45°) pour réduire le besoin de supports
- Évitez les orientations qui nécessitent beaucoup de supports sauf si nécessaire

---

## 3. Réglages d'Impression

### Profil d'Impression
1. Dans le panneau de droite, sous **Réglages d'impression**, sélectionnez un profil prédéfini :
   - **0.20mm Standard** (recommandé pour le prototypage rapide)
   - **0.16mm Fine** (meilleure qualité, temps plus long)
   - **0.28mm Draft** (rapide, qualité moindre)

Pour du prototypage, utilisez le profil **0.20mm Standard**.

### Supports
1. Dans la section **Support**, activez **Générer les supports automatiquement**
2. Bambu Studio placera automatiquement les supports nécessaires
3. Vous pouvez prévisualiser les supports en cliquant sur l'onglet **Aperçu**

### Autres Réglages
Les réglages par défaut sont optimisés pour votre imprimante et conviennent parfaitement au prototypage.

**Pour tout problème ou besoin de réglages avancés, veuillez notifier M. PICARD.**

---

## 4. Export vers Carte Micro SD et Impression

### Slicer le Modèle
1. Cliquez sur le bouton **Slicer** (en haut à droite)
2. Bambu Studio calcule les couches d'impression
3. Une fois terminé, vous pouvez :
   - Consulter le **temps d'impression estimé**
   - Consulter la **quantité de filament nécessaire**
   - Visualiser l'**aperçu couche par couche** avec le curseur en bas

### Exporter le Fichier
1. Cliquez sur **Exporter le plateau en G-code**
2. Choisissez l'emplacement de sauvegarde sur votre **carte micro SD** (insérée dans votre ordinateur)
3. Donnez un nom au fichier et enregistrez

Le fichier sera au format **.gcode** ou **.3mf** selon vos paramètres.

### Retirer la Carte et Lancer l'Impression
1. **Éjectez proprement** la carte micro SD de votre ordinateur
2. **Insérez la carte** dans le lecteur de carte de l'imprimante A1 Mini
3. Sur l'écran tactile de l'imprimante :
   - Accédez au menu **Imprimer**
   - Sélectionnez votre fichier dans la liste
   - Appuyez sur **Démarrer l'impression**

L'imprimante commencera automatiquement le chauffage du plateau et de la buse, puis lancera l'impression.

---

## Conseils Utiles

- **Première couche** : Surveillez toujours la première couche pour vous assurer qu'elle adhère correctement au plateau
- **Nettoyage du plateau** : Nettoyez régulièrement le plateau avec de l'alcool isopropylique pour une meilleure adhérence
- **Rangement du filament** : Conservez vos bobines dans un endroit sec pour éviter l'absorption d'humidité

---

## Support

**Pour tout problème technique, besoin d'assistance ou question concernant les réglages avancés, veuillez notifier M. PICARD.**

Bonne impression ! 🎉
