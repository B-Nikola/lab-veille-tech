---
title: "Ajustements pilotés par LLM dans Serious Games"
date: 2026-01-24
tags: ["IA", "LLM", "rééducation"]
---

# Utilisation des LLM pour la Personnalisation des Serious Games  
Ajustements pilotés par Large Language Models en rééducation neurologique

**Référence principale**  
Mostachetti I, Vitali A, Regazzoni D, Rizzi C, Salvi GP.  
**Titre** : LLM-Driven Adjustments in Serious Games: A Feasibility Analysis  
**Revue** : Studies in Health Technology and Informatics (IOS Press)  
**Date de publication** : 24 avril 2025  
**DOI** : 10.3233/SHTI250180  
**Lien PubMed** : https://pubmed.ncbi.nlm.nih.gov/40270404  
**Lien full text (paywall probable)** : https://ebooks.iospress.nl/pdf/doi/10.3233/SHTI250180

## Résumé de l'article

**Contexte**  
Les serious games (SG) et la télérééducation jouent un rôle clé dans la récupération des fonctions perdues chez les patients neurologiques (ex. : AVC, lésions médullaires, maladies neurodégénératives). La personnalisation et l’ajustement dynamique de la difficulté sont essentiels pour maintenir l’engagement et l’efficacité thérapeutique.

**Objectif**  
Étudier la **faisabilité** d’intégrer un **Large Language Model (LLM)** dans un Assessment Serious Game (ASG) pour analyser les données d’exercices en temps réel et recommander des programmes de rééducation personnalisés, y compris des ajustements de difficulté et des configurations pour d’autres SG.

**Méthodologie**  
- Acquisition de connaissances médicales via réunions avec professionnels (neurologues, kinés) pour identifier pathologies cibles et paramètres pertinents.  
- Intégration d’un LLM via **GroqCloud** (API rapide pour inférence LLM).  
- Conception d’un **prompt** spécifique : le LLM agit simultanément comme **physiothérapeute** et **développeur de serious games**.  
  → Analyse des données d’exercice (performances, erreurs, temps, etc.).  
  → Ajustements en temps réel de la difficulté.  
  → Suggestions de paramètres pour configurer d’autres jeux (ex. : vitesse, amplitude, nombre de répétitions).  
- Test préliminaire pour évaluer les capacités du système (reconnaissance d’ajustements, respect des instructions, pertinence des recommandations).

**Résultats**  
- Le LLM reconnaît efficacement les ajustements en temps réel.  
- Il suit correctement les instructions pour modifier les paramètres des SG.  
- Limites identifiées :  
  - Degré d’ajustement parfois insuffisant (pas assez fin ou audacieux).  
  - Suggestions numériques de paramètres (ex. : +15 % vitesse) encore imprécises ou incohérentes.  
- Preuve de concept validée : le prompt bien conçu permet au LLM de jouer un rôle dual (expert médical + game designer).

**Conclusions**  
L’intégration d’un LLM dans les serious games est **faisable** et prometteuse pour des ajustements dynamiques et personnalisés en télérééducation neurologique. Cependant, des améliorations sont nécessaires sur la fiabilité, la précision numérique et la robustesse face à des données bruitées ou incomplètes. Cela ouvre la voie à des systèmes hybrides (SG + IA générative) pour une rééducation plus adaptive et accessible à domicile.

## Intérêt pour mon domaine de veille (Serious Games + IA)

Cet article (2025) est l’un des premiers à démontrer concrètement l’utilisation d’un **LLM** (via GroqCloud, probablement un modèle rapide comme Llama ou Mixtral) pour la **personnalisation en temps réel** des serious games thérapeutiques.  
Il croise parfaitement mes deux passions :  
- **Serious games en santé** (rééducation neurologique, exergames, VR/AR).  
- **IA générative** (LLM pour analyse de données patient et adaptation dynamique).  

Pourquoi c’est passionnant pour moi :  
- Les ajustements statiques (règles prédéfinies) limitent souvent l’engagement → un LLM peut interpréter des patterns complexes (fatigue, compensation motrice, motivation) et proposer des scénarios narratifs ou mécaniques adaptés.  
- Potentiel énorme en **télérééducation** : moins de supervision humaine, plus d’autonomie pour le patient, scalabilité.  
- Aligné avec l’évolution post-2024 : explosion des LLM open-source rapides (Groq, Ollama local) + casques VR autonomes (Quest 3/4) → je peux prototyper ça en local !

## Quand et pourquoi cet article sera utile pour moi ?

- **Maintenant (2026)** : Inspiration immédiate pour des projets perso (ex. : intégrer un LLM local via Ollama dans un exergame Unity pour rééducation bras/épaule).  
- **Court terme** : Tester des prompts similaires (physio + game dev) pour ajuster difficulté en fonction de scores réels (temps, précision, HR si capteur).  
- **Moyen terme** : Suivre les suites (améliorations fiabilité, intégration fine-tuning, RCTs plus larges).  
- **Long terme** : Contribuer à des outils open-source ou papiers sur LLM + SG en neuro-réhab (conf GaLA, JMIR, etc.).

**Mots-clés**  
large language model, LLM, serious games, exergaming, neurological rehabilitation, telerehabilitation, personalization, difficulty adjustment, GroqCloud, prompt engineering

Cet article marque un tournant : les LLM ne sont plus seulement pour du chat — ils deviennent des **co-designers intelligents** dans les serious games thérapeutiques !