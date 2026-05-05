## Ticket 002 - Problème d’authentification multifacteur

### Problème
Utilisateur bloqué par l’authentification multifacteur (MFA)

---

### 🔍 Enquête
Dans Microsoft Entra ID :

✔️ Vérifier :
- Méthodes MFA manquantes ou invalides  
- Authenticator non configuré ou perdu  
- Téléphone non accessible  
- Politique MFA obligatoire activée  

---

### 🛠️ Résolution

Dans :contentReference[oaicite:0]{index=0} :

- Users → sélectionner l’utilisateur  
- Authentication methods  
- Cliquer **Require re-register MFA**  

OU

- Supprimer les méthodes MFA existantes  
- Forcer une nouvelle configuration à la prochaine connexion  

---

### ⏳ Résultat
- MFA réinitialisé  
- L’utilisateur doit reconfigurer son authentification  
- Accès à Microsoft 365 restauré  

---

### 📌 Cas réel
Utilisateur bloqué après changement de téléphone ou perte de Microsoft Authenticator

---

### 🎬 Démonstration
<gif>: En Préparation
