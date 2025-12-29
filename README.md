# 🏠 RealEstate Pro - Système d'Annonces Immobilières
## 🚀 Sprint 1 : Visiteur & Découverte

<div align="center">
  <p><strong>Réalisé par :</strong> Ayoub JALYTA</p>
  <p><strong>Encadré par :</strong> M. ESSARRAJ Fouad</p>
</div>

---

### 📖 Introduction et Contexte Général
Le projet **RealEstate Pro** est une plateforme web moderne conçue pour la gestion professionnelle d'annonces immobilières. Elle permet de centraliser les offres, d'assurer la qualité des données et de faciliter la mise en relation entre agents et acquéreurs.

**La problématique :**
La gestion manuelle ou via des réseaux sociaux manque de rigueur (validation des données), de recherche avancée (filtres précis) et de suivi efficace des demandes de contact.

**La solution :**
Un système robuste avec un workflow d'approbation administrateur, une recherche multicritères intuitive et une interface responsive pour une expérience utilisateur premium.

---

### 🔍 Analyse des Besoins
1.  **Gestion de Qualité :** Toutes les annonces doivent être approuvées par un admin avant publication.
2.  **Accessibilité Publique :** Recherche avancée (Prix, Ville, Type de bien, Chambres).
3.  **Conversion client :** Formulaires de contact directs liés aux propriétés spécifiques.
4.  **Rôles & Sécurité :** Distinction claire entre Admin (supervision), Assistant (création) et Visiteur (consultation).

---

### ⚙️ Méthodologies Employées

#### 🏃 Méthode Scrum
Structure en sprints de 2 semaines pour ce projet :
*   **Sprint 1 :** Portail Public & Recherche.

<p align="center">
  <img src="./assets/scrum.jpg" alt="Méthode Scrum" width="600">
</p>

#### 🔍 Recherche & Inspiration
Analyse de plateformes existantes :
*   **PropertyFinder**
*   **Avito Immobilier**
*   **Leboncoin Immobilier**

**Objectif :** Adopter les meilleures pratiques UX/UI tout en gardant une solution simple et efficace.
---

### 🎯 Détails du Sprint 1 : Portail Web Public
Ce premier sprint se concentre sur l'expérience du visiteur anonyme (le futur acquéreur).

**Fonctionnalités clés :**
*   **Moteur de Recherche :** Filtrage par prix, localisation et type de bien.
*   **Galerie de Propriétés :** Affichage optimisé des annonces actives.
*   **Page de Détails :** Vue immersive avec photos haute résolution et caractéristiques techniques.
*   **Inquiry System :** Formulaire "Contactez-nous à propos de ce bien".

---

### 🛠️ Travail Réalisé
**Focus Principal : Développement du Portail Public**
*   **Réalisation de la Page "Property Details" :** Développement complet de la fiche produit intégrant :
    *   Galerie d'images immersive.
    *   Grille d'informations techniques (info-grid).
    *   Composants de contact (contact-card) et Breadcrumb.

#### 🧪 Lab
*   **Laravel Deployment** Framework backend pour sa solidité et sa gestion des Policies.

#### 📐 Maquettes et Tests Utilisateurs
*   **Maquette clé :** Page `Property_details` avec UX moderne.
*   **Outils :** Figma / Tailwind CSS, Lucide Icons.

<p align="center">
  <img src="./assets/maquette_property_details.png" alt="Maquette RealEstate Pro" width="1000">
  <br>
  <em>Maquette de la Page Détails des Propriétés</em>
</p>

---

### 🔎 Fonctionnalités de la Page Articles (Annonces)
Le flux utilisateur suit le diagramme de cas d'utilisation conçu pour ce sprint :
*   **Acteurs :** Visiteur / Public.
*   **Flux :** Recherche → Sélection → Consultation des caractéristiques → Contact.

<p align="center">
  <img src="./assets/use_case_diagram.png" alt="Use Case Real Estate" width="600">
  <br>
  <em>Diagramme de Cas d'Utilisation - Sprint 1</em>
</p>

**Fonctionnalités Détaillées :**
*   **Recherche Globale :** Filtrage en temps réel.
*   **Service de Détails :** Récupération dynamique des données (Prix, Surface, Équipements).
*   **Navigation Intuitive :** Fil d'ariane pour un retour fluide à la liste des biens.


---
<div align="center">
  <p><em>© 2025 - RealEstate Pro - Sprint 1</em></p>
</div>