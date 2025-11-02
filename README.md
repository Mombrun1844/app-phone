
GESTION DE STOCK ET VENTE (ANDROID)
===================================

Ce dépôt contient le projet Flutter pour l'application mobile "Gestion de Stock et Vente" (locale, HTG).

Objectif: obtenir un fichier APK installable sans config locale complexe en utilisant GitHub Actions (CI) pour builder l'APK.

Étapes simples (si tu veux que je le fasse pour toi):
1) Crée un compte GitHub (https://github.com) si tu n'en as pas.
2) Crée un nouveau dépôt GitHub (nom: gestion_stock_vente) et **uploade** le contenu de ce dossier (tous les fichiers).
   - Tu peux zipper et uploader via l'interface ou utiliser Git depuis ton PC.
3) Sur GitHub, va dans l'onglet **Actions** du dépôt et tu verras le workflow "Build APK".
   Clique sur **Run workflow** ou pousse un commit sur la branche `main`.
4) Après l'exécution, dans l'onglet Actions -> Build APK -> sélectionne la run, puis **Artifacts** -> télécharge `app-release-apk` (APK).
5) Transfère l'APK sur ton téléphone et installe-le (autoriser l'installation d'apps inconnues si demandé).

Remarques:
- L'APK généré par ce workflow est non signé (pour tests). Pour publier sur Google Play, il faut créer une clé de signature et configurer les secrets pour signer l'APK.
- Si tu préfères, je peux t'aider pas-à-pas à pousser ce projet sur GitHub et à récupérer l'APK — dis-moi et je t'accompagne étape par étape.
- Security: SMTP password will be stored locally in app storage if you enable email alerts. Consider using secure storage (I can add this).

Si tu veux, je peux aussi préparer une version complète avec écran vente, formulaires, et packaging iOS. Dis-moi si tu veux que je prépare ces fichiers supplémentaires maintenant.
