# 🏪 Stock Management Application

## 📖 Description

Cette application web de **gestion de stock** a été développée dans le cadre du projet de fin d’année à l’**EMSI Rabat**.  
Elle a pour objectif d’aider les entreprises à gérer efficacement leurs **produits, clients, fournisseurs et ventes**, tout en assurant un suivi en temps réel des stocks.

## 🚀 Objectifs du projet

- Fournir une solution simple et performante pour suivre les mouvements de stock.  
- Réduire les risques de **rupture** ou de **surstockage**.  
- Faciliter la gestion quotidienne des **ventes, achats, clients et fournisseurs**.  
- Générer des rapports d’inventaire précis et fiables.  
- Offrir une **interface intuitive et responsive** grâce à Django & Bootstrap.

---

## 🛠️ Technologies utilisées

| Catégorie | Technologies |
|------------|---------------|
| **Langage principal** | Python |
| **Framework web** | Django |
| **Base de données** | SQLite (défaut) / PostgreSQL |
| **Front-end** | HTML5, CSS3, JavaScript, Bootstrap |
| **Modélisation** | UML (StarUML) |
| **IDE** | Visual Studio Code |

---

## 🧩 Fonctionnalités principales

### 🔐 Authentification
- Connexion sécurisée via un écran de login.
- Différents niveaux d’accès : **Administrateur** / **Responsable de stock**.

### 📦 Gestion des Produits
- Ajouter, modifier et supprimer des produits.
- Association avec des fournisseurs.
- Mise à jour automatique du stock après chaque vente.

### 👥 Gestion des Clients et Fournisseurs
- CRUD complet pour les clients et fournisseurs.
- Vérification de doublons avant enregistrement.

### 🧾 Gestion des Ventes
- Création de commandes clients.
- Déduction automatique du stock après paiement.
- Historique complet des ventes et paiements.

### 📊 Tableau de bord & Historique
- Visualisation des stocks en temps réel.
- Historique des commandes et mouvements d’articles.
- Recherche rapide et filtrage par nom.

---

## 🧠 Modélisation UML (extraits du rapport)

### 📘 Diagramme de cas d’utilisation
- Gestion des utilisateurs
- Gestion des produits
- Gestion des clients
- Gestion des fournisseurs
- Consultation du stock

### 📗 Diagramme de séquence
- Authentification
- Gestion des ventes
- Gestion des stocks

### 📙 Diagramme de classes
- Relations entre les entités : `Client`, `Produit`, `Stock`, `Fournisseur`, `Commande`, `HistCommande`.

---

## 💻 Installation et exécution

### 1️⃣ Cloner le dépôt
git clone https://github.com/Ayaaa9/Stock-Management-Application.git
cd Stock-Management-Application

2️⃣ Créer et activer un environnement virtuel
python -m venv myvenv
myvenv\Scripts\activate  # sous Windows
source myvenv/bin/activate  # sous Linux/Mac

3️⃣ Installer les dépendances
pip install -r requirements.txt

4️⃣ Démarrer le serveur
python manage.py runserver
Accéder à l’application : 👉 http://127.0.0.1:8000/

📸 Interfaces principales
Login : aze
Password : aze

Produits : Liste, ajout, modification, suppression

Clients / Fournisseurs : Gestion complète

Caisse / Vente : Enregistrement et validation des commandes

Historique des ventes : Suivi et consultation

(Captures disponibles dans le dossier static/ ou dans le rapport PDF.)

📈 Perspectives d’évolution
Ajout de tableaux de bord analytiques (statistiques et graphiques).

Intégration d’un module d’alertes automatiques par e-mail pour les stocks bas.

Amélioration de la sécurité et du système d’authentification.

Déploiement sur une plateforme cloud (Render, Railway ou Heroku).

🏁 Conclusion
Ce projet démontre la capacité de concevoir et implémenter une application complète de gestion de stock en utilisant des technologies modernes.
Il combine rigueur d’analyse (UML), qualité du code (Django), et design simple et intuitif (Bootstrap).
L’application peut être facilement adaptée à d’autres domaines (pharmacies, magasins, librairies…).

📄 Licence
Ce projet est publié sous licence MIT.
Vous êtes libre de l’utiliser, le modifier et le redistribuer avec mention des auteurs originaux.
