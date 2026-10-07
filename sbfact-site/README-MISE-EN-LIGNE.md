# Mini-site SBFact — mise en ligne

Le site fonctionne sans installation ni compilation. Ouvrez index.html pour le consulter. Toutes les pages fonctionnent sans JavaScript. Les liens relatifs conviennent aussi à un dépôt GitHub Pages placé dans un sous-dossier.

## Avant la mise en ligne

1. Le contact sonicboomfactory@gmail.com est intégré aux trois pages. Vérifiez que cette boîte reçoit les demandes.
2. Le logo original n’était pas disponible dans la conversation récupérée. assets/logo-sbfact.svg est une signature typographique provisoire, pas une reproduction du logo choisi. Remplacez-la par votre logo ; si son format change, adaptez les trois balises img. L’illustration BrickArrow est décorative, pas une capture du jeu. Aucun détail de gameplay ni disponibilité Play Store n’a été inventé.
3. Relisez les deux politiques avec la version Android réellement distribuée. Voir VERIFICATIONS-EDITEUR.md. La politique ne prouve pas que les SDK respectent les choix. Une fois les vérifications faites, retirez le bloc `<div class="notice">…</div>` des deux pages. Modifiez les deux langues ensemble et leur date de révision.

## GitHub Pages : quelques clics

1. Connectez-vous à GitHub, créez un dépôt public (par exemple `sbfact-site`).
2. Dans ce dépôt, choisissez **Add file → Upload files**. Déposez le CONTENU de ce dossier, en conservant assets/ et brickarrow/. index.html doit être à la racine du dépôt. Vérifiez également la présence de .nojekyll. Validez avec **Commit changes**.
3. Ouvrez **Settings → Pages**. Source : **Deploy from a branch**. Branche : **main**, dossier : **/(root)**. Cliquez **Save**.
4. Attendez que GitHub affiche l’adresse du site. Ouvrez-la sur téléphone et ordinateur, sans être connecté à GitHub. Activez **Enforce HTTPS** si l’option est disponible.
5. Ajoutez `brickarrow/privacy/` à la fin de l’adresse affichée : c’est l’URL française à utiliser dans AdMob et Google Play. L’anglais est à `brickarrow/privacy/en.html`. Exemple de structure uniquement : `https://VOTRE_COMPTE.github.io/NOM_DU_DEPOT/brickarrow/privacy/`. Ne copiez pas cet exemple tel quel.

Pas de domaine à acheter. Aucun domaine fictif, lien Play Store fictif ou CNAME n’est inclus. Un domaine personnel pourra être configuré plus tard dans Settings → Pages.

## Autre hébergement statique

Envoyez le contenu du dossier dans la racine publique de votre hébergement. Il doit servir index.html dans les dossiers, conserver les sous-dossiers et proposer HTTPS sans connexion ni mot de passe. N’ajoutez pas de scripts de publicité ou de mesure d’audience à ces pages.

## Retour dans AdMob et Google Play

- Ouvrez l’URL publique de confidentialité en navigation privée : aucun accès connecté ne doit être nécessaire.
- Renseignez cette URL dans la fiche BrickArrow d’AdMob et dans la politique de confidentialité Google Play. Ajoutez aussi le lien dans le jeu.
- La rubrique Google Play « Sécurité des données » est une déclaration distincte : vérifiez ses réponses à partir des SDK et de la configuration réels. Ce site ne remplit pas cette rubrique.
- Publiez le message UMP dans AdMob après vérification de la configuration et testez acceptation, refus et changement des choix sur téléphone.
- app-ads.txt est un autre sujet : récupérez la ligne exacte fournie par AdMob si vous l’activez. Aucun identifiant éditeur inventé n’est fourni ici.

## Fichiers

- index.html : accueil, studio, BrickArrow, contact.
- brickarrow/privacy/index.html : confidentialité française.
- brickarrow/privacy/en.html : confidentialité anglaise.
- assets/style.css : style responsive et impression.
- assets/logo-sbfact.svg : signature typographique remplaçable.
- assets/brickarrow-art.svg : composition graphique locale.
- assets/favicon.svg : icône locale.
- .nojekyll : site statique sans traitement Jekyll.

Aucun JavaScript nécessaire, dépendance, formulaire, cookie, stockage local, police distante ou tracker ajouté. Les liens externes ne sont chargés qu’en cliquant. Les journaux et pratiques de l’hébergeur restent sous sa responsabilité.
