# Deepfake — IA Générative, Médias et Cybersécurité

Projet de recherche et d'analyse portant sur la technologie des deepfakes : leur fonctionnement, leurs usages, les menaces qu'ils représentent, leurs impacts sociétaux ainsi que les mécanismes de détection et de prévention associés.

Ce travail a été réalisé dans le cadre du module **PHR (Projet de Recherche)** à l'**IUT Clermont Auvergne — Université Clermont Auvergne**, et présenté à l'oral devant jury.

Il repose sur une **veille scientifique, technologique et cyber** approfondie ainsi qu'une synthèse critique des connaissances existantes. Aucun développement logiciel n'a été produit dans ce cadre.

---

## Contexte et objectifs

Les deepfakes illustrent de manière frappante à quel point l'intelligence artificielle générative peut transformer notre rapport aux médias — pour le meilleur comme pour le pire. Ce projet part de ce constat pour répondre à plusieurs questions concrètes :

- Qu'est-ce qu'un deepfake, et comment fonctionne-t-il techniquement ?
- Quels modèles d'IA sont impliqués dans leur création ?
- Quelles menaces posent-ils réellement, et pour qui ?
- Comment les détecter, et comment s'en prémunir ?
- Existe-t-il des usages légitimes et bénéfiques de cette technologie ?

---

## Fondements technologiques

La création de deepfakes repose sur plusieurs familles de modèles d'apprentissage profond :

**Réseaux Antagonistes Génératifs (GAN)** — au cœur de la plupart des systèmes de deepfake. Un générateur produit du contenu synthétique tandis qu'un discriminateur tente de le détecter. Les deux s'améliorent mutuellement par un processus adversarial, jusqu'à produire des contenus d'un réalisme difficile à distinguer du réel.

**Auto-encodeurs** — utilisés principalement pour l'échange de visages. L'encodeur extrait une représentation compressée du visage source, que le décodeur reconstruit sur un autre visage cible en conservant les expressions et mouvements d'origine.

**Réseaux convolutifs (CNN)** — pour l'analyse et la reproduction précise des traits du visage.

**Réseaux récurrents (RNN)** — pour assurer la cohérence temporelle des vidéos, notamment la synchronisation labiale.

**NLP et synthèse vocale** — pour cloner la voix et le timbre d'un individu à partir d'un échantillon audio.

---

## Menaces identifiées

Le projet met en évidence plusieurs vecteurs de risque concrets :

- **Désinformation et manipulation politique** — simulation de déclarations de personnalités publiques pour influencer l'opinion ou déstabiliser des institutions
- **Fraude économique** — notamment la fraude au président (*CEO fraud*), où un deepfake audio imite la voix d'un dirigeant pour ordonner un virement frauduleux
- **Usurpation d'identité et contournement biométrique** — exploitation des deepfakes pour tromper des systèmes d'authentification vocale ou faciale
- **Atteintes aux individus** — création de contenus non consentis à caractère diffamatoire ou sexuel
- **Compromission de la preuve numérique** — remise en question de l'authenticité de tout contenu audiovisuel, y compris dans un contexte judiciaire

---

## Impacts analysés

**Sur le plan sociétal** — les deepfakes alimentent une crise de confiance dans les médias et l'information. Quand on ne peut plus faire confiance à ce qu'on voit ou entend, c'est le débat public lui-même qui s'érode.

**Sur le plan économique** — les entreprises sont exposées à des risques financiers directs (fraude) mais aussi à des atteintes à leur réputation difficiles à réparer.

**Sur le plan juridique** — le droit peine à suivre l'évolution de la technologie. Des questions fondamentales restent ouvertes : qui est propriétaire d'une image synthétisée ? Qui est responsable des dommages causés ? Comment établir l'authenticité d'une preuve numérique ?

---

## Détection et prévention

La lutte contre les deepfakes nécessite une approche combinée :

- Détection automatique par IA — analyse des incohérences visuelles (clignements anormaux, artefacts) et audio (variations spectrales)
- Filigrane numérique (*watermarking*) — intégration de marques invisibles pour prouver l'authenticité d'un contenu
- Blockchain — pour enregistrer l'historique d'un média et garantir sa traçabilité
- Authentification renforcée — MFA et vérifications dynamiques pour contrer l'usurpation biométrique
- Sensibilisation — formation du public et des professionnels à adopter un regard critique face aux contenus audiovisuels

---

## Usages positifs

Malgré les risques, la technologie deepfake présente des applications légitimes et bénéfiques :

- **Cinéma et doublage multilingue** — synchronisation labiale réaliste dans des langues différentes
- **Éducation et formation** — avatars interactifs pour des expériences d'apprentissage immersives
- **Création artistique** — génération de contenus visuels et musicaux innovants
- **Restauration historique** — amélioration de vieilles vidéos ou reconstitutions historiques animées

---

## Modalités du projet

| Élément | Détail |
|---|---|
| Type | Projet de recherche académique |
| Module | PHR — Projet de Recherche |
| Établissement | IUT Clermont Auvergne — Université Clermont Auvergne |
| Restitution | Rapport écrit + présentation orale |
| Mode de travail | Groupe de 5 étudiants |
| Outils | Veille documentaire — aucun développement logiciel |
| Année | 2025–2026 |

---

## Compétences mobilisées

- Veille technologique et scientifique sur des sujets à évolution rapide
- Lecture et synthèse critique de ressources académiques et industrielles
- Culture en intelligence artificielle générative et cybersécurité
- Vulgarisation de concepts techniques complexes
- Analyse d'impact sociétal et éthique
- Communication orale et travail collaboratif

---

## Mots-clés

`Deepfake` `GAN` `IA générative` `Cybersécurité` `Dual-Use` `Médias` `Éthique` `Veille` `PHR` `Recherche`
