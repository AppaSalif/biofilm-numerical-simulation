# biofilm-numerical-simulation


## 📌 Méthodes numériques utilisées

- **Volumes finis** : schémas conservatifs (Godunov, MUSCL, Lax-Wendroff).
- **Splitting de Lie-Trotter / Strang** pour gérer convection + diffusion.
- **Méthode de projection de Chorin** adaptée à la contrainte de remplissage volumique.
- **Maillages décalés** pour améliorer la stabilité numérique.

## 🔬 Résultats principaux

- Étude des propriétés fondamentales : consistance, stabilité, TVD, principe du maximum.
- Convergence des schémas sur l’équation de Burgers.
- Simulation réaliste de la croissance d’un biofilm à 3 phases (algues, EPS, liquide).
