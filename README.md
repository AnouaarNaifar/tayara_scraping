# Scraper Tayara.tn - Voitures

Script Python pour scraper les annonces de voitures sur **Tayara.tn**.

## Fonctionnalités
- Scraping automatique des annonces de voitures (jusqu’à plusieurs pages).
- Extraction des caractéristiques techniques.
- Export des données dans un fichier **CSV**.

## Données extraites
**Informations de base :**
- Titre de l'annonce  
- Prix du véhicule  
- Numéro de page  
- URL de l'annonce  

**Caractéristiques techniques (si disponibles, jusqu’à 11) :**
- Puissance fiscale  
- Type de carrosserie  
- Énergie  
- Boîte de vitesses  
- Transmission  
- Marque  
- Modèle  
- Année  
- Kilométrage  
- Couleur  
- État général  

## Utilisation
Exécuter le script :
```bash
python tayara_scraper.py

Un fichier CSV sera généré automatiquement : tayara_scrapping.csv.

Structure du projet
tayara-scraper/
├── tayara_scraper.py     # Script principal
├── tayara_scrapping.csv  # Données exportées (généré automatiquement)
└── README.md             # Documentation du projet


✍️ Développé par Anouaar NAIFAR