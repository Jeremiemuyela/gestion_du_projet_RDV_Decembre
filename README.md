# Le Rendez-vous de Décembre — Site vitrine

Site vitrine de l’événement entrepreneurial à **Lubumbashi** (décembre 2026) : exposer, réseauter, se développer — avec vote public et Gala.

## Stack

- [Astro](https://astro.build) (statique) + TypeScript
- Hébergement prévu : **GitHub Pages** (`base`: `/gestion_du_projet_RDV_Decembre`)
- Formulaire exposant → FormSubmit → `rendezvousdedecembre@gmail.com`

## Développement

```bash
# Node via nvm si besoin
export NVM_DIR="$HOME/.nvm" && . "$NVM_DIR/nvm.sh"

npm install
npm run dev
```

Build / preview :

```bash
npm run build
npm run preview
```

## Contenu figé (brief)

- Slogan : **Exposez. Connectez. Soyez reconnus.**
- Piliers logo : RÉSEAUTER · EXPOSER · SE DÉVELOPPER
- 3 jours + Gala le 3ᵉ soir (dates & lieu à confirmer)
- Exposants payants (tarif sur demande) ; visiteurs gratuits
- Paiement : espèce ou Mobile Money (numéros à préciser)
- Organisateurs : Uriel Deborah, Jeremie Muyela, Jason Kalaba, Nathan Bondo

## Publication GitHub

Le clone HTTPS a échoué (auth absente). Remote déjà pointé :

```bash
git remote -v
# Après `gh auth login` ou SSH :
git add -A && git commit -m "…" && git push -u origin main
```

Activer GitHub Pages sur la branche `main` / dossier `dist` (ou Action Astro).

## Cursor

Rules Web du kit + `rdv-decembre-content.mdc` dans `.cursor/rules/`.
