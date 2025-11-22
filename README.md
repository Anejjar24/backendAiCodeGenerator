# 🧠 AI Code Generator — Backend

Backend du projet **AI Code Generator**, une plateforme permettant de :

- Générer du code à partir d’un prompt en langage naturel
- Exécuter le code généré
- Visualiser les résultats et des graphiques

Ce backend est construit avec **Django + Django REST Framework** et sert de couche API pour le frontend React.

> 👉 **Pour installer le Frontend**, consultez :
> https://github.com/Anejjar24/FrontendAICodeGenrator


<img width="300" height="110" alt="Image" src="https://github.com/user-attachments/assets/5b5f9ae2-173f-43ef-b897-5fc62b6bc06b" />

---

<img width="1920" height="929" alt="Image" src="https://github.com/user-attachments/assets/18f9645b-e07a-4d21-a993-742836d628aa" />
<img width="1920" height="927" alt="Image" src="https://github.com/user-attachments/assets/e7b67dc3-f804-40ab-82c8-25d765e86932" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1eb97022-70d6-4993-877c-82d5f1d638a9" />

## 🎬 Démonstration vidéo

https://github.com/user-attachments/assets/a285767f-d1a5-4b21-8899-1752601bc0c3

## 📦 Technologies utilisées

- Python 3.8+
- Django
- Django REST Framework
- CORS Headers
- Python-dotenv

## 🚀 Installation & Démarrage

### 1️⃣ Cloner le dépôt

```bash
git clone https://github.com/Anejjar24/BackEndPFA.git
```

### 2️⃣ Créer et activer un environnement virtuel

```bash
virtualenv venv
```

Sous Windows :

```bash
venv\Scripts\activate
```

### 3️⃣ Installer les dépendances

```bash
pip install django djangorestframework django-cors-headers python-dotenv
```

### 4️⃣ Créer ou préparer le projet Django

```bash
django-admin startproject PFA
cd PFA
```

### 5️⃣ Configurer l’e-mail dans settings.py

```python
EMAIL_HOST_USER = "votre-email@gmail.com"
EMAIL_HOST_PASSWORD = "votre-google-app-password"
```

### 6️⃣ Migrer et lancer le serveur

```bash
python manage.py migrate
python manage.py runserver
```

## 📁 Structure

```
PFA/
│── manage.py
│── api/
│── settings.py
│── urls.py
