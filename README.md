# 🧠 Classification Alzheimer avec Deep Learning et Ensemble Learning
Projet de classification des stades de la maladie d'Alzheimer à partir d'images IRM cérébrales en utilisant CNN, VGG16, Xception, Voting et Grad-CAM.
## 📚 Table des matières
- [Aperçu](#aperçu)
- [Objectifs](#objectifs)
- [Données](#données)
- [Modèles utilisés](#modèles-utilisés)
- [Résultats](#résultats)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Interprétation Grad-CAM](#interprétation-grad-cam)
- [Technologies](#technologies)
- [Auteur](#auteur)
## 👀 Aperçu
Ce projet a pour but d'entraîner plusieurs modèles de Deep Learning pour classifier les IRM cérébrales selon les stades de la maladie d'Alzheimer, puis de les combiner à l’aide d’une méthode d’ensemble (Hard Voting). L’interprétabilité est également étudiée grâce à Grad-CAM.
## 🎯 Objectifs
- Construire des modèles CNN performants
- Appliquer du Transfer Learning (VGG16, Xception)
- Combiner les modèles via une méthode d’ensemble
- Visualiser les activations grâce à Grad-CAM
## 📁 Données
Les données sont organisées par classe :
- Non Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented
Voici quelques images IRM représentatives de chaque classe dans le dataset : 
![Exemples IRM](ImageDeLaDataset.png) 
## 🧠 Modèles utilisés
- CNN simple (entraîné from scratch)
- VGG16 avec fine-tuning
- Xception avec fine-tuning
- Voting Classifier (Hard Voting)
- Visualisation par Grad-CAM
## 📊 Résultats
- Accuracy individuelle des modèles
- Accuracy du modèle combiné (Voting)
- Matrices de confusion
- Visualisation des courbes d'entraînement
  ## 📈 Courbes d'entraînement et de validation

### 🔹 CNN
![Courbes CNN](AccuraccyandlossfortrainingCNN.png)

### 🔹 VGG16
![Courbes VGG16](AccuracyandlossforTrainingVGG16.png)

### 🔹 Xception
![Courbes Xception](AccuracyandlossforTrainingXception.png)

### 🔹 Voting Classifier (Hard Voting)
![Courbes Voting](Accuraccyandlossfortraining.png)

## ⚙️ Installation

Clone le repo :
```bash
git clone https://github.com/tonpseudo/ton-repo.git
cd ton-repo
pip install -r requirements.txt

---

### 10. 🚀 Utilisation

```markdown
## 🚀 Utilisation
Lance simplement le notebook :

```bash
jupyter notebook Ensemble_Approch_alzheimer-2.ipynb

---

### 11. 🧠 Interprétation Grad-CAM

```markdown
## 🔍 Interprétation Grad-CAM
Grad-CAM permet de visualiser quelles zones de l'image ont influencé la décision du modèle, utile pour valider les prédictions médicalement.
## 🛠️ Technologies
- Python, TensorFlow, Keras
- Matplotlib, Seaborn
- Scikit-learn, NumPy, Pandas
- PIL / Pillow
## 👤 Auteur
Yeddes Nawres 
Scrum Master & Chef de Projet Data Science
