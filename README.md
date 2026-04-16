# Projet Chatbot RAG

## Présentation
Ce projet est une implémentation simple d’un système RAG (Retrieval-Augmented Generation) en Python.

Le principe est de combiner une recherche dans des documents avec un modèle de langage afin de répondre aux questions de l’utilisateur avec du contexte.

Une interface web avec Streamlit a aussi été ajoutée pour rendre le chatbot plus facile à utiliser.

---

## Ce que fait le projet

- L’utilisateur pose une question
- Le système cherche un texte pertinent dans une petite base de données
- Ce texte est envoyé à un modèle de langage (Groq API)
- Le modèle génère une réponse en se basant sur ce contexte

---

## Fonctionnement

### 1. Récupération (Retrieval)
Le programme compare la question avec une liste de documents et sélectionne celui qui est le plus proche.

### 2. Génération
Le texte récupéré est envoyé au modèle qui génère une réponse finale.

---

## Technologies utilisées

- Python
- API Groq
- Streamlit
- Google Colab

---

## Lancer le projet

Installer les dépendances :

```bash
pip install groq streamlit numpy
