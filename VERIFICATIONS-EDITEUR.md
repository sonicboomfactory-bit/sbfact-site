# Vérifier la politique avec le jeu

Les données connues : jeu Android gratuit, AdMob/Mobile Ads, annonces Rewarded et éventuellement Interstitial, UMP et GameAnalytics. Le code, les versions des SDK et les tableaux de bord n’ont pas été audités.

Avant de supprimer la mention de préparation des pages :

- Vérifier que le nom d’éditeur est cohérent avec Google Play et que l’adresse email fonctionne. Si SBFact est uniquement une marque, identifier correctement l’éditeur/responsable légal selon votre situation ; aucune identité personnelle ou adresse n’a été inventée.
- Confirmer les formats publicitaires effectivement activés et les éventuels SDK de médiation supplémentaires. S’il y en a, les ajouter à la politique et à la déclaration Play.
- Relever les données et événements GameAnalytics réellement envoyés, les identifiants et permissions des SDK. Préciser le texte si la configuration diffère ou collecte d’autres données.
- Tester le formulaire UMP, le refus et le retour aux options de confidentialité. Ajouter une entrée visible et utilisable dans le jeu lorsque requise. Mettre les deux politiques à jour avec le chemin exact du menu une fois connu.
- Vérifier séparément GameAnalytics : information, choix analytique, blocage de la collecte avant consentement requis et arrêt après retrait. UMP seul ne garantit pas cela. Ne pas affirmer l’existence d’un bouton d’opt-out absent du jeu.
- Confirmer les bases légales effectivement retenues, les contrats des fournisseurs, destinataires/transferts et les durées de conservation des données et éventuels exports détenus par SBFact. La politique signale honnêtement que les délais propres au jeu ne sont pas encore établis ; les préciser après cette vérification.
- Confirmer la tranche d’âge déclarée dans Play et les réglages enfants/âge de consentement si applicables. Les fichiers ne supposent pas que le jeu vise ou exclut les enfants.
- Vérifier toute fonctionnalité supplémentaire (compte, achat, cloud, support intégré). Aucune absence de ces fonctions n’est promise dans les pages.
- Harmoniser politique, rubrique Sécurité des données, écrans de consentement et comportement de l’APK publié.

## Sources officielles consultées le 7 octobre 2026

- https://developers.google.com/admob/android/privacy/play-data-disclosure
- https://developers.google.com/admob/android/privacy
- https://policies.google.com/privacy
- https://www.gameanalytics.com/trust/privacy-faq
- https://www.gameanalytics.com/trust/privacy-notice
- https://www.gameanalytics.com/trust/eu-data-processing-addendum
- https://docs.gameanalytics.com/event-tracking-and-integrations/data-retention-and-limits/data-retention-practices/
- https://support.google.com/googleplay/android-developer/answer/10144311?hl=fr

Ces pages sont des références de services, pas la preuve de la configuration de BrickArrow. Les versions « upcoming » GameAnalytics n’ont pas servi à affirmer des changements déjà effectifs. La livraison prépare les fichiers ; elle ne publie pas le jeu ni le site.
