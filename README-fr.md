[English](README.md) · [日本語](README-ja.md) · [繁體中文](README-zh-TW.md) · [简体中文](README-zh.md) · [Deutsch](README-de.md) · Français · [Español](README-es.md) · [Bahasa Indonesia](README-id.md)

# VoiceFlow - Application avancée de synthèse vocale

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

Une application web de synthèse vocale moderne et complète, construite avec React et TypeScript. VoiceFlow offre une interface intuitive pour transformer du texte en voix naturelle, avec surlignage des mots en temps réel, réglages de voix personnalisables et gestion des contenus.

## Captures d’écran

![Interface de l’application VoiceFlow](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*L’interface intuitive de VoiceFlow, avec surlignage des mots en temps réel, commandes de voix personnalisables et gestion des contenus.*

## Fonctionnalités

### Fonctions principales
- Synthèse vocale : synthèse de haute qualité grâce à la Web Speech API
- Surlignage des mots en temps réel : les mots lus sont mis en évidence avec une animation
- Contrôles de lecture : lecture, pause et arrêt avec des commandes réactives
- Plusieurs voix : choix parmi les voix du système, avec détection de la langue

### Personnalisation
- Vitesse de lecture réglable : de 0,5x à 2x
- Hauteur de la voix : réglage fin pour une écoute optimale
- Volume : réglage du niveau de sortie
- Choix de la voix : parmi les voix disponibles sur le système

### Gestion des contenus
- Bibliothèque de textes : organisez plusieurs documents avec des titres
- Ajouter, modifier, supprimer : gestion complète des textes
- Changement de contenu : passage fluide d’un texte à l’autre
- Stockage persistant : les contenus sont enregistrés localement dans le navigateur

### Interface
- Thème sombre moderne : une interface sombre élégante et reposante pour les yeux
- Design responsive : fonctionne sur ordinateur, tablette et mobile
- Dégradés : de beaux textes et éléments visuels en dégradé
- Commandes intuitives : une interface simple avec un retour visuel clair

## Prise en main

### Prérequis
- Node.js (version 16 ou plus récente)
- npm ou yarn
- Un navigateur moderne compatible avec la Web Speech API

### Installation

1. Clonez le dépôt
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. Installez les dépendances
   ```bash
   npm install
   # or
   yarn install
   ```

3. Lancez le serveur de développement
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Ouvrez votre navigateur
   Rendez-vous sur `http://localhost:5173` pour voir l’application

### Compilation pour la production

```bash
npm run build
# or
yarn build
```

Les fichiers compilés se trouvent dans le répertoire `dist/`.

## Utilisation

### Utilisation de base
1. Choisissez ou ajoutez un texte : parmi les exemples fournis, ou ajoutez le vôtre
2. Réglez les paramètres : voix, vitesse, hauteur et volume selon vos préférences
3. Lancez la lecture : cliquez sur le bouton de lecture pour démarrer la synthèse vocale
4. Suivez le texte : regardez les mots se surligner en temps réel pendant la lecture

### Fonctions avancées
- Gestion des contenus : organisez plusieurs documents dans la bibliothèque
- Changement de voix : essayez différentes voix et langues
- Contrôle de la vitesse : adaptez le rythme de lecture à la compréhension ou à l’accessibilité
- Mobile : toutes les fonctions sont disponibles sur mobile

## Stack technique

- Framework frontend : React 18
- Langage : TypeScript
- Outil de build : Vite
- Styles : Tailwind CSS
- Icônes : Lucide React
- API vocale : Web Speech API (SpeechSynthesis)

## Compatibilité des navigateurs

VoiceFlow fonctionne sur les navigateurs modernes compatibles avec la Web Speech API :

- Chrome/Chromium (recommandé)
- Edge
- Safari
- Firefox (choix de voix limité)
- Navigateurs mobiles (iOS Safari, Chrome Mobile)

## Design responsive

VoiceFlow est conçu pour fonctionner parfaitement sur tous les types d’appareils :
- Ordinateur : toutes les fonctions, avec une mise en page optimisée
- Tablette : interface tactile et commandes adaptatives
- Mobile : design compact avec les fonctions essentielles à portée de main

## Contribuer

Les contributions de la communauté sont les bienvenues ! Consultez le [guide de contribution](CONTRIBUTING.md) pour savoir comment commencer.

### Démarrage rapide pour les contributeurs
1. Forkez le dépôt
2. Créez une branche (`git checkout -b feature/amazing-feature`)
3. Faites vos modifications
4. Committez vos modifications (`git commit -m 'Add amazing feature'`)
5. Poussez la branche (`git push origin feature/amazing-feature`)
6. Ouvrez une pull request

## Licence

Ce projet est sous licence MIT ; voir le fichier [LICENSE](LICENSE) pour les détails.

## Problèmes et support

- Signaler un bug : [créer une issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- Demandes de fonctionnalités : [proposer une fonctionnalité](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- Discussions : [rejoindre la conversation](https://github.com/didvc/text-to-speech/discussions)

## Remerciements

- La Web Speech API, qui fournit la synthèse vocale
- Les communautés React et TypeScript, pour leurs excellents outils
- Tailwind CSS, pour son beau système de styles
- Lucide React, pour ses icônes nettes et modernes

## Points forts du projet

- Taille du build : optimisée pour un chargement rapide
- Dépendances : minimales et choisies avec soin
- Performances : animations fluides à 60 fps et interactions réactives
- Accessibilité : conforme WCAG, avec navigation au clavier

---

<div align="center">

[Essayer VoiceFlow en ligne](https://text-speech.pages.dev) | [Documentation](https://github.com/didvc/text-to-speech/wiki) | [Discussions](https://github.com/didvc/text-to-speech/discussions)

Réalisé par [didvc](https://github.com/didvc)

</div>