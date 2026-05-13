## Cycle de vie utilisateur

Actions :
- Block sign-in
- Enable user
- Delete user
- Restore user

### Block sign-in
- Test : accès refusé
- Cas : départ employé

### Enable user
![Restore user](./images/users_delete_steps.png)

- Test : accès OK
- Cas : retour employé

### Delete user
![Restore user](./images/users_delete_steps.png)
![Restore user](./images/User_deja_supprime.png)

![Restore user](./images/USERS_DELETED.png)

- Test : compte supprimé
- Cas : suppression RH

### Restore user
![Restore user](./images/User_restores.png)
- Test : compte restauré
- Cas : erreur suppression

### Cas réel
Employé quitte -> disable account