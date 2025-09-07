# ERD - Airbnb Database

Ce diagramme entité-association (ERD) représente le modèle de base de données pour un système similaire à Airbnb.

### Entités principales :
- **Users** : contient les informations des utilisateurs (id, nom, email, mot de passe).
- **Properties** : contient les annonces publiées par les hôtes.
- **Bookings** : représente les réservations effectuées par les utilisateurs.
- **Payments** : enregistre les paiements liés aux réservations.
- **Reviews** : stocke les évaluations et commentaires laissés par les utilisateurs.

### Relations :
- Un utilisateur peut posséder plusieurs propriétés.
- Un utilisateur peut effectuer plusieurs réservations.
- Une réservation génère un paiement et peut avoir un avis.
