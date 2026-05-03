# Microsoft-Entra-ID
Microsoft Entra ID

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Microsoft Entra ID — Enterprise Lab</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 40px;
    line-height: 1.6;
    background-color: #f9f9f9;
}
h1, h2, h3 {
    color: #333;
}
pre {
    background: #222;
    color: #0f0;
    padding: 15px;
    overflow-x: auto;
}
.section {
    background: #fff;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
    box-shadow: 0 0 5px rgba(0,0,0,0.1);
}
</style>
</head>
<body>

<h1>🧪 Microsoft Entra ID — Enterprise Lab</h1>

<div class="section">
<h2>📁 Structure du projet</h2>
<pre>
EntraID-Enterprise-Lab/

│
├── README.md
│
├── 00-Overview/
│   ├── objectives.md
│   ├── environment.md
│   ├── architecture.md
│
├── 01-Users/
│   ├── create-users.md
│   ├── password-management.md
│   ├── lifecycle.md
│   ├── screenshots/
│
├── 02-Groups/
│   ├── groups-creation.md
│   ├── membership.md
│   ├── owners.md
│   ├── screenshots/
│
├── 03-Roles/
│   ├── role-assignment.md
│   ├── helpdesk-admin.md
│   ├── least-privilege.md
│   ├── screenshots/
│
├── 04-Security-MFA/
│   ├── mfa-setup.md
│   ├── conditional-access.md
│   ├── testing.md
│   ├── screenshots/
│
├── 05-Helpdesk-Scenarios/
│   ├── login-issue.md
│   ├── mfa-issue.md
│   ├── account-disabled.md
│   ├── access-denied.md
│
├── 06-Troubleshooting/
│   ├── methodology.md
│   ├── decision-tree.md
│   ├── common-issues.md
│
└── 07-Evidence/
    ├── users/
    ├── groups/
    ├── mfa/
    ├── roles/
</pre>
</div>

<div class="section">
<h2>🎯 Objectif</h2>
<p>
Ce projet simule un environnement d’entreprise en utilisant Microsoft Entra ID afin de développer des compétences en gestion des identités, sécurité et support technique IT.
</p>
</div>

<div class="section">
<h2>🏢 Environnement</h2>
<ul>
<li>IT</li>
<li>RH</li>
<li>Finance</li>
<li>TR (Training)</li>
</ul>
</div>

<div class="section">
<h2>🧠 Architecture</h2>
<p>Users → Groups → Roles → Security (MFA)</p>
</div>

<div class="section">
<h2>🔧 Compétences couvertes</h2>
<ul>
<li>Gestion des utilisateurs</li>
<li>Gestion des groupes</li>
<li>Attribution des rôles</li>
<li>Sécurité (MFA, Conditional Access)</li>
<li>Troubleshooting help desk</li>
</ul>
</div>

<div class="section">
<h2>🧪 Scénarios simulés</h2>
<ul>
<li>Login failure</li>
<li>MFA blocked</li>
<li>Account disabled</li>
<li>Access denied</li>
</ul>
</div>

<div class="section">
<h2>📸 Evidence</h2>
<p>Voir dossier /07-Evidence</p>
</div>

<div class="section">
<h2>👤 Gestion des utilisateurs</h2>

<h3>Création</h3>
<ul>
<li>ItUser</li>
<li>RhUser</li>
<li>financeuser</li>
<li>TrUser</li>
</ul>

<h3>Sécurité</h3>
<ul>
<li>Mot de passe temporaire</li>
<li>Require password change at next login</li>
</ul>

<h3>Lifecycle</h3>
<ul>
<li>Reset password</li>
<li>Block sign-in</li>
<li>Enable user</li>
<li>Delete user</li>
<li>Restore user</li>
</ul>
</div>

<div class="section">
<h2>👥 Gestion des groupes</h2>

<h3>Groupes créés</h3>
<ul>
<li>IT</li>
<li>HR</li>
<li>Finance</li>
<li>TR</li>
</ul>

<h3>Actions</h3>
<ul>
<li>Ajouter membres</li>
<li>Retirer membres</li>
<li>Assign owners</li>
</ul>

<h3>Logique</h3>
<p>User → Group → Access</p>
</div>

<div class="section">
<h2>🛡️ Rôles administratifs</h2>

<h3>Assignation</h3>
<ul>
<li>Helpdesk Administrator → IT user</li>
</ul>

<h3>Concepts</h3>
<ul>
<li>Least privilege</li>
<li>Role ≠ Group</li>
</ul>
</div>

<div class="section">
<h2>🔐 Sécurité</h2>

<h3>MFA</h3>
<ul>
<li>Activation MFA</li>
<li>Test login</li>
</ul>

<h3>Conditional Access</h3>
<ul>
<li>Policy : Require MFA</li>
<li>Scope : Users / Groups</li>
</ul>

<h3>Scénarios</h3>
<ul>
<li>Reset MFA</li>
<li>User blocked</li>
</ul>
</div>

<div class="section">
<h2>🧪 Scénarios</h2>
<ul>
<li>Login issue → Reset password</li>
<li>MFA issue → Reset MFA</li>
<li>Account disabled → Enable account</li>
<li>Access denied → Check group</li>
</ul>
</div>

<div class="section">
<h2>🧠 Méthodologie</h2>
<p>User → Password → MFA → Group → Role → Access</p>
</div>

</body>
</html>
