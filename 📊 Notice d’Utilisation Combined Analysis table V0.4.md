# **![][image1]**

# **📊 Notice d’Utilisation** 

*Pour débutants et investisseurs avertis – Comprendre, utiliser et personnaliser votre tableau d’analyse boursière avec ajustement automatique des paramètres. Investir comporte des risques, ce tableau n’est pas magique, assurez vous de comprendre pourquoi un paramètre est rouge ou vert.*

---

**📖 PARTIE 1 : GUIDE POUR DÉBUTANTS**

*Comment utiliser le tableau pour prendre des décisions d’investissement ?*

---

## **🎯 À quoi sert ce script ?**

Ce script est un **outil d’analyse complet et adaptatif** qui combine : ✅ **L’analyse technique** (graphiques, tendances, indicateurs comme le RSI, MACD, moyennes mobiles). ✅ **L’analyse fondamentale** (valeur intrinsèque, rentabilité, dette). ✅ **Un système d’ajustement automatique** des paramètres en fonction de votre **horizon d’investissement** (court, moyen ou long terme). ✅ **Un tableau clair** avec des signaux visuels (✅/❌, vert/rouge) pour savoir **quand acheter, vendre ou attendre**.

**Objectif final** : Vous aider à **comprendre si une action est intéressante à acheter**, en fonction de **critères objectifs adaptés à votre stratégie**.

---

## **📋 Structure du Tableau**

Le tableau est divisé en **2 colonnes** :

* **1ère colonne** : **Nom du critère** (ex : "Bull %", "RSI", "Stratégie").  
* **2ème colonne** : **Valeur ou signal** (ex : "72.5%", "45.2", "✅", "BULLISH").

**Les couleurs ont une signification** :

* **🟢 Vert** \= **Signal positif** (favorable à l’achat ou à la hausse).  
* **🔴 Rouge** \= **Signal négatif** (favorable à la vente ou à éviter).  
* **🟠 Orange** \= **Signal neutre** (ni bon ni mauvais, à surveiller).  
* **⚪ Gris/Jaune** \= **Information neutre ou mise en avant** (ex : "HIGH ◆", "Stratégie").

---

## **🔍 Explication Ligne par Ligne**

---

### **🎯 0\. Stratégie (Nouveauté \!)**

**🔹 Définition** : Affiche **la période d’investissement sélectionnée** (ex : "Auto: Medium-term (3-12 months)") et si le mode **Auto-adjust Parameters** est activé ou non.

**🔹 Utilité** :

* **Transparence** : Vous savez **immédiatement** quelle stratégie est active.  
* **Traçabilité** : En cas de doute sur un signal, vous pouvez vérifier **quels paramètres ont été utilisés**.

**🔹 Interprétation** :

* **"Auto: Short-term (0-3 months)"** : Les paramètres sont **optimisés pour le trading court terme** (réactifs aux mouvements rapides).  
* **"Manuel: Long-term (12+ months)"** : Les paramètres sont **définis manuellement** pour une stratégie long terme.  
* **Couleur jaune** : Mise en évidence pour une **visibilité maximale**.

**💡 Conseil** : Vérifiez toujours cette ligne pour **comprendre le contexte** des autres signaux.

---

### **📈 1\. Bull % (Pourcentage Haussier)**

**🔹 Définition** : Probabilité (en %) que le marché soit en **tendance haussière** (les prix montent) selon l’analyse technique du script.

**🔹 Utilité** :

* **Plus le % est élevé**, plus la tendance est **favorable à la hausse**.  
* Utile pour **confirmer une tendance globale** avant d’acheter.

**🔹 Interprétation** :

* **🟢 \> 60%** : Forte probabilité de hausse (tendance haussière).  
* **🟠 40-60%** : Marché neutre (pas de tendance claire).  
* **🔴 \< 40%** : Forte probabilité de baisse (tendance baissière).

**💡 Conseil** : Si **Bull % \> 60%** ET que d’autres critères sont verts, c’est un **bon signe pour acheter**.

---

### **📉 2\. Bear % (Pourcentage Baissier)**

**🔹 Définition** : Probabilité (en %) que le marché soit en **tendance baissière** (les prix baissent).

**🔹 Utilité** :

* **Complémentaire au Bull %** : Les deux doivent faire **100%** (ex : Bull % \= 70% → Bear % \= 30%).  
* Utile pour **anticiper les corrections** (baisses temporaires).

**🔹 Interprétation** :

* **🔴 \> 60%** : Forte probabilité de baisse (éviter d’acheter).  
* **🟠 40-60%** : Marché indécis.  
* **🟢 \< 40%** : Faible risque de baisse.

**💡 Conseil** : Si **Bear % \> 60%**, attendez une **meilleure opportunité** avant d’acheter.

---

### **🏆 3\. Regime (Régime du Marché)**

**🔹 Définition** : État général du marché pour cette action :

* **BULLISH** \= Haussier (les prix montent).  
* **BEARISH** \= Baissier (les prix baissent).  
* **NEUTRAL** \= Ni haussier ni baissier.

**🔹 Utilité** :

* **Résumé simple** de la tendance actuelle.  
* Utile pour **savoir si le marché est favorable ou non**.

**🔹 Interprétation** :

* **🟢 BULLISH** : Bonne période pour acheter (si d’autres critères sont verts).  
* **🔴 BEARISH** : Période risquée pour acheter.  
* **🟠 NEUTRAL** : Attendre une confirmation.

**💡 Conseil** : Un régime **BULLISH** avec un **Bull % \> 60%** est un **signal fort**.

---

### **📊 4\. Volatility (Volatilité)**

**🔹 Définition** : Mesure de **l’amplitude des variations de prix** :

* **HIGH ◆** \= Forte volatilité (les prix montent/descendent beaucoup).  
* **LOW ◇** \= Faible volatilité (les prix bougent peu).

**🔹 Utilité** :

* **Haute volatilité** \= **Risque élevé** mais aussi **opportunités de gains rapides**.  
* **Basse volatilité** \= **Risque faible** mais peu de mouvements (peu intéressant pour le trading).

**🔹 Interprétation** :

* **⚪ HIGH ◆** : Marché agité (attention aux risques \!).  
* **⚪ LOW ◇** : Marché calme (moins de risques, mais aussi moins de gains potentiels).

**💡 Conseil** :

* **Débutants** : Préférez les actions avec **LOW ◇** (moins de stress).  
* **Traders expérimentés** : Peuvent chercher des opportunités en **HIGH ◆**.

---

## **📉 Partie Analyse Technique (Graphiques)**

---

### **📈 5\. Trend Score (Score de Tendance)**

**🔹 Définition** : Score **entre \-100 et \+100** qui mesure la **force de la tendance** :

* **\> 0** \= Tendance haussière.  
* **\< 0** \= Tendance baissière.

**🔹 Utilité** :

* **Confirme la direction du marché** (hausse ou baisse).  
* Plus le score est **élevé (ex: \+50)**, plus la tendance haussière est forte.

**🔹 Interprétation** :

* **🟢 \> \+30** : Tendance haussière forte.  
* **🟠 \-30 à \+30** : Tendance neutre.  
* **🔴 \< \-30** : Tendance baissière forte.

**💡 Conseil** : Un **Trend Score \> \+30** avec un **Regime BULLISH** est un **bon signe**.

---

### **🧠 6\. Memory (Mémoire du Modèle)**

**🔹 Définition** : Valeur **entre \-100 et \+100** qui représente **l’état accumulé du marché** sur le long terme (mémoire des tendances passées).

**🔹 Utilité** :

* **Stabilise les signaux** en évitant les réactions excessives aux mouvements courts.  
* Utile pour **éviter les faux signaux** (ex : un pic temporaire qui ne dure pas).

**🔹 Interprétation** :

* **🟢 \> 0** : Mémoire haussière (le marché a été globalement positif).  
* **🔴 \< 0** : Mémoire baissière (le marché a été globalement négatif).

**💡 Conseil** : Si **Memory \> 0** ET **Trend Score \> 0**, la tendance a plus de chances de **durée**.

---

## **💰 Partie Analyse Fondamentale (Santé de l’Entreprise)**

---

### **🛡️ 7\. Margin of Safety (30%) (Marge de Sécurité)**

**🔹 Définition** : Indique si le **prix actuel de l’action est inférieur de 30% à sa valeur intrinsèque** (valeur "réelle" estimée).

* **✅** \= Le prix est **sous-évalué** (bon moment pour acheter).  
* **❌** \= Le prix est **trop élevé** (risque de surpayer).

**🔹 Utilité** :

* **Principe clé du Value Investing** (Warren Buffett) : Acheter une action **à un prix inférieur à sa valeur réelle**.  
* **Réduit le risque** : Si vous achetez avec une marge de sécurité, même si l’entreprise performe moins bien que prévu, vous êtes protégé.

**🔹 Interprétation** :

* **🟢 ✅** : **Opportunité d’achat** (l’action est en promotion \!).  
* **🔴 ❌** : **Attendre une baisse du prix** avant d’acheter.

**💡 Conseil** : C’est l’un des **critères les plus importants** pour un investissement long terme.

---

### **📊 8\. ROE/ROIC ≥ 15% (Rentabilité de l’Entreprise)**

**🔹 Définition** :

* **ROE (Return on Equity)** \= **Rentabilité des capitaux propres** (combien l’entreprise gagne avec l’argent des actionnaires).  
* **ROIC (Return on Invested Capital)** \= **Rentabilité du capital investi** (combien l’entreprise gagne avec tout son capital).

**🔹 Utilité** :

* **ROE/ROIC ≥ 15%** \= L’entreprise est **très rentable** (ex : Apple, Microsoft).  
* **ROE/ROIC \< 15%** \= L’entreprise est **peu rentable** (risque de stagnation).

**🔹 Interprétation** :

* **🟢 ✅** : **ROE et ROIC ≥ 15%** → L’entreprise est **rentable** (bon signe).  
* **🔴 ❌** : **ROE ou ROIC \< 15%** → L’entreprise est **peu rentable** (à éviter).

**💡 Conseil** : Préférez les entreprises avec **ROE/ROIC ≥ 15%** (donc **✅ dans votre tableau**).

---

### **💳 9\. Dette/EBITDA \< 2 (Santé Financière)**

**🔹 Définition** : Ratio qui mesure **la capacité de l’entreprise à rembourser sa dette** avec ses bénéfices (EBITDA \= bénéfice avant intérêts, impôts, dépréciation).

* **Dette/EBITDA \< 2** \= L’entreprise a **peu de dette** par rapport à ses bénéfices (sain).  
* **Dette/EBITDA ≥ 2** \= L’entreprise est **trop endettée** (risque de faillite).

**🔹 Utilité** :

* **Évite les entreprises fragiles** qui pourraient faire faillite.  
* Warren Buffett **évite les entreprises avec une dette élevée**.

**🔹 Interprétation** :

* **🟢 ✅** : **Dette/EBITDA \< 2** → Entreprise **saine financièrement**.  
* **🔴 ❌** : **Dette/EBITDA ≥ 2** → Entreprise **trop endettée** (risque élevé).

**💡 Conseil** : **Toujours vérifier ce critère** avant d’investir. Une entreprise avec **✅ ici** est plus sûre.

---

## **📊 Partie Analyse Technique Avancée**

---

### **📈 10\. Analyse Graphique**

**🔹 Définition** : Vérifie si le **prix est au-dessus des moyennes mobiles** (EMA 20 et EMA 50).

* **✅** \= Le prix est **au-dessus des deux moyennes** → **Tendance haussière confirmée**.  
* **❌** \= Le prix est **en dessous d’au moins une moyenne** → **Tendance faible ou baissière**.

**🔹 Utilité** :

* **Confirme visuellement la tendance** (les traders utilisent souvent les moyennes mobiles).  
* **Évite les faux signaux** (ex : un pic temporaire sans tendance sous-jacente).

**🔹 Interprétation** :

* **🟢 ✅** : **Bonne tendance haussière** (le prix monte et reste au-dessus des moyennes).  
* **🔴 ❌** : **Tendance faible ou baissière** (le prix pourrait continuer à baisser).

**💡 Conseil** : Un **✅ ici** \+ un **Regime BULLISH** \= **Signal fort pour acheter**.

---

### **🎯 11\. Indicateurs Techniques**

**🔹 Définition** : Vérifie si **au moins un des indicateurs suivants est favorable** :

* **RSI \< 30** (surchargé à la vente → rebond possible).  
* **MACD \> Signal** (le MACD est au-dessus de sa ligne de signal → hausse probable).  
* **Volume \> moyenne sur 20 jours** (fort intérêt des investisseurs).

**🔹 Utilité** :

* **RSI \< 30** \= L’action est **trop vendue** → **Opportunité d’achat** (rebond possible).  
* **MACD \> Signal** \= **Signal haussier** (les acheteurs prennent le contrôle).  
* **Volume élevé** \= **Confirmation** que le mouvement est fort (pas un faux signal).

**🔹 Interprétation** :

* **🟢 ✅** : **Au moins un indicateur est favorable** → **Signal technique positif**.  
* **🔴 ❌** : **Aucun indicateur favorable** → **Pas de signal clair**.

**💡 Conseil** : Si **✅ ici** \+ **Trend Score \> 0**, c’est un **bon moment pour acheter**.

---

## **🤖 Partie Indicateurs Clés**

---

### **📊 12\. Quantitative Value**

**🔹 Définition** : Score basé sur une **méthode quantitative** (ex : modèle de Joel Greenblatt) qui évalue si une action est **sous-évaluée** par rapport à sa rentabilité.

**🔹 Utilité** :

* **Identifie des actions "bon marché"** avec un bon potentiel de croissance.  
* **Approche systématique** (pas basée sur l’intuition).

**🔹 Interprétation** :

* **🟢 ✅** : L’action est **sous-évaluée et rentable** (bon signe).  
* **🔴 ❌** : L’action est **trop chère ou peu rentable**.

**💡 Conseil** : Un **✅ ici** \+ **Margin of Safety ✅** \= **Excellente opportunité**.

---

### **📈 13\. RSI (Relative Strength Index)**

**🔹 Définition** : Indicateur **entre 0 et 100** qui mesure **la force relative de l’action** :

* **\< 30** \= **Surchargé à la vente** (opportunité d’achat, le prix a trop baissé).  
* **\> 70** \= **Surchargé à l’achat** (risque de correction, le prix a trop monté).  
* **50** \= **Zone neutre**.

**🔹 Utilité** :

* **RSI \< 30** \= L’action est **trop vendue** → **Bon moment pour acheter**.  
* **RSI \> 70** \= L’action est **trop achetée** → **Risque de baisse**.

**🔹 Interprétation dans votre script** :

* **🟢 Vert si RSI \< 50** : L’action est **en dessous de sa moyenne** (opportunité d’achat).  
* **🔴 Rouge si RSI \> 50** : L’action est **au-dessus de sa moyenne** (risque de correction).

**💡 Conseil** :

* **RSI \< 30** \= **Très bon signal d’achat** (surchargé à la vente).  
* **RSI \> 70** \= **Signal de vente** (surchargé à l’achat).  
* **50 \< RSI \< 70** \= **Zone de prudence** (attendre une confirmation).

---

### **🧠 14\. Memory State (État de la Mémoire)**

**🔹 Définition** : Valeur **entre \-100 et \+100** qui représente **l’état accumulé de tous les indicateurs** (trend, momentum, RSI, etc.) sur le long terme.

**🔹 Utilité** :

* **Résumé global** de la santé technique de l’action.  
* **Stabilise les signaux** pour éviter les réactions aux mouvements courts.

**🔹 Interprétation** :

* **🟢 \> 0** : **État global positif** (les indicateurs sont majoritairement haussiers).  
* **🔴 \< 0** : **État global négatif** (les indicateurs sont majoritairement baissiers).

**💡 Conseil** : Si **Memory State \> 0** \+ **Trend Score \> 0**, la tendance a de **bonnes chances de continuer**.

---

## **🎯 Comment Utiliser le Tableau pour Prendre une Décision ?**

---

### **📌 Stratégie Recommandée pour Débutants**

#### **🔥 Signaux Forts pour ACHETER**

| Critère | Valeur Attendue | Couleur |
| ----- | ----- | ----- |
| Stratégie | Auto: \[Période\] | ⚪ Jaune |
| Bull % | \> 60% | 🟢 |
| Regime | BULLISH | 🟢 |
| Margin of Safety | ✅ | 🟢 |
| Dette/EBITDA \< 2 | ✅ | 🟢 |
| Analyse Graphique | ✅ | 🟢 |
| Indicateurs Techniques | ✅ | 🟢 |
| Quantitative Value | ✅ | 🟢 |
| RSI | \< 50 | 🟢 |

**💡 Si 6-7 critères sont 🟢** → **Excellente opportunité d’achat \!**

---

#### **⚠️ Signaux pour ATTENDRE ou VENDRE**

| Critère | Valeur à Éviter | Couleur |
| ----- | ----- | ----- |
| Stratégie | Manuel (sans ajustement) | ⚪ Jaune |
| Bear % | \> 60% | 🔴 |
| Regime | BEARISH | 🔴 |
| ROE/ROIC ≥ 15% | ❌ | 🔴 |
| Dette/EBITDA \< 2 | ❌ | 🔴 |
| Analyse Graphique | ❌ | 🔴 |
| Indicateurs Techniques | ❌ | 🔴 |
| Quantitative Value | ❌ | 🔴 |
| RSI | \> 50 | 🔴 |

**⚠️ Si 4+ critères sont 🔴** → **Éviter d’acheter ou vendre si déjà en position.**

---

# **📖 PARTIE 2 : GUIDE AVANCÉ POUR PERSONNES INFORMÉES**

*Comprendre et personnaliser les paramètres du script*

---

## **🔧 À quoi servent les paramètres dans les "Settings" ?**

Les **paramètres** (ou *inputs*) du script permettent de **personnaliser son comportement** en fonction :

* De votre **style d’investissement** (court terme, long terme, value investing, etc.).  
* De votre **tolérance au risque** (conservateur, modéré, agressif).  
* Des **caractéristiques du marché** (volatilité, secteur d’activité, etc.).

---

## **📌 Nouveau : Groupe "Investment Strategy" (Stratégie d'Investissement)**

*Ces paramètres permettent de sélectionner votre horizon d’investissement et d’activer l’ajustement automatique des autres paramètres.*

---

### **🎯 1\. Investment Period (Période d’Investissement)**

**🔹 Définition** : Sélectionne **l’horizon temporel** de votre stratégie d’investissement.

* **Short-term (0-3 months)** : Pour le **trading court terme** (mouvements rapides).  
* **Medium-term (3-12 months)** : Pour le **swing trading** (tendances moyennes).  
* **Long-term (12+ months)** : Pour l’**investissement long terme** (buy & hold).

**🔹 Pourquoi le modifier ?**

* **Adapte automatiquement** tous les autres paramètres (ex : `Sequence Length`, `Memory Decay`) pour **optimiser les signaux** selon votre horizon.  
* Exemple :  
  * **Short-term** : Paramètres **réactifs** (pour capturer des mouvements rapides).  
  * **Long-term** : Paramètres **stables** (pour éviter les faux signaux).

**💡 Conseil** :

* **Trading actif** : `Short-term (0-3 months)`.  
* **Investissement équilibré** : `Medium-term (3-12 months)`.  
* **Buy & Hold** : `Long-term (12+ months)`.

---

### **⚙️ 2\. Auto-adjust Parameters (Ajustement Automatique)**

**🔹 Définition** : Active ou désactive **l’ajustement automatique des paramètres** en fonction de la période sélectionnée.

**🔹 Pourquoi le modifier ?**

* **Activé (true)** :  
  * Les paramètres sont **automatiquement optimisés** pour la période sélectionnée.  
  * **Idéal pour les débutants** ou ceux qui veulent une configuration clé en main.  
* **Désactivé (false)** :  
  * Vous pouvez **définir manuellement** chaque paramètre (pour les utilisateurs avancés).  
  * **Idéal pour affiner** votre stratégie.

**💡 Conseil** :

* **Débutants** : Gardez **`true`** (mode automatique).  
* **Experts** : Passez en **`false`** pour personnaliser chaque paramètre.

---

## **📊 Groupe 1 : Core Settings (Paramètres de Base)**

*Ces paramètres influencent les calculs des indicateurs techniques.*

---

### **📊 1\. Sequence Length (bars)**

**🔹 Définition** : Nombre de **barres (périodes)** utilisées pour calculer certains indicateurs (ex : momentum, volatilité).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `20`  
* **Medium-term** : `60`  
* **Long-term** : `120`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 100-240)** :  
  * Donne plus de poids aux **tendances long terme**.  
  * **Moins sensible aux variations courtes** (idéal pour le *swing trading* ou l’investissement long terme).  
* **Diminuer (ex: 10-30)** :  
  * Donne plus de poids aux **mouvements récents**.  
  * **Plus sensible aux variations courtes** (idéal pour le *day trading*).

**💡 Conseil** :

* **Débutants** : Gardez les valeurs **automatiques**.  
* **Traders court terme** : `20-30` (si mode manuel).  
* **Investisseurs long terme** : `100-200` (si mode manuel).

---

### **📉 2\. Volatility Window**

**🔹 Définition** : Nombre de bars utilisées pour calculer la **volatilité** (écart-type des rendements).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `10`  
* **Medium-term** : `20`  
* **Long-term** : `50`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 50-100)** :  
  * Mesure une volatilité **plus lissée** (moins sensible aux pics).  
* **Diminuer (ex: 5-10)** :  
  * Mesure une volatilité **plus réactive** (sensible aux mouvements récents).

**💡 Conseil** :

* **Actions stables** (ex : utilities) : `30-50`.  
* **Actions volatiles** (ex : tech, crypto) : `10-20`.

---

### **📈 3\. Long Vol Baseline Window**

**🔹 Définition** : Nombre de bars utilisées pour calculer la **volatilité de référence** (moyenne mobile de la volatilité).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `50`  
* **Medium-term** : `100`  
* **Long-term** : `200`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 200-300)** :  
  * Compare la volatilité actuelle à une **base plus large** (idéal pour les tendances long terme).  
* **Diminuer (ex: 50\)** :  
  * Compare la volatilité actuelle à une **base plus courte** (idéal pour le trading court terme).

**💡 Conseil** : Gardez les valeurs **automatiques** pour la plupart des cas.

---

## **🧠 Groupe 2 : Memory (Recurrent State)**

*Paramètre lié à la "mémoire" du modèle, qui influence la stabilité des signaux.*

---

### **🔄 Memory Decay (α)**

**🔹 Définition** : Coefficient **entre 0.1 et 0.99** qui détermine **combien les anciennes données influencent le calcul actuel**.

* **Proche de 1 (ex: 0.99)** : La mémoire **retient beaucoup le passé** (signaux très stables, mais lents à réagir).  
* **Proche de 0 (ex: 0.1)** : La mémoire **oublie vite le passé** (signaux réactifs, mais moins stables).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.7`  
* **Medium-term** : `0.85`  
* **Long-term** : `0.9`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.9-0.99)** :  
  * **Signaux plus stables** (moins de faux signaux).  
  * **Réagit lentement** aux changements de tendance.  
* **Diminuer (ex: 0.5-0.7)** :  
  * **Signaux plus réactifs** (réagit vite aux nouveaux mouvements).  
  * **Plus sensible aux faux signaux** (bruit).

**💡 Conseil** :

* **Investissement long terme** : `0.9-0.95`.  
* **Trading court terme** : `0.7-0.85`.

---

## **⚖️ Groupe 3 : Signal Weights (Poids des Signaux)**

*Ces paramètres déterminent l’importance relative de chaque indicateur dans le calcul du score global.*

---

### **📊 1\. Weight: Trend Direction**

**🔹 Définition** : Poids accordé à la **tendance générale** (EMA 20, 50, 200\) dans le calcul du score composite.

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.25`  
* **Medium-term** : `0.35`  
* **Long-term** : `0.40`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.4-0.5)** :  
  * Donne **plus d’importance à la tendance long terme** (idéal pour le *value investing*).  
* **Diminuer (ex: 0.2-0.3)** :  
  * Donne **moins d’importance à la tendance** (idéal si vous préférez les indicateurs comme le RSI).

**💡 Conseil** :

* **Traders tendanciels** : `0.4-0.5`.  
* **Traders oscillateurs** : `0.2-0.3`.

---

### **📈 2\. Weight: Momentum**

**🔹 Définition** : Poids accordé au **momentum** (vitesse de montée/descente des prix) dans le calcul du score.

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.35`  
* **Medium-term** : `0.30`  
* **Long-term** : `0.25`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.35-0.4)** :  
  * Donne **plus d’importance à la vitesse des mouvements** (idéal pour le *momentum trading*).  
* **Diminuer (ex: 0.2)** :  
  * Donne **moins d’importance au momentum** (idéal pour les stratégies plus stables).

**💡 Conseil** :

* **Traders momentum** : `0.35-0.4`.  
* **Investisseurs long terme** : `0.2-0.25`.

---

### **🔄 3\. Weight: RSI**

**🔹 Définition** : Poids accordé au **RSI** (Relative Strength Index) dans le calcul du score.

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.30`  
* **Medium-term** : `0.20`  
* **Long-term** : `0.15`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.25-0.3)** :  
  * Donne **plus d’importance aux surcharges d’achat/vente** (idéal pour le *swing trading*).  
* **Diminuer (ex: 0.1-0.15)** :  
  * Donne **moins d’importance au RSI** (si vous préférez d’autres indicateurs).

**💡 Conseil** :

* **Traders RSI** : `0.25-0.3`.  
* **Investisseurs fondamentaux** : `0.1-0.15`.

---

### **🧠 4\. Weight: Memory State**

**🔹 Définition** : Poids accordé à la **mémoire du modèle** (état accumulé des indicateurs) dans le calcul du score.

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.10`  
* **Medium-term** : `0.15`  
* **Long-term** : `0.20`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.2-0.25)** :  
  * Donne **plus d’importance à la stabilité long terme** (idéal pour éviter les faux signaux).  
* **Diminuer (ex: 0.1)** :  
  * Donne **moins d’importance à la mémoire** (si vous préférez réagir aux mouvements récents).

**💡 Conseil** : Gardez les valeurs **automatiques** pour la plupart des cas.

---

## **🎯 Groupe 4 : Thresholds & Display (Seuils et Affichage)**

*Ces paramètres définissent les seuils pour les signaux et l’affichage du tableau.*

---

### **📈 1\. Bull Entry Threshold**

**🔹 Définition** : Seuil **en pourcentage** à partir duquel le régime est considéré comme **BULLISH** (haussier).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.55`  
* **Medium-term** : `0.60`  
* **Long-term** : `0.65`

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 0.65-0.70)** :  
  * **Moins de signaux BULLISH** (seulement quand la tendance est très forte).  
  * **Réduit les faux positifs** (moins de signaux d’achat erronés).  
* **Diminuer (ex: 0.50-0.55)** :  
  * **Plus de signaux BULLISH** (dès qu’il y a une légère tendance haussière).  
  * **Risque de faux positifs** (plus de signaux d’achat erronés).

**💡 Conseil** :

* **Conservateur** : `0.65-0.70`.  
* **Agressif** : `0.50-0.55`.

---

### **📉 2\. Bear Entry Threshold**

**🔹 Définition** : Seuil **en pourcentage** en dessous duquel le régime est considéré comme **BEARISH** (baissier).

**🔹 Valeur par défaut (mode Auto)** :

* **Short-term** : `0.45`  
* **Medium-term** : `0.40`  
* **Long-term** : `0.35`

**🔹 Pourquoi le modifier ?**

* **Diminuer (ex: 0.30-0.35)** :  
  * **Moins de signaux BEARISH** (seulement quand la tendance est très baissière).  
* **Augmenter (ex: 0.45-0.50)** :  
  * **Plus de signaux BEARISH** (dès qu’il y a une légère tendance baissière).

**💡 Conseil** :

* **Conservateur** : `0.30-0.35`.  
* **Agressif** : `0.45-0.50`.

---

### **🌈 3\. Dim signals in low-volatility regime**

**🔹 Définition** : Si **activé (true)**, les signaux sont **atténués** (moins visibles) lorsque la volatilité est faible.

**🔹 Valeur par défaut** : `true` (activé).

**🔹 Pourquoi le modifier ?**

* **Désactiver (false)** :  
  * Les signaux restent **visibles même en faible volatilité** (idéal si vous tradez des actions peu volatiles).  
* **Activer (true)** :  
  * Les signaux sont **moins visibles en faible volatilité** (idéal pour éviter les faux signaux en marché calme).

**💡 Conseil** : Gardez `true` pour la plupart des cas.

---

## **📊 Groupe 5 : New Criteria (Critères Fondamentaux et Avancés)**

*Ces paramètres permettent d’ajuster les seuils pour les critères fondamentaux et les modèles avancés.*

---

### **💰 1\. Intrinsic Value**

**🔹 Définition** : Valeur **estimée** de l’action (en dollars) selon votre analyse fondamentale.

* Le script compare le **prix actuel** à cette valeur pour calculer la **Margin of Safety**.

**🔹 Valeur par défaut** : `100.0` (à ajuster manuellement).

**🔹 Pourquoi le modifier ?**

* **Augmenter** :  
  * Si vous pensez que l’action **vaut plus** que sa valeur actuelle (ex : `150` pour une action à `120$`).  
* **Diminuer** :  
  * Si vous pensez que l’action **vaut moins** que sa valeur actuelle (ex : `80` pour une action à `100$`).

**💡 Conseil** :

* Utilisez des **méthodes d’évaluation** (DCF, P/E, P/B) pour estimer cette valeur.  
* Exemple : Si une action vaut `100$` selon votre analyse, entrez `100`.

---

### **📈 2\. ROE (%)**

**🔹 Définition** : **Return on Equity** (Rentabilité des capitaux propres) de l’entreprise, en pourcentage.

**🔹 Valeur par défaut** : `12.0` (à ajuster manuellement).

**🔹 Pourquoi le modifier ?**

* **Augmenter** :  
  * Si l’entreprise a un **ROE plus élevé** (ex : `20` pour Apple).  
* **Diminuer** :  
  * Si l’entreprise a un **ROE plus faible** (ex : `8` pour une entreprise moins performante).

**💡 Conseil** :

* **ROE ≥ 15%** \= Entreprise **très rentable**.  
* **ROE \< 15%** \= Entreprise **peu rentable** (à éviter).

---

### **🔄 3\. ROIC (%)**

**🔹 Définition** : **Return on Invested Capital** (Rentabilité du capital investi) de l’entreprise, en pourcentage.

**🔹 Valeur par défaut** : `10.0` (à ajuster manuellement).

**🔹 Pourquoi le modifier ?**

* **Augmenter** :  
  * Si l’entreprise a un **ROIC plus élevé** (ex : `18` pour Microsoft).  
* **Diminuer** :  
  * Si l’entreprise a un **ROIC plus faible** (ex : `7` pour une entreprise moins efficace).

**💡 Conseil** :

* **ROIC ≥ 15%** \= Entreprise **très efficace**.  
* **ROIC \< 15%** \= Entreprise **peu efficace** (à éviter).

---

### **💳 4\. Dette/EBITDA**

**🔹 Définition** : Ratio **Dette / EBITDA** de l’entreprise (mesure de sa capacité à rembourser sa dette).

**🔹 Valeur par défaut** : `2.5` (à ajuster manuellement).

**🔹 Pourquoi le modifier ?**

* **Diminuer** :  
  * Si l’entreprise a **moins de dette** (ex : `1.5` pour une entreprise saine).  
* **Augmenter** :  
  * Si l’entreprise a **plus de dette** (ex : `4` pour une entreprise endettée).

**💡 Conseil** :

* **Dette/EBITDA \< 2** \= Entreprise **saine financièrement**.  
* **Dette/EBITDA ≥ 2** \= Entreprise **trop endettée** (risque élevé).

---

### **📊 5\. Quantitative Value Score**

**🔹 Définition** : Score **entre 0 et 100** représentant la **valeur quantitative** de l’action (basé sur des modèles comme celui de Joel Greenblatt).

**🔹 Valeur par défaut** : `70.0` (à ajuster manuellement).

**🔹 Pourquoi le modifier ?**

* **Augmenter** :  
  * Si l’action a un **score plus élevé** (ex : `85` pour une action très sous-évaluée).  
* **Diminuer** :  
  * Si l’action a un **score plus faible** (ex : `50` pour une action moyennement sous-évaluée).

**💡 Conseil** :

* **Score ≥ 70** \= Action **sous-évaluée et intéressante**.  
* **Score \< 70** \= Action **peu intéressante**.

---

## **🎨 Groupe 6 : Table Settings (Paramètres du Tableau)**

*Ces paramètres contrôlent l’apparence et la position du tableau.*

---

### **📍 1\. Table Position**

**🔹 Définition** : Position du tableau sur le graphique.

**🔹 Options** :

* `Top Right` (Haut à droite) → **Par défaut**.  
* `Top Left` (Haut à gauche).  
* `Bottom Right` (Bas à droite).  
* `Bottom Left` (Bas à gauche).

**💡 Conseil** : Choisissez la position qui **n’interfère pas avec votre analyse graphique**.

---

### **🎨 2\. Background Transparency**

**🔹 Définition** : Transparence du **fond du tableau** (0 \= transparent, 100 \= opaque).

**🔹 Valeur par défaut** : `80`.

**🔹 Pourquoi le modifier ?**

* **Augmenter (ex: 90-100)** :  
  * Fond **plus opaque** (meilleure lisibilité).  
* **Diminuer (ex: 50-70)** :  
  * Fond **plus transparent** (moins intrusif sur le graphique).

**💡 Conseil** :

* **Graphiques clairs** : `70-80`.  
* **Graphiques sombres** : `90-100`.

---

### **🔝 3\. Bring Table to Front**

**🔹 Définition** : Si **activé (true)**, le tableau est **affiché au-dessus des autres éléments** du graphique (candles, indicateurs).

**🔹 Valeur par défaut** : `true`.

**💡 Conseil** : Gardez `true` pour **toujours voir le tableau clairement**.

---

## **🎯 Exemple de Configuration Personnalisée**

Voici un exemple de **paramétrage adapté à différents profils** :

| Profil | Période | Auto-adjust | Sequence Len | Memory Decay | Weight: RSI | Bull Threshold | Dette/EBITDA |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **Trader Court Terme** | Short-term (0-3 mois) | ✅ Oui | 20 | 0.7 | 0.30 | 0.55 | 2.0 |
| **Swing Trader** | Medium-term (3-12 mois) | ✅ Oui | 60 | 0.85 | 0.20 | 0.60 | 2.0 |
| **Investisseur Long Terme** | Long-term (12+ mois) | ✅ Oui | 120 | 0.9 | 0.15 | 0.65 | 1.5 |
| **Expert (Manuel)** | Medium-term | ❌ Non | 50 | 0.8 | 0.25 | 0.58 | 1.8 |

---

## **⚠️ Attention aux Conflits de Paramètres**

Certains paramètres peuvent **se contredire** :

* Exemple : Si vous augmentez **Bull Entry Threshold** à `0.70` (signaux BULLISH plus rares) mais diminuez **Memory Decay** à `0.5` (signaux plus réactifs), le script peut **changer de régime trop souvent**.  
* **Solution** : Testez toujours vos modifications sur des **données historiques** avant de les utiliser en direct.

---

## **💡 Conseils pour Personnaliser Votre Script**

1. **Commencez par les valeurs par défaut** et observez le comportement du script.  
2. **Modifiez un paramètre à la fois** pour voir son impact.  
3. **Backtestez** (testez sur des données passées) pour valider vos modifications.  
4. **Adaptez les paramètres à votre style** :  
   * **Investissement long terme** : Augmentez `Sequence Length`, `Memory Decay`, et `Bull Entry Threshold`.  
   * **Trading court terme** : Diminuez `Sequence Length`, `Memory Decay`, et augmentez le poids du **Momentum** et du **RSI**.  
5. **Notez vos modifications** pour pouvoir les reproduire ou les ajuster.

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAdwAAADjCAYAAAAv+KU5AAA4MUlEQVR4Xu2de9QVxbmnXSv/zPlnAkZRghGDV0AEBK+EcInGwAEUA4qKlxiDl+BoFBJvGAUjx2siahKCiUFiFLyCEo0X8DIaMYcjGE2CzEyOk2SdWeusOROdNVlncuasHt8m7+bdv6rqrq6+7Np7v99az6ruqurq7rer6vl6f/313uPjH/944sPeAwYkHx59YgtaxzqKoiiKotjZAzOIAR/JdMLnxidX/+Ds5LyrZyQDBw5sky2D2+21117JxIkTo4COBY9PURRF6U1o3t9nn32MfBeHH354bv0PP/ywFIcddlhbe4Zw99133+S6+89rY8jAPf8q2VvTNEneS1PK5+1QeE1DwZPn8YlPfCLNx/NrgunTpxt5yM6dO408RVGUGNi8ebORFyt0g4h5RTjuuOOMvLlz5xryLAO3awhXivafP/inlL335DvcduF+4q8n2uk7W5StxHWnO2jQoNby+vXrjfIyuIRLkg0V7fnnn5+mgwcPNspiADs9fSqCdWy88847yYIFC5KxY8em66+++mry2GOPGfWqQF5zRekUN954o5EXC5s2bTLyquL+++9vW+cxb+P5559vmysffvjhdN02hocMGWLkFQXvdFGYZeE73TbhDh06tCVb+uHlr901L/nDuCltHyfTOm+HAnxjx87klBMnJnfOnpgG6YrvvpDmP/PRMte59Zldy1S+5s1dy2+uWWi05QMdw7PPPpum9957b5rOnj27dWzyHImZM2caeXRBMS+LLHG6hDt16tTM7VwceOCBaTps2DCjjLC1actjXnvtNSMvJui3S8wjrrjiCiMvK1+yaNGiZPHixenyvHnz2sooVnRtcBvCp+06mDNnjpGn9Aauvtbpu8qRI0em6VVXXZWsXbs2d07ctm1bmv7qV79KkXk2qE3My2PGjBmpfHk9a15jssasq0zetN1yyy1tsjzppJOS3//+9+lxcN4ee+xhSJVZtWqVkUdQ223CHTVqlCFcTkm6dKdL9fjOlkEB7tz5zEfpwtYdHUH5WcLduWNTKeGefPLJacoXhC8ulyNnnXVWOgHzJLx8+XKjjotrr702GT58eHp3hmVE1cKV8PFKqM0VK1a01pcuXZrmPfroo235DAv3gAMOSHbs2JHWpWWsJ6F4vvDCC0Z+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>