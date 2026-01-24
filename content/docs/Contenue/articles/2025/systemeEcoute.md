---
title: "Mon système d'écoute pour la veille Serious Games"
date: 2026-01-24
tags: ["veille", "outils"]
---

# Mon Système d'Écoute pour la Veille Serious Games

**Date de mise à jour** : Janvier 2026  
**Objectif** : Capturer en temps réel les avancées scientifiques, technologiques et pratiques dans le domaine des **Serious Games** (santé, éducation, formation, VR/AR, gamification, intégration IA/LLM), tout en minimisant le bruit et en priorisant les sources de haute qualité.

Ce système est **semi-automatisé**, gratuit/majoritairement gratuit, et conçu pour être maintenable par une personne seule (moi !).

## 1. Sources principales surveillées

| Rang | Source                                      | Type       | Fréquence d'update | Flux / Lien principal                                                                 | Pourquoi prioritaire ? |
|------|---------------------------------------------|------------|---------------------|---------------------------------------------------------------------------------------|------------------------|
| 1    | JMIR Serious Games                          | Revue      | Hebdo/mensuel      | [RSS](https://games.jmir.org/feed/rss2.xml)                                           | Référence mondiale #1 en serious games appliqués (santé, éducation, VR). RCTs & méta-analyses fréquentes. |
| 2    | International Journal of Serious Games (IJSG) | Revue    | Trimestriel        | Site : https://journal.seriousgamessociety.org/ (pas de RSS public clair → surveiller via Google Alerts ou page "Current Issue") | Journal officiel de la Serious Games Society. Focus théorique & expérimental. |
| 3    | Google Scholar Alerts                       | Alertes académiques | Quotidien/hebdo   | Mots-clés : "serious games" OR "jeux sérieux" OR "game-based learning" + VR OR LLM OR "chronic pain" OR rehabilitation | Capture articles récents + préprints (arXiv, ResearchGate). Filtrage fin possible. |
| 4    | X / Twitter (listes & hashtags)             | Réseau social | Temps réel        | Hashtags : #SeriousGames #JeuxSérieux #EdTech #HealthTech #VRtherapy #Gamification<br>Listes perso : chercheurs (Zyda, Kato, etc.) + labs (USC GamePipe, etc.) | Discussions rapides, annonces de conférences, previews d'articles, retours d'usage réels. |
| 5    | Serious Games Society (site + newsletter)   | Communauté | Mensuel            | https://seriousgamessociety.org/                                                      | Actualités, appels à papiers, événements (GaLA Conf, etc.). |
| 6    | Conférences phares (via alertes)            | Événements | Annuel             | CHI Play, FDG, ECGBL, Games for Health, Meaningful Play → surveiller via Google Alerts | Lieux où sortent les travaux les plus innovants (souvent avant publication journal). |

## 2. Outils et flux d'automatisation

- **Agrégateur RSS principal** : **Inoreader** (ou Feedly)  
  → Tous les flux RSS (JMIR + IJSG via workaround + arXiv "cs.HC" + "cs.MM")  
  → Filtres : mots-clés positifs (VR, rehabilitation, LLM, chronic pain, education) / négatifs (-blockchain, -NFT, -crypto pour éviter le bruit)

- **Alertes académiques** : **Google Scholar** + **Semantic Scholar**  
  → 3-4 alertes thématiques (ex. : "serious games" AND (VR OR AR OR LLM OR "large language model"))

- **Réseaux sociaux** : **X (Twitter)** + **LinkedIn**  
  → Listes privées X : 20-30 comptes clés (Michael Zyda, Pamela Kato, Serious Games Initiative, JMIR éditeurs, labs Purdue/HEIG-VD)  
  → Recherche avancée X : `"serious games" OR #SeriousGames filter:links min_faves:5 since:2025-01-01`

- **Automatisations légères** (Zapier / IFTTT / Make.com)  
  → Nouvel article JMIR → envoi email digest hebdo  
  → Nouvel article Scholar → ajout auto dans Notion / Obsidian (via webhook)  
  → Tweet intéressant → sauvegarde dans Pocket / Raindrop.io

- **Stockage & annotation** : **Obsidian** ou **Notion**  
  → Vault/dossier "Veille Serious Games" avec tags : #santé #éducation #VR #LLM #RCT #2026  
  → Lecture + highlights + liens vers PDF (via Zotero ou directement)

## 3. Processus hebdomadaire (30-60 min/sem)

1. Lundi matin : scan Inoreader → lecture titres/abstracts → 3-5 articles à lire en profondeur  
2. Mercredi : check Google Scholar Alerts + X listes → noter 1-2 news/anomalies  
3. Vendredi : revue rapide des ajouts Obsidian → tagger + prioriser pour blog  
4. Fin de mois : synthèse des 5-10 avancées majeures → draft article "Veille mensuelle"

## 4. Pourquoi ce système est intéressant pour moi (et mon KI)

- Aligné avec mon intérêt pour **l'IA appliquée aux serious games** (LLM pour personnalisation, adaptation dynamique, génération de contenu narratif/santé)  
- Permet de capter **très tôt** les croisements VR/AR + LLM (ex. : agents conversationnels dans jeux thérapeutiques)  
- Oriente mes projets perso/dev (ex. : prototyper un exergame RV avec LLM pour rééducation)  
- Me garde connecté à la communauté (chercheurs, labs, Serious Games Society) sans passer 5h/jour sur Google

## 5. Quand et pourquoi ce système est utile ?

- **Maintenant (2026)** : Alimente directement ce blog de veille (articles JMIR, IJSG, etc.)  
- **Court terme** : Identifier les gaps → idées de projets (ex. : serious game LLM pour fibromyalgie post-méta-analyse 2022)  
- **Moyen terme** : Suivre l'évolution post-2025 (essor des Quest 3/4, intégration Grok/Mistral dans jeux éducatifs)  
- **Long terme** : Construire une expertise solide pour contribuer (papier, conf, outil open-source)

Ce système est **vivant** : je l'ajuste tous les 3 mois en fonction des nouvelles revues (ex. : Frontiers in Virtual Reality) ou outils (nouveaux agrégateurs IA ?).

**Sources de référence principales**  
- RSS JMIR Serious Games : https://games.jmir.org/feed/rss2.xml  
- IJSG : https://journal.seriousgamessociety.org/  
- Google Scholar : https://scholar.google.com  
- Serious Games Society : https://seriousgamessociety.org/