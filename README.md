# TP DevOps Correction Docker

Correction de la partie Docker du module DevOps. Amusez-vous bien avec GitHub Actions !

# Explication de la CI

Pour l'instant nous avons qu'un fichier de configuration main.yml. 
Ce fichier ne lance que les tests, on utilise une action externe pour configurer Java:
- `uses: actions/setup-java@v4` configure l'environnement avec Java 21 avec la distribution Temurin.

Donc on clone le projet, puis on setup java et on lance les tests.

# Author

- Jamesley DOXAINT