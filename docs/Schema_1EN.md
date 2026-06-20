---
hide:
  - toc
---

# 1. Study related information - Informations rélatives à l'étude

| PID | Variable Name | Label FR | Description FR | Label EN | Description EN | Variable Type | Cardinalité |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S-064 | **StudyRelatedInfo** | Informations relatives à l'étude |  | Study related informations |  | section | 1 |
| S-063 | **StudyOverview** | Présentation de l'étude |  | Study overview |  | section | 1 |
| E-016 | **Title** | Titre de l'étude |  | Study title |  | string '' | 1 |
| E-017 | **Acronym** | Acronyme de l'étude |  | Study acronym |  | string '' | 0-1 |
| E-051 | **StudyStatus** | Statut actuel de l'étude | Indique le statut actuel de l'étude | Current study status | Indicates the current status of the study | [choix unique](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/StudyStatus/) | 1 |
| E-052 | **Purpose** | Objectifs de l'étude |  | Study objectives |  | string '' | 0-1 |
| E-053 | **Summary** | Résumé de l'étude |  | Study summary |  | string '' | 1 |
| E-056 | **Keyword** | Mots-clés libres |  | Free keywords |  | string '' | 0-n |
|  |  | ST : A séparer par un point-virgule |  | ST : To separate by a semicolon |  |  | - |
| S-028 | **Theme** | Thématique | Section dédiée aux aspects thématiques de l’étude | Theme | Section dedicated to the thematic aspects of the study | section | 1 |
| E-169 | **IsHealthTheme** | L'étude porte-t-elle sur une ou plusieurs spécialité(s) médicale(s) ? |  | Does the study cover one or more medical speciality(ies)? |  | boolean | 1 |
| E-054 | **HealthTheme** | Spécialité(s) médicale(s) concernée(s) | Spécialités médicales auxquelles se rapporte l'étude | Medical speciality(ies) concerned | Medical specialties covered by the study | [choix multiple](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/health-theme/) | 0-n |
| E-186 | **OtherHealthTheme** | Autre spécialité médicale, précisions |  | Other medical specialty, details |  | string '' | 0-1 |
| E-057 | **HealthDeterminant** | Déterminants de santé | Facteurs personnels, sociaux, économiques et environnementaux qui déterminent l’état de santé des individus ou des populations. | Health determinants | Personal, social, economic, and environmental factors that determine the health status of individuals or populations. | [choix multiple](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/Health-determinant/) | 0-n |
| E-172 | **OtherSocioDemoDeterminant** | Autres déterminants socio-démographiques et économiques, précisions |  | Other socio-demographic and economic determinants, details |  | string '' | 0-1 |
| E-173 | **OtherEnvironmentalDeterminant** | Autres déterminants environnementaux, précisions |  | Other environmental determinants, details |  | string '' | 0-1 |
| E-174 | **OtherHealthcarSystemDeterminant** | Autres déterminants liés au système de santé, précisions |  | Other healthcare system determinants, details |  | string '' | 0-1 |
| E-175 | **OtherBehavioralDeterminant** | Autres déterminants comportementaux, précisions |  | Other behavioral determinants, details |  | string '' | 0-1 |
| E-176 | **OtherBiologicalDeterminant** | Autres déterminants biologiques, précisions |  | Other biological determinants, details |  | string '' | 0-1 |
| E-177 | **OtherDeterminant** | Autres déterminants, précisions |  | Other determinants, details |  | string '' | 0-1 |
| E-055 | **Pathology** | Pathologie(s), affection(s) ou diagnostic(s) ciblé(s) par l’étude | Pathologies, affections ou diagnostics qui constituent l’objet principal de la recherche. | Pathology(ies), condition(s) or diagnose(s) targeted by the study | Pathology, condition, or diagnosis that constitutes the main focus of the research. | [choix multiple](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/Pathology/) | 0-n |
| E-059 | **RareDiseases** | L'étude porte-t-elle sur une ou plusieurs maladie(s) rare(s) ? |  | Does the study cover one or more rare disease(s)? |  | boolean | 1 |
| S-046 | **Population** | Population de l'étude | La catégorie ou groupe de personnes qui font l'objet de la recherche. | Study population | The category or groupe of persons targeted by the research. | section | 1 |
| E-106 | **PopulationType** | Type de population | Catégorie principale des personnes concernées par l’étude (population générale, patients, personnes en situation de handicap). | Population type | Main category of persons concerned by the study (general population, patients, persons with disabilities). | [choix unique](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/populationType/) | 1 |
| E-107 | **OtherPopulationType** | Autre type de population, précisions | Indique la catégorie de population étudiée lorsqu’elle ne correspond pas aux options proposées | Other population type, details | Indicates the population category studied when it does not correspond to the options provided. | string '' | 0-1 |
| S-047 | **DemographicInfo** | Caractéristiques démographiques | Attributs démographiques qui caractérisent les participants de l'étude | Demographic characteristics | Demographic attributes that characterise study participants | section | 1 |
| E-108 | **Sex** | Sexe | Un type de critère d'éligibilité qui indique le sexe,  basé sur des distinctions biologiques, des personnes pouvant participer à une étude. | Sex | A type of eligibility criterion that indicates the sex, based on biological distinctions, of individuals who may participate in a study. | [choix unique](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/Sex/) | 1-n |
| E-109 | **Age** | Age | Un type de critère d'éligibilité qui indique la tranche d'âge d'une personne pouvant participer à une étude. | Age | A type of eligibility criteria that indicates the age groupe of a person to participate in a study. | [choix unique](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/Age/) | 1-n |
| S-048 | **OtherClusion** | Autres critères d'éligibilité | Autres exigences clés auxquelles les participants à une étude doivent satisfaire ou caractéristiques qu'ils doivent posséder. Les critères d'éligibilité comprennent à la fois les critères d'inclusion (qui sont requis pour qu'une personne puisse participer à l'étude) et les critères d'exclusion (qui empêchent une personne de participer). | Other eligibility criteria | Other key requirements that participants in a study must meet or the characteristics they must have. Eligibility criteria consist of both inclusion criteria (which are required for a person to participate in the study) and exclusion criteria (which prevent a person from participating). | section | 1 |
| E-110 | **InclusionCriterion** | Critères d'inclusion | Conditions que doivent remplir les personnes pour pouvoir participer à l’étude. | Inclusion criteria | Conditions that individuals must meet in order to participate in the study. | string '' | 0-1 |
| E-111 | **ExclusionCriterion** | Critères d'exclusion | Caractéristiques qui rendent une personne non éligible à participer à l’étude, même si elle répond aux critères d’inclusion. | Exclusion criteria | Characteristics that make a person ineligible to participate in the study, even if they meet the inclusion criteria. | string '' | 0-1 |
| S-049 | **GeographicalCoverage** | Champ géographique | Aire géographique couverte par la population étudiée. | Geographical coverage | Geographical area covered by the population studied. | section | 1 |
| E-112 | **Nation** | Pays concerné(s) | Pays concernés par l'étude | Country(ies) concerned | Countries covered by the study | [choix unique](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/GeographicalCoverage/) | 1-n |
| E-113 | **FranceRegion** | Région(s) française(s) concernée(s) | Régions françaises couvertes par l'étude | French region(s) concerned | French regions covered by the study | [choix multiple](https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/GeographicalCoverage/) | 0-n |
| E-114 | **GeoDetail** | Champ géographique, précisions | Précisions sur le périmètre géographique concerné par l'étude | Geographical coverage, details | Details on the geographical scope covered by the study | string '' | 0-1 |
