# 🎵 Ukulélé Tabs - Application d'apprentissage

Une application web interactive pour apprendre les accords de ukulélé et créer des séquences musicales personnalisées.

![Ukulélé Tabs Preview](https://img.shields.io/badge/Status-Ready-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Tone.js](https://img.shields.io/badge/Tone.js-FF6B6B?logo=javascript&logoColor=white)

## ✨ Fonctionnalités

### 🎼 **Bibliothèque d'accords complète**
- **Accords majeurs** : C, D, E, F, G, A, B
- **Accords mineurs** : Cm, Dm, Em, Fm, Gm, Am, Bm
- **Accords 7ème** : C7, D7, E7, F7, G7, A7, B7
- **Accords majeur 7ème** : Cmaj7, Dmaj7, Fmaj7, Gmaj7

### 📊 **Représentation graphique**
- **Diagrammes de tablatures** interactifs
- **Mini-diagrammes** sur chaque bouton d'accord
- **Vue agrandie** avec position des doigts détaillée
- **Notation standard** : frettes, cordes (G-C-E-A)

### 🔊 **Audio intégré**
- **Synthétiseur réaliste** avec Tone.js
- **Pré-écoute** de chaque accord
- **Son authentique** de ukulélé
- **Accordage standard** GCEA

### 🎵 **Séquenceur musical**
- **Création de progressions** d'accords personnalisées
- **Contrôle du tempo** : 60-200 BPM
- **Durée variable** : 4 temps à ½ temps par accord
- **Lecture en boucle** automatique
- **Indicateur visuel** de l'accord en cours

### 🎮 **Interface intuitive**
- **Design responsive** pour tous les appareils
- **Catégories organisées** avec menus dépliants
- **Gestion facile** de la séquence (ajout/suppression)
- **Contrôles de lecture** Play/Pause/Stop

## 🚀 Utilisation

### **Accès direct**
L'application fonctionne directement dans votre navigateur. Ouvrez simplement le fichier `index.html`.

**🌐 [Démo en ligne](https://votre-username.github.io/ukulele-tabs)**

### **Étapes d'utilisation**

1. **📂 Parcourir les accords**
   - Cliquez sur les catégories (Majeurs, Mineurs, etc.)
   - Explorez les mini-diagrammes de chaque accord

2. **🔍 Sélectionner un accord**
   - Cliquez sur un mini-diagramme pour l'agrandir
   - Visualisez la position des doigts en détail

3. **🎧 Écouter**
   - Utilisez "Pré-écouter" pour entendre l'accord
   - Testez les sonorités avant de les ajouter

4. **➕ Créer une séquence**
   - Cliquez sur "Ajouter à la séquence"
   - Construisez votre progression d'accords

5. **🎛️ Personnaliser la lecture**
   - Réglez le **BPM** (tempo)
   - Ajustez la **durée** de chaque accord
   - Lancez avec **Play/Pause/Stop**

6. **🗑️ Gérer votre séquence**
   - Supprimez des accords individuellement
   - Visualisez l'aperçu de votre progression

## 🛠️ Installation locale

### **Méthode 1 : Téléchargement direct**
```bash
# Téléchargez le fichier index.html
# Ouvrez-le dans votre navigateur
```

### **Méthode 2 : Clone GitHub**
```bash
git clone https://github.com/votre-username/ukulele-tabs.git
cd ukulele-tabs
# Ouvrez index.html dans votre navigateur
```

### **Méthode 3 : Serveur local (optionnel)**
```bash
# Avec Python
python -m http.server 8000

# Avec Node.js
npx serve .

# Puis ouvrez http://localhost:8000
```

## 📱 Compatibilité

| Navigateur | Version minimale | Support |
|------------|------------------|---------|
| Chrome | 66+ | ✅ Complet |
| Firefox | 60+ | ✅ Complet |
| Safari | 12+ | ✅ Complet |
| Edge | 79+ | ✅ Complet |

**📱 Mobile** : Compatible iOS Safari, Android Chrome

## 🎼 Accords disponibles

### Majeurs
`C` `D` `E` `F` `G` `A` `B`

### Mineurs  
`Cm` `Dm` `Em` `Fm` `Gm` `Am` `Bm`

### Septième
`C7` `D7` `E7` `F7` `G7` `A7` `B7`

### Majeur 7ème
`Cmaj7` `Dmaj7` `Fmaj7` `Gmaj7`

## 🔧 Technologies utilisées

- **HTML5** - Structure et sémantique
- **CSS3** - Styling avec Tailwind CSS
- **JavaScript ES6+** - Logique interactive
- **Tone.js** - Synthèse audio et séquenceur
- **SVG** - Diagrammes de tablatures vectoriels

## 📖 Exemples d'utilisation

### **Progression classique (C-Am-F-G)**
```
1. Sélectionnez C → Ajouter à la séquence
2. Sélectionnez Am → Ajouter à la séquence  
3. Sélectionnez F → Ajouter à la séquence
4. Sélectionnez G → Ajouter à la séquence
5. Réglez BPM à 120, durée à 1 temps
6. Appuyez sur Play ▶️
```

### **Blues en C (C-C7-F-C-G7-F-C-G7)**
```
Parfait pour pratiquer le blues basique !
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

- 🐛 Signaler des bugs
- 💡 Proposer de nouvelles fonctionnalités  
- 🎵 Suggérer de nouveaux accords
- 📝 Améliorer la documentation

### **Comment contribuer**
```bash
1. Fork le projet
2. Créez une branche feature (git checkout -b feature/AmazingFeature)
3. Committez vos changements (git commit -m 'Add some AmazingFeature')
4. Push vers la branche (git push origin feature/AmazingFeature)
5. Ouvrez une Pull Request
```

## 📜 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 🙏 Remerciements

- **Tone.js** - Pour l'excellente bibliothèque audio
- **Tailwind CSS** - Pour le framework CSS utilitaire
- **Communauté ukulélé** - Pour l'inspiration et les retours

## 📧 Contact

**Créateur** : [Votre nom]  
**Email** : votre.email@example.com  
**GitHub** : [@votre-username](https://github.com/votre-username)

---

⭐ **N'oubliez pas de donner une étoile si ce projet vous plaît !**

🎵 **Bon apprentissage du ukulélé !** 🎵
