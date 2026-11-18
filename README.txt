BLACK HAIR — première version Android (PWA)

CONTENU
- index.html : application
- manifest.webmanifest : configuration installable
- sw.js : cache hors connexion

FONCTIONS
- Code PIN propriétaire (sur cet appareil)
- Enregistrement des recettes et dépenses en GNF
- Catégories de coiffure et charges
- Totaux généraux et résumé du mois
- Historique, suppression d'opérations
- Export et restauration d'une sauvegarde JSON
- Cache hors connexion après premier chargement

INSTALLATION / TEST
1. Héberger le dossier sur un site HTTPS (par exemple un hébergement web).
2. Ouvrir l'adresse dans Chrome sur Android.
3. Attendre le premier chargement avec Internet.
4. Menu Chrome > Ajouter à l'écran d'accueil / Installer l'application.

LIMITES IMPORTANTES
- Cette version est une première base locale. Les données restent sur le téléphone.
- Le PIN est une protection d'accès simple, pas une sécurité bancaire.
- Le mode hors connexion fonctionne après le premier chargement et la mise en cache.
- La synchronisation en ligne automatique n'est PAS encore implémentée : elle nécessite un serveur sécurisé et une base de données.
- Pour éviter de perdre les données, exporter régulièrement le fichier de sauvegarde et le conserver ailleurs.
- Pour une utilisation commerciale réelle, prévoir sauvegarde serveur, authentification robuste, chiffrement et tests.
