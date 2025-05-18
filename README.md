# 📂 Script Python – Uploader un dossier local vers AWS S3

Troisième projet cloud AWS de Cédric Haegele.  
Ce script Python envoie automatiquement tous les fichiers d’un dossier local dans un bucket S3.

---

## 🧰 Technologies utilisées

- Python 3.13  
- Boto3  
- AWS CLI  
- Amazon S3

---

## 📦 Fonctionnement

1. Se connecte au bucket `cedric-s3-demo`
2. Parcourt tous les fichiers du dossier `fichiers_a_uploader`
3. Envoie chaque fichier dans S3
4. Affiche un résumé du nombre de fichiers envoyés

---

## 🔐 Prérequis

- Avoir un compte AWS  
- Avoir installé et configuré AWS CLI (`aws configure`)  
- Avoir créé un bucket S3 (`cedric-s3-demo`)  
- Avoir installé la bibliothèque Boto3 :
```bash
pip install boto3
```

---

## ▶️ Lancement

```bash
python upload_folder_to_s3.py
```

---

## ✍️ Auteur

**Cédric Haegele**  
🔗 [LinkedIn](https://www.linkedin.com/in/cedric-haegele)  
📂 [GitHub](https://github.com/CedricHaegele)
