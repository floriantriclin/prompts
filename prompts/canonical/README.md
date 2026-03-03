# 🔗 Prompts Canoniques

Ce dossier contient les **versions canoniques** de chaque prompt — des fichiers sans numéro de version dont l'URL GitHub ne changera jamais.

**Utilisation** : copiez l'URL Raw d'un fichier dans vos projets Claude. Même quand une v2 sort, le lien reste valable : il suffit de mettre à jour le fichier canonical dans ce dossier.

---

## 📋 URLs Raw (à copier dans les projets Claude)

### 🧠 Architectes Cognitifs
| Prompt | URL Raw |
|---|---|
| Prompt Architect | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/prompt-architect.md` |
| NEXUS-GENESIS | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/nexus-genesis.md` |

### ⚛️ LangGraph
| Prompt | URL Raw |
|---|---|
| LangGraph Architect Pro | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/langgraph-architect-pro.md` |

### 📝 Notion
| Prompt | URL Raw |
|---|---|
| Notion Architect | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/notion-architect.md` |

### 🎯 Assistants
| Prompt | URL Raw |
|---|---|
| Master Buddy (Gemini) | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/master-buddy-gemini.md` |
| Master Buddy (TypingMind) | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/master-buddy-typingmind.md` |
| Coach Dynamo | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/coach-dynamo.md` |

### 💼 Career & Coaching
| Prompt | URL Raw |
|---|---|
| Coach Candidature | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/coach-carriere-candidature.md` |
| Career Strategist | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/career-strategist.md` |
| Interview Forge | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/interview-forge.md` |

### ⚙️ Methodology
| Prompt | URL Raw |
|---|---|
| BMAD Strategist | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/bmad-strategist.md` |

### ✍️ Content
| Prompt | URL Raw |
|---|---|
| Ghostwriter Florian | `https://raw.githubusercontent.com/floriantriclin/prompts/master/prompts/canonical/ghostwriter-florian.md` |

---

## 🔄 Workflow — Mettre à jour un prompt

Quand une nouvelle version d'un prompt est prête :

```bash
# 1. Créer le fichier versionné dans la catégorie (ex : v2.0 d'Interview Forge)
cp prompts/career/interview-forge-1-0.md prompts/career/interview-forge-2-0.md
# ... éditez le nouveau fichier ...

# 2. Mettre à jour le fichier canonical (l'URL dans les projets Claude est automatiquement à jour)
cp prompts/career/interview-forge-2-0.md prompts/canonical/interview-forge.md

# 3. Commiter les deux fichiers
git add prompts/career/interview-forge-2-0.md prompts/canonical/interview-forge.md
git commit -m "Update: interview-forge v2.0"
git push
```

**Les projets Claude continuent de pointer vers la même URL** — ils récupèrent automatiquement la v2.

---

## ⚠️ Règles de maintenance

- **Ne jamais renommer** les fichiers de ce dossier (cela casserait les URLs dans les projets Claude)
- **Ne jamais supprimer** un fichier de ce dossier sans mettre à jour les projets Claude correspondants
- **Toujours** mettre à jour le fichier canonical en même temps que le fichier versionné
- Les fichiers versionnés (`interview-forge-1-0.md`, etc.) dans leurs dossiers de catégorie restent intacts — ils constituent l'historique

---

**Dernière mise à jour** : 2026-03-03
