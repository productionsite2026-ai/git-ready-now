# Cahier des Charges Fonctionnel – Plateforme DogWalking

## 1. Vision Stratégique et Concept Fondamental

DogWalking s'établit comme la plateforme de référence en France pour la mise en relation entre les propriétaires d'animaux et des **Accompagnateurs Certifiés**. Contrairement aux modèles traditionnels de mise en relation, DogWalking repose sur un triptyque de valeurs non négociables : la **Confiance Vérifiée**, la **Transparence Totale** et la **Preuve de Service**. L'objectif est de lever toute incertitude liée à l'accompagnement animalier en imposant des standards de sécurité et de validation uniques sur le marché.

Le concept de "Confiance Vérifiée" se manifeste par une sélection manuelle rigoureuse de chaque candidat, visant un taux d'acceptation cible de **35%**. Cette sélectivité garantit que seuls les profils les plus qualifiés et fiables accèdent à la plateforme. La sécurité financière est assurée par un système de **paiement par séquestre**, où les fonds sont bloqués dès la réservation et ne sont libérés qu'après la validation finale du propriétaire via un **code unique**. Enfin, la plateforme privilégie la **Preuve Visuelle Obligatoire** (photos et vidéos de prise en charge et de fin de mission) au détriment du suivi GPS intrusif, offrant ainsi une garantie concrète et humaine de la réalisation du service.

---

## 2. Architecture du Projet et Structure Numérique

Pour garantir une expérience utilisateur fluide et une gestion optimale des différents flux, le projet DogWalking est structuré autour de trois piliers numériques distincts, chacun répondant à des objectifs spécifiques.

| Entité | URL Cible | Public Cible | Objectifs Principaux |
| :--- | :--- | :--- | :--- |
| **Site Public** | dogwalking.fr | Prospect, Public, SEO | Marketing, Information, Référencement, Conversion. |
| **Application** | app.dogwalking.fr | Propriétaires & Accompagnateurs | Gestion des missions, Réservations, Paiements, Outil "GO". |
| **Administration** | admin.dogwalking.fr | Équipe Interne Manus | Modération, Validation CNI/B2, Suivi financier, Litiges. |

---

## 3. Spécifications du Site Public (dogwalking.fr)

Le site public constitue la vitrine technologique et marketing de DogWalking. Il doit rassurer l'utilisateur dès les premières secondes de navigation en mettant en avant les garanties de sécurité et la simplicité du processus.

La **Page d'Accueil** présente le concept innovant de la plateforme et permet une recherche rapide d'Accompagnateurs à proximité. La **Page Services** détaille les quatre types de prestations proposées (Promenade, Garde, Visite, Soins) en utilisant systématiquement la mention "À partir de..." pour refléter la liberté tarifaire des prestataires. La **Page Tarifs** joue un rôle pédagogique crucial en expliquant le fonctionnement du séquestre, la commission de **15%** (dont 85% reversés à l'Accompagnateur) et la protection incluse. Enfin, la section **À propos / Concept** expose la mission de l'entreprise et le sérieux du processus de sélection manuel effectué par nos experts.

---

## 4. Spécifications de l'Application et de l'Outil "GO" (app.dogwalking.fr)

L'application est le cœur opérationnel du projet, gérant l'intégralité du cycle de vie d'une mission, de la réservation à la libération des fonds.

### 4.1 Dashboard Propriétaire
Le propriétaire dispose d'un espace dédié pour gérer le profil de ses chiens (nom, race, tempérament, besoins spécifiques). Lors d'une réservation, le système procède au blocage des fonds en séquestre. Un **code unique de validation** est généré pour chaque mission ; ce code est la seule clé permettant de libérer le paiement à l'Accompagnateur une fois le service rendu. Le propriétaire reçoit également des notifications en temps réel incluant les preuves visuelles obligatoires envoyées par le prestataire.

### 4.2 Dashboard Accompagnateur et Outil "GO"
L'accès à l'outil "GO" est strictement conditionné à la validation manuelle préalable de la pièce d'identité (CNI) et du casier judiciaire (B2). Le flux d'une mission est strictement encadré par le protocole suivant :

| Étape | Action Requise | Impact Système |
| :--- | : :--- | :--- |
| **1. Sélection** | Choix d'une mission confirmée | Préparation de l'outil "GO". |
| **2. Départ** | **Photo de prise en charge obligatoire** | Démarrage du chronomètre de mission. |
| **3. Mission** | Envoi de preuves visuelles (photos/vidéos) | Notification en temps réel au Propriétaire. |
| **4. Clôture** | Rédaction du **Compte-rendu obligatoire** | Arrêt du chronomètre. |
| **5. Validation** | **Saisie du code unique** fourni par le client | Libération immédiate des fonds (85%). |

---

## 6. Règles de Gestion, Sécurité et Conformité

La plateforme impose des règles strictes pour garantir la sérénité de tous les utilisateurs. L'annulation d'une mission est autorisée et gratuite jusqu'à **3 heures** avant le début prévu de la prestation. La communication entre les parties est protégée : elle s'effectue via des messages pré-enregistrés avant la sécurisation du paiement, puis bascule en chat libre une fois les fonds bloqués en séquestre. Sur le plan de la conformité, DogWalking assure une protection complète pour chaque mission et garantit un respect strict du RGPD concernant les données personnelles et les documents d'identité stockés.
