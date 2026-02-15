Contexte
Il s'agit d'un jeu de données multivarié, c'est-à-dire comportant diverses variables mathématiques ou statistiques distinctes, et nécessitant une analyse de données numériques multivariées. Il est composé de 14 attributs : l'âge, le sexe, le type de douleur thoracique, la pression artérielle au repos, le cholestérol sérique, la glycémie à jeun, les résultats de l'électrocardiogramme au repos, la fréquence cardiaque maximale atteinte, l'angor d'effort, le sous-décalage du segment ST induit par l'effort par rapport au repos (oldpeak), la pente du segment ST au pic d'effort, le nombre de vaisseaux principaux et la thalassémie. Cette base de données comprend 76 attributs, mais toutes les études publiées se rapportent à l'utilisation d'un sous-ensemble de 14 d'entre eux. La base de données de Cleveland est la seule utilisée à ce jour par les chercheurs en apprentissage automatique. L'une des principales tâches liées à ce jeu de données est de prédire, à partir des attributs fournis, si un patient est atteint d'une maladie cardiaque. Une autre tâche consiste à diagnostiquer et à extraire diverses informations de ce jeu de données afin de mieux comprendre le problème.

Description des colonnes :
id(Identifiant unique pour chaque patient)
age(Âge du patient en années)
origin(lieu d'études)
sex(Homme/Femme)
cptype de douleur thoracique ([angine typique, angine atypique, non angineuse, asymptomatique])
trestbpspression artérielle au repos (pression artérielle au repos (en mm Hg à l'admission à l'hôpital))
chol(cholestérol sérique en mg/dl)
fbs(si la glycémie à jeun est supérieure à 120 mg/dl)
restecg (Résultats de l'électrocardiogramme au repos)
-- Valeurs : [normal, anomalie du segment ST, hypertrophie du VG]
thalach: fréquence cardiaque maximale atteinte
exang: angine de poitrine induite par l'effort (Vrai/Faux)
oldpeakDépression du segment ST induite par l'exercice par rapport au repos
slope: la pente du segment ST à l'effort maximal
ca: nombre de vaisseaux principaux (0-3) colorés par fluoroscopie
thal: [normal ; défaut fixe ; défaut réversible]
num: l'attribut prédit
