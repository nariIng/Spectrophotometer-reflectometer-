# 📡 Mini Spectrophotomètre et Réflectomètre Visible

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![Platform](https://img.shields.io/badge/platform-ESP32-blue.svg)]()

Ce projet concerne la **conception et réalisation d'un mini spectrophotomètre et réflectomètre visible** en vue d'analyse de solutions chimiques et de surfaces.

## 📜 Introduction
L'objectif principal de ce projet est de concevoir et développer ces appareils en utilisant des **technologies embarquées modernes**, accessibles et peu coûteuses.

---

# 🟢 Partie 1 : Spectrophotomètre Visible

## 🛠️ Matériel Utilisé
- **ESP32** : Microcontrôleur pour le traitement des données
- **Photodétecteurs** : Capteurs de lumière sensible aux longueurs d’onde spécifiques
- **LED RVB** : Source de lumière calibrée
- **Écran LCD 16x2** : Affichage des résultats
- **Cuvettes à échantillons** : Pour contenir les solutions analysées

## ⚙️ Schéma de Principe
![Schéma](path_to_schema_spectro.png)

Le système fonctionne selon le principe de la **spectrophotométrie d’absorption** : un faisceau de lumière traverse un échantillon et le capteur mesure la quantité de lumière absorbée.

## 📊 Fonctionnement et Algorithme
1. **Émission de lumière** par LED RVB calibrée.
2. **Interaction avec l'échantillon** : absorption des longueurs d'onde spécifiques.
3. **Détection par photodiode** : mesure de l'intensité lumineuse transmise.
4. **Traitement des données** via l’ESP32.
5. **Affichage des résultats** en unités d'absorbance.

## 🏭 Intérêt Industriel
Le spectrophotomètre est largement utilisé dans :
- **L’industrie pharmaceutique** : contrôle de la concentration des substances actives.
- **L’industrie alimentaire** : analyse des colorants et additifs.
- **L’industrie chimique** : détermination des concentrations en solutions.
- **Le domaine environnemental** : analyse des eaux usées et polluants.

## 🔬 Résultats Expérimentaux
### Courbe d’Absorbance en Fonction de la Concentration
![Graphique](path_to_graph_spectro.png)

### Comparaison avec un Spectrophotomètre Commercial
| Paramètre | Appareil Conçu | Appareil Commercial |
|-----------|---------------|---------------------|
| Précision | ±0.02 A.U. | ±0.01 A.U. |
| Longueurs d'onde couvertes | 400-700 nm | 350-750 nm |
| Coût estimé | ~50€ | >1000€ |

---

# 🔵 Partie 2 : Réflectomètre Visible

## 🛠️ Matériel Utilisé
- **ESP32** : Microcontrôleur pour le traitement des données
- **Photodétecteurs** : Capteurs de réflexion
- **LED RVB** : Source de lumière calibrée
- **Écran LCD 16x2** : Affichage des résultats

## ⚙️ Schéma de Principe
![Schéma](path_to_schema_reflecto.png)

Le réflectomètre fonctionne en mesurant l’intensité de lumière réfléchie par une surface et en la comparant à des références colorimétriques.

## 📊 Fonctionnement et Algorithme
1. **Émission de lumière** par LED RVB calibrée.
2. **Réflexion sur la surface analysée**.
3. **Détection par photodiode** de l’intensité réfléchie.
4. **Traitement des données** via l’ESP32.
5. **Affichage des résultats** en valeurs colorimétriques.

## 🏭 Intérêt Industriel
Le réflectomètre est crucial dans :
- **L’industrie textile** : contrôle des nuances et uniformité des couleurs.
- **L’industrie automobile** : vérification des peintures et finitions.
- **L’industrie cosmétique** : standardisation des teintes.
- **L’impression et la fabrication de papiers** : contrôle des couleurs et qualité.

## 🔬 Résultats Expérimentaux
### Modèles de Réflectance Mesurés
![Graphique](path_to_graph_reflecto.png)

---

## 🏆 Avantages du Projet
✅ **Faible coût** : utilisation de composants abordables.<br>
✅ **Portable** : conçu pour être compact et transportable.<br>
✅ **Open-source** : possibilité d’amélioration et d’adaptation.<br>

## 📌 Améliorations Futures
- Intégration d'un module **Bluetooth/WiFi** pour la transmission des données en temps réel.
- Ajout d'un **module d’intelligence artificielle** pour l’interprétation automatique des résultats.
- Développement d'une **interface web interactive** pour le contrôle à distance.

## 📝 Installation et Utilisation
1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/votre-repo/spectrophotometre.git
   ```
2. **Uploader le code sur l'ESP32** via l'IDE Arduino.
3. **Configurer les paramètres** selon le protocole expérimental.
4. **Lancer l’analyse** et visualiser les résultats sur l’écran LCD.

## 🧑‍🔬 Auteur
**Narindranjanahary Emmanuëla** - [LinkedIn](https://linkedin.com/in/your-profile)

## 📜 Licence
Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
