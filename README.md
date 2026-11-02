# Mission Méthode

Apprends à apprendre, mission par mission. Une application pour aider les élèves de 3e à tester des méthodes de travail et à construire la leur, pensée d'abord pour les ateliers BAR.
© Lucas Le Coadou - Professeur d'espagnol dans l'académie de Montpellier

## Ce que voient les élèves

- **Tableau de bord** : les 5 missions, la progression, la collection de récompenses et des rappels (test différé prêt, cartes à réviser, bilan de la semaine, mission proposée par le professeur).
- **Mission 01 – Mon profil de travail** : 11 situations concrètes. Résultat : une carte de départ avec deux priorités (mémoriser, vérifier ce que je sais, comprendre, m'organiser, me concentrer) et les expériences conseillées. Pas de profil « visuel / auditif / kinesthésique ».
- **Mission 02 – Le laboratoire des méthodes** : quatre expériences, deux suffisent pour le carnet d'expériences.
  - **Le duel** : 16 mots de swahili, une moitié apprise en relisant, l'autre en se testant, puis un test immédiat et un **test différé** au moins 20 h plus tard.
  - **Transforme ton cours en questions** : sur une vraie leçon, avec deux révisions espacées.
  - **Explique-le comme à un camarade** : souvenirs notés sans le cours, explication à voix haute, comparaison.
  - **Vrai ou faux ? Les idées reçues** : 8 affirmations, avec ce que dit la recherche.
- **Mission 03 – Muscle ta mémoire** : paquets de cartes (saisie, collage de plusieurs lignes « question ; réponse », import des questions du laboratoire), révision en boîtes espacées (1, 2, 4, 7 puis 14 jours), quiz à choix multiple, calendrier des révisions des 7 prochains jours.
- **Mission 04 – Maîtrise ton temps** : liste des travaux avec échéance et « par quoi commencer ? », planning de la semaine (bouton « Répartir » pour étaler les révisions d'un contrôle, alertes si une journée dépasse 1 h 30 ou si tout est la veille), parades contre les distractions, séance focus minutée (15, 20 ou 25 min) avec objectif. Le programme s'imprime.
- **Mission 05 – Construis ta méthode** : le passeport méthode. L'élève garde, adapte ou laisse chaque méthode testée et choisit 1 à 3 engagements. Il s'imprime.
- **Mon suivi** : activité des 14 derniers jours, bilan hebdomadaire des engagements (tenus, en partie, pas vraiment), comparaison avant / maintenant quand l'élève refait le questionnaire.

## Données des élèves

- Aucun compte, aucune donnée envoyée : tout est enregistré dans le navigateur de l'élève.
- **Mes données** (lien en bas de page) :
  - un **code de sauvegarde** pour reprendre sur un autre appareil ;
  - une **fiche pour mon professeur** (code `MMF1-…`) qui contient le prénom, la carte de départ, les résultats d'expériences, les chiffres de révision et de planning, et les engagements, mais pas le contenu des cours ni ce que l'élève a écrit dans ses cartes ;
  - un bouton pour tout effacer (ordinateurs du collège).

## Espace enseignant

Lien **Espace enseignant** en bas de page. Il ne stocke rien : tout disparaît quand on ferme la page.

- **Fiches élèves** : colle une ou plusieurs fiches `MMF1-…` (une par ligne). Tu obtiens un tableau récapitulatif, puis une fiche détaillée par élève avec des **pistes pour l'entretien** générées à partir de ses résultats. Imprimable.
- **Proposer une mission** : choisis une mission ou une expérience, ajoute un message, et copie le lien à envoyer par l'ENT. L'élève voit ta proposition en haut de son accueil.
- **Animer un atelier** : un déroulé de trois ateliers BAR de 30 minutes.

## Mise en ligne (une seule fois)

1. Crée un dépôt **public** sur GitHub, nommé par exemple `mission-methode`.
2. Dépose dedans `index.html` et le fichier `.nojekyll` (s'il n'apparaît pas sur ton ordinateur, crée-le directement sur GitHub : **Add file > Create new file**, nom `.nojekyll`, contenu vide).
3. Dans le dépôt, va dans **Settings > Pages**. Choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis enregistre.
4. Au bout d'une minute environ, le site est en ligne à `https://<ton-pseudo>.github.io/mission-methode/`.

Aucune clé d'accès n'est nécessaire.

Pour une mise à jour, remplace seulement `index.html` : les progressions des élèves, stockées dans leur navigateur, sont conservées.

## Tester rapidement

Ajoute `?demo` à l'adresse (`…/mission-methode/?demo`) : les minuteurs passent à quelques secondes, et le test différé, les révisions espacées et les cartes s'ouvrent tout de suite. Un badge jaune signale ce mode. Ne donne pas ce lien aux élèves.
