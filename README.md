# 📝 Gestion de Notes - `gestion_note_back_front`

**`gestion_note_back_front`** est une application mobile/web complète de **gestion des notes académiques**, conçue pour les enseignants, administrateurs et étudiants.  
Elle s’appuie sur un **backend Django** avec une base **SQLite**, et une interface utilisateur fluide développée avec **Flutter**.

---

## 📚 Fonctionnalités

- ✅ Ajouter, modifier, supprimer des **étudiants**, **matières**, et **notes**
- 🔎 Filtrer les notes par étudiant, matière ou semestre
- 📊 Calcul automatique des **moyennes** et **validation** (ex: mention, admis)
- 📱 Interface Flutter compatible **mobile** et **web**
- 🔐 Authentification simple pour sécuriser l'accès (à ajouter avec Django ou Firebase Auth)

---

## 🛠️ Technologies Utilisées

### 🔙 Backend – Django

- **Langage** : Python 3.x
- **Framework** : Django
- **Base de données** : SQLite
- **API** : Django REST Framework (DRF) recommandé pour Flutter

### 🔜 Frontend – Flutter

- **Langage** : Dart
- **Framework UI** : Flutter SDK (mobile/web)
- **Gestion HTTP** : `http` ou `dio` pour interagir avec l’API
- **State Management** : `Provider`, `Riverpod`, ou `Bloc` (au choix)

---

## 🚀 Prérequis

### Backend (Django)
- Python 3.8+
- pip
- virtualenv (optionnel)

### Frontend (Flutter)
- Flutter SDK (version stable)
- Dart SDK (installé avec Flutter)
- Un éditeur (Android Studio, VS Code ou IntelliJ)

---

## Installation & Lancement
### 1. Cloner le dépôt
```bash
Copier
Modifier
git clone https://github.com/ton-utilisateur/gestion_note_back_front.git
cd gestion_note_back_front
```
### 2. Backend Django
```bash
Copier
Modifier
cd gestion_note_back/
```

### Créer un environnement virtuel
```bash
python -m venv env
```
### Windows
```bash
env\Scripts\activate
```
### macOS/Linux
```bash
source env/bin/activate
```

### Installer les dépendances
```bash
pip install -r requirements.txt
```

### Appliquer les migrations
```bash
python manage.py migrate
```

### Lancer le serveur
```bash
python manage.py runserver
```
🟢 Le backend est maintenant disponible sur http://127.0.0.1:8000/

3. Frontend Flutter
```bash
Copier
Modifier
cd ../gestion_note_front/
```

# Mettre à jour les packages
flutter pub get

# Lancer l’application (web ou mobile)
flutter run -d chrome        # Pour Web
flutter run -d android       # Pour Android
flutter run -d ios           # Pour iOS (macOS uniquement)
