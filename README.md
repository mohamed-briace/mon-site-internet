# Mohamed Briace — site internet

Site vitrine statique en français, prêt à être publié avec GitHub Pages. Il est construit en HTML, CSS et JavaScript, sans outil de compilation ni dépendance à installer.

## Publier avec GitHub Pages

1. Dans le dépôt, ouvrez `Settings` → `Pages`.
2. Dans `Build and deployment`, choisissez `GitHub Actions` comme source.
3. Le workflow `.github/workflows/pages.yml` publiera le site après un push sur `main` (ou manuellement depuis l’onglet `Actions`).
4. Une fois le workflow terminé, l’URL du site apparaît dans `Settings` → `Pages` et dans l’environnement `github-pages` du workflow.

## À personnaliser avant le lancement

- Dans `index.html`, remplacez `bonjour@votreadresse.fr` par votre adresse e-mail, dans le lien `mailto:` et le texte juste en dessous.
- Adaptez les prestations et les textes pour refléter précisément vos services.
- Le site utilise les polices Google Fonts lorsqu’une connexion Internet est disponible et garde des polices de secours intégrées.
