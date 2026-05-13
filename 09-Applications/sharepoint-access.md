## Accès SharePoint

### Problème
L'utilisateur ne peut pas accéder à SharePoint

### 🔍 Analyse
Dans Microsoft Entra ID ou Microsoft 365 Admin Center

✔️ Vérifier :
- User dans le bon groupe
- Permissions SharePoint manquantes
- Accès site non attribué

### Solution
Dans Microsoft Entra ID :

- Groups  
- Ouvrir le groupe concerné  
- Add member → user  

Et/ou dans SharePoint :
- Ajouter user aux permissions du site (Member / Visitor)

### Résultat
- Accès SharePoint autorisé  
- User peut ouvrir sites et fichiers  
- Synchronisation OneDrive possible  

### Cas réel
Utilisateur rejoint une équipe → besoin d’accès SharePoint pour fichiers et documents

<gif>:lemplacelt ou le gif de ces étapes
