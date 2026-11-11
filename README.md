# STAMINA — site vitrine

Maquette du site de l'agence STAMINA (photo et vidéo : sport, immobilier, architecture).

## Structure

- `index.html` : le site complet (HTML, CSS et JavaScript dans un seul fichier, sans dépendance locale).
- `.github/workflows/pages.yml` : déploiement automatique sur GitHub Pages à chaque push sur `main`.

## Mise en ligne (GitHub Pages)

1. Créer un dépôt sur GitHub (public, ou privé avec un compte payant) et y pousser ces fichiers sur la branche `main`.
2. Dans le dépôt : **Settings → Pages → Build and deployment → Source : GitHub Actions**.
3. Le workflow se lance tout seul. Le site est ensuite disponible à `https://<votre-compte>.github.io/<nom-du-depot>/`.

## À remplacer avant la mise en ligne définitive

- Les blocs gris « Photo » par les vraies photos (dans les sections Présentation et Travail).
- Les noms de clients fictifs (section Clients) par les vrais clients, avec leur accord.
- L'adresse e-mail `contact@stamina.fr` et les mentions légales (adresse, SIRET, hébergeur).
- La description et les balises de partage (Open Graph) si vous voulez un aperçu propre sur les réseaux.

Le formulaire de contact est visuel uniquement : il n'envoie rien pour l'instant. Pour recevoir les messages, il faudra brancher un service d'envoi (par exemple Formspree ou Web3Forms).
