## Accès Teams

### Objectif
Rétablir l’accès à Microsoft Teams

### 🔍 Analyse (toujours en premier)
Dans Microsoft Entra ID ou Microsoft 365 Admin Center

✔️ Vérifier :
- Licence Microsoft 365 assignée
- User dans un groupe licencié
- Teams activé dans la licence

### 🛠️ Correction (selon le problème)

#### Cas A — Pas de licence
Dans Microsoft 365 Admin Center :
- Users → Active users  
- Licenses and apps  
- Ajouter licence  

#### Cas B — Licence par groupe
Dans Microsoft Entra ID :
- Groups  
- Ouvrir groupe licencié  
- Add member → user  

#### Cas C — Teams désactivé
Dans la licence :
- Activer Microsoft Teams (ON)

### ⏳ Attente
- Attendre 5 à 15 minutes  
- Se déconnecter / reconnecter  

### ✅ Résultat
- User voit Teams  
- Accès aux équipes  
- Chat + réunions fonctionnent  

### 📌 Cas réel
User rejoint une équipe → besoin de Microsoft Teams

<gif>:lemplacelt ou le gif de ces etapes
