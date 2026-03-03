# 🤖 AI Agent Prompts Collection

Collection privée de prompts système pour agents IA spécialisés.

## 📚 Prompts Disponibles

### 🧠 Architectes Cognitifs
- **Prompt Architect 1.0** *(ébauche originelle de NEXUS-GENESIS)* - Co-création de system prompts par blocs, interaction séquentielle guidée
- **NEXUS-GENESIS 2.0** - Architecte cognitif pour la conception de system prompts industriels avec frameworks avancés (ReAct, CoT, ToT, Constitutional AI, Reflexion)

### ⚛️ LangGraph Specialists
- **LangGraph Architect Pro 1.0** - Architecture de systèmes d'orchestration d'agents avec LangGraph
- **LangGraph Architect Pro 1.1** - Version améliorée avec optimisations RAG et scalabilité

### 📝 Notion Specialists
- **Notion Architect 1.0** - Spécialiste de l'architecture et intégration Notion
- **Notion Architect 1.1** - Version améliorée avec fonctionnalités étendues
- **Notion Architect 1.1 Complete** - Version complète avec toutes les fonctionnalités

### 🎯 Assistants Généraux
- **Master Buddy (Gemini)** - Assistant polyvalent optimisé pour Google Gemini
- **Master Buddy (TypingMind)** - Assistant polyvalent pour TypingMind
- **Coach Dynamo 1.0** - Coach de vie et productivité quotidienne (planification, time-boxing, anti-procrastination)

### 💼 Career & Coaching
- **Coach Candidature 1.0** - Expert recrutement pour optimiser CV, lettres de motivation et emails de candidature
- **Career Strategist 1.0** - Expert en stratégie de carrière (SWOT, Ikigai, RIASEC, Schein) pour orienter sa trajectoire professionnelle
- **Interview Forge 1.0** - Coach d'entretien professionnel de niveau élite pour postes cadres (méthode STAR, simulation RH/Métier, feedback exigeant)

### ⚙️ Methodology
- **BMAD Strategist 1.0** - Mentor stratégique pour l'implémentation de la méthode BMAD V6 (Agile AI-Driven Development)

### ✍️ Content
- **Ghostwriter Florian 1.0** - Ghostwriter LinkedIn personnalisé (publications basées sur le vécu professionnel de Florian Triclin)

## 🗂️ Structure du Projet

```
.
├── README.md                          # Documentation principale
├── .gitignore                         # Fichiers à ignorer
├── LICENSE                            # Licence (usage privé)
├── prompts/                           # Dossier des prompts organisés
│   ├── cognitive-architects/          # Architectes cognitifs & prompt engineering
│   │   ├── prompt-architect-1-0.md    # ébauche originelle de nexus-genesis
│   │   └── nexus-genesis-2-0.md
│   ├── langgraph/                     # Spécialisés LangGraph
│   │   ├── langGraph-architect-pro-1-0.md
│   │   └── langGraph-architect-pro-1-1.md
│   ├── notion/                        # Spécialisés Notion
│   │   ├── notion-architect-1-0.md
│   │   ├── notion-architect-1-1.md
│   │   └── notion-architect-1-1-complete.md
│   ├── assistants/                    # Assistants généraux
│   │   ├── master-buddy-gemini-1-0.md
│   │   ├── master-buddy-typingmind-1-0.md
│   │   └── coach-dynamo-1-0.md
│   ├── career/                        # Career & Coaching
│   │   ├── coach-carriere-candidature-1-0.md
│   │   ├── career-strategist-1-0.md
│   │   └── interview-forge-1-0.md
│   ├── methodology/                   # Méthodologies de développement
│   │   └── bmad-strategist-1-0.md
│   ├── content/                       # Création de contenu
│   │   └── ghostwriter-florian-1-0.md
│   └── canonical/                     # URLs stables pour projets Claude (sans numéro de version)
│       ├── README.md                  # Liste des URLs raw et workflow de mise à jour
│       ├── interview-forge.md
│       ├── nexus-genesis.md
│       └── ...
├── docs/                              # Documentation supplémentaire
│   ├── usage-guide.md                 # Guide d'utilisation
│   └── prompt-templates.md            # Templates de prompts
├── examples/                          # Exemples d'utilisation
│   └── use-cases.md
└── plans/                             # Plans et stratégies
    └── github-repository-setup.md     # Plan de création du dépôt
```

## 🔗 URLs Canoniques (projets Claude)

Chaque prompt dispose d'une **URL stable permanente** dans `prompts/canonical/`. Elle ne change pas lors des mises à jour — à utiliser dans vos projets Claude.

Format : `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/{nom}.md`

Exemples :
```
interview-forge       → .../canonical/interview-forge.md
nexus-genesis         → .../canonical/nexus-genesis.md
career-strategist     → .../canonical/career-strategist.md
```

Voir [`prompts/canonical/README.md`](prompts/canonical/README.md) pour la liste complète des URLs et le workflow de mise à jour.

## 🚀 Utilisation Rapide

1. **Choisir le prompt** adapté à votre besoin dans le dossier `prompts/`
2. **Copier le contenu** du fichier `.md` correspondant
3. **L'utiliser comme system prompt** dans votre application IA
4. **Adapter selon vos besoins** spécifiques

### Exemple
```bash
# Copier le contenu du prompt NEXUS-GENESIS
cat prompts/cognitive-architects/nexus-genesis-2-0.md
```

## 📖 Documentation

Consultez le dossier `docs/` pour plus d'informations :
- **usage-guide.md** - Guide d'utilisation détaillé de chaque prompt
- **prompt-templates.md** - Templates pour créer vos propres prompts
- **examples/use-cases.md** - Cas d'usage concrets et exemples

## 🔒 Confidentialité

Ce dépôt est **privé** et destiné à un usage personnel/professionnel uniquement.

## 📄 Licence

Tous droits réservés - Usage privé uniquement

## 🔄 Workflow de Contribution

Pour ajouter ou modifier des prompts :

```bash
# Créer une branche pour votre modification
git checkout -b feature/nouveau-prompt

# Ajouter votre prompt
git add prompts/categorie/nouveau-prompt.md

# Commiter avec un message descriptif
git commit -m "Add: nouveau prompt pour [description]"

# Pousser vers GitHub
git push origin feature/nouveau-prompt
```

## 📊 Statistiques

- **Total de prompts** : 15
- **Catégories** : 7 (Cognitive Architects, LangGraph, Notion, Assistants, Career & Coaching, Methodology, Content)
- **Dernière mise à jour** : 2026-03-03

## 🎯 Prochaines Étapes

- [ ] Ajouter des tags pour les versions importantes
- [ ] Créer des branches pour les expérimentations
- [ ] Documenter les cas d'usage dans `examples/`
- [ ] Maintenir un CHANGELOG.md
- [ ] Créer des templates pour faciliter la création de nouveaux prompts

## 💡 Suggestions d'Amélioration

- Ajouter des scripts d'automatisation pour la validation des prompts
- Créer un système de versioning sémantique
- Développer des tests pour vérifier la qualité
- Intégrer un système de documentation automatique
- Créer des workflows GitHub Actions

## 📞 Support

Pour toute question ou suggestion, consultez la documentation ou créez une issue.

---

**Dernière mise à jour** : 2026-03-03
