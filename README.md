# EMODAILY 🌱

Application iOS qui permet aux jeunes de 15 à 29 ans d'exprimer et de suivre leur état émotionnel grâce à un journal digital.

## 📓 CONTEXTE

Projet réalisé en équipe de 4 dans le cadre de l'Extended Apple Foundation Program chez SIMPLON.CO, en mars 2026.

Challenge : « améliorer le suivi émotionnel des jeunes âgés de 15 à 29 ans ». EmoDaily y répond en favorisant l'expression régulière des émotions.

## 🎯 FONCTIONNALITÉS

- Journal sous forme de calendrier (semaine, mois, année)
- Nouvelle entrée : date, émotions, santé, note et photo
- Défis individuels et collectifs, avec tampons à collectionner
- Statistiques sur l'ensemble des entrées
- Profil utilisateur

## 🛠 TECHNOLOGIES

| Technologie | Usage |
|---|---|
| Swift / SwiftUI | Langage et interface |
| Observation | Gestion de l'état |
| PhotosUI | Sélection des photos |
| API Airtable | Stockage des utilisateurs, entrées et défis |
| Cloudinary | Hébergement des photos |

## 🚀 INSTALLATION

1. Cloner le projet

   ```bash
   git clone https://github.com/kays-dev/emodailyapp.git
   ```

2. Ouvrir `projetEmoDaily.xcodeproj` dans Xcode
3. Renseigner votre clé API Airtable dans les ViewModels (`Data/ViewModels`) : elle n'est pas fournie dans le dépôt
4. Build & Run (⌘R)

## 👥 AUTEUR·ES

| Membre | GitHub | Contributions principales |
|---|---|---|
| Krystal | [@kays-dev](https://github.com/kays-dev) | Structure du projet et modèle de données · écran Nouvelle entrée · upload des photos (Cloudinary) · connexion à l'API Airtable |
| Julien | [@hjulien02](https://github.com/hjulien02) | Défis et quêtes, tampons, statistiques, refonte de l'arborescence des vues |
| Thomas | [@toto38000](https://github.com/toto38000) | Statistiques et profil, connectés à l'API |
| Myris | [@myrisz](https://github.com/myrisz) | Journal et calendrier (semaine, mois), fenêtre d'entrée |

## 📜 LICENSE

Ce projet a été développé dans un cadre pédagogique.