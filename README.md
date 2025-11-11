# Gestionnaire de Stock

Système de gestion de stock avec tests automatisés.

##  Fonctionnalités

- Gestion des produits
- Calcul du stock total
- Tests unitaires automatisés
- Intégration continue avec GitHub Actions

## Tests

Les tests s'exécutent automatiquement sur GitHub Actions à chaque push.

### Exécution locale

```bash
# Installation des dépendances
pip install -r requirements.txt

# Initialisation de la base de données
python init.py

# Exécution des tests
python -m unittest discover tests -v
