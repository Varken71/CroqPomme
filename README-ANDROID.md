# FIX ANDROID - Croq'Pomme

## Pourquoi "Impossible d'installer" ?
Tu essayais d'installer depuis le lien preview Meta AI (container://...) -> ce n'est PAS en https, Android refuse.
Il FAUT passer par GitHub Pages en https.

## Étapes OBLIGATOIRES
1. Upload TOUT ce dossier sur GitHub repo croqpomme-pwa (comme avant)
2. Settings > Pages > main / root > Save
3. Attends 1-2 min, ouvre le VRAI lien https://TON_PSEUDO.github.io/croqpomme-pwa/ dans Chrome Android
4. Maintenant Chrome verra la PWA :
   - Soit il propose direct "Installer"
   - Soit Menu 3 points > "Installer l'application"
   - Soit Menu 3 points > "Ajouter à l'écran d'accueil" (marche toujours même si Install ne s'affiche pas)
5. Un bouton noir "Installer Croq'Pomme" apparaît aussi en bas de l'écran si installable

## Si ça dit encore impossible
- Vérifie que tu es bien en https (cadenas)
- Vide le cache Chrome : Paramètres > Confidentialité > Effacer données
- Vérifie dans Chrome > DevTools > Application > Manifest que tout est vert
- Essaie "Ajouter à l'écran d'accueil" au lieu de "Installer"

Cette version a le manifest corrigé pour Android (id, scope, start_url ./)
