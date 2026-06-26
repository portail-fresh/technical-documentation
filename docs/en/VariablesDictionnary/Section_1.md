---
hide:
  - toc
---

# 1. Study related information

<table>
<thead>
<tr BGCOLOR="#00a6e2">
<th style="color:#FFFFFF;">FReSH PID</th>
<th style="color:#FFFFFF;">Variable Name</th>
<th style="color:#FFFFFF;">Label FR</th>
<th style="color:#FFFFFF;">Description FR</th>
<th style="color:#FFFFFF;">Label EN</th>
<th style="color:#FFFFFF;">Description EN</th>
<th style="color:#FFFFFF;">Data Type</th>
<th style="color:#FFFFFF;">Cardinality</th>
</tr>
</thead>
<tbody>
<tr>
<td>S-064</td>
<td><strong>StudyRelatedInfo</strong></td>
<td>Informations relatives à l'étude</td>
<td></td>
<td>Study related informations</td>
<td></td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-063</td>
<td><strong>StudyOverview</strong></td>
<td>Présentation de l'étude</td>
<td></td>
<td>Study overview</td>
<td></td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-016</td>
<td><strong>Title</strong></td>
<td>Titre de l'étude</td>
<td></td>
<td>Study title</td>
<td></td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-017</td>
<td><strong>Acronym</strong></td>
<td>Acronyme de l'étude</td>
<td></td>
<td>Study acronym</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-051</td>
<td><strong>StudyStatus</strong></td>
<td>Statut actuel de l'étude</td>
<td>Indique le statut actuel de l'étude</td>
<td>Current study status</td>
<td>Indicates the current status of the study</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/StudyStatus/"><i>Study status</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-052</td>
<td><strong>Purpose</strong></td>
<td>Objectifs de l'étude</td>
<td></td>
<td>Study objectives</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-053</td>
<td><strong>Summary</strong></td>
<td>Résumé de l'étude</td>
<td></td>
<td>Study summary</td>
<td></td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-056</td>
<td><strong>Keyword</strong></td>
<td>Mots-clés libres</td>
<td></td>
<td>Free keywords</td>
<td></td>
<td><i>string</i></td>
<td>0-n</td>
</tr>
<tr>
<td>S-028</td>
<td><strong>Theme</strong></td>
<td>Thématique</td>
<td>Section dédiée aux aspects thématiques de l’étude</td>
<td>Theme</td>
<td>Section dedicated to the thematic aspects of the study</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-169</td>
<td><strong>IsHealthTheme</strong></td>
<td>L'étude porte-t-elle sur une ou plusieurs spécialité(s) médicale(s) ?</td>
<td></td>
<td>Does the study cover one or more medical speciality(ies)?</td>
<td></td>
<td>boolean</td>
<td>1</td>
</tr>
<tr>
<td>E-054</td>
<td><strong>HealthTheme</strong></td>
<td>Spécialité(s) médicale(s) concernée(s)</td>
<td>Spécialités médicales auxquelles se rapporte l'étude</td>
<td>Medical speciality(ies) concerned</td>
<td>Medical specialties covered by the study</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/health-theme/"><i>Health theme</i></a></td>
<td>0-n</td>
</tr>
<tr>
<td>E-186</td>
<td><strong>OtherHealthTheme</strong></td>
<td>Autre spécialité médicale, précisions</td>
<td></td>
<td>Other medical specialty, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-057</td>
<td><strong>HealthDeterminant</strong></td>
<td>Déterminants de santé</td>
<td>Facteurs personnels, sociaux, économiques et environnementaux qui déterminent l’état de santé des individus ou des populations.</td>
<td>Health determinants</td>
<td>Personal, social, economic, and environmental factors that determine the health status of individuals or populations.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Health-determinant/"><i>Health determinant</i></a></td>
<td>0-n</td>
</tr>
<tr>
<td>E-172</td>
<td><strong>OtherSocioDemoDeterminant</strong></td>
<td>Autres déterminants socio-démographiques et économiques, précisions</td>
<td></td>
<td>Other socio-demographic and economic determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-173</td>
<td><strong>OtherEnvironmentalDeterminant</strong></td>
<td>Autres déterminants environnementaux, précisions</td>
<td></td>
<td>Other environmental determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-174</td>
<td><strong>OtherHealthcarSystemDeterminant</strong></td>
<td>Autres déterminants liés au système de santé, précisions</td>
<td></td>
<td>Other healthcare system determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-175</td>
<td><strong>OtherBehavioralDeterminant</strong></td>
<td>Autres déterminants comportementaux, précisions</td>
<td></td>
<td>Other behavioral determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-176</td>
<td><strong>OtherBiologicalDeterminant</strong></td>
<td>Autres déterminants biologiques, précisions</td>
<td></td>
<td>Other biological determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-177</td>
<td><strong>OtherDeterminant</strong></td>
<td>Autres déterminants, précisions</td>
<td></td>
<td>Other determinants, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-055</td>
<td><strong>Pathology</strong></td>
<td>Pathologie(s), affection(s) ou diagnostic(s) ciblé(s) par l’étude</td>
<td>Pathologies, affections ou diagnostics qui constituent l’objet principal de la recherche.</td>
<td>Pathology(ies), condition(s) or diagnose(s) targeted by the study</td>
<td>Pathology, condition, or diagnosis that constitutes the main focus of the research.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Pathology/"><i>ICD-11</i></a></td>
<td>0-n</td>
</tr>
<tr>
<td>E-059</td>
<td><strong>RareDiseases</strong></td>
<td>L'étude porte-t-elle sur une ou plusieurs maladie(s) rare(s) ?</td>
<td></td>
<td>Does the study cover one or more rare disease(s)?</td>
<td></td>
<td>boolean</td>
<td>1</td>
</tr>
<tr>
<td>S-046</td>
<td><strong>Population</strong></td>
<td>Population de l'étude</td>
<td>La catégorie ou groupe de personnes qui font l'objet de la recherche.</td>
<td>Study population</td>
<td>The category or groupe of persons targeted by the research.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-106</td>
<td><strong>PopulationType</strong></td>
<td>Type de population</td>
<td>Catégorie principale des personnes concernées par l’étude (population générale, patients, personnes en situation de handicap).</td>
<td>Population type</td>
<td>Main category of persons concerned by the study (general population, patients, persons with disabilities).</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/populationType/"><i>Population type</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-107</td>
<td><strong>OtherPopulationType</strong></td>
<td>Autre type de population, précisions</td>
<td>Indique la catégorie de population étudiée lorsqu’elle ne correspond pas aux options proposées</td>
<td>Other population type, details</td>
<td>Indicates the population category studied when it does not correspond to the options provided.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-047</td>
<td><strong>DemographicInfo</strong></td>
<td>Caractéristiques démographiques</td>
<td>Attributs démographiques qui caractérisent les participants de l'étude</td>
<td>Demographic characteristics</td>
<td>Demographic attributes that characterise study participants</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-108</td>
<td><strong>Sex</strong></td>
<td>Sexe</td>
<td>Un type de critère d'éligibilité qui indique le sexe,  basé sur des distinctions biologiques, des personnes pouvant participer à une étude.</td>
<td>Sex</td>
<td>A type of eligibility criterion that indicates the sex, based on biological distinctions, of individuals who may participate in a study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Sex/"><i>Sex</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-109</td>
<td><strong>Age</strong></td>
<td>Age</td>
<td>Un type de critère d'éligibilité qui indique la tranche d'âge d'une personne pouvant participer à une étude.</td>
<td>Age</td>
<td>A type of eligibility criteria that indicates the age groupe of a person to participate in a study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Age/"><i>Age</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>S-048</td>
<td><strong>OtherClusion</strong></td>
<td>Autres critères d'éligibilité</td>
<td>Autres exigences clés auxquelles les participants à une étude doivent satisfaire ou caractéristiques qu'ils doivent posséder. Les critères d'éligibilité comprennent à la fois les critères d'inclusion (qui sont requis pour qu'une personne puisse participer à l'étude) et les critères d'exclusion (qui empêchent une personne de participer).</td>
<td>Other eligibility criteria</td>
<td>Other key requirements that participants in a study must meet or the characteristics they must have. Eligibility criteria consist of both inclusion criteria (which are required for a person to participate in the study) and exclusion criteria (which prevent a person from participating).</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-110</td>
<td><strong>InclusionCriterion</strong></td>
<td>Critères d'inclusion</td>
<td>Conditions que doivent remplir les personnes pour pouvoir participer à l’étude.</td>
<td>Inclusion criteria</td>
<td>Conditions that individuals must meet in order to participate in the study.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-111</td>
<td><strong>ExclusionCriterion</strong></td>
<td>Critères d'exclusion</td>
<td>Caractéristiques qui rendent une personne non éligible à participer à l’étude, même si elle répond aux critères d’inclusion.</td>
<td>Exclusion criteria</td>
<td>Characteristics that make a person ineligible to participate in the study, even if they meet the inclusion criteria.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-049</td>
<td><strong>GeographicalCoverage</strong></td>
<td>Champ géographique</td>
<td>Aire géographique couverte par la population étudiée.</td>
<td>Geographical coverage</td>
<td>Geographical area covered by the population studied.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-112</td>
<td><strong>Nation</strong></td>
<td>Pays concerné(s)</td>
<td>Pays concernés par l'étude</td>
<td>Country(ies) concerned</td>
<td>Countries covered by the study</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/GeographicalCoverage/"><i>Geographical coverage</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-113</td>
<td><strong>FranceRegion</strong></td>
<td>Région(s) française(s) concernée(s)</td>
<td>Régions françaises couvertes par l'étude</td>
<td>French region(s) concerned</td>
<td>French regions covered by the study</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/GeographicalCoverage/"><i>Geographical coverage</i></a></td>
<td>0-n</td>
</tr>
<tr>
<td>E-114</td>
<td><strong>GeoDetail</strong></td>
<td>Champ géographique, précisions</td>
<td>Précisions sur le périmètre géographique concerné par l'étude</td>
<td>Geographical coverage, details</td>
<td>Details on the geographical scope covered by the study</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
</tbody>
</table>