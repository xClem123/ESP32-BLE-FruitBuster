# ESP32-BLE-FruitBuster

![ESP32 BLE](https://img.shields.io/badge/ESP32-BLE-blue.svg) ![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-green.svg)

Un projet fun et éducatif pour ESP32 exploitant le BLE pour taquiner les appareils Apple ! Il permet de simuler des AirPods, une Apple TV, ou d’envoyer des paquets "Sour Apple" pour perturber les iOS voisins. **À utiliser avec responsabilité !**

## 🚀 Fonctionnalités
- **🔹 Mode Simulation** : Se fait passer pour un appareil Apple (AirPods, Apple TV, etc.).
- **⚠️ Mode Sour Apple** : Envoie des paquets BLE pour perturber les dispositifs iOS à proximité.
- **💡 LED Feedback** :
  - Fixe en mode Simulation.
  - Clignotante en mode Sour Apple.
- **🎛️ Contrôle via le bouton BOOT (GPIO 0)** pour changer de mode.

## 🛠️ Installation
1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/TonPseudo/ESP32-BLE-FruitBuster.git
   ```
2. Ouvrir dans l'IDE Arduino.
  - Installer les dépendances :
  - Bibliothèque BLE (ESP32 standard).
  - Bibliothèque NimBLE-Arduino (via le gestionnaire de bibliothèques).
    
3. Téléverser le code sur l’ESP32.
4. 
🎮 Utilisation
- Mode 0 : Désactivé (LED éteinte).
- Mode 1 : Simulation Apple (LED fixe).
- Mode 2 : Attaque Sour Apple (LED clignote).
- Changer de mode : Appuyer sur BOOT (GPIO 0).
  
📜 Crédits
- [RapierXbox](https://github.com/RapierXbox/ESP32-Sour-Apple) : Pour le code Sour Apple.
- [ckcr4lyf](https://github.com/ckcr4lyf/EvilAppleJuice-ESP32) : Base de code pour le BLE spam.
  
📜 Licence
Ce projet est sous licence GNU GPL v3.0. Voir le fichier LICENSE pour plus de détails.
```
⚠️ Avertissement : Ce projet est destiné à l'éducation et aux tests dans un environnement contrôlé. Ne pas abuser sur des appareils non consentants !
```
