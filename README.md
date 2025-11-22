# 🧠 AI Code Generator — Backend

Backend du projet **AI Code Generator**, une plateforme permettant de :

- Générer du code à partir d’un prompt en langage naturel
- Exécuter le code généré
- Visualiser les résultats et des graphiques

Ce backend est construit avec **Django + Django REST Framework** et sert de couche API pour le frontend React.

> 👉 **Pour installer le Frontend**, consultez :
> https://github.com/Anejjar24/FrontendAICodeGenrator

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
