# AspisAI

**AspisAI** est un projet académique visant à créer un assistant intelligent en cybersécurité. L'utilisateur n'a qu'à poser ses questions à l'IA pour vérifier si un système est sécurisé, sans avoir besoin de manipuler des outils complexes.

---

## Objectifs

- Fournir une interface simple et intuitive pour l'analyse de sécurité.
- Intégrer des outils de sécurité existants avec une couche d'intelligence artificielle.
- Expliquer clairement les résultats des audits de sécurité.
- Rendre la cybersécurité accessible même aux non-experts.

---

## Architecture globale

L'architecture du projet se compose de plusieurs couches :

1. **Interface Utilisateur (UI / Frontend)**  
   - Permet à l'utilisateur de soumettre ses requêtes et de visualiser les résultats.

2. **AI Decision & Explainer**  
   - Analyse la demande et décide quels outils de sécurité exécuter.
   - Explique les résultats obtenus de manière compréhensible.

3. **Backend**  
   - Exécute les outils de sécurité et récupère les données brutes.

4. **Parser**  
   - Nettoie et structure les données brutes pour qu'elles soient exploitables.

5. **Outils de sécurité**  
   - Intègre des outils tels que Nmap, OpenVAS ou d'autres scanners pour l'analyse du système.

---
## Structure du projet
-/AILogic
---

## Fonctionnement

1. L'utilisateur soumet une requête via l'interface.
2. L'AI analyse la requête et choisit l'outil adapté.
3. Le backend exécute l'outil de sécurité.
4. Les résultats bruts sont nettoyés par le parser.
5. L'AI Explainer interprète les résultats et fournit un retour clair.
6. L'interface affiche les résultats et recommandations à l'utilisateur.

---

## Technologies utilisées

- **Frontend:** React / Vue.js, Tailwind CSS
- **Backend:** Python / Node.js, API REST
- **AI:** Transformers / GPT, PyTorch ou TensorFlow
- **Outils de sécurité:** Nmap, OpenVAS, VirusTotal API
- **Parser:** Python

---

## Contribution

Ce projet est collaboratif et vise à être un outil pédagogique et pratique pour la cybersécurité assistée par IA.

---

## Licence

[À définir selon votre choix]
