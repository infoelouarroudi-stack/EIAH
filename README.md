# Système adaptatif d'apprentissage par LLM : Enjeux éthiques

## Présentation synthétique (5 min)

### Système proposé

Un LLM fine-tuné qui analyse les données élèves (performances, erreurs, rythme) pour scorer la pertinence des exercices proposés. 

**Trois composants principaux :**
- Profil apprenant
- Module de scoring LLM
- Adaptation dynamique

---

## Enjeux éthiques prioritaires

### 1. Fairness et biais

**Problème :** Les LLM peuvent reproduire des biais systémiques (recommandations inégales selon origine/genre)

**Solution :** Approche BiFair avec optimisation bi-niveau pour corriger les biais a priori et d'entraînement simultanément

### 2. Impact environnemental

**Problème :** L'inférence LLM représente 60-70% de la consommation énergétique totale

**Solution :** 
- Modèles distillés
- Cache de recommandations
- Mesure du CO₂ comme métrique

### 3. Inégalité numérique

**Problème :** Tous les élèves n'ont pas accès aux mêmes ressources technologiques

**Solution :**
- Mode hors-ligne
- Interface accessible (lecteurs d'écran)
- Support multimodal

### 4. Au-delà du RGPD/AI Act

**Mesures renforcées :**
- Minimisation stricte des données collectées
- Anonymisation renforcée contre la mémorisation par le LLM
- Droit à l'oubli effectif via ré-entraînement périodique

---

## Évaluation

### Métriques pédagogiques
- Engagement
- Progression des scores
- Précision du matching exercice-niveau

### Métriques d'équité
- Écart de performance entre sous-groupes
- Taux d'exercices pertinents par catégorie

### Protocole d'évaluation

Étude A/B sur un trimestre comparant système adaptatif vs recommandation traditionnelle, avec :
- Données quantitatives
- Entretiens qualitatifs

### Audit éthique
- Test de réidentification
- Empreinte carbone par requête
- Accessibilité WCAG

---

## Références

1. [ScienceDirect - Adaptive Learning Systems](https://www.sciencedirect.com/science/article/pii/S2949678025000248)
2. [QuizCat - Metrics for Evaluating Adaptive Learning](https://www.quizcat.ai/blog/top-5-metrics-for-evaluating-adaptive-learning)
3. [arXiv - BiFair Approach](https://arxiv.org/html/2507.04294v1)
4. [Polytechnique Insights - AI Energy Consumption](https://www.polytechnique-insights.com/en/columns/energy/generative-ai-energy-consumption-soars/)
5. [PubMed - Digital Accessibility](https://pubmed.ncbi.nlm.nih.gov/41479106/)
6. [CEDTECH - Bridging the Digital Divide](https://www.cedtech.net/download/bridging-the-digital-divide-promoting-inclusive-education-for-students-with-disabilities-in-17452.pdf)
7. [CNIL - Legal Basis for AI Systems](https://www.cnil.fr/en/relying-legal-basis-legitimate-interests-develop-ai-system)
8. [PMC - Adaptive Learning Research](https://pmc.ncbi.nlm.nih.gov/articles/PMC9073638/)
9. [Frontiers in Education - Ethical Guidelines](https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2025.1565938/full)
10. [European Commission - Ethical Guidelines for Educators](https://education.ec.europa.eu/focus-topics/digital-education/action-plan/ethical-guidelines-for-educators-on-using-ai)
