# TP Agentic AI : LangChain, LangGraph et MCP

- **EMSI Casablanca** – 5IAD, groupe G2
- **Réalisé par :** Aya Khalil
- **Encadrant :** Mohamed YOUSSFI
- **Date :** 26/11/2026

## Objectif du TP

Ce TP a pour but de découvrir la construction d'agents IA avec LangChain, l'orchestration de workflows multi-étapes avec LangGraph, et l'intégration d'outils externes via le protocole MCP (Model Context Protocol). Il se termine par une application de synthèse pour le service après-vente (SAV).

## Structure du dépôt

| Dossier / Fichier | Description |
|---|---|
| `langchain/` | Prise en main de LangChain : modèles, prompts, chaînes et agents avec outils |
| `langgraph/` | Workflows d'agents sous forme de graphes (états, nœuds, transitions) |
| `mcp/` | Serveur et client MCP pour exposer des outils à un agent |
| `synthese_sav/` | Projet de synthèse : agent pour le service après-vente |
| `requirements.txt` | Dépendances Python du projet |
| `.gitignore` | Fichiers exclus du dépôt (clés API, environnement virtuel...) |

## Prérequis

- Python 3.10+
- Une clé API pour le modèle de langage utilisé (OpenAI, Groq, etc.)

## Installation

```bash
git clone https://github.com/Aya-khalil167/agentic-ai-langchain-langgraph-mcp-main.git
cd agentic-ai-langchain-langgraph-mcp-main

python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Linux / macOS

pip install -r requirements.txt
```

## Configuration

Créer un fichier `.env` à la racine du projet avec votre clé API (ce fichier n'est pas versionné) :

```env
OPENAI_API_KEY=votre_cle_api
```

## Exécution

Chaque dossier contient ses propres scripts. Exemple :

```bash
cd langchain
python nom_du_script.py
```

## Résultats

Ajouter ici vos captures d'écran ou exemples de sortie des agents.

## Auteur

**Aya Khalil** – Étudiante ingénieure en IA & Data, EMSI Casablanca
GitHub : [@Aya-khalil167](https://github.com/Aya-khalil167)
