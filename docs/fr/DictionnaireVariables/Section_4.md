---
hide:
  - toc
---

# 4. Collecte et accès aux données

<table>
<thead>
<tr BGCOLOR="#00a6e2">
<th style="color:#FFFFFF;">PID FReSH</th>
<th style="color:#FFFFFF;">Nom Variable</th>
<th style="color:#FFFFFF;">Titre FR</th>
<th style="color:#FFFFFF;">Description FR</th>
<th style="color:#FFFFFF;">Titre EN</th>
<th style="color:#FFFFFF;">Description EN</th>
<th style="color:#FFFFFF;">Type de données</th>
<th style="color:#FFFFFF;">Cardinalité</th>
</tr>
</thead>
<tbody>
<tr>
<td>S-074</td>
<td><strong>DataCollectionAccess</strong></td>
<td>Collecte et accès aux données</td>
<td></td>
<td>Data collection and access</td>
<td></td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-051</td>
<td><strong>DataCollectionIntegration</strong></td>
<td>Collecte et réutilisation de données</td>
<td>Cette section décrit les données utilisées dans l’étude, qu’elles soient collectées spécifiquement pour celle-ci ou réutilisées à partir de sources tierces préexistantes.</td>
<td>Data collection and reuse</td>
<td>This section describes the data used in the study, whether collected specifically for this study or reused from pre-existing third-party sources.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-051</td>
<td><strong>SampleSize</strong></td>
<td>Nombre de participants</td>
<td>Nombre de participants prévus et effectifs</td>
<td>Number of participants</td>
<td>Planned and actual number of participants</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-117</td>
<td><strong>PlannedSampleSize</strong></td>
<td>Nombre prévu de participants</td>
<td>Nombre de participants spécifié dans le plan d'étude ou le protocole</td>
<td>Target number of participants</td>
<td>Number of participants specified in the study design or protocol</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PlannedSampleSize/"><i>Nombre prévu de participants</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-118</td>
<td><strong>FinalSampleSize</strong></td>
<td>Nombre actuel de participants</td>
<td>Nombre de participants qui ont effectivement été inclus ou ont participé</td>
<td>Actual number of participants</td>
<td>Number of participants who were actually included or participated</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-043</td>
<td><strong>CollectionChronology</strong></td>
<td>Chronologie de la collecte</td>
<td>Indique la période pendant laquelle les données de l’étude ont été recueillies.</td>
<td>Collection chronology</td>
<td>Indicates the period during which the study data were collected.</td>
<td><i>section</i></td>
<td>-</td>
</tr>
<tr>
<td>E-096</td>
<td><strong>CollectionStart</strong></td>
<td>Date de début de la collecte (recrutement du premier participant)</td>
<td>la date à laquelle la collecte des données individuelles a commencé dans le cadre de l’étude</td>
<td>Collection start date (recruitment of the first participant)</td>
<td>the date on which the collection of individual data began as part of the study</td>
<td><i>date</i></td>
<td>1</td>
</tr>
<tr>
<td>E-097</td>
<td><strong>CollectionEnd</strong></td>
<td>Date de fin de la collecte (dernier suivi du dernier participant)</td>
<td>la date à laquelle la collecte des données individuelles a été terminée dans le cadre de l’étude</td>
<td>Collection end date (last follow-up of the last participant)</td>
<td>the date on which the collection of individual data was completed as part of the study</td>
<td><i>date</i></td>
<td>1</td>
</tr>
<tr>
<td>E-086</td>
<td><strong>CollectionFrequency</strong></td>
<td>Fréquence de la collecte</td>
<td>Intervalles ou nombre de mesures réalisées au cours de l’étude</td>
<td>Collection frequency</td>
<td>Intervals or number of measurements performed during the study</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>S-041</td>
<td><strong>DataCollection</strong></td>
<td>Informations concernant les données collectées auprès des participants dans le cadre de l'étude</td>
<td>Ensemble des informations recueillies directement auprès des participants au cours de l’étude, que ce soit par observation, mesure, examen, prélèvement, entretien, questionnaire ou suivi.</td>
<td>Information concerning data collected from participants during the study</td>
<td>All information collected directly from study participants during the course of the study, through observation, measurement, examination, sampling, interview, questionnaire, or follow-up.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-042</td>
<td><strong>CollectionProcess</strong></td>
<td>Procédure de collecte</td>
<td>Section décrivant la manière dont les données sont recueillies dans le cadre de l’étude.</td>
<td>Collection procedure</td>
<td>Section describing how data are collected in the study.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-087</td>
<td><strong>CollectionMode</strong></td>
<td>Mode de collecte</td>
<td>Méthode utilisée pour recueillir les données</td>
<td>Collection mode</td>
<td>The method used to collect data</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/collectionMode/"><i>Mode de collecte</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-088</td>
<td><strong>CollectionModeOther</strong></td>
<td>Autre mode de collecte, précisions</td>
<td>Spécifie le mode de collecte si « Autre » a été sélectionné ci-dessus.</td>
<td>Other collection mode, details</td>
<td>Specifies the collection mode if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-089</td>
<td><strong>CollectionModeDetails</strong></td>
<td>Mode de collecte, précisions</td>
<td>Informations complémentaires sur la collecte, comme le contexte, les instruments ou protocoles utilisés.</td>
<td>Collection mode, details</td>
<td>Additional information about the collection, such as context, instruments, or protocols used.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-092</td>
<td><strong>SamplingMode</strong></td>
<td>Procédure d'échantillonage à l'inclusion</td>
<td>Décrit la méthode utilisée pour sélectionner les participants lors de leur inclusion dans l’étude</td>
<td>Sampling procedure at inclusion</td>
<td>Describes the method used to select participants when they were included in the study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/SamplingMode/"><i>Procédure d'échantillonnage</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-093</td>
<td><strong>SamplingModeOther</strong></td>
<td>Autre procédure d'échantillonnage, précisions</td>
<td>Spécifie la procédure d'échantillonnage si « Autre » a été sélectionné ci-dessus.</td>
<td>Other sampling mode, details</td>
<td>Specifies the sampling procedure if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-095</td>
<td><strong>RecruitmentSource</strong></td>
<td>Source de recrutement des participants</td>
<td>Décrit l’origine ou le canal utilisé pour identifier et inclure les participants dans l’étude</td>
<td>Participants recruitment source</td>
<td>Describes the origin or channel used to identify and include participants in the study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/RecruitmentSource/"><i>Source de recrutement</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-095</td>
<td><strong>RecruitmentSourceOther</strong></td>
<td>Autre source de recrutement, précisions</td>
<td>Spécifie la source de recrutement si « Autre » a été sélectionné ci-dessus.</td>
<td>Other recruitment source, details</td>
<td>Specify the recruitment source if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-044</td>
<td><strong>ActiveFollowUp</strong></td>
<td>Suivi actif des participants</td>
<td>Le suivi actif désigne une procédure systématique de collecte d’informations auprès des participants après leur inclusion dans l’étude, à l’initiative de l’équipe de recherche.</td>
<td>Active follow-up</td>
<td>Active follow-up refers to a systematic process of collecting information from participants after their inclusion in the study, initiated by the research team.</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-098</td>
<td><strong>IsActiveFollowUp</strong></td>
<td>Un suivi actif des participants est-il réalisé ?</td>
<td>Indique si les participants font l’objet d’un suivi actif dans le cadre de l’étude et la modalité du suivi</td>
<td>It is an active follow-up?</td>
<td>Indicates whether participants are followed over time within the study and the method used.</td>
<td>boolean</td>
<td>1</td>
</tr>
<tr>
<td>E-099</td>
<td><strong>FollowUpMode</strong></td>
<td>Modalités du suivi actif</td>
<td>Indique les modalités du suivi actif des participants</td>
<td>Follow-up method</td>
<td>Indicates the ways of active follow-up of participants.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/FollowUpMode/"><i>Modalités de suivi</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-100</td>
<td><strong>FollowUpModeOther</strong></td>
<td>Autre modalité de suivi, précisions</td>
<td>Spécifie la modalité de suivi si « Autre » a été sélectionné ci-dessus.</td>
<td>Other follow-up method, details</td>
<td>Specifies the follow-up method if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-052</td>
<td><strong>DataTypes</strong></td>
<td>Types de données</td>
<td>Décrit les types de données recueillies au cours de l'étude auprès des participants</td>
<td>Data types</td>
<td>Describes the types of data collected directly from study participants during the study</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-119</td>
<td><strong>DataType</strong></td>
<td>Type de données</td>
<td>Sélection, à partir d’une liste prédéfinie, du ou des types de données collectées dans l’étude</td>
<td>Data type</td>
<td>Selection, from a predefined list, of the type(s) of data collected in the study</td>
<td><i>choix multiple</i></td>
<td>1-n</td>
</tr>
<tr>
<td>E-124</td>
<td><strong>DataTypeOther</strong></td>
<td>Autre type de données, précisions</td>
<td>Spécifie le type de données si « Autre » a été sélectionné ci-dessus.</td>
<td>Other data type, details</td>
<td>Specifies the data type if “Other” was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-120</td>
<td><strong>ClinicalDataDetails</strong></td>
<td>Données cliniques, précisions</td>
<td>Précisions concernant les données cliniques collectées</td>
<td>Clinical data, details</td>
<td>Details regarding the clinical data collected</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-198</td>
<td><strong>ParaclinicalDataOther</strong></td>
<td>Autres données paracliniques (hors biologiques), précisions</td>
<td>Spécifie le type de données paracliniques (hors biologiques) si « Autre » a été sélectionné ci-dessus.</td>
<td>Other paraclinical data (non-biological), details</td>
<td>Specify the type of paraclinical data (non-biological)</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-121</td>
<td><strong>BiologicalDataDetails</strong></td>
<td>Données biologiques, précisions</td>
<td>Précisions concernant les données biologiques collectées</td>
<td>Biological data, details</td>
<td>Details regarding the biological data collected</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-122</td>
<td><strong>isDataInBiobank</strong></td>
<td>Présence d'échantillons de données biologiques dans une biobanque ?</td>
<td>Indique si une collection d’échantillons biologiques est conservée et mis à disposition au sein d'une biobanque</td>
<td>Presence of biological data samples in a biobank ?</td>
<td>Indicates whether a collection of biological samples is stored and made available in a biobank.</td>
<td>boolean</td>
<td>0-1</td>
</tr>
<tr>
<td>E-123</td>
<td><strong>BiobankContent</strong></td>
<td>Nature des échantillons</td>
<td>Sélection, à partir d’une liste prédéfinie, du ou des types d'échantillons contenus dans la biobanque</td>
<td>Nature of samples</td>
<td>Selection, from a predefined list, of the type(s) of samples contained in the biobank</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/BiobankContent/"><i>Nature des échantillons</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-155</td>
<td><strong>BiobankContentOther</strong></td>
<td>Autre échantillon, précisions</td>
<td></td>
<td>Other sample, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-156</td>
<td><strong>OtherLiquidsDetails</strong></td>
<td>Autres liquides ou sécrétions biologiques, précisions</td>
<td></td>
<td>Other fluids and secretions, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-101</td>
<td><strong>IsDataIntegration</strong></td>
<td>Des données individuelles provenant d'autres sources sont-elles réutilisées dans le cadre de cette étude ?</td>
<td>Indique si les données individuelles préexistantes issues de sources tierces ont été utilisées dans le cadre de l'étude</td>
<td>Are individual data from other sources reused in this study?</td>
<td>Indicates whether pre-existing individual data from third-party sources were used in the study.</td>
<td>boolean</td>
<td>1</td>
</tr>
<tr>
<td>S-066</td>
<td><strong>DataIntegration</strong></td>
<td>Réutilisation de données existantes</td>
<td>La réutilisation de données existantes désigne le recours, dans le cadre de l’étude, à des données déjà collectées pour un autre objectif (recherche antérieure, registre, base administrative, dossier médical, etc.), sans nouvelle collecte directe auprès des participants.</td>
<td>Reuse of existing data</td>
<td>The reuse of existing data refers to the use, within the study, of data previously collected for another purpose (such as a prior research project, registry, administrative database, or medical record), without new data collection directly from participants.</td>
<td><i>section</i></td>
<td>-</td>
</tr>
<tr>
<td>E-020</td>
<td><strong>ConformityDeclaration</strong></td>
<td>Déclaration de conformité</td>
<td>Engagement formel qu’un projet de recherche respecte l’ensemble des conditions fixées par une Méthodologie de Référence (MR) de la CNIL, permettant d’utiliser des données de santé sans autorisation spécifique.</td>
<td>Declaration of conformity</td>
<td>Formal statement that a research project complies with all requirements of a CNIL Reference Methodology, allowing the use of health data without specific authorisation.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/ConformityDeclaration/"><i>Déclaration de conformité</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>S-045</td>
<td><strong>ThirdPartySource</strong></td>
<td>Informations concernant les données réutilisées pour l'étude</td>
<td>Cette section décrit les sources des données préexistantes réutilisées dans le cadre de l'étude</td>
<td>Information concerning data reused for the study</td>
<td>This section describes the sources of pre-existing data reused in the study</td>
<td><i>section</i></td>
<td>1-n</td>
</tr>
<tr>
<td>E-102</td>
<td><strong>SourceName</strong></td>
<td>Description de la source</td>
<td>Toute information supplémentaire caractérisant la source ( nom, origine, qualité, modalités d'accès, liens eventuels)</td>
<td>Source description</td>
<td>Any additional information characterising the source (name, origin, quality, access methods, any links)</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-157</td>
<td><strong>SourceId</strong></td>
<td>Identifiant de la source</td>
<td></td>
<td>Source identifier</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-103</td>
<td><strong>SourceType</strong></td>
<td>Type de source</td>
<td>Type de source des données utilisées</td>
<td>Source type</td>
<td>Type of data source used</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/SourceType/"><i>Type de source</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-104</td>
<td><strong>SourcePurpose</strong></td>
<td>Objectif de l'intégration de la source</td>
<td>Finalité de l’utilisation de la source dans le cadre de l'étude</td>
<td>Source integration purpose</td>
<td>Purpose of using the source in the study</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/SourcePurpose/"><i>Objectif de l'intégration de la source</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-105</td>
<td><strong>OtherSourceType</strong></td>
<td>Autre type de source, précisions</td>
<td>Indique le type de source lorsqu’il ne correspond pas aux options proposées</td>
<td>Other source type, details</td>
<td>Indicate the type of source when it does not correspond to the options provided</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-053</td>
<td><strong>DataAccess</strong></td>
<td>Accès aux données</td>
<td>Cette section décrit différents aspects d'accès aux données recueillies au cours de l'étude.</td>
<td>Data access</td>
<td>This section describes various aspects of accessing the data collected during the study.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-057</td>
<td><strong>DataQuality</strong></td>
<td>Qualité des données</td>
<td>Informations sur les procédures et outils mis en place pour assurer la qualité, la cohérence et la traçabilité des données collectées dans l’étude.</td>
<td>Data quality</td>
<td>Information on the procedures and tools implemented to ensure the quality, consistency, and traceability of data collected in the study.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-140</td>
<td><strong>UsedStandards</strong></td>
<td>Standard(s) ou nomenclature(s) employé(s)</td>
<td>Normes, classifications ou terminologies utilisées pour coder et structurer les données (ex. : ICD-10, LOINC, SNOMED CT)</td>
<td>Standard(s) or nomenclature(s) used</td>
<td>Standards, classifications, or terminologies used to code and structure data (e.g., ICD-10, LOINC, SNOMED CT)</td>
<td><i>string</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-141</td>
<td><strong>QualityProcedure</strong></td>
<td>Procédure qualité utilisée</td>
<td>Méthodes et contrôles appliqués pour garantir l’exactitude, la complétude et la cohérence des données (ex. : validation, audit, double saisie)</td>
<td>Quality procedure used</td>
<td></td>
<td><i>string</i></td>
<td>0-n</td>
</tr>
<tr>
<td>S-067</td>
<td><strong>DataAvailability</strong></td>
<td>Disponibilité du jeu de données</td>
<td></td>
<td>Data availability</td>
<td></td>
<td><i>section</i></td>
<td>-</td>
</tr>
<tr>
<td>E-125</td>
<td><strong>IndividualDataAccess</strong></td>
<td>Accès aux données individuelles</td>
<td>Statut de disponibilité des données individuelles à la fin de la collecte</td>
<td>Access to individual data</td>
<td>Individual data availability status at the end of the collect</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/IndividualDataAccess/"><i>Accès aux données individuelles</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-126</td>
<td><strong>AggregatedDataAccess</strong></td>
<td>Modalités de mise à disposition des données agrégées</td>
<td>Modalités de mise à disposition des données agrégées</td>
<td>Conditions under which the aggregated data are made available</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-054</td>
<td><strong>DataAccessRequestTool</strong></td>
<td>Outil de demande d'accès aux données</td>
<td>Cette section regroupe les informations relatives à l’existence éventuelle d’un outil d'accès aux données</td>
<td>Data access request tool</td>
<td>This section contains information about the possible presence of a data access request tool</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-127</td>
<td><strong>DataAccessRequestToolAvailable</strong></td>
<td>Existe-t-il un outil de demande d'accès aux données ?</td>
<td>Indique si un outil (plateforme, formulaire en ligne ou autre système) permettant de formuler une demande d’accès aux données est disponible.</td>
<td>A data access request tool is it available ?</td>
<td>Indicates whether a tool (platform, online form, or other system) is available for submitting a request for access to data.</td>
<td>boolean</td>
<td>0-1</td>
</tr>
<tr>
<td>E-128</td>
<td><strong>DataAccessRequestToolLocation</strong></td>
<td>Lien vers l'outil de demande d'accès</td>
<td>Fournit l’URL ou la référence donnant accès à cet outil lorsque celui-ci est disponible.</td>
<td>Link to the data access request tool</td>
<td>Provides the URL or reference giving access to this tool when it is available.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-134</td>
<td><strong>DataFileCompleteness</strong></td>
<td>Complétude des fichiers des données</td>
<td>Indique l'écart éventuel entre les données collectées et les données disponibles. Il permet de préciser, le cas échéant, les raisons pour lesquelles certains éléments collectés n’ont pas été inclus dans le fichier de données partagées (par exemple, les éléments directement identifiants).</td>
<td>Data file completeness</td>
<td>Indicates any discrepancy between the data collected and the data available. It allows you to specify, where applicable, the reasons why certain items collected have not been included in the shared data file (e.g. items that directly identify individuals).</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-136</td>
<td><strong>DataLocation</strong></td>
<td>Localisation des données</td>
<td>Emplacement où les données collectées sont actuellement stockées.</td>
<td>Data location</td>
<td>Location where the data collection is currently stored.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-068</td>
<td><strong>UseStatement</strong></td>
<td>Conditions d'usage</td>
<td></td>
<td>Use conditions</td>
<td></td>
<td><i>section</i></td>
<td>-</td>
</tr>
<tr>
<td>E-129</td>
<td><strong>AccessConditions</strong></td>
<td>Conditions d'accès aux données</td>
<td>Toute information supplémentaire susceptible d'aider l'utilisateur à comprendre les conditions d'accès et d'utilisation de la collecte de données (par exemple, contacter l'investigateur principal pour plus d'information)</td>
<td>Data access conditions</td>
<td>Any additional information that will assist the user in understanding the access and use conditions of the data collection (for example, contact the principal investigator for more information).</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-130</td>
<td><strong>AccessRestrictions</strong></td>
<td>Restrictions d'accès</td>
<td>Toute restriction relative à l'accès ou à l'utilisation du recueil de données, telle que la certification de confidentialité ou les restrictions de distribution, doit être indiquée ici. Il peut s'agir de restrictions appliquées par l'auteur, le producteur ou le diffuseur des données.</td>
<td>Access restrictions</td>
<td>Any restrictions on access to or use of the data collection such as privacy certification or distribution restrictions should be indicated here. These can be restrictions applied by the author, producer, or disseminator of the data.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-131</td>
<td><strong>AdditionalDataAccessLink</strong></td>
<td>Lien vers le plan de partage des données ou vers une documentation relative à l'accès aux données</td>
<td>Indique une URL ou une référence pointant vers le plan de partage ou vers une page ou un document décrivant plus en détail les conditions et procédures d’accès aux données.</td>
<td>Link to sharing plan or to documentation relating to data access.</td>
<td>Provides a URL or reference to a sharing plan or to a page or document that describes in more detail the conditions and procedures for accessing the data.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-137</td>
<td><strong>NonDisclosureAgreement</strong></td>
<td>Accord de confidentialité</td>
<td>Indique si la signature d’une déclaration de confidentialité est requise pour accéder à la ressource.</td>
<td>Non-disclosure agreement</td>
<td>Indicates whether a confidentiality agreement must be signed in order to access the resource.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-073</td>
<td><strong>DataInformationContact</strong></td>
<td>Personne à contacter pour des renseignements concernant les données</td>
<td>Noms et adresses des personnes impliquées dans l'étude, à contacter pour obtenir les renseignements concernant les données. Elles peuvent être sollicitées en tant que personnes ressources pour les problèmes ou questions soulevés par les utilisateurs.</td>
<td>Contact person for data information</td>
<td>Names and addresses of individuals involved in the study who can be contacted for information about the data. They can be consulted as resource persons for problems or questions raised by users.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-183</td>
<td><strong>DIContactName</strong></td>
<td>Prénom NOM du contact</td>
<td></td>
<td>First name LAST NAME of the contact</td>
<td></td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-184</td>
<td><strong>DIContactMail</strong></td>
<td>Email du contact</td>
<td></td>
<td>Contact email</td>
<td></td>
<td><i>email</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-055</td>
<td><strong>DataCitation</strong></td>
<td>Obligations liées à l’usage des données</td>
<td>Indique les responsabilités de l’utilisateur vis-à-vis des données</td>
<td>Obligations related to data use</td>
<td>Indicates the user's responsibilities with regard to data</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-132</td>
<td><strong>DataCitationRequirement</strong></td>
<td>Obligation de transmission des travaux</td>
<td>Indique l’obligation pour les utilisateurs d’informer le producteur et le distibuteur des données de toute utilisation des données, en fournissant les références des publications ou des copies des papiers s’appuyant sur ces données.</td>
<td>Reporting requirement</td>
<td>Indicates the obligation for users to inform the data producer and distributor of any use of the data, providing references to publications or copies of papers based on this data.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-133</td>
<td><strong>DataCitationStatement</strong></td>
<td>Obligation de citation</td>
<td>Exigence selon laquelle un recueil de données doit être correctement cité dans les articles ou autres publications basés sur l'analyse de ces données.</td>
<td>Citation requirement</td>
<td>Requirement that a data collection should be cited properly in articles or other publications that are based on analysis of the data.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-058</td>
<td><strong>VariableDictionnary</strong></td>
<td>Dictionnaire des variables</td>
<td>Document listant et décrivant toutes les variables collectées, leur format, unités et modalités de codage.</td>
<td>Data dictionary</td>
<td>Document listing and describing all collected variables, their format, units, and coding modalities.</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-142</td>
<td><strong>VariableDictionnaryAvailable</strong></td>
<td>Existe-t-il un dictionnaire des variables ?</td>
<td>Existence d’un dictionnaire des variables</td>
<td>A data dictionary is it available ?</td>
<td>Presence of a data dictionary</td>
<td>boolean</td>
<td>1</td>
</tr>
<tr>
<td>E-143</td>
<td><strong>VariableDictionnaryLink</strong></td>
<td>Lien vers le dictionnaire des variables</td>
<td>URL ou adresse permettant d’accéder au dictionnaire des variables lorsque celui-ci est disponible.</td>
<td>Link to the data dictionary</td>
<td>URL or address providing access to the data dictionary when it is available.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-056</td>
<td><strong>MockSample</strong></td>
<td>Echantillon fictif</td>
<td>Cette section regroupe les informations relatives à l’existence éventuelle d’un échantillon fictif (données simulées ou anonymisées à des fins de test ou de démonstration)</td>
<td>Mock sample</td>
<td>This section contains information about the possible existence of a synthetic sample (simulated or anonymised data for testing or demonstration purposes).</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-138</td>
<td><strong>MockSampleAvailable</strong></td>
<td>Un échantillon fictif du jeu de données est-il disponible ?</td>
<td>Indique si un échantillon fictif du jeu de données est disponible</td>
<td>A mock sample is it available ?</td>
<td>Indicate whether a synthetic sample of the dataset is available.</td>
<td>boolean</td>
<td>0-1</td>
</tr>
<tr>
<td>E-139</td>
<td><strong>MockSampleLocation</strong></td>
<td>Lien vers l'échantillon fictif ou vers les renseignements pour y accéder</td>
<td>Si un échantillon fictif est disponible, fournir un lien ou des précisions pour y accéder.</td>
<td>Link to the sample of to information on how to access it</td>
<td>If a synthetic sample is available, provide a link or details on how to access it.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-144</td>
<td><strong>OtherDocumentation</strong></td>
<td>Documentation complémentaire sur les données</td>
<td>Tout autre document utile pour comprendre et réutiliser les données (protocoles de collecte, guides de codage, procédures de nettoyage, métadonnées complémentaires)</td>
<td>Additional documentation on data</td>
<td>Any other document useful for understanding and reusing the data (collection protocols, coding guides, cleaning procedures, additional metadata)</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-059</td>
<td><strong>DatasetPID</strong></td>
<td>Identification pérenne du jeu de données</td>
<td>Identifiant unique et stable permettant de référencer durablement le jeu de données, indépendamment de son emplacement technique</td>
<td>Persistent identifier of the dataset</td>
<td>A unique and stable identifier that allows the dataset to be referenced permanently, regardless of its technical location.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-147</td>
<td><strong>DatasetPIDSchema</strong></td>
<td>Type d'identifiant du jeu de données</td>
<td>Type de l’identifiant pérenne utilisé</td>
<td>Identifier type of the dataset</td>
<td>Type of persistent identifier used</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/DatasetPIDSchema/"><i>Type d'identifiant du jeu de données</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-146</td>
<td><strong>URI</strong></td>
<td>Identifiant du jeu de données</td>
<td>Code ou référence unique permettant d’identifier et de retrouver le jeu de données.</td>
<td>Dataset identifier</td>
<td>Unique code or reference used to identify and locate the dataset.</td>
<td><i>url</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-060</td>
<td><strong>RelatedDocument</strong></td>
<td>Documents connexes</td>
<td>Dans cette section, vous pouvez signaler tout document pertinent relatif à l’étude et accessible sur le web.</td>
<td>Related documents</td>
<td>In this section, you can report any relevant documents related to the study available on the web.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-193</td>
<td><strong>DocumentType</strong></td>
<td>Type de document</td>
<td>Type du document connexe</td>
<td>Document type</td>
<td>Type of related document</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/DocumentType/"><i>Type de document</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-194</td>
<td><strong>DocumentTitle</strong></td>
<td>Titre du document</td>
<td></td>
<td>Document title</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-195</td>
<td><strong>DocumentLink</strong></td>
<td>Lien vers le document</td>
<td>Lien permettant d’accéder au document</td>
<td>Document link</td>
<td>Link to access the document</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
</tbody>
</table>