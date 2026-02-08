# Politique de confidentialité — Solya

**Date d'entrée en vigueur : 8 février 2026**

Solya est une application d'assistant vocal conçue pour les personnes aveugles et malvoyantes. Elle permet de gérer les emails, le calendrier, les SMS, les appels téléphoniques, les rappels, la messagerie instantanée, les notes, la météo, les actualités et la recherche web par la voix.

## 1. Données collectées et finalité

### Données audio (microphone)
- **Quoi** : Enregistrements vocaux captés via le microphone de l'appareil.
- **Pourquoi** : Reconnaissance vocale pour contrôler l'application par la voix.
- **Traitement** : Les enregistrements sont transmis en temps réel à un service de transcription vocale puis supprimés immédiatement. Aucun enregistrement audio n'est stocké sur nos serveurs.

### Emails
- **Quoi** : Contenu des emails via Gmail ou IMAP.
- **Pourquoi** : Lire, résumer et répondre aux emails par la voix.
- **Traitement** : Les emails sont traités en mémoire sur l'appareil et transmis à un service d'intelligence artificielle pour résumé et rédaction de réponses. Un cache local stocke les métadonnées des pièces jointes.

### Calendrier
- **Quoi** : Événements du calendrier Google.
- **Pourquoi** : Consulter, créer et gérer les événements par la voix.
- **Traitement** : Accès via l'API Google. Les données restent sur l'appareil.

### Contacts
- **Quoi** : Noms et numéros de téléphone du répertoire Android.
- **Pourquoi** : Passer des appels, envoyer des SMS et identifier les correspondants.
- **Traitement** : Lecture seule depuis le répertoire local. Les contacts ne sont pas transmis à des tiers.

### SMS
- **Quoi** : Messages SMS envoyés et reçus.
- **Pourquoi** : Lire et envoyer des SMS par la voix.
- **Traitement** : Accès aux SMS via les API Android. Le contenu peut être transmis à un service d'intelligence artificielle pour résumé.

### Journal d'appels
- **Quoi** : Historique des appels téléphoniques.
- **Pourquoi** : Consulter les appels manqués et rappeler des contacts.
- **Traitement** : Lecture depuis le journal d'appels Android. Les données ne sont pas transmises à des tiers.

### Localisation
- **Quoi** : Position géographique approximative ou précise.
- **Pourquoi** : Fournir la météo locale et du contexte géographique.
- **Traitement** : Transmise au service météo pour obtenir les prévisions. Non stockée.

### Applications installées
- **Quoi** : Liste des applications installées sur l'appareil.
- **Pourquoi** : Permettre le lancement d'applications par commande vocale.
- **Traitement** : Lecture locale uniquement. La liste n'est pas transmise à des tiers.

### Pièces jointes d'emails
- **Quoi** : Documents et images en pièce jointe.
- **Pourquoi** : Analyse et description vocale du contenu (OCR, vision).
- **Traitement** : Transmises à un service d'analyse de documents pour extraction de contenu (OCR, vision), puis supprimées. Un cache local temporaire est utilisé.

### Sauvegarde
- **Quoi** : Paramètres et données de l'application.
- **Pourquoi** : Permettre la restauration sur un nouvel appareil.
- **Traitement** : Sauvegarde chiffrée sur Google Drive (optionnel, à l'initiative de l'utilisateur).

## 2. Services tiers

Pour fonctionner, Solya fait appel à des services tiers dans les catégories suivantes :

- **Reconnaissance vocale** : transcription de la voix en texte (flux audio en temps réel, non conservé).
- **Synthèse vocale** : conversion du texte en parole.
- **Intelligence artificielle** : compréhension des commandes, résumé de contenus et rédaction de réponses.
- **Services Google** : accès aux emails, au calendrier et à la sauvegarde via votre compte Google.
- **Analyse de documents** : extraction de texte depuis les pièces jointes (OCR, vision).
- **Recherche web** : exécution de recherches à la demande de l'utilisateur.

Ces services sont soumis à leurs propres politiques de confidentialité. Les données transmises se limitent au strict nécessaire pour chaque fonctionnalité.

## 3. Stockage des données

- **Sur l'appareil** : Paramètres, cache de pièces jointes (SQLite), cache audio TTS, notes et rappels.
- **Sur Google Drive** : Sauvegarde chiffrée (optionnelle).
- **Aucun serveur propre** : Solya ne possède pas de serveur backend. Toutes les communications se font directement entre l'appareil et les services tiers.

## 4. Partage des données

Solya ne vend, ne loue et ne partage aucune donnée personnelle à des fins publicitaires ou commerciales. Les données ne sont transmises aux services tiers que dans le strict cadre des fonctionnalités décrites ci-dessus.

## 5. Sécurité

- Les communications avec les services tiers utilisent le protocole HTTPS (chiffrement TLS).
- L'authentification Google utilise le protocole OAuth 2.0 (aucun mot de passe Google n'est stocké par l'application).
- Les sauvegardes Google Drive sont chiffrées.

## 6. Droits des utilisateurs

Vous pouvez à tout moment :
- **Révoquer les permissions** de l'application dans les paramètres Android.
- **Révoquer l'accès Google** depuis votre compte Google (https://myaccount.google.com/permissions).
- **Supprimer les données locales** en désinstallant l'application.
- **Supprimer la sauvegarde** depuis Google Drive.

## 7. Utilisation par des mineurs

Solya n'est pas destinée aux enfants de moins de 13 ans. Nous ne collectons pas sciemment de données auprès de mineurs.

## 8. Modifications

Cette politique de confidentialité peut être mise à jour. La date d'entrée en vigueur en haut du document indique la dernière révision. L'utilisation continue de l'application après modification vaut acceptation.

## 9. Contact

Pour toute question concernant cette politique de confidentialité, contactez-nous à :
**Email** : contact@solya.app
