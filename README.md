# Rapports et projets — Adrien Chaudron

Recueil de mes rapports techniques, classés par année d'école d'ingénieur.

## 3A

| Rapport | Description |
|---|---|
| [Dossier technique — Olympiades FANUC 2025](3A/Dossier_technique_Olympiades_FANUC_2025.pdf) | Conception d'une cellule robotisée d'encaissage et de palettisation de bouteilles : choix des préhenseurs et des robots, étude des temps de cycle, simulation ROBOGUIDE, line tracking et analyse des risques. Projet en équipe avec Kassoum Kone et Serigne Mbaye. |

## 4A — Stage chez Gradel Lightweight

| Rapport | Description |
|---|---|
| [Annexe technique — solveur IK redondant](4A/Annexe_Gradel_solveur_IK_redondant.pdf) | Formulation mathématique et algorithmique d'un solveur de cinématique inverse pour un robot ABB IRB 6640 sur rail linéaire avec mandrin rotatif (RobotComponents / Grasshopper). |

## 5A

| Rapport | Description |
|---|---|
| [Segmentation CNN du cerceau — drone Tello](5A/Rapport_CNN_segmentation_cerceau_drone_Tello.pdf) | Partie vision d'un projet de vol autonome : réseau RingSegNet (MobileNetV3-small + décodeur U-Net) pour segmenter un cerceau indépendamment de sa couleur, puis le localiser en 2D et en 3D. |
| [Article — vol autonome d'un drone Tello à travers un cerceau](5A/Article_vol_autonome_drone_Tello.pdf) | Article complet du projet, écrit avec Samuel Stef : identification et asservissement de la hauteur, du lacet et de l'axe X, réseau de neurones de détection du cerceau, position 3D, architecture HIL multi-thread, communication MQTT, tableau de bord temps réel et machine à états. |
| [Code source — drone Tello](https://github.com/AdrienChaudron/drone-tello-cerceaux) | Dépôt du projet : détection du cerceau par CNN, position 3D, machine à états de recherche et de mise en axe, liaison MQTT avec le PC de contrôle. |
