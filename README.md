# app-banque
Nous souhaitons réaliser une application permettant de gérer les compte bancaires:
 - chaque Compte est définit par un code, un solde et une date de création
 - Un Compte courant est un Compte qui possède en plus un découvert
 - Chaque Compte appartient à un Client
 - Chaque Client est défini par son code, son email, son mot de passe et son nom
 - Chaque Compte peut subir plusieur Opération
 - Il existe deux type d'opération: Versement et Retrait
 - Une Opération est définie pas son numéro, la date et le montant

   ## Enoncé
   L'application doit permettre de:
    - Gérer les Client:
      -- Ajouter un Client
      -- Consulter les Clients
      -- Consulter les Client dont le nom contient un mot clé
    - Gérer les Comptes:
      -- Ajouter un Compte
      -- Consulter un Compte
   - Gérer les Opérations
     -- Effectuer le versement d'un montant dans un Compte
     -- Effectuer le retrait d'un montant dans un Compte
     -- Consulter les Opérations d'un Compte page par page
     -- 
