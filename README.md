# Banque Islamique de Développement — PROTOTYPE

Application bancaire virtuelle de démonstration.

## Fonctions

- création de comptes fictifs
- connexion / déconnexion
- solde virtuel en dollars américains (USD)
- crédit de démonstration de $1,000
- virements internes simulés
- bénéficiaires
- historique avec solde après opération
- français / English / العربية
- SQLite avec dossier de données configurable
- endpoint `/health` pour le déploiement
- configuration Render incluse dans `render.yaml`

## Lancer localement

```bash
npm install
npm start

Le fichier `render.yaml` configure un service Node avec un disque persistant monté sur `/var/data` et une clé de session générée automatiquement.

Le projet reste une **simulation** : ne pas utiliser de vrais identifiants bancaires, cartes, comptes ou fonds.
