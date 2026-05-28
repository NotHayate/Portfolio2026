# Portfolio BUT3 – Spécifications, Contenu Final & Instructions Strictes pour GitHub Copilot

Ce fichier contient :
- le contenu final du portfolio (texte définitif)
- la structure exacte du site web
- les règles strictes que GitHub Copilot doit respecter
- les TODO pour améliorer le design sans toucher au texte
- les consignes pédagogiques BUT3 intégrées

Copilot doit se baser **uniquement** sur ce fichier pour générer le site.

---

# 🧭 Structure du site (obligatoire)

Le site doit contenir les sections suivantes, dans cet ordre :

1. Accueil / Présentation professionnelle  
2. Expérience professionnelle (Stage Promod)  
3. Compétences techniques (Hard Skills)  
4. Compétences comportementales (Soft Skills)  
5. Analyse réflexive  
6. Contact  

Chaque section doit être dans un `<section id="...">` avec un `<h2>` clair.

---

# 🧑‍💼 1. Présentation professionnelle

Je m’appelle **Enzo**, étudiant en **BUT3 Informatique**, actuellement en stage au **siège social de Promod** au sein de l’équipe d’exploitation.

Mon stage m’a permis de prendre en charge un projet concret et structurant : la **refonte d’une partie de l’infrastructure serveurs**, en migrant des environnements critiques depuis une ancienne stack RedHat vers des serveurs **Ubuntu 24** plus modernes et plus fiables.

J’ai travaillé sur :
- la mise en place de serveurs  
- le déploiement de services (JBoss AMQ, $U, batchs…)  
- la gestion d’incidents  
- la documentation technique  

Je me positionne comme un **jeune professionnel autonome, adaptable et orienté résolution de problèmes**, avec une appétence forte pour l’infrastructure et l’exploitation.

---

# 🏢 2. Expérience professionnelle – Stage Promod

## Contexte
Stage au **siège social de Promod**, dans l’équipe d’exploitation.  
Objectif : moderniser une infrastructure serveurs vieillissante sous RedHat et migrer les services vers **Ubuntu 24**.

## Rôle
- Mise en place de serveurs Ubuntu 24  
- Déploiement de services (JBoss AMQ, $U, batchs)  
- Reprise et adaptation de configurations  
- Documentation technique  
- Résolution d’incidents  
- Gestion des accès firewall et dépendances inter‑serveurs  

## Autonomie
Autonomie forte : brief → réalisation complète → validation.

## Interactions
Collaboration avec :
- équipe exploitation  
- équipe infrastructure  
- équipes applicatives  

---

# 🛠️ 3. Compétences techniques (Hard Skills)

## Administration système
- **Ubuntu 24** : installation, configuration, sécurisation  
- **RedHat** : analyse et migration de configurations  

## Déploiement & services
- **JBoss AMQ** : installation, migration, résolution d’incidents  
- **$U (Dollar Universe)** : configuration, batchs, diagnostics  
- **Batchs automatisés** : analyse, logs, corrections  

## Réseau & infrastructure
- Gestion des accès firewall  
- Tests de communication inter‑serveurs  

## Méthodes & bonnes pratiques
- Documentation technique  
- Analyse & résolution d’incidents  
- Autonomie technique  

---

# 🤝 4. Compétences comportementales (Soft Skills)

## Autonomie professionnelle
Installation complète d’un serveur + service fonctionnel du premier coup.

## Adaptabilité
Gestion d’incompatibilités RedHat → Ubuntu, crashs, configs obsolètes.

## Gestion du stress
Blocages firewall, incidents critiques, délais serrés.

## Communication technique
Demandes claires aux équipes infra (ports, accès, justification).

## Écoute & feedback
Amélioration de documentations suite aux retours de l’équipe.

## Travail en équipe
Coordination avec exploitation, infra, applicatif.

## Résolution collaborative
Analyse de crashs de batchs avec un collègue.

---

# 🧠 5. Analyse réflexive

## Ce que j’ai appris
- Je suis capable de travailler en autonomie.  
- J’aime l’infrastructure et la résolution de problèmes.  
- Je m’adapte vite à des environnements inconnus.  

## Points forts
- Autonomie  
- Analyse  
- Adaptabilité  
- Communication claire  
- Rigueur  

## Axes de progrès
- Planification  
- Sécurité (firewall, durcissement)  
- Vision globale des architectures  

## Besoins pour évoluer
- Projets d’infra plus larges  
- Automatisation (Ansible, CI/CD)  
- Encadrement ponctuel par un profil senior  

---

# 📞 6. Contact

- Email : **À compléter**  
- GitHub : **À compléter**  
- LinkedIn : **À compléter**  

---

# 🧩 Instructions STRICTES pour GitHub Copilot

## ❗ Règle 1 — Ne jamais modifier le texte
- Le contenu textuel ci-dessus est **définitif**.  
- Copilot ne doit **pas reformuler**, **pas raccourcir**, **pas réécrire**.  
- Copilot doit uniquement structurer et mettre en forme.

## ❗ Règle 2 — Améliorer uniquement le design
Copilot doit :
- moderniser la mise en page  
- ajouter du spacing  
- ajouter un `max-width` pour la lisibilité  
- utiliser une typographie professionnelle  
- ajouter un thème clair ou sombre cohérent  
- rendre le site responsive  
- ajouter des animations légères (fade-in, hover)  
- créer une navigation sticky  

## ❗ Règle 3 — Structure HTML obligatoire
- Une section = un `<section id="...">`  
- Titres en `<h2>`  
- Sous-titres en `<h3>`  
- Navigation fixe ou sticky  
- Footer simple  

## ❗ Règle 4 — CSS dans un fichier séparé
- Le style doit être dans `style.css`  
- Code propre, commenté, lisible  

---

# TODO pour Copilot (à exécuter)

- [ ] Ajouter un layout moderne (max-width 900–1100px)  
- [ ] Ajouter un spacing généreux entre les sections  
- [ ] Ajouter une palette de couleurs sobres  
- [ ] Ajouter une typographie professionnelle (Inter, Roboto, etc.)  
- [ ] Ajouter un header fixe ou sticky  
- [ ] Ajouter un footer simple  
- [ ] Rendre le site responsive (mobile first)  
- [ ] Ajouter des animations légères (fade-in, hover)  
- [ ] Ne pas toucher au texte  

---

# Fin du fichier
