# Analyse du Marché de l'Emploi au Maroc 2023–2024
Tableau de bord interactif réalisé avec Power BI, basé sur 700 offres d'emploi couvrant 8 villes marocaines et 12 secteurs d'activité sur la période 2023–2024.

### Contenu du projet
FichierDescriptiondashboard_emploi_maroc.pbixFichier Power BI principaldataset_emploi_maroc.xlsxDataset source (700 offres d'emploi)

### Structure du Dataset
ColonneDescriptionOffre_IDIdentifiant unique de l'offrePosteIntitulé du posteSecteurSecteur d'activité (12 secteurs)EntrepriseNom de l'entrepriseVilleVille de l'offreType_ContratCDI / CDD / Freelance / StageNiveau_ExpérienceDébutant → ExpertNiveau_ÉtudesBac+2 → Bac+8Salaire_Min_MADSalaire minimum en MADSalaire_Max_MADSalaire maximum en MADTélétravailPrésentiel / Hybride / Full RemoteCompétencesCompétences requisesLanguesLangues demandéesDate_PublicationDate de publication de l'offreMoisMois de publicationAnnéeAnnée de publication

#### KPIs Clés
IndicateurValeur Nombre total d'offres700 Salaire maximum55 000 MAD Salaire minimum4 000 MAD %CDI 41.71% %Télétravail 36.71%

#### Pages du Dashboard
### Page 1 — Vue Générale
Aperçu global du marché : répartition des offres par secteur, type de contrat, mode de travail et salaire moyen par niveau d'expérience.
Visualisations :

KPI Cards : Nombre Offres / Salaire Max / %CDI / %Télétravail
Bar Chart : Nombre d'offres par secteur
Donut Chart : Répartition par Type_Contrat (CDI 41.71% — CDD 28.57% — Freelance 16.72% — Stage 13%)
Donut Chart : Répartition par Télétravail (Présentiel 63.29% — Hybride 19.86% — Full Remote 16.86%)
Column Chart : Salaire Moyen par Niveau_Expérience

Insights :

L'IT & Digital est le secteur le plus actif sur le marché
Le CDI reste le contrat dominant malgré une présence notable du Freelance
Plus d'un tiers des offres proposent une option de télétravail
L'écart salarial entre Débutant et Expert dépasse les 30 000 MAD


### Page 2 — Géographie & Entreprises
Analyse territoriale des offres et classement des entreprises par volume et rémunération.
Visualisations :

Clustered Bar Chart : Nombre d'offres par Ville et Année (2023 vs 2024)
Bar Chart : Salaire Moyen par Ville
Table : Top entreprises — Nombre d'offres + Salaire Moyen
Column Chart : Répartition des offres par Niveau_Expérience

Insights :

Casablanca concentre le plus grand volume d'offres, suivie de Rabat et Tanger
Oujda affiche le salaire moyen le plus élevé malgré un faible volume d'offres
CNSS (22 561 MAD), Total Maroc (21 513 MAD) et OCP Group (20 352 MAD) sont les entreprises les mieux rémunératrices
Le profil Intermédiaire (2–5 ans) est le plus recherché sur le marché


### Page 3 — Tendances & Compétences
Analyse temporelle des recrutements, niveaux d'études requis et salaires par secteur.
Visualisations :

Line Chart : Évolution du nombre d'offres par Mois
Bar Chart : Nombre d'offres par Niveau_Études
Stacked Bar Chart : Offres par Secteur et Type_Contrat
Bar Chart : Salaire Moyen par Secteur

Insights :

Les recrutements sont réguliers toute l'année sans saisonnalité marquée (entre 50 et 70 offres/mois)
Le Bac+5 est le niveau d'études le plus demandé, suivi du Bac+3
Transport & Logistique et Tourisme affichent les salaires moyens les plus élevés par secteur
Éducation & Formation et Juridique présentent les salaires moyens les plus bas


### Technologies utilisées

Power BI Desktop
Microsoft Excel (source de données)
Dataset : 700 offres d'emploi — Maroc 2023–2024 (données simulées basées sur le marché réel)


 Comment utiliser ce projet

Cloner le repository :

bashgit clone https://github.com/Faridoumnay/ emploi_maroc.git

Ouvrir dashboard_emploi_maroc.pbix avec Power BI Desktop
Re-lier le dataset si nécessaire : Transform Data → Data Source Settings
Explorer les 3 pages du dashboard avec les slicers disponibles


## Auteur
### Farid Oumnay
