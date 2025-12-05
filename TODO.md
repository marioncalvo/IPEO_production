| Personne | Partie principale                      | Dans votre projet                           |
| -------- | -------------------------------------- | ------------------------------------------- |
| A        | **Data + DataLoader + Augmentation**   | Analyse des images + préparation + transfos |
| B        | **Modèles + Entraînement**             | ResNet / MobileNet + training               |
| C        | **Évaluation + Calibration + Analyse** | Accuracy, F1, Reliability Diagram           |


5. Planning clair de début (1ère semaine)
Jour 1 – TOUS (1h)
Lire le sujet
Regarder ton PDF inspiration ensemble
Créer GitHub + dossier
Jour 2
A : explore le dataset
B : importe ResNet + DataLoader minimal
C : lit sur calibration + fait un premier code de reliability diagram
Jour 3
B : entraîne premier modèle
A : fait data visualization
C : commence les métriques
Jour 4
Comparaison des premiers résultats
Création du squelette du rapport

Modèle à teste proposer par chatgpt (à regarder si ça fait du sens)
| Modèle       | Accuracy | F1 | ECE (calibration) |
| ------------ | -------- | -- | ----------------- |
| ResNet18     | x        | x  | x                 |
| MobileNet    | x        | x  | x                 |
| ResNet + aug | x        | x  | x                 |

lien de ma discussion avec chat si jamais: https://chatgpt.com/share/6932b252-53f4-8010-9f8f-2896ef082d22
