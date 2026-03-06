# meilleure-assurance-animale.com

Site statique SEO-first compatible hébergement mutualisé (cPanel/MassiveHoster).

## Déploiement MassiveHoster / cPanel
1. Compresser tout le dossier du projet en `.zip`.
2. Dans cPanel > File Manager, ouvrir `public_html/` (ou le dossier du domaine).
3. Uploader l'archive puis extraire les fichiers à la racine.
4. Vérifier que `index.html`, `robots.txt`, `sitemap.xml` sont bien à la racine du domaine.
5. Dans Google Search Console, soumettre `https://meilleure-assurance-animale.com/sitemap.xml`.

## Conventions SEO
- URLs en minuscules avec tirets et trailing slash.
- Canonical auto-référent sur les pages principales.
- Maillage interne : Home -> pages piliers -> satellites -> comparatifs.
- CTA affiliation en placeholders `href="#"` + `rel="sponsored noopener"`.

## Évolutivité
- Ajouter les nouveaux articles dans `/blog/slug/index.html`.
- Mettre à jour `sitemap.xml` et `/plan-du-site/`.
- Réutiliser les classes CSS : `.card`, `.pros-cons`, `.callout`, `.faq`.
