# 📡 Daily AI Watch

Veille quotidienne automatisée sur l'intelligence artificielle, générée chaque matin et publiée dans ce dépôt.

## 🎯 Objectif

Suivre en continu les avancées de l'IA dans 5 domaines clés, sans manquer une annonce importante des grands laboratoires ni une sortie de modèle open-source.

## 🗂️ Structure du dépôt

```
daily-ai-watch/
└── veille/
    ├── veille-2026-04-19.md
    ├── veille-2026-04-20.md
    └── ...
```

Chaque fichier correspond à une journée de veille au format `veille-YYYY-MM-DD.md`.

## 📋 Contenu de chaque rapport

Chaque rapport quotidien est structuré en 7 sections :

| Section | Description |
|---------|-------------|
| 🔥 **Faits saillants** | 3 à 5 points clés du jour, classés par importance |
| 🛠️ **Nouveaux outils & modèles** | Tableau des sorties du jour avec description et lien |
| 🤖 **LLMs & modèles locaux** | Nouveautés Ollama, Hugging Face, LM Studio |
| 🔒 **Cybersécurité IA** | Vulnérabilités, attaques LLM, outils de défense |
| 🖥️ **Hardware & performance** | GPUs, NPUs, benchmarks, comparatifs |
| 📰 **Autres actualités** | Tout ce qui ne rentre pas dans les catégories ci-dessus |
| 🔗 **Liens de référence** | Sources complètes pour chaque information |

## 🔍 Sources surveillées

- **Labs IA** — Anthropic, OpenAI, Google DeepMind, Meta AI, Mistral, xAI
- **Modèles & outils** — Hugging Face Blog, Ollama Library, LM Studio
- **Recherche** — ArXiv (cs.AI, cs.LG, cs.CR)
- **Actualités tech** — The Decoder, VentureBeat AI, Simon Willison's blog
- **Hardware** — Tom's Hardware, AnandTech, NVIDIA Blog

## 🚀 Comment ça fonctionne

La veille est réalisée par **Claude (Anthropic)** via Claude Code :

1. **Recherches parallèles** sur toutes les catégories simultanément
2. **Compilation** et traduction en français
3. **Génération du rapport** Markdown structuré
4. **Dépôt automatique** dans ce repo GitHub via l'API Git

Aucune entrée n'est dupliquée d'un rapport à l'autre.

## 📅 Premier rapport

- **Date** : 19 avril 2026
- **Faits saillants** : GPT-5.4 (OpenAI), Grok 4.20 Beta 2 (xAI), Voxtral TTS (Mistral), durcissement d'Atlas contre le prompt injection (OpenAI), TinyGPU notarisé par Apple pour CUDA sur Apple Silicon

---

*Propulsé par [Claude Code](https://claude.ai/code) — Anthropic*
