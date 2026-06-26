---
hide:
  - toc
---

# 3. Study methodology

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
<td>S-065</td>
<td><strong>StudyMethodology</strong></td>
<td>Méthodologie de l'étude</td>
<td></td>
<td>Study Methodology</td>
<td></td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-061</td>
<td><strong>AnalysisUnit</strong></td>
<td>Unité de collecte</td>
<td>Décrit l'entité analysée dans l'étude ou la variable.</td>
<td>Collection unit</td>
<td>Describes the entity being analysed in the study or variable</td>
<td><i>"Individuals"</i></td>
<td>1</td>
</tr>
<tr>
<td>E-062</td>
<td><strong>ResearchType</strong></td>
<td>Modèle d'étude</td>
<td>Indique la nature de la recherche comprenant les études interventionnelles (également appelées expérimentales) et les études observationnelles.</td>
<td>Study Type</td>
<td>Indicates the type of the research, including interventional (also known as experimental) studies and observational studies.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/ResearchType/"><i>Study type</i></a></td>
<td>1</td>
</tr>
<tr>
<td>S-029</td>
<td><strong>InterventionalStudy</strong></td>
<td>Etude interventionnelle (expérimentale)</td>
<td>Une recherche dans laquelle les investigateurs réalisent une action ou une modification intentionnelle dans un groupe cible (ex. : traitement médical, programme de prévention, changement organisationnel, action éducative ou sociale), dans le but d’en évaluer les effets sur la santé, les comportements, ou les pratiques liés à la santé.</td>
<td>Interventional Study</td>
<td>Research in which investigators carry out an intentional action or change in a target group (e.g., medical treatment, prevention program, organisational change, educational or social action) with the aim of evaluating its effects on health, behaviors, or health-related practices.</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-153</td>
<td><strong>IsClinicalTrial</strong></td>
<td>S'agit-il d'un essai clinique?</td>
<td></td>
<td>Is this a clinical trial?</td>
<td></td>
<td><i>boolean</i></td>
<td>1</td>
</tr>
<tr>
<td>E-064</td>
<td><strong>TrialPhase</strong></td>
<td>Phase de l'essai</td>
<td>Stade d’un essai clinique définissant les objectifs et méthodes de l’évaluation d’un médicament ou produit biologique (tolérance, efficacité, comparaison, suivi). Pour les essais à phases combinées, cocher plusieurs cases.</td>
<td>Study Phase</td>
<td>The stage of a clinical trial defining the objectives and methods of evaluating a drug or biological product (tolerance, efficacy, comparison, follow-up). For combined phases, check several options.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/trial-phase/"><i>Trial phase</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-063</td>
<td><strong>ResearchPurpose</strong></td>
<td>Objectif principal de la recherche</td>
<td>L'objectif principal de la ou des interventions évaluées dans le cadre de l'étude.</td>
<td>Primary research purpose</td>
<td>The main objective of the intervention(s) being evaluated by the study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/ResearchPurpose/"><i>Research purpose</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>E-178</td>
<td><strong>OtherResearchPurpose</strong></td>
<td>Autre objectif principal, précisions</td>
<td></td>
<td>Other research purpose, details</td>
<td></td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-199</td>
<td><strong>IsInclusionGroups</strong></td>
<td>L'étude comporte-t-elle plusieurs groupes définis dès l'inclusion ?</td>
<td></td>
<td>Does the study include several groups defined at the time of inclusion ?</td>
<td></td>
<td><i>boolean</i></td>
<td>-</td>
</tr>
<tr>
<td>S-038</td>
<td><strong>InclusionGroup</strong></td>
<td>Groupes à l'inclusion</td>
<td>Section décrivant chaque groupe à l'inclusion.</td>
<td>Enrollment groups</td>
<td>Section describing each group at inclusion.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-079</td>
<td><strong>GroupName</strong></td>
<td>Nom du groupe</td>
<td>Le libellé choisi pour le groupe à l'inclusion, unique dans le cadre de l'étude</td>
<td>Group name</td>
<td>The title chosen for the inclusion group, unique within the study.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-080</td>
<td><strong>GroupDescription</strong></td>
<td>Description du groupe</td>
<td>Description des caractéristiques de chaque groupe à l’inclusion, précisant sur quels critères ils ont été distingués (par exemple : type d’exposition, caractéristiques cliniques, socio-démographiques ou contextuelles).</td>
<td>Group description</td>
<td>Description of the characteristics of each group at inclusion, specifying the criteria used to distinguish them (e.g. type of exposure, clinical, socio-demographic or contextual characteristics).</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-065</td>
<td><strong>InterventionalStudyModel</strong></td>
<td>Schéma d’intervention</td>
<td>Conception générale de la stratégie d'attribution des interventions aux participants d'une étude clinique. Les types de modèles d'intervention comprennent : l'attribution à un seul groupe, l'attribution parallèle, l'attribution croisée et l'attribution factorielle.</td>
<td>Intervention model</td>
<td>The general design of the strategy for assigning interventions to participants in a clinical study. Types of intervention models include: single group assignment, parallel assignment, cross-over assignment, and factorial assignment.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/InterventionalStudyModel/"><i>Interventional study model</i></a></td>
<td>1</td>
</tr>
<tr>
<td>S-030</td>
<td><strong>Allocation</strong></td>
<td>Allocation</td>
<td>Méthode utilisée pour affecter les participants à un groupe d'intervention ou à un bras d'une étude clinique.</td>
<td>Allocation</td>
<td>A method used to assign participants to an an intervention group or arm of a clinical study.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-066</td>
<td><strong>AllocationMode</strong></td>
<td>Mode d'allocation</td>
<td>Les modes d'allocation sont l'allocation randomisée et l'allocation non randomisée.</td>
<td>Allocation type</td>
<td>The types of allocation are randomized allocation and nonrandomized.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/AllocationMode/"><i>Allocation type</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-067</td>
<td><strong>AllocationUnit</strong></td>
<td>Unité d'allocation</td>
<td>Entité à laquelle l'intervention est attribuée (individuelle ou cluster).</td>
<td>Allocation unit</td>
<td>Entity to which the intervention is assigned (individual or cluster).</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/AllocationUnit/"><i>Allocation unit</i></a></td>
<td>1</td>
</tr>
<tr>
<td>S-031</td>
<td><strong>Masking</strong></td>
<td>Insu</td>
<td>Stratégie de conception d'une étude dans laquelle une ou plusieurs parties impliquées dans l'étude, telles que l'investigateur ou les participants, ne savent pas quels participants ont été assignés à quelles interventions.</td>
<td>Masking</td>
<td>A study design strategy in which one or more parties involved in the study, such as the investigator or participants, do not know which participants have been assigned which interventions.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-068</td>
<td><strong>MaskingType</strong></td>
<td>Mode d'insu</td>
<td>Indique si l’étude est conduit en ouvert (toutes les parties connaissent l’intervention attribuée) ou avec insu (au moins une partie est tenue dans l’ignorance de l’intervention attribuée).</td>
<td>Masking type</td>
<td>Indicates whether the study is conducted open-label (all parties know the assigned intervention) or with masking (at least one party is unaware of the assigned intervention).</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/MaskingType/"><i>Masking type</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-069</td>
<td><strong>BlindedMaskingDetails</strong></td>
<td>Groupe(s) avec insu (en aveugle)</td>
<td>Précise quels acteurs de l’étude (participant, personnel soignant, investigateur, analyste des données) ignorent l’intervention attribuée, afin de limiter les biais.</td>
<td>Blinded masking group(s)</td>
<td>Specifies which stakeholders in the study (participant, care provider, investigator, outcome assessor ) are unaware of the assigned intervention, in order to reduce bias.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/BlindedMaskingDetails/"><i>Blinded masking details</i></a></td>
<td>1-n</td>
</tr>
<tr>
<td>S-033</td>
<td><strong>Arm</strong></td>
<td>Bras (ou sous-groupe de participants)</td>
<td>Sous-groupe de participants dans une étude interventionnelle. Chaque bras reçoit une intervention spécifique ou suit une stratégie particulière, permettant de comparer les effets entre bras.</td>
<td>Arm (or subgroup of participants)</td>
<td>Subgroup of participants in an interventional study. Each arm receives a specific intervention or follows a particular strategy, allowing comparison of effects across arms.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-071</td>
<td><strong>ArmName</strong></td>
<td>Nom du bras</td>
<td>Le libellé choisi pour le bras, unique dans le cadre de l'étude</td>
<td>Arm name</td>
<td>The title chosen for the arm, unique within the study</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-072</td>
<td><strong>ArmType</strong></td>
<td>Type de bras</td>
<td>Description générale du bras participant à l'étude. Elle identifie le rôle de l'intervention dont bénéficient les participants. Les types de bras comprennent le bras expérimental, comparateur actif, comparateur placebo, comparateur fictif et le bras sans intervention.</td>
<td>Arm type</td>
<td>A general description of the study arm. It identifies the role of the intervention that participants receive. Types of arms include experimental arm, active comparator arm, placebo comparator arm, sham comparator arm, and no intervention arm.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/ArmType/"><i>Arm type</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-073</td>
<td><strong>ArmTypeOther</strong></td>
<td>Autre type de bras, précisions</td>
<td>Spécifie le type de bras si « Autre » a été sélectionné ci-dessus.</td>
<td>Other arm type, details</td>
<td>Specifies the arm type if “Other” was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-074</td>
<td><strong>ArmDescription</strong></td>
<td>Description du bras</td>
<td>Brève description du bras, y compris son objectif ou ses caractéristiques.</td>
<td>Arm description</td>
<td>Brief description of the arm, including its purpose or characteristics.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-039</td>
<td><strong>Intervention</strong></td>
<td>Facteur, processus ou exposition étudié</td>
<td>Tout processus, action ou facteur auquel les participants sont soumis ou exposés, et qui fait l’objet d’une étude observationnelle afin d’évaluer ses effets sur la santé.</td>
<td>Studied factor, process, or exposure</td>
<td>Any process, action or factor to which participants are subjected or exposed, and which is the subject of an observational study to assess its effects on health.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-082</td>
<td><strong>InterventionName</strong></td>
<td>Nom du facteur ou de l'exposition</td>
<td>Le nom spécifique de l'action, du facteur ou de l'exposition tel qu'il est mentionné dans l'étude. Les facteurs comprennent différents produits de santé ou des approches non invasives, telles que l'éducation ou la modification du régime alimentaire et de l'exercice physique. Les expositions peuvent concerner par exemple des habitudes de vie, des facteurs environnementaux ou des antécédents médicaux.</td>
<td>Factor/exposure name</td>
<td>The specific name of the action, factor or exposure as it is referred to in the study. Factors include various health products or non-invasive approaches, such as education or changes to diet and exercise. Exposures may include, for example, lifestyle habits, environmental factors, or medical history.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-083</td>
<td><strong>InterventionType</strong></td>
<td>Type de facteur ou d'exposition</td>
<td>Sélection de la catégorie qui décrit le mieux le facteur ou l'exposition, à partir de la liste prédéfinie d'options.</td>
<td>Factor/exposure type</td>
<td>Selection of the category that best describes the factor or the exposure from the predefined list of options.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/InterventionType/"><i>Factor/exposure type</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-084</td>
<td><strong>InterventionTypeOther</strong></td>
<td>Autre type de facteur ou d'exposition, précisions</td>
<td>Spécifie le type du facteur ou d'exposition si « Autre » a été sélectionné ci-dessus.</td>
<td>Other factor/exposure type, details</td>
<td>Specifies the type of factor or exposure if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-034</td>
<td><strong>ObservationalStudy</strong></td>
<td>Etude observationnelle</td>
<td>Une recherche dans laquelle les investigateurs n’interviennent pas activement sur les participants ou le contexte étudié, mais observent, décrivent et analysent des situations existantes. Elle peut porter sur des données issues de soins courants, d’enquêtes, de registres, d’observations de comportements ou d’environnements, sans introduire de modification volontaire du réel.</td>
<td>Observational study</td>
<td>Research in which the investigators do not actively intervene with participants or the study context, but rather observe, describe, and analyze existing situations. It may involve data from routine care, surveys, registries, or observations of behaviors or environments, without introducing any deliberate changes to reality.</td>
<td><i>section</i></td>
<td>0-1</td>
</tr>
<tr>
<td>E-075</td>
<td><strong>ObservationalStudyDesign</strong></td>
<td>Modèle de l’étude observationnelle</td>
<td>Indique l’approche méthodologique de l’étude observationnelle, précisant comment les participants sont sélectionnés et suivis ou observés.</td>
<td>Observational study  design</td>
<td>Describes the methodological approach of the observational study, specifying how participants are selected and monitored or observed.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/ObservationalStudy/"><i>Observational study design</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-076</td>
<td><strong>OtherResearchTypeDetails</strong></td>
<td>Autre type d'étude observationnelle, précisions</td>
<td>Indique le modèle de recherche observationnelle lorsqu’il ne correspond pas aux options proposées</td>
<td>Other research type, details</td>
<td>Indicates the observational study design when it does not correspond to the options provided.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-154</td>
<td><strong>TimePerspective</strong></td>
<td>Perspective temporelle</td>
<td>Indique la dimension temporelle de la collecte des données dans l’étude observationnelle.</td>
<td>Time perspective</td>
<td>Indicates the temporal dimension of data collection in the observational study.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/RecrutmentTiming/"><i>Time perspective</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-199</td>
<td><strong>IsInclusionGroups</strong></td>
<td>L'étude comporte-t-elle plusieurs groupes définis dès l'inclusion ? ST: Si oui, remplir les champs suivants</td>
<td></td>
<td>Does the study include several groups defined at enrollment ?</td>
<td></td>
<td><i>boolean</i></td>
<td>-</td>
</tr>
<tr>
<td>S-038</td>
<td><strong>InclusionGroup</strong></td>
<td>Groupes à l'inclusion</td>
<td>Section décrivant chaque groupe à l'inclusion.</td>
<td>Enrollment groups</td>
<td>Section describing each group at inclusion.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-079</td>
<td><strong>GroupName</strong></td>
<td>Nom du groupe</td>
<td>Le libellé choisi pour le groupe à l'inclusion, unique dans le cadre de l'étude</td>
<td>Group name</td>
<td>The title chosen for the inclusion group, unique within the study.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-080</td>
<td><strong>GroupDescription</strong></td>
<td>Description du groupe</td>
<td>Description des caractéristiques de chaque groupe à l’inclusion, précisant sur quels critères ils ont été distingués (par exemple : type d’exposition, caractéristiques cliniques, socio-démographiques ou contextuelles).</td>
<td>Group description</td>
<td>Description of the characteristics of each group at inclusion, specifying the criteria used to distinguish them (e.g. type of exposure, clinical, socio-demographic or contextual characteristics).</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-039</td>
<td><strong>Intervention</strong></td>
<td>Facteur, processus ou exposition étudié</td>
<td>Tout processus, action ou facteur auquel les participants sont soumis ou exposés, et qui fait l’objet d’une étude observationnelle afin d’évaluer ses effets sur la santé.</td>
<td>Studied factor, process, or exposure</td>
<td>Any process, action or factor to which participants are subjected or exposed, and which is the subject of an observational study to assess its effects on health.</td>
<td><i>section</i></td>
<td>0-n</td>
</tr>
<tr>
<td>E-082</td>
<td><strong>InterventionName</strong></td>
<td>Nom du facteur ou de l'exposition</td>
<td>Le nom spécifique de l'action, du facteur ou de l'exposition tel qu'il est mentionné dans l'étude. Les facteurs comprennent différents produits de santé ou des approches non invasives, telles que l'éducation ou la modification du régime alimentaire et de l'exercice physique. Les expositions peuvent concerner par exemple des habitudes de vie, des facteurs environnementaux ou des antécédents médicaux.</td>
<td>Factor/exposure name</td>
<td>The specific name of the action, factor or exposure as it is referred to in the study. Factors include various health products or non-invasive approaches, such as education or changes to diet and exercise. Exposures may include, for example, lifestyle habits, environmental factors, or medical history.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-083</td>
<td><strong>InterventionType</strong></td>
<td>Type de facteur ou d'exposition</td>
<td>Sélection de la catégorie qui décrit le mieux le facteur ou l'exposition, à partir de la liste prédéfinie d'options.</td>
<td>Factor/exposure type</td>
<td>Selection of the category that best describes the factor or the exposure from the predefined list of options.</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/InterventionType/"><i>Factor/exposure type</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-084</td>
<td><strong>InterventionTypeOther</strong></td>
<td>Autre type de facteur ou d'exposition, précisions</td>
<td>Spécifie le type du facteur ou d'exposition si « Autre » a été sélectionné ci-dessus.</td>
<td>Other factor/exposure type, details</td>
<td>Specifies the type of factor or exposure if ‘Other’ was selected above.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
<tr>
<td>S-050</td>
<td><strong>Outcomes</strong></td>
<td>Critères d'évaluation (de jugement)</td>
<td>Mesure ou observation relative à la santé utilisée pour évaluer l’effet d’une intervention ou décrire la survenue, l’évolution ou les déterminants d’une maladie ou d’une caractéristique.</td>
<td>Health-related outcomes</td>
<td>A health-related measurement or observation used to assess the effect of an intervention or describe the occurrence, progression, or determinants of a disease or characteristic.</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-115</td>
<td><strong>PrimaryOutcomes</strong></td>
<td>Critère d'évaluation (de jugement) principal</td>
<td>Mesure ou observation prioritaire de l’étude, définie à l’avance, qui sert à répondre à la question de recherche principale.</td>
<td>Primary Outcome</td>
<td>The main pre-specified measurement or observation of the study, used to address the primary research question.</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-116</td>
<td><strong>SecondaryOutcomes</strong></td>
<td>Critère(s) d'évaluation (de jugement) secondaire(s)</td>
<td>Mesures ou observations complémentaires, définies à l’avance, qui permettent d’apporter des informations supplémentaires ou d’explorer des aspects associés à la question principale.</td>
<td>Secondary Outcome(s)</td>
<td>Additional pre-specified measurements or observations that provide complementary information or explore related aspects of the primary question.</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
</tbody>
</table>