# 🤖 Mes Projets d'Automatisation No-Code & IA (Make.com)

Bienvenue sur mon dépôt GitHub dédié à mes réalisations en automatisation intelligente et ingénierie de workflows. À travers ces projets, j'ai développé une expertise approfondie sur la plateforme **Make.com**, l'intégration d'Intelligences Artificielles (OpenAI, Google Gemini) et la synchronisation des outils de la suite Google (Workspace).

---

## 🛠️ Projets Réalisés

### 1. Assistant de Tri et de Réponse d'E-mails Intelligent (IA)
* **Description :** Création d'un agent de messagerie autonome capable de surveiller une boîte de réception Gmail, d'analyser le contenu textuel des e-mails entrants, et de générer une action contextuelle.
* **Architecture du flux :** `Gmail (Watch Emails) ➔ Google Gemini (Analyse JSON) ➔ JSON Parser ➔ Google Sheets (Log) ➔ Gmail (Create Draft)`
* **Fonctionnalités :**
  * Extraction automatique de l'intention de l'expéditeur, du résumé du message et du degré d'urgence.
  * Stockage structuré de l'analyse dans un tableau de bord Google Sheets.
  * Génération automatique d'un brouillon de réponse adapté dans le fil de discussion d'origine (Thread ID).

### 2. Système de Relance Client Automatique & Gestion de Statuts
* **Description :** Automatisation d'un cycle de suivi commercial post-rendez-vous pour éviter les oublis et optimiser la conversion client.
* **Architecture du flux :**
  `Google Sheets (Watch Rows) ➔ Filtre Statut ➔ Google Calendar (Quick Add) ➔ Google Sheets (Update Row)`
* **Fonctionnalités :**
  * Détection en temps réel des nouveaux prospects dans une base de données.
  * Calcul dynamique de date de relance à J+7 et création automatique d'un rappel dans Google Calendar via langage naturel (*Quick Add*).
  * Système anti-doublon robuste par mise à jour automatique du statut de la ligne traitée (*Update a Row*).

---

## 🎯 Compétences Techniques Acquises

En développant ces automatisations, j'ai acquis une solide maîtrise des concepts avancés d'ingénierie de flux sur **Make.com** :

* **Gestion des Flux de Données (Data Architecture) :** Compréhension fine de la structure des données (Dictionnaires, Tableaux) et de la manipulation des **Bundles** (paquets de données).
* **Traitement en Boucle (Multi-Bundles Execution) :** Capacité à orchestrer des traitements de données de masse (gestion simultanée de plusieurs lignes/fichiers sans plantage).
* **Filtrage Conditionnel (Advanced Filtering) :** Création de barrières logiques et de règles de validation strictes pour orienter les flux de données selon des critères précis.
* **Prompt Engineering appliqué aux API :** Conception de prompts directifs pour forcer un modèle de langage (Gemini/ChatGPT) à répondre sous un format standardisé et strict (**JSON propre**).
* **Parsing et Structuration (JSON Manipulation) :** Transformation de chaînes de caractères brutes en variables exploitables par des outils tiers.
* **Sécurisation des Processus (Anti-Collision/Doublon) :** Implémentation de boucles de rétroaction pour mettre à jour l'application source et empêcher les exécutions infinies ou répétitives.

---

## 🔧 Outils et Technologies
* **Plateforme d'intégration :** Make.com
* **IA & LLM :** Google Gemini API (Modèle Flash), OpenAI API, Google AI Studio
* **Google Workspace API :** Gmail, Google Sheets, Google Calendar
* **Formats de données :** JSON, Text, Datetime Math Operations

---
*Dépôt mis à jour dans le cadre d'un parcours de montée en compétences en Ingénierie d'Automatisation.*
