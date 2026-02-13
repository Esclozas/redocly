---
title: Règles d’utilisation d’un OTP
description: Bonnes pratiques et contraintes liées à l’utilisation d’un code à usage unique (OTP) dans le processus d’authentification.
---

# 🔐 Règles d’utilisation d’un OTP

Ce guide présente les règles à suivre pour l’utilisation d’un code OTP (*One-Time Password*) dans le cadre du processus d’authentification.

---
 
## 1. ⏱️ Durée de validité du code

ahlalalala

Une fois généré et envoyé, le code OTP reste **valable pendant 15 minutes**.

Après ce délai :
- le code n’est plus utilisable ;
- l’utilisateur doit **générer un nouveau code** pour se reconnecter.

> ⚠️ **Attention :** Les codes expirés ne peuvent pas être réactivés.  
> Un nouvel OTP doit toujours être demandé.

---

## 2. ✉️ Génération du code lors de l’accès via Magic Link

Un code OTP est généré **uniquement lors du premier clic** sur le *magic link*.

Si vous cliquez à nouveau sur le même lien :
- un nouveau code **ne sera pas renvoyé automatiquement** ;
- vous devez **demander explicitement un renvoi** pour obtenir un nouveau code.

> 💡 **Bon à savoir :** Le *magic link* ne peut être utilisé qu’une seule fois pour générer un OTP actif.

---

## 3. 🔁 Réutilisation du code pendant la durée de validité

Même si le code est encore valide (dans la limite des 15 minutes), il **ne peut pas être utilisé plusieurs fois**.

Chaque tentative de connexion nécessite un **nouveau code OTP**.

---

## 4. 🚫 Validité après utilisation

Tout code OTP devient **immédiatement invalide** après sa première utilisation.

Il **ne peut donc pas être réutilisé**, même s’il reste dans la période de validité.

---

## 📋 En résumé

| **Règle**              | **Description** |
|--------------------------|----------------|
| **Durée de validité**   | 15 minutes maximum |
| **Envoi du code**       | Une seule fois à la génération initiale |
| **Réutilisation**       | Non, usage unique |
| **Après utilisation**   | Le code est immédiatement invalide |

---

> 🛡️ **Conseil de sécurité :**  
> Ne partagez jamais votre code OTP.  
> Il est strictement personnel et à usage unique.

