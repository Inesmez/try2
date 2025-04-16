# try2
# 🎛️ Gesture-to-Speech Project

## 📌 Description
Ce projet a pour but de convertir des gestes détectés par un capteur de mouvement (APDS-9960) via Arduino en texte et son pour aider les personnes muettes et sourdes.

## 📂 Structure du projet

- `code_arduino/` : contient le code Arduino (.ino)
- `essais/` : contient les fichiers d’essai de mouvements récupérés depuis le Serial Monitor sous forme de `.txt` ou `.csv`
- `README.md` : documentation du projet

## 📥 Comment enregistrer un essai

1. Ouvrir le Serial Monitor sur Arduino IDE.
2. Copier les données reçues.
3. Créer un fichier `essaiX.csv` dans `essais/`.
4. Coller les données dedans et sauvegarder.
5. Commiter les changements sur GitHub :
   ```bash
   git add essais/essaiX.csv
   git commit -m "Ajout essai X"
   git push
