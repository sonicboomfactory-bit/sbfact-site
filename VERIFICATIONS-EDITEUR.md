# Vérifications éditeur — BrickArrow

Préparation du 8 octobre 2026. Aucun AAB, APK, code du jeu ou tableau de bord AdMob n’a été inspecté.

## Informations utilisées

- Votre contexte indique AdMob / Mobile Ads, UMP, des publicités interstitielles et récompensées et des sauvegardes locales.
- GameAnalytics inactif dans la Release repose sur votre déclaration, pas sur une analyse binaire.
- L’archive brickarrow-politiques-corrigees.zip fournit les textes FR/EN. Les affirmations sur le chargement au démarrage, la présence du SDK GameAnalytics et ses clés ont été retirées faute de vérification.
- Aucun identifiant éditeur, lien Play Store, menu exact, délai de conservation ou tranche d’âge n’a été inventé.

## Avant l’enregistrement définitif dans Play

1. Relever les versions des SDK réellement distribués et les éventuels partenaires de médiation. La documentation Mobile Ads décrit une version et une configuration données ; elle ne prouve pas la configuration de votre Release.
2. Vérifier GameAnalytics dans la Release et tous les autres flux du jeu.
3. Tester UMP : actualisation des informations de consentement, formulaire requis, autorisation de demander des annonces, refus et modification des choix. Fournir une entrée d’options visible et utilisable lorsque requise.
4. Confirmer les réponses Data Safety selon les traitements réels : position approximative via IP, interactions, diagnostics et identifiants sont documentés pour Mobile Ads standard. La catégorie « Autres données de performance » nécessite une correspondance justifiée avec les données du SDK utilisé ; ne pas la cocher ou décocher automatiquement.
5. Ne pas déduire une collecte entièrement facultative du seul formulaire UMP ou du caractère volontaire des annonces récompensées.
6. Le chiffrement TLS indiqué par Google concerne Mobile Ads. Vérifier tous les autres flux avant d’affirmer un chiffrement global.
7. Tester la réception des demandes par email et la procédure réelle de suppression ; effacer les sauvegardes locales n’efface pas les données transmises à Google.
8. Confirmer l’identité du responsable, les bases légales, les destinataires, les transferts, les durées de conservation et le public visé selon votre situation. Les textes proposés ne constituent pas une certification de conformité juridique.
9. Harmoniser les réponses Play, les politiques FR/EN et le comportement du jeu. Conserver le formulaire en brouillon tant que les points nécessaires restent incertains.

## Références officielles consultées

- Google Mobile Ads : https://developers.google.com/admob/android/privacy/play-data-disclosure
- Google UMP : https://developers.google.com/admob/android/privacy
- Google Play Data Safety : https://support.google.com/googleplay/android-developer/answer/10787469?hl=en

Le site statique n’ajoute aucun tracker, script publicitaire, formulaire, cookie ou stockage local. L’hébergeur conserve ses propres pratiques techniques.
