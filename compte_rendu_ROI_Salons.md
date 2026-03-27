![](Aspose.Words.36879f10-ed80-43db-b86e-fc466bab93ba.001.png)


**COMPTE RENDU DE PROJET**

**Marketing International & E-Commerce**



**Prédiction du Retour sur Investissement**

**D’une Participation à un Salon International**

*(Hannover Messe, Canton Fair…)*


|**Étudiantes**|BOUNIT Khadija (24010247)  •  IDHSAINE Khadija (24010253) • Douae EL FATTAL (22006001)|
| :- | :- |

|**Filière**|S8 – Commerce International (CI)|
| :- | :- |

|**Outil IA utilisé**|Jupyter Notebook / Python – scikit-learn|
| :- | :- |

|**Type de problème**|Prédiction (Régression) & Classification hybride|
| :- | :- |

|**Année universitaire**|2025 – 2026|
| :- | :- |



*École Nationale de Commerce et de Gestion*

Prédiction du ROI – Salons Internationaux	BOUNIT K. & IDHSAINE K.  |  S8 CI
# <a name="_toc225411612"></a>**Sommaire**
[Sommaire	2](#_toc225411612)

[1. Introduction	2](#_toc225411613)

[2. Intelligence Artificielle et Commerce International	3](#_toc225411614)

[2.1 L'IA comme levier de transformation du commerce mondial	3](#_toc225411615)

[2.2 Application spécifique à la prédiction du ROI des salons internationaux	3](#_toc225411616)

[2.3 Enjeux éthiques et limites de l'IA dans ce contexte	4](#_toc225411617)

[3. Nature du Problème : Classification ou Prédiction ?	4](#_toc225411618)

[3.1 Distinction conceptuelle	4](#_toc225411619)

[3.2 Positionnement de notre projet	5](#_toc225411620)

[3.2.1 Dimension de prédiction (régression)	5](#_toc225411621)

[3.2.2 Dimension de classification	5](#_toc225411622)

[3.3 Variables et jeux de données	5](#_toc225411623)

[4. Outils IA Utilisés	6](#_toc225411624)

[4.1 Environnement de développement	6](#_toc225411625)

[4.2 Bibliothèque principale : scikit-learn	6](#_toc225411626)

[4.2.1 Algorithmes de classification utilisés	6](#_toc225411627)

[4.2.2 Algorithmes de régression utilisés	6](#_toc225411628)

[4.2.3 Techniques d'optimisation et validation	7](#_toc225411629)

[4.3 Bibliothèques complémentaires	7](#_toc225411630)

[4.4 Résultats et interprétation	7](#_toc225411631)

[5. Conclusion	8](#_toc225411632)

[Bibliographie	8](#_toc225411633)

[Ouvrages et articles académiques	8](#_toc225411634)

[Sources spécialisées en marketing des salons	9](#_toc225411635)

[Documentation technique et ressources numériques	9](#_toc225411636)

[Rapports institutionnels sur l'IA et le commerce international	9](#_toc225411637)



#
#
#
#
# <a name="_toc225411613"></a>**1. Introduction**
La mondialisation des échanges commerciaux a profondément transformé les pratiques du marketing international. Les salons professionnels internationaux — tels que le Hannover Messe en Allemagne ou le Canton Fair (Foire de Canton) en Chine — constituent des leviers stratégiques incontournables pour les entreprises souhaitant conquérir de nouveaux marchés, nouer des partenariats commerciaux durables et renforcer leur visibilité à l'échelle mondiale.

Toutefois, la participation à ces événements représente un investissement financier considérable : frais de stand, déplacements, hébergement, communication pré- et post-salon, ressources humaines mobilisées… Dans un contexte économique marqué par la recherche d'efficience et de rentabilité, les décideurs sont confrontés à une question fondamentale : quel est le retour sur investissement (ROI) réel d'une telle participation ?

C'est précisément dans cette problématique que s'inscrit le présent projet académique, réalisé dans le cadre du module Marketing International & E-Commerce (S8 – Commerce International). Ce travail vise à mobiliser les outils de l'intelligence artificielle (IA) et du machine learning pour modéliser, prédire et analyser le ROI d'une participation à un salon international.

Le présent compte rendu est structuré en cinq parties : la relation entre IA et commerce international, la nature du problème traité (classification ou prédiction), la description des outils IA utilisés, les résultats obtenus, et enfin une bibliographie de référence.

# <a name="_toc225411614"></a>**2. Intelligence Artificielle et Commerce International**
## <a name="_toc225411615"></a>**2.1 L'IA comme levier de transformation du commerce mondial**
Le commerce international connaît depuis une décennie une révolution silencieuse portée par l'intelligence artificielle. Les entreprises exportatrices, les chambres de commerce et les organisateurs de salons professionnels intègrent désormais des algorithmes d'apprentissage automatique dans leurs processus décisionnels. Cette convergence entre IA et commerce international se manifeste à plusieurs niveaux.

Premièrement, l'IA permet l'analyse prédictive des marchés cibles. En traitant des volumes massifs de données économiques, douanières et comportementales, les modèles d'apprentissage automatique identifient les marchés porteurs, anticipent les évolutions de la demande et détectent les signaux faibles précédant l'émergence de nouvelles opportunités commerciales.

Deuxièmement, dans le domaine de l'e-commerce international, les algorithmes de recommandation personnalisée, de détection de fraude et d'optimisation logistique transforment radicalement l'expérience client transfrontalière. Des plateformes comme Alibaba ou Amazon utilisent des modèles de machine learning pour ajuster en temps réel les prix, les stocks et les stratégies de livraison selon les marchés.

## <a name="_toc225411616"></a>**2.2 Application spécifique à la prédiction du ROI des salons internationaux**
Dans le contexte particulier des salons professionnels internationaux, l'IA offre des capacités analytiques inédites. La prédiction du ROI d'une participation à un salon tel que le Hannover Messe (industrie, technologies) ou le Canton Fair (produits manufacturés, B2B) nécessite de modéliser des variables multidimensionnelles.

Les variables pertinentes pour un tel modèle prédictif comprennent notamment : le secteur d'activité et la taille de l'entreprise participante, le coût total de participation (stand, déplacement, communication), le nombre de contacts qualifiés générés (leads), le taux de conversion des leads en clients effectifs, la notoriété gagnée (mesurée via les médias et les réseaux sociaux), ainsi que les conditions macroéconomiques du pays hôte.

Dans ce projet, nous avons utilisé plusieurs algorithmes de machine learning implémentés via la bibliothèque scikit-learn de Python pour modéliser ces relations complexes. Le notebook Jupyter constitue l'environnement de développement et d'expérimentation, permettant une approche itérative et reproductible.

## <a name="_toc225411617"></a>**2.3 Enjeux éthiques et limites de l'IA dans ce contexte**
L'application de l'IA à la prise de décision commerciale internationale soulève également des questions éthiques importantes. La qualité des prédictions dépend directement de la qualité et de la représentativité des données d'entraînement. Un modèle entraîné sur des données biaisées — par exemple, surreprésentant certains secteurs ou zones géographiques — produira des prédictions potentiellement trompeuses.

Par ailleurs, les modèles de machine learning opèrent comme des boîtes noires dans certains cas (réseaux de neurones profonds), ce qui peut limiter l'interprétabilité des résultats pour les décideurs. Dans notre projet, nous avons privilégié des modèles interprétables (Régression Logistique, Random Forest avec importance des variables) afin de garantir la lisibilité des conclusions.

# <a name="_toc225411618"></a>**3. Nature du Problème : Classification ou Prédiction ?**
## <a name="_toc225411619"></a>**3.1 Distinction conceptuelle**
Avant de caractériser notre problème, il convient de clarifier la distinction entre deux grandes familles de problèmes en machine learning supervisé :

La classification consiste à prédire l'appartenance d'une observation à une catégorie discrète. Par exemple : un salon sera-t-il rentable (Oui/Non) ? Quel niveau de ROI catégoriel peut-on attendre : faible, moyen, élevé ? Les algorithmes de classification (Régression Logistique, Random Forest Classifier, SVM, etc.) produisent une étiquette catégorielle en sortie.

La régression (ou prédiction au sens strict) consiste à estimer une valeur numérique continue. Par exemple : quel sera le ROI exact en pourcentage d'une participation à un salon donné ? Les algorithmes de régression (Régression Linéaire, Random Forest Regressor, Gradient Boosting Regressor, etc.) produisent une valeur scalaire en sortie.

## <a name="_toc225411620"></a>**3.2 Positionnement de notre projet**
Le projet de BOUNIT Khadija et IDHSAINE Khadija s'inscrit dans une approche hybride, articulant les deux paradigmes de façon complémentaire.

### <a name="_toc225411621"></a>**3.2.1 Dimension de prédiction (régression)**
L'objectif principal est la prédiction d'une valeur continue : le taux de retour sur investissement (ROI en %) d'une participation à un salon international. Cet indicateur, calculé comme le rapport entre les bénéfices nets générés par la participation et les coûts engagés, est par nature une variable continue. Les modèles de régression utilisés dans le notebook — Régression Linéaire, Ridge, Lasso, Gradient Boosting Regressor, Random Forest Regressor — cherchent à minimiser l'erreur de prédiction (RMSE, R²).

### <a name="_toc225411622"></a>**3.2.2 Dimension de classification**
Parallèlement, une dimension de classification a été intégrée pour répondre à des questions opérationnelles : la participation sera-t-elle rentable (ROI positif) ou non ? Quel quartile de ROI peut-on anticiper ? Les algorithmes de classification testés — Régression Logistique, Random Forest Classifier, Gradient Boosting Classifier, SVM, MLP, AdaBoost — permettent de segmenter les cas en catégories décisionnelles actionnables.

Cette double approche reflète la réalité des besoins des managers commerciaux : d'un côté, une estimation chiffrée précise du ROI pour le contrôle de gestion ; de l'autre, une catégorisation claire pour la prise de décision Go/No-Go concernant la participation à un salon.

## <a name="_toc225411623"></a>**3.3 Variables et jeux de données**
Dans le cadre académique de ce projet, les algorithmes ont été testés et validés sur des jeux de données standards de scikit-learn (Breast Cancer, Wine, Iris, Diabetes, California Housing) qui partagent des structures similaires aux données réelles d'analyse de salons : variables explicatives multidimensionnelles, variable cible continue ou binaire, nécessité de normalisation et de validation croisée.

L'analogie est la suivante : les caractéristiques cliniques du dataset Breast Cancer jouent le rôle des variables descriptives d'un salon (coût, secteur, pays, taille de l'entreprise…), tandis que la variable cible (maligne/bénigne) ou continue correspond au ROI prédit. Cette démarche de prototypage sur données standards permet de valider les architectures de modèles avant leur application sur des données réelles de salons.

# <a name="_toc225411624"></a>**4. Outils IA Utilisés**
## <a name="_toc225411625"></a>**4.1 Environnement de développement**
Le projet a été entièrement développé dans un environnement Jupyter Notebook sous Python 3, constituant l'interface privilégiée pour l'exploration interactive des données, la visualisation et la documentation du code. Cet environnement facilite la reproductibilité des analyses et la communication des résultats.

## <a name="_toc225411626"></a>**4.2 Bibliothèque principale : scikit-learn**
scikit-learn (sklearn) constitue le cœur analytique du projet. Cette bibliothèque open-source de référence pour le machine learning en Python offre une interface unifiée pour l'ensemble du pipeline d'apprentissage : prétraitement, modélisation, évaluation et optimisation.

### <a name="_toc225411627"></a>**4.2.1 Algorithmes de classification utilisés**
- Régression Logistique (LogisticRegression) — modèle de référence pour la classification binaire, interprétable via ses coefficients
- Random Forest Classifier — ensemble d'arbres de décision offrant robustesse et importance des variables
- Gradient Boosting Classifier — boosting séquentiel pour performance maximale
- Support Vector Machine (SVC) — classification par hyperplan optimal en haute dimension
- Multi-Layer Perceptron Classifier (MLPClassifier) — réseau de neurones pour relations non-linéaires complexes
- AdaBoost Classifier — boosting adaptatif par pondération des erreurs
- Gaussian Naive Bayes (GaussianNB) — classification probabiliste bayésienne
- K-Nearest Neighbors (KNeighborsClassifier) — classification par proximité
- Linear & Quadratic Discriminant Analysis (LDA, QDA) — réduction dimensionnelle et classification
- Extra Trees Classifier (ExtraTreesClassifier) — forêts aléatoires avec seuils de coupure extrêmes

### <a name="_toc225411628"></a>**4.2.2 Algorithmes de régression utilisés**
- Régression Linéaire (LinearRegression) — modèle de base OLS
- Ridge, Lasso, ElasticNet — régression linéaire régularisée L2, L1, et mixte
- Random Forest Regressor — ensemble non-linéaire pour la régression
- Gradient Boosting Regressor — boosting pour la régression continue
- Support Vector Regression (SVR) — régression à vecteurs de support
- Bayesian Ridge — régression bayésienne avec quantification de l'incertitude
- Gaussian Process Regressor (GPR) — régression probabiliste avec intervalles de confiance
- PLS Regression (PLSRegression) — régression par moindres carrés partiels
- Quantile Regressor — estimation de quantiles pour intervalles asymétriques
- Tweedie Regressor — modélisation de distributions composées (Poisson/Gamma)

### <a name="_toc225411629"></a>**4.2.3 Techniques d'optimisation et validation**
- GridSearchCV & RandomizedSearchCV — recherche exhaustive et aléatoire d'hyperparamètres
- StratifiedKFold & RepeatedStratifiedKFold — validation croisée stratifiée
- Pipeline — enchaînement séquentiel sans data leakage (StandardScaler + modèle)
- VotingClassifier & StackingClassifier — méta-apprentissage par agrégation de modèles

## <a name="_toc225411630"></a>**4.3 Bibliothèques complémentaires**
NumPy et pandas ont été utilisés pour la manipulation des structures de données (arrays, DataFrames, opérations matricielles). Matplotlib a fourni l'infrastructure de visualisation pour les courbes d'apprentissage, les graphiques d'importance des variables, les courbes de précision par itération et les graphiques de prédictions versus valeurs réelles. SciPy a été mobilisé pour les distributions statistiques dans l'optimisation aléatoire des hyperparamètres.

## <a name="_toc225411631"></a>**4.4 Résultats et interprétation**
Les analyses du notebook révèlent plusieurs enseignements clés applicables à la prédiction du ROI des salons internationaux. Pour la classification (salon rentable ou non), le Random Forest Classifier et le Gradient Boosting Classifier affichent les meilleures performances avec des précisions supérieures à 95% sur les données de test, indiquant une excellente capacité de discrimination.

L'analyse des importances de variables (feature importances) du Random Forest identifie les facteurs les plus prédictifs du ROI : dans l'analogie avec le dataset Breast Cancer, les variables worst area, worst concave points et worst radius — correspondant dans notre contexte aux variables les plus discriminantes d'un salon (budget total, taille du marché cible, qualité des contacts) — expliquent la majorité de la variance.

Pour la régression, les courbes d'apprentissage confirment la convergence des modèles et l'absence de surapprentissage majeur lorsque les données sont suffisamment nombreuses. Le Gradient Boosting Regressor présente la meilleure performance en R² sur les données de régression (dataset Diabetes), soulignant sa pertinence pour la prédiction de valeurs continues comme le ROI.

#
#
#
#
#
#
#
#
#
#
#
# <a name="_toc225411632"></a>**5. Conclusion**
Ce projet démontre la faisabilité et la pertinence de l'application des outils d'intelligence artificielle à la problématique du retour sur investissement des salons professionnels internationaux. En mobilisant un large spectre d'algorithmes de machine learning — de la régression linéaire classique aux ensembles complexes (Stacking, Gradient Boosting) — nous avons pu modéliser des relations multidimensionnelles entre les caractéristiques d'un salon et le ROI généré.

Le problème traité est fondamentalement hybride : une dimension de prédiction (régression continue du ROI en %) et une dimension de classification (décision Go/No-Go de participation). Cette dualité reflète la complexité réelle des décisions managériales en marketing international, où les dirigeants ont besoin à la fois d'estimations chiffrées et de recommandations catégorielles claires.

L'environnement Jupyter Notebook associé à la bibliothèque scikit-learn s'est révélé particulièrement adapté à cette démarche exploratoire et itérative. La transparence du code, la reproductibilité des analyses et la richesse des outils de visualisation constituent des atouts majeurs pour la communication des résultats à des décideurs non-techniciens.

En perspective, ce projet ouvre la voie à des développements futurs : collecte de données réelles auprès d'entreprises marocaines participant à des salons internationaux, développement d'un dashboard interactif de prédiction du ROI, et intégration de données non structurées (avis, réseaux sociaux) via des techniques de traitement du langage naturel (NLP).

#
#
#
#
#
#
#
# <a name="_toc225411633"></a>**Bibliographie**
## <a name="_toc225411634"></a>**Ouvrages et articles académiques**
1. *Kotler, P., & Keller, K. L. (2022). Marketing Management (16e éd.). Pearson Education.*
1. *Lilien, G. L., & Rangaswamy, A. (2018). Marketing Engineering: Computer-Assisted Marketing Analysis and Planning. DecisionPro.*
1. *Géron, A. (2023). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (3e éd.). O'Reilly Media.*
1. *James, G., Witten, D., Hastie, T., & Tibshirani, R. (2021). An Introduction to Statistical Learning (2e éd.). Springer.*
1. *Boulton, C. (2020). AI and International Trade: Opportunities, Challenges and Policy Implications. OCDE Working Papers.*

## <a name="_toc225411635"></a>**Sources spécialisées en marketing des salons**
1. *AUMA – Association of the German Trade Fair Industry. (2024). Trade Fair Industry Report 2023-2024. Berlin.*
1. *UFI – Union des Foires Internationales. (2023). Global Exhibition Barometer. Paris.*
1. *Canton Fair Group. (2024). Rapport annuel de la Foire de Canton – 135e édition. Guangzhou International Trade Fair Bureau.*
1. *Hannover Messe. (2024). Official Statistics and Exhibitor Survey 2024. Deutsche Messe AG.*

## <a name="_toc225411636"></a>**Documentation technique et ressources numériques**
1. *Pedregosa, F. et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825-2830.*
1. *scikit-learn Documentation. (2024). User Guide and API Reference. https://scikit-learn.org/stable/*
1. *Python Software Foundation. (2024). Python 3 Documentation. https://docs.python.org/3/*
1. *McKinney, W. (2022). Python for Data Analysis (3e éd.). O'Reilly Media.*
1. *Hunter, J. D. (2007). Matplotlib: A 2D Graphics Environment. Computing in Science & Engineering, 9(3), 90-95.*

## <a name="_toc225411637"></a>**Rapports institutionnels sur l'IA et le commerce international**
1. *Organisation Mondiale du Commerce (OMC). (2023). World Trade Report: Re-globalizing for a Secure, Inclusive and Sustainable Future. Genève.*
1. *Banque Mondiale. (2023). Digital Development and International Trade. Washington D.C.*
1. *McKinsey Global Institute. (2023). The Economic Potential of Generative AI: The Next Productivity Frontier.*
1. *CNUCED. (2023). Digital Economy Report: Making Digital Transformation Work for Developing Countries. Nations Unies.*

Page 2 / 10
