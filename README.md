Upright
=======

Simple symfony2 platform helps manage students offices and associations

Upright est une plateforme de management simple et performante dans le but de gérer les actions menées par des bureaux d'élèves ou des associations.

  * Les utilisateurs sont préenregistrés, ce sont souvent des membres ou des étudiants ajoutés par un importateur XLS ou XML. Les inscriptions sont donc fermées.
  * Les utilisateurs ont des groupes qui peuvent être dans l'ordre hiérarachique :
    * SUPERADMIN
    * ADMIN
    * SECRETARY
    * USER
  * Des ADMIN peuvent ajouter des utilisateurs à la volée
  * Chaque utilisateur a un profil avec un QRCode
  * Un utilisateur peut modifier ses infos principales
  * Un utilisateur ajouté doit recevoir un mail pour changer ses identifiants

  * Une gestion de produit est necessaire. Ces produits peuvent être :
    * Event
    * Apparel
    * Goodies
  * La vente en ligne n'est pas autorisée, la vente se fait par échange B2C physique en étudiant et secrétaire/admin
  * Le gérant crée alors une nouvelle transaction entre le produit et l'utilisateur
  * Les stocks sont alors mis à jour

  * Des mails simple doivent être pouvoir envoyé
  * Il faut pouvoir attribuer des mailinglist à des utilisateurs
  * Des mailinglists doivent être auto configurée en fonction des caractéristiques d'un utilisateur (promotions, associations...)
  
  * La partie gestion visible par les secrétaire/admin doit regrouper les dernière transactions et des statistiques simples de compte
  * Les actions ci-dessous doivent être mise en évidence :
    * Utilisateurs
    * Nouvelle transaction
    * Nouveau mail
