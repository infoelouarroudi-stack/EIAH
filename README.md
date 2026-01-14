# Système adaptatif d'apprentissage par LLM : Enjeux éthiques

## Présentation synthétique (5 min)

### Système proposé

(Le système repose sur un modèle LLM fine-tuné qui analyse les données d'apprentissage des élèves (historique de performance, vitesse de résolution, types d'erreurs) pour scorer et classifier la pertinence des exercices proposés. L'architecture comporte deux modules principaux:)

**Trois composants principaux :**
- Profil apprenant (Un module de représentation des profils d'apprenants qui encode le niveau actuel, les lacunes identifiées et le rythme d'apprentissage)
- Module de scoring LLM(Un module de scoring de pertinence basé sur LLM qui évalue l'adéquation exercice-élève selon plusieurs critères (difficulté, prérequis, style pédagogique))

---

## Enjeux éthiques prioritaires

### 1. Fairness et biais

**Problème :** Les LLM peuvent reproduire des biais systémiques 

**Solution :** Approche BiFair avec optimisation bi-niveau pour corriger les biais a priori et d'entraînement simultanément

---

## Évaluation

### Métriques pédagogiques
- Engagement
- Progression des scores
- Précision du matching exercice-niveau

### Protocole d'évaluation

Étude A/B sur un trimestre comparant système adaptatif vs recommandation traditionnelle, avec :
- Données quantitatives
- Entretiens qualitatifs


