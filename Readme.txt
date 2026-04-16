# 📦 StockManager CI

## 📌 Description

StockManager CI est une application de gestion de stock développée en Java avec le Professeur ATTA  FERDINAND 
dans le cadre d’un projet de fin de module.  
Elle permet de gérer efficacement les produits, les fournisseurs et les mouvements de stock à travers une interface graphique moderne.

---

## 🎯 Objectifs du projet

- Concevoir une application complète en Java
- Implémenter une interface graphique avec JavaFX
- Gérer une base de données avec MySQL
- Mettre en place un système de gestion de stock
- Créer un tableau de bord dynamique

---

## ⚙️ Technologies utilisées

- **Java (JDK 21)**
- **JavaFX** (interface graphique)
- **MySQL** (base de données)
- **JDBC** (connexion BD)
- **Maven** (gestion du projet)
- **Architecture DAO** (Data Access Object)

---

## 🏗️ Architecture du projet

Le projet suit une architecture inspirée du modèle MVC :

- **Model** : classes `Produit`, `Fournisseur`, `Mouvement`
- **DAO** : accès aux données (`ProduitDAO`, `FournisseurDAO`, `MouvementDAO`)
- **View** : interfaces JavaFX
- **Controller** : `MainApp`

---

## 🗄️ Base de données

### Tables principales :

- `produits`
- `fournisseurs`
- `mouvements`

### Fonctionnalités BD :

- Gestion des stocks
- Historique des mouvements
- Calcul du stock critique

---

## 🚀 Fonctionnalités

### 📦 Gestion des produits
- Ajouter un produit
- Modifier un produit
- Supprimer un produit
- Pagination des résultats

### 👨‍💼 Gestion des fournisseurs
- Ajouter un fournisseur
- Afficher la liste des fournisseurs

### 🔄 Gestion des mouvements
- Entrée de stock
- Sortie de stock
- Historique des mouvements

### 📊 Tableau de bord
- Nombre de produits
- Nombre de fournisseurs
- Nombre de mouvements
- Stock critique
- Graphique dynamique

### 📁 Export
- Export en PDF
- Export en Excel

---

## 🔐 Gestion des rôles

- **ADMIN**
  - Accès complet (ajout, modification, suppression)
- **UTILISATEUR**
  - Accès limité (consultation uniquement)

---

## 🖥️ Installation et exécution

### 1. Prérequis

- Java JDK 21
- MySQL
- Maven (optionnel si projet déjà compilé)

---

### 2. Base de données

- Créer une base MySQL
- Importer le fichier `base.sql`

---

### 3. Lancer le projet

#### Option 1 : IntelliJ / IDE
- Ouvrir le projet
- Lancer `MainApp.java`

#### Option 2 : Version portable
- Double-cliquer sur :