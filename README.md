# Menhir Control

Menhir Control transforme un téléphone ou une tablette Android en panneau de contrôle pour Windows et les jeux.

[**Télécharger la bêta APK + Windows du 14 novembre 2026**](https://github.com/sebastiensanchez83-stack/menhir-control-releases/releases/tag/v0.1.0-beta.20261114)

Ce dépôt distribue les exécutables et les guides. Les profils, associations et autorisations personnelles ne sont pas inclus.

## Installation

1. Téléchargez le ZIP de la release et extrayez-le entièrement.
2. Sur Windows x64, lancez `Windows/MenhirControl.exe` en conservant tous les fichiers de ce dossier. Le runtime Microsoft Edge WebView2 Evergreen doit être installé.
3. Sur Android 10 ou plus récent, installez `Android/MenhirControl.apk`.
4. Connectez le téléphone et le PC au même réseau local, puis utilisez le QR code ou le code OTP affiché par Menhir.
5. Consultez le dossier `Guides` de l’archive pour la connexion, les pages et Discord.

Mise à jour : quittez Menhir par son icône près de l’horloge Windows, remplacez le dossier portable et relancez-le. Installez l’APK par-dessus la version précédente. Les données locales et associations sont conservées ; une sauvegarde de vos profils reste recommandée avant un changement de version.

## Pages partagées

Dans le Studio Windows, sélectionnez la page principale, ouvrez **Partager cette page**, cochez les profils destinataires et cliquez sur **Publier**. Les boutons, logos, actions et positions suivent ensuite la source. **Modifier la page principale** rejoint la source ; **Rendre indépendante** conserve une copie sans synchronisation.

Les commandes clavier propres à un jeu restent locales. Limite actuelle : huit pages par profil. Les anciennes versions Windows ne comprennent pas les liens de pages.

## Discord

Les bascules micro et sourdine fonctionnent en arrière-plan après configuration des raccourcis globaux dans Discord : **Ctrl + Maj + M** pour le micro et **Ctrl + Maj + D** pour la sourdine. Les commandes de navigation affichent Discord avant d’agir.

L’affichage du salon, de l’état micro et des personnes qui parlent reste expérimental et dépend des autorisations accordées par Discord. La validation réalisée avec un compte personnel ne constitue pas une autorisation générale pour tous les comptes.

## Statut de cette distribution

Bêta de test : application Windows non signée et APK signé avec une clé de développement. La release est marquée **Pre-release**. Il ne s’agit pas d’un installateur Windows autonome : conservez le dossier Windows complet.

Site : [menhir-racing.fr](https://menhir-racing.fr/applications).
