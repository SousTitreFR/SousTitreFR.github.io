# Politique de confidentialité de SousTitreFR

*Dernière mise à jour : 25 octobre 2026*

Cette page explique quelles données le bot SousTitreFR traite, pourquoi, et combien de temps il les garde. En résumé : **le bot collecte le strict minimum, ne lit pas les messages de ton serveur et ne vend ni ne partage aucune donnée.**

## 1. Ce que le bot ne collecte pas

Le bot **ne lit pas** les messages publiés sur ton serveur Discord : il n'a pas accès à leur contenu. Il ne collecte pas non plus :

- la liste des membres du serveur ;
- les statuts en ligne ou les activités ;
- les adresses e-mail, les adresses IP ni aucune autre information de compte.

Il ne reçoit que les commandes qui lui sont adressées directement (`/last`, `/search`, `/status`, `/setup`, `/unsetup`).

## 2. Données enregistrées

| Donnée | Quand | Pourquoi | Durée de conservation |
|---|---|---|---|
| Identifiant du serveur et identifiant du salon d'annonce | `/setup` | Savoir où publier les annonces | Jusqu'à `/unsetup`, le retrait du bot du serveur ou la suppression du salon : elle est alors effacée automatiquement |
| Nom d'utilisateur Discord, nom du serveur et nom du salon | `/setup` et `/unsetup` | Journal technique (savoir qui a activé ou arrêté les annonces) | Journal système du serveur, effacé automatiquement par rotation |
| Pseudo IRC et texte de la commande | Commandes `!last`, `!search`, `!status` sur IRC | Journal technique (diagnostic, lutte contre les abus) | Journal système du serveur, effacé automatiquement par rotation |
| Messages d'erreur techniques | En cas de panne | Diagnostic | Journal système du serveur, effacé automatiquement par rotation |

Les termes saisis dans `/search` sur Discord ne sont pas enregistrés : ils servent uniquement à produire la réponse.

Le bot conserve aussi l'historique des sous-titres annoncés (titre, lien, date). Ce sont des informations publiques issues des sites de sous-titres. Elles ne concernent aucun utilisateur.

## 3. Utilisation et partage

Les données ne servent qu'au fonctionnement du bot. Elles ne sont **ni vendues, ni louées, ni partagées** avec des tiers, et ne servent à aucune publicité ni à aucun profilage.

Elles sont stockées sur le serveur privé qui fait tourner le bot, accessible au seul exploitant.

Discord traite de son côté les données liées à ton utilisation de sa plateforme, y compris les commandes que tu envoies, selon sa propre [politique de confidentialité](https://discord.com/privacy).

## 4. Tes droits

Tu peux à tout moment :

- **arrêter le traitement pour ton serveur** : utilise `/unsetup` ou retire le bot du serveur. L'identifiant du serveur et celui du salon sont alors supprimés immédiatement ;
- **demander l'accès à tes données ou leur suppression**, y compris dans les journaux techniques, en ouvrant un ticket sur <https://github.com/SousTitreFR/SousTitreFR.github.io/issues>.

Si tu résides dans l'Union européenne, tu disposes aussi des droits prévus par le RGPD (accès, rectification, effacement, opposition), et tu peux saisir l'autorité de protection des données de ton pays (en France, la [CNIL](https://www.cnil.fr)).

## 5. Modifications

Cette politique peut évoluer. La date de dernière mise à jour figure en haut de cette page.

## 6. Contact

<https://github.com/SousTitreFR/SousTitreFR.github.io/issues>
