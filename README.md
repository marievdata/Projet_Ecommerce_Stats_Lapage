# 📚 Lapage : Analyse des Ventes & Comportement Client

### 🎯 Contexte du Projet
La librairie historique Lapage a lancé son site e-commerce il y a 2 ans. L'objectif de cette mission est de réaliser un audit complet de la performance de la boutique en ligne et de profiler le comportement d'achat des clients pour orienter la stratégie du CODIR.

### ⚙️ Compétences techniques & méthodologie
- **Data Cleaning (Python/Pandas) :** Consolidation de 3 bases brutes (clients, produits, transactions) aboutissant à un dataset fiable de +680 000 transactions.
- **Analyse Macro-économique :** Étude du Chiffre d'Affaires et analyse de la concentration via la **Courbe de Lorenz** (Indice de Gini).
- **Statistiques Inférentielles :** Application de tests mathématiques pour prouver les corrélations :
  - **Test de Pearson :** Analyse de la corrélation entre l'âge, le panier moyen et la fréquence d'achat.
  - **Test ANOVA :** Validation de l'impact de l'âge sur le choix de la catégorie de produits.

### 📊 Résultats clés
- Mise en évidence d'une corrélation inverse forte : plus l'acheteur est jeune, plus son panier moyen est élevé (p-value = 0).
- Preuve statistique que chaque catégorie du catalogue possède une cible démographique très spécifique, nécessitant une segmentation marketing adaptée.
- Identification d'une forte dépendance au catalogue (Indice de Gini à 0.74), où une minorité de références porte la majorité du CA.

### 📂 Contenu du dépôt
- `notebook_lapage.ipynb` : Le code Python contenant le nettoyage, l'exploration et les algorithmes de tests statistiques.
- `presentation_Lapage.pdf` : Le support de présentation orienté "Data Storytelling" et facilitation visuelle, présenté au Comité de Direction.
