# Notifications de groupe dans Teams

Cocoom vous permet d’envoyer des notifications non seulement aux utilisateurs individuels, mais aussi à des groupes ou des canaux Teams.
Grâce à l’application Workflows de Microsoft Teams, vous pouvez configurer des scénarios pour diffuser automatiquement des alertes Cocoom dans un canal d’équipe ou un groupe de discussion.

Cette intégration facilite la communication collective et garantit que vos informations clés atteignent rapidement toutes les personnes concernées, directement dans leur espace de collaboration.

Ce type de notifications peut être configuré en 2 étapes principales :

1. Côté Microsoft Teams : création d'un webhook dans le canal de l'équipe ou du groupe de discussion de votre choix
2. Côté Cocoom : ajout de ce webhook à la configuration d'un fil (catégorie de contenu) de votre choix

## 1. Côté Microsoft Teams : création d'un webhook

Ouvrez Microsoft Teams et accédez à l'équipe et au canal où vous souhaitez recevoir les notifications Cocoom.

### 1.2. Sélection de l'extension

Cliquez sur les trois points à côté du nom du canal pour ouvrir le menu contextuel, puis sélectionnez "Workflows".

![Étape 1](/img/fr/guide/msteams-app/notifications/step1-workflows-menu-selection.png)

### 1.3. Sélection du type de workflow

Filtrez le type de workflow en tapant "Webhook" dans le champ de recherche.

![Étape 2](/img/fr/guide/msteams-app/notifications/step2-workflow-type-selection.png)

### 1.4. Connexion à utiliser pour les notifications

Dans la fenêtre des workflows, cliquez sur les 3 points pour sélectionner une connexion existante ou ajouter une nouvelle connexion.

Choisissez un nom pour ce workflow.

![Étape 3](/img/fr/guide/msteams-app/notifications/step3-connections.png)

### 1.5. Sélection de la destination de notification

Sélectionnez l'équipe Teams et le canal où les notifications doivent être envoyées (cas d'usage pour une notification de canal ; il existe un équivalent pour les notifications de groupe de discussion).

![Étape 4](/img/fr/guide/msteams-app/notifications/step4-notification-targeted-channel-choice.png)

### 1.6. Copier le lien Webhook

Cliquez sur le bouton "Copier le lien" pour copier l'URL du webhook dans le presse-papiers.

![Étape 5](/img/fr/guide/msteams-app/notifications/step5-link-to-copy.png)

## 2. Côté Cocoom : configurer un fil Cocoom pour notifier dans Teams

Accédez à la section d'administration, puis sélectionnez l'élément de menu "Canaux".

### 2.1. Modifier un fil Cocoom

Cliquez sur le bouton "Modifier" pour le fil Cocoom à lier à Teams pour les notifications.

### 2.2. Intégration Microsoft Teams

Faites défiler la page jusqu'à la section "Intégration avec vos outils" jusqu'à atteindre la section "Microsoft Teams"

![Étape 6](/img/fr/guide/msteams-app/notifications/step6-add-webhook-to-cocoom-channel.png)

### 2.3. Coller le lien webhook

Collez le lien "Webhooks", précédemment copié, dans le champ prévu à cet effet.

Vous pouvez ajouter un commentaire pour qualifier le lien (par exemple, le nom de l'équipe Teams et le nom du canal Teams).

### 2.4. Valider l'association

L'association est maintenant active et prête à relayer les notifications de groupe comme lors de la publication d'un nouveau mémo.

### 2.5. Vérifier l'association

Exemple de notification lorsqu'un contenu est publié dans le fil précédemment choisi.

![Étape 7](/img/fr/guide/msteams-app/notifications/step7-channel-notification-example.png)
