# 🌌 Game of Life 3D Explorer

Un simulateur de l'automate cellulaire du Jeu de la Vie de Conway dans un environnement 3D immersif avec des effets visuels dynamiques.

![Screenshot du Jeu de la Vie 3D](https://placehold.co/600x400/222/fff?text=Game+of+Life+3D)

## 🚀 Fonctionnalités

- **Environnement 3D complet** - Explorez le Jeu de la Vie sous tous les angles avec des contrôles de caméra intuitifs
- **Interface utilisateur intuitive** - Contrôles facilement accessibles pour modifier les paramètres en temps réel
- **Rendu visuel spectaculaire** - Cellules animées avec effets dynamiques, couleurs vives et effets lumineux
- **Configurations célèbres intégrées** - Découvrez les modèles emblématiques du Jeu de la Vie (canon à planeurs, pulsar, etc.)
- **Hautement personnalisable** - Ajustez la vitesse, la taille de la grille et autres paramètres selon vos préférences

## 🎮 Comment l'utiliser

1. **Navigation :**
   - **Rotation** : Cliquez et faites glisser pour tourner autour de la grille
   - **Zoom** : Utilisez la molette de la souris pour zoomer/dézoomer
   - **Déplacement** : Clic droit + déplacement pour déplacer la caméra

2. **Contrôles :**
   - **Pause/Play** : Arrêtez ou relancez la simulation
   - **Réinitialisation** : Créez une configuration aléatoire ou videz complètement la grille
   - **Vitesse** : Ajustez la vitesse de la simulation via le curseur
   - **Taille** : Modifiez la taille de la grille via le menu déroulant (de 20×20 à 70×70)

3. **Exploration de configurations :**
   - **Planeur** : Petit motif qui "vole" à travers la grille
   - **Canon à planeurs** : Configuration qui génère indéfiniment des planeurs
   - **Pulsar** : Structure oscillante avec période de 3
   - **Pentadécathlon** : Oscillateur complexe avec période de 15

## 🔧 Technologies utilisées

- **Three.js** - Moteur de rendu 3D WebGL
- **ES6+** - JavaScript moderne avec modules
- **HTML5 & CSS3** - Interface utilisateur responsive

## 💡 Qu'est-ce que le Jeu de la Vie?

Inventé par le mathématicien britannique John Conway en 1970, le Jeu de la Vie est un automate cellulaire qui illustre comment des règles simples peuvent générer des comportements complexes :

- Une cellule vivante avec moins de 2 voisins meurt (sous-population)
- Une cellule vivante avec 2 ou 3 voisins survit
- Une cellule vivante avec plus de 3 voisins meurt (surpopulation)
- Une cellule morte avec exactement 3 voisins devient vivante (reproduction)

À partir de ces règles élémentaires émergent des structures fascinantes, des oscillateurs, et même des "vaisseaux" qui se déplacent indéfiniment.

## 🛠️ Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-username/game-of-life-3d.git
   ```

2. Ouvrez `index.html` dans votre navigateur, ou utilisez un serveur local :
   ```bash
   npx http-server
   ```

## 🤝 Contribuer

Les contributions sont toujours bienvenues ! Voici quelques idées pour améliorer ce projet :

- [ ] Ajout de nouvelles structures et configurations célèbres
- [ ] Sauvegarde et chargement de configurations personnalisées
- [ ] Mode édition pour dessiner des motifs personnalisés
- [ ] Statistiques en temps réel (nombre de cellules vivantes, génération, etc.)
- [ ] Thèmes visuels alternatifs
- [ ] Support des appareils tactiles/mobiles

### Comment contribuer :

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/amazing-feature`)
3. Committez vos changements (`git commit -m 'Add some amazing feature'`)
4. Poussez vers la branche (`git push origin feature/amazing-feature`)
5. Ouvrez une Pull Request

## 📜 Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

## 👏 Remerciements

- John Conway pour l'invention du Jeu de la Vie
- L'équipe de Three.js pour leur incroyable bibliothèque
- Tous les contributeurs et enthousiastes du Jeu de la Vie qui continuent à explorer cet univers fascinant

---

⭐ Si vous aimez ce projet, n'hésitez pas à lui donner une étoile sur GitHub !