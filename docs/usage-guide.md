# 📖 Guide d'Utilisation des Prompts

Ce guide explique comment utiliser efficacement les prompts de cette collection.

## 🎯 Sélectionner le Bon Prompt

### Par Catégorie

#### 🧠 Architectes Cognitifs
**Quand l'utiliser** : Vous avez besoin de concevoir des system prompts complexes et robustes pour des agents IA spécialisés.

- **Prompt Architect 1.0** *(ébauche originelle de NEXUS-GENESIS 2.0)* : Co-création de prompts par blocs avec interaction séquentielle
  - Idéal pour : Comprendre la genèse de NEXUS-GENESIS, créer des prompts simples guidés pas à pas
  - Complexité : Moyenne (3/5)
  - Token count : ~2,000

- **NEXUS-GENESIS 2.0** : Framework complet avec ReAct, CoT, ToT, Constitutional AI, Reflexion
  - Idéal pour : Conception d'agents multi-domaines, systèmes d'orchestration
  - Complexité : Élevée (5/5)
  - Token count : ~15,000

#### ⚛️ LangGraph Specialists
**Quand l'utiliser** : Vous travaillez avec LangGraph et avez besoin d'architectures d'agents sophistiquées.

- **LangGraph Architect Pro 1.0** : Architecture de base pour orchestration d'agents
  - Idéal pour : Systèmes d'agents avec LangGraph
  - Complexité : Moyenne-Élevée (4/5)
  - Token count : ~12,000

- **LangGraph Architect Pro 1.1** : Version améliorée avec RAG et scalabilité
  - Idéal pour : Systèmes RAG avancés, scalabilité horizontale
  - Complexité : Élevée (5/5)
  - Token count : ~14,000

#### 📝 Notion Specialists
**Quand l'utiliser** : Vous intégrez Notion dans votre workflow ou créez des agents Notion.

- **Notion Architect 1.0** : Spécialiste Notion de base
  - Idéal pour : Intégration Notion simple
  - Complexité : Moyenne (3/5)
  - Token count : ~8,000

- **Notion Architect 1.1** : Version améliorée
  - Idéal pour : Workflows Notion avancés
  - Complexité : Moyenne-Élevée (4/5)
  - Token count : ~10,000

- **Notion Architect 1.1 Complete** : Version complète avec toutes les fonctionnalités
  - Idéal pour : Utilisation complète de Notion
  - Complexité : Élevée (5/5)
  - Token count : ~12,000

#### 🎯 Assistants Généraux
**Quand l'utiliser** : Vous avez besoin d'un assistant polyvalent et flexible.

- **Master Buddy (Gemini)** : Optimisé pour Google Gemini
  - Idéal pour : Utilisation avec Gemini API
  - Complexité : Moyenne (3/5)
  - Token count : ~6,000

- **Master Buddy (TypingMind)** : Optimisé pour TypingMind
  - Idéal pour : Utilisation avec TypingMind
  - Complexité : Moyenne (3/5)
  - Token count : ~6,000

- **Coach Dynamo 1.0** : Coach de vie et productivité quotidienne
  - Idéal pour : Planification journalière, lutte contre la procrastination, time-boxing
  - Complexité : Moyenne (3/5)
  - Token count : ~3,000

#### 💼 Career & Coaching
**Quand l'utiliser** : Vous travaillez sur votre trajectoire professionnelle, une candidature ou la préparation d'entretien.

- **Coach Candidature 1.0** : Expert recrutement pour l'optimisation des candidatures
  - Idéal pour : Rédaction et adaptation CV, lettre de motivation, email — avant l'entretien
  - Complexité : Moyenne (3/5)
  - Token count : ~2,000

- **Career Strategist 1.0** : Expert en stratégie de carrière
  - Idéal pour : Réorientation, bilan de compétences, choix de trajectoire (SWOT, Ikigai, RIASEC, Schein)
  - Complexité : Moyenne-Élevée (4/5)
  - Token count : ~3,000

- **Interview Forge 1.0** : Coach d'entretien de niveau élite
  - Idéal pour : Préparation intensive d'entretiens RH et Métier, postes cadres
  - Complexité : Élevée (4/5)
  - Token count : ~12,000
  - Spécificités : Analyse CV ↔ JD, réponses STAR personnalisées, simulation différenciée RH/Métier, feedback exigeant

#### ⚙️ Methodology
**Quand l'utiliser** : Vous implémentez une méthode de développement logiciel assisté par IA.

- **BMAD Strategist 1.0** : Mentor stratégique BMAD V6
  - Idéal pour : Projets Greenfield/Brownfield suivant la méthode BMAD (Agile AI-Driven Development)
  - Complexité : Élevée (4/5)
  - Token count : ~3,000

#### ✍️ Content
**Quand l'utiliser** : Vous créez du contenu personnel ou professionnel.

- **Ghostwriter Florian 1.0** : Ghostwriter LinkedIn personnel
  - Idéal pour : Rédaction de posts LinkedIn basés sur le vécu professionnel de Florian Triclin
  - Complexité : Moyenne (3/5)
  - Token count : ~5,000

## 🚀 Étapes d'Utilisation

### 1. Copier le Prompt

```bash
# Exemple : Copier NEXUS-GENESIS 2.0
cat prompts/cognitive-architects/nexus-genesis-2-0.md
```

Ou ouvrir directement le fichier dans votre éditeur de texte.

### 2. Adapter le Prompt

Avant d'utiliser le prompt, adaptez-le à votre contexte :

- **Remplacer les placeholders** : `[VOTRE_CONTEXTE]`, `[VOTRE_DOMAINE]`, etc.
- **Ajuster la complexité** : Simplifier ou enrichir selon vos besoins
- **Personnaliser le ton** : Adapter la personnalité de l'agent
- **Ajouter des contraintes** : Spécifier les limites et règles métier

### 3. Tester le Prompt

1. Utiliser le prompt dans votre application IA
2. Tester avec plusieurs requêtes
3. Évaluer la qualité des réponses
4. Itérer et affiner

### 4. Documenter les Modifications

Garder une trace de vos adaptations :

```markdown
## Adaptations Effectuées

- Ajout de contrainte : [description]
- Modification du ton : [description]
- Intégration d'outils : [description]
```

## 💡 Bonnes Pratiques

### ✅ À Faire

- **Tester progressivement** : Commencer avec des cas simples
- **Documenter les changements** : Garder une trace des modifications
- **Versionner** : Utiliser Git pour tracker les évolutions
- **Évaluer régulièrement** : Mesurer la performance de l'agent
- **Itérer** : Améliorer continuellement le prompt

### ❌ À Éviter

- **Utiliser tel quel sans adaptation** : Chaque contexte est unique
- **Ignorer les limitations** : Respecter les guardrails définis
- **Surcharger le prompt** : Garder une certaine concision
- **Négliger les tests** : Valider avant utilisation en production
- **Oublier la documentation** : Documenter pour la maintenabilité

## 🔧 Personnalisation Avancée

### Ajouter des Outils

Si votre agent a besoin d'outils supplémentaires :

```markdown
## 🛠️ TOOL USAGE

### Outils Disponibles
- [Votre outil 1] : Description
- [Votre outil 2] : Description

### Protocole d'Appel
[Détails du protocole]
```

### Modifier le Framework Cognitif

Pour adapter le framework de raisonnement :

```markdown
## 🧠 COGNITIVE FRAMEWORK

Framework utilisé : [ReAct|CoT|ToT|Hybrid]

Justification : [Votre justification]
```

### Ajouter des Guardrails

Pour ajouter des limites spécifiques :

```markdown
## 🚨 GUARDRAILS

### Refus Explicites
- [Ce que l'agent ne doit JAMAIS faire]

### Disclaimers
- [Limitations importantes]
```

## 📊 Évaluation de la Performance

### Métriques à Suivre

- **Pertinence** : Les réponses sont-elles pertinentes ?
- **Complétude** : Les réponses couvrent-elles tous les aspects ?
- **Clarté** : Les réponses sont-elles claires et compréhensibles ?
- **Conformité** : L'agent respecte-t-il les guardrails ?
- **Efficacité** : Les réponses sont-elles générées rapidement ?

### Exemple de Scoring

```markdown
| Métrique | Score | Commentaire |
|----------|-------|-------------|
| Pertinence | 8/10 | Généralement pertinent |
| Complétude | 7/10 | Manque quelques détails |
| Clarté | 9/10 | Très clair |
| Conformité | 10/10 | Respecte tous les guardrails |
| Efficacité | 8/10 | Réponses rapides |
| **TOTAL** | **8.4/10** | Bon, ajustements mineurs |
```

## 🔄 Workflow d'Itération

```
1. Copier le prompt
   ↓
2. Adapter au contexte
   ↓
3. Tester avec cas simples
   ↓
4. Évaluer les résultats
   ↓
5. Identifier les améliorations
   ↓
6. Modifier le prompt
   ↓
7. Tester à nouveau
   ↓
8. Documenter les changements
   ↓
9. Versionner (Git)
   ↓
10. Utiliser en production
```

## 🆘 Dépannage

### Le prompt ne fonctionne pas bien

1. **Vérifier l'adaptation** : Avez-vous bien adapté le prompt ?
2. **Tester les cas limites** : Testez avec des entrées difficiles
3. **Consulter la documentation** : Relire les sections pertinentes
4. **Simplifier** : Réduire la complexité du prompt
5. **Itérer** : Faire des ajustements progressifs

### L'agent dépasse les limites

1. **Ajouter des guardrails** : Renforcer les limites
2. **Clarifier les règles** : Être plus explicite
3. **Tester les refus** : Vérifier que l'agent refuse bien
4. **Documenter** : Clarifier les comportements attendus

### Les réponses sont trop longues/courtes

1. **Ajuster les instructions** : Spécifier la longueur attendue
2. **Ajouter des exemples** : Montrer le format attendu
3. **Modifier le framework** : Changer la stratégie de raisonnement

## 📚 Ressources Supplémentaires

- **examples/use-cases.md** : Cas d'usage concrets
- **prompt-templates.md** : Templates pour créer vos propres prompts
- **plans/github-repository-setup.md** : Plan de configuration

## 🎓 Apprentissage Continu

Pour améliorer votre utilisation des prompts :

1. Lire les commentaires dans les prompts
2. Étudier les frameworks cognitifs utilisés
3. Expérimenter avec différentes adaptations
4. Partager vos découvertes avec l'équipe
5. Contribuer à l'amélioration des prompts

---

**Dernière mise à jour** : 2026-03-03
