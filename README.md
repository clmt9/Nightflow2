# NightFlow

Application web personnelle (PWA) pour iPhone.

## Mise en ligne gratuite avec GitHub Pages
1. Crée un compte GitHub si tu n'en as pas.
2. Crée un dépôt public nommé `nightflow`.
3. Ajoute tous les fichiers de ce dossier à la racine du dépôt.
4. Dans le dépôt, ouvre **Settings → Pages**.
5. Dans **Build and deployment**, choisis **Deploy from a branch**.
6. Choisis la branche **main** et le dossier **/(root)**, puis **Save**.
7. Attends la publication. L'adresse sera généralement `https://TON-PSEUDO.github.io/nightflow/`.

## Installation sur iPhone
1. Ouvre l'adresse publiée dans Safari.
2. Appuie sur Partager.
3. Choisis **Sur l'écran d'accueil** / **Ajouter à l'écran d'accueil**.
4. Active si proposé **Ouvrir comme app web**, puis Ajouter.

## Limites à connaître
- Les réveils affichés dans NightFlow sont des pense-bêtes : crée les alarmes réelles dans l'app Horloge.
- Le minuteur web n'est pas garanti lorsque Safari est en arrière-plan ou l'iPhone verrouillé.
- Les playlists sont ouvertes dans Deezer. La lecture intégrée n'est pas fournie dans cette version.
- Le site ne peut pas garantir l'activation du mode avion à la fin du minuteur. Les fonctions système doivent être exécutées par des raccourcis iOS compatibles.
- Les données de réveils et playlists sont stockées localement dans le navigateur via localStorage.

## Minuteur et raccourcis iOS
- Le minuteur accepte un nombre personnalisé de minutes et de secondes.
- Crée un raccourci nommé **NightFlow Fin** avec, dans cet ordre : 1) activer la concentration Sommeil ; 2) activer le mode Avion. Copie son lien iOS et colle-le dans les réglages de NightFlow.
- Facultatif : crée **NightFlow Alarme** pour lancer ton raccourci d’alarme depuis NightFlow, puis colle son lien dans les réglages.
- Le minuteur web ne peut pas garantir l’exécution lorsque iOS suspend l’app web ou verrouille l’iPhone. Le retour dans NightFlow actualise le compte à rebours, mais ne peut pas réveiller une page suspendue à l’instant exact. Teste le raccourci séparément.
