# Publication Odoo - Daw'Invest Conseil

## Fichiers

- `odoo-page.html` : bloc HTML complet a coller dans Odoo.
- `../assets` : logo, image de presentation et les deux PDF a televerser dans Odoo.

## Etapes

1. Ouvrir Odoo avec un compte administrateur ou editeur du site web.
2. Aller dans `Site Web`, puis ouvrir ou creer la page Daw'Invest.
3. Televerser dans la mediatheque Odoo :
   - `dawinvest-logo.jfif`
   - `djibouti-hero.jpg`
   - `Infos Pratiques.pdf`
   - `GUIDE-DE-LINVESTISSEUR.pdf`
4. Copier l'URL publique de chaque media.
5. Ouvrir `odoo-page.html` et remplacer :
   - `ODOO_LOGO_URL`
   - `ODOO_HERO_IMAGE_URL`
   - `ODOO_INFOS_PRATIQUES_PDF_URL`
   - `ODOO_GUIDE_INVESTISSEUR_PDF_URL`
6. Dans l'editeur Odoo, ajouter un bloc `HTML / Code personnalise`.
7. Coller tout le contenu de `odoo-page.html`.
8. Enregistrer puis publier la page.

Si Odoo bloque la balise `script`, il faut placer le JavaScript dans la zone de code personnalise du site, ou me donner l'acces editeur/admin pour l'integrer directement.
