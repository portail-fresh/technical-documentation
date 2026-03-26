---
hide:
  - toc
---

# 2. Renseignements administratifs

| PID | Nom Variable | Titre FR | Description FR | Titre EN | Description EN | Type Variable | Cardinalité |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S-006 | **AdministrativeInformation** | Renseignements administratifs |  | Administrative information |  | section | 1 |
| S-008 | **RegulatoryRequirements** | Pré-requis réglementaires | Cette section rassemble les informations relatives aux procédures réglementaires encadrant la mise en place de la recherche | Regulatory requirements | This section contains information on the regulatory procedures involved in setting up  the study | section | 0-1 |
| S-009 | **ObtainedAuthorization** | Autorisation(s) ou avi(s) obtenu(s) | Cette section indique quelles autorisations réglementaires ou avis éthiques ont été obtenus pour la recherche. | Authorisation(s) or approval(s) obtained | This section indicates which regulatory approvals or ethical approvals have been obtained for the research. | section | 0-n |
| E-018 | **AuthorizingAgency** | Autorité compétente ayant délivré l'autorisation ou l'avis de validité de l'étude |  | Competent authority that issued the authorisation or notice of validity for the study |  | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/AuthorizationAgency/) | 1 |
| E-019 | **OtherAuthorizingAgency** | Autre autorité compétente, précisions | Si l'instance n'est pas dans la liste, spécifier | Other competent authority, details | Other authorities not included in the list | string '' | 0-1 |
| E-152 | **IsContributorPI** | Etes-vous l'investigateur principal (PI) de l'étude ? |  | Are you the Principal Investigator (PI) of the study ? |  | boolean | 1 |
| S-010 | **PrimaryInvestigator** | Investigateur principal | Cette section contient les informations concernant l'investigateur principal de l'étude | Principal investigator | This section contains information about the principal investigator of the study. | section | 1-n |
| E-021 | **PIName** | Prénom NOM de l'investigateur principal |  | First name LAST NAME of the principal investigator |  | string '' | 1 |
| E-197 | **PIMail** | Email de l'investigateur principal |  | Principal investigator's email |  | email | 1 |
| E-158 | **PIORCID** | ORCID de l'investigateur principal |  | Principal investigator's ORCID |  | string '' | 0-1 |
| E-159 | **PIIdRef** | Identifiant IdRef |  | IdRef Identifier |  | string '' | 0-1 |
| S-069 | **PIAffiliation** | Affiliation(s) de l'investigateur principal | Section identifiant l'organisation ou l'institution d'appartenance de l'investigateur principal | Principal investigator affiliation(s) |  | section | 1 |
| E-024 | **OrganisationName** | Nom de l'organisation d'affiliation principale | Nom de l'organisation d'affiliation | Main affiliated organisation name | Affiliated institution name | string '' | 1 |
| S-013 | **OrganisationPID** | Identification de l'organisation d'affiliation principale | Identifiant de l’organisation d’affiliation | Main affiliated organisation identification | Affiliated organisation identifier | section | 0-1 |
| E-022 | **PIDSchema** | Type d'identifiant de l'organisation d'affiliation principale | Type d'identifiant d'organisation d'affiliation | Main affiliated organisation identifier type | Affiliated organisation identifier type | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PIDSchema/) | 1 |
| E-023 | **URI** | Identifiant de l’organisation d’affiliation principale |  | Main affiliated organisation identifier |  | url | 1 |
| E-160 | **PILabo** | Affiliation(s), précisions |  | Affiliation(s), details |  | string '' | 0-1 |
| E-161 | **PILaboId** | Identifiant RNSR du laboratoire d'appartenance |  | Affiliated laboratory RNSR identifier |  | string '' | 0-1 |
| E-179 | **IsPIContact** | L'investigateur principal est-il un point de contact ? |  | Is the principal investigator a contact point? |  | boolean | 0-1 |
| E-196 | **AddTeamMember** | D'autres équipes sont-elles impliquées dans cette étude ? |  | Are other teams involved in this study? |  | boolean | 0-1 |
| S-070 | **TeamMember** | Responsable de l'équipe partenaire | Cette section décrit les personnes ayant contribué à l'étude | Partner team leader | This section describes the persons who contributed to the study. | section | 0-n |
| E-162 | **TeamMemberName** | Prénom NOM du responsable de l'équipe | Nom et prénom de la personne ayant contribué à l'étude | First name LAST NAME of the team leader | Full name of the person who contributed to the study | string '' | 1 |
| E-163 | **TeamMemberORCID** | ORCID du responsable de l'équipe |  | Team leader's ORCID |  | string '' | 0-1 |
| E-164 | **TeamMemberIdRef** | Identifiant IdRef |  | IdRef Identifier |  | string '' | 0-1 |
| S-071 | **TeamMemberAffiliation** | Affiliation(s) du responsable de l'équipe | Cette section précise l'affiliation institutionnelle de la personne ayant contribué à l'étude | Team leader affiliation(s) |  | section | 0-1 |
| E-024 | **OrganisationName** | Nom de l'organisation d'affiliation principale | Nom de l'organisation d'affiliation | Main affiliated organisation name | Affiliated institution name | string '' | 1 |
| S-013 | **OrganisationPID** | Identification de l'organisation d'affiliation principale | Identifiant de l’organisation d’affiliation | Main affiliated organisation identification | Affiliated organisation identifier | section | 0-1 |
| E-022 | **PIDSchema** | Type d'identifiant de l'organisation d'affiliation principale | Type d'identifiant d'organisation d'affiliation | Main affiliated organisation identifier type | Affiliated organisation identifier type | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PIDSchema/) | 1 |
| E-023 | **URI** | Identifiant de l’organisation d’affiliation principale |  | Main affiliated organisation identifier |  | url | 1 |
| E-165 | **TeamMemberLabo** | Affiliation(s), précisions |  | Affiliation(s), details |  | string '' | 0-1 |
| E-166 | **TeamMemberLaboId** | Identifiant RNSR du laboratoire d'appartenance |  | Affiliated laboratory RNSR identifier |  | string '' | 0-1 |
| E-180 | **IsTeamMemberContact** | Le responsable de l'équipe est-il un point de contact ? |  | Is the team leader a contact point ? |  | boolean | 0-1 |
| S-018 | **ContactPoint** | Point(s) de contact | Cette section contient les informations concernant les personnes référentes pour l’étude | Contact point(s) | This section contains information about the contact persons for the study. | section | 1-n |
| E-033 | **ContactName** | Prénom NOM du contact | Nom de la personne référente | First name LAST NAME of the contact | Name of the contact person | string '' | 1 |
| E-034 | **EMail** | Email du contact | Adresse mail de la personne référente | Contact email | Email addresse of the contact person | email | 1 |
| S-072 | **ContactPointAffiliation** | Affiliation(s) du contact | Cette section précise l'affiliation institutionnelle de la personne réfrente | Contact affiliation(s) | This section specifies the institutional affiliation of the contact person. | section | 0-1 |
| E-024 | **OrganisationName** | Nom de l'organisation d'affiliation principale | Nom de l'organisation d'affiliation | Main affiliated organisation name | Affiliated organisation name | string '' | 1 |
| S-013 | **OrganisationPID** | Identification de l'organisation d'affiliation principale | Identifiant de l’organisation d’affiliation | Main affiliated organisation identification | Affiliated organisation identifier | section | 0-1 |
| E-022 | **PIDSchema** | Type d'identifiant de l'organisation d'affiliation principale | Type d'identifiant d'organisation d'affiliation | Main affiliated organisation identifier type | Affiliated organisation identifier type | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PIDSchema/) | 1 |
| E-023 | **URI** | Identifiant de l’organisation d’affiliation principale |  | Main affiliated organisation identifier |  | url | 1 |
| E-167 | **ContactPointLabo** | Affiliation(s), précisions |  | Affiliation(s), details |  | string '' | 0-1 |
| E-168 | **ContactPointLaboId** | Identifiant RNSR du laboratoire d'appartenance |  | Affiliated laboratory RNSR identifier |  | string '' | 0-1 |
| S-021 | **FundingAgent** | Financeur | Cette section contient les informations concernant les financeurs de l'étude | Funder | This section contains information about the study's funders | section | 0-n |
| E-038 | **FundingAgentName** | Nom du financeur | Nom de l'organisme financeur | Funder name | Funding body name | string '' | 1 |
| E-039 | **FundingAgentType** | Type de financeur | Type d'organisme financeur | Funder type | Funding body type | choix unique | 1 |
| E-181 | **OtherFundingAgentType** | Autre type de financeur, précisions |  | Other funder type, details |  | string '' | 0-1 |
| S-022 | **FundingAgentPID** | Identification du financeur | Section identifiant l'organisme financeur | Funder identification | Section identifying the funding body | section | 0-1 |
| E-022 | **PIDSchema** | Type d'identifiant du financeur | Type d'identifiant d'organisme financeur | Funder identifier type | Type of funding body identifier | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PIDSchema/) | 1 |
| E-023 | **URI** | Identifiant du financeur | Identifiant de l'organisme financeur | Funder identifier | Funder identifier URI | url | 1 |
| S-023 | **OrganisationGovernance** | Organisation et gouvernance | Cette section rassemble les informations sur la gouvernance du projet, incluant le promoteur de l’étude, l’organisation responsable du traitement des données et les collaborations associées. | Organisation and governance | This section contains information about the governance of the project, including the study sponsor, the organisation responsible for data processing, and associated collaborations. | section | 1 |
| S-024 | **Sponsor** | Promoteur de l'étude (Organisation responsable) | Cette section contient les informations concernant le promoteur de l'étude | Sponsor (Responsible organisation) |  | section | 1-n |
| E-042 | **SponsorName** | Nom du promoteur | Nom de l'organisme promoteur de l'étude | Sponsor name | Name of the sponsor institution | string '' | 1 |
| E-043 | **SponsorType** | Statut du promoteur | Statut de l'organisme promoteur | Sponsor type | Sponsor institution type | choix unique | 1 |
| E-182 | **OtherSponsorType** | Autre statut du promoteur, précisions |  | Other sponsor type, details |  | string '' | 0-1 |
| S-025 | **SponsorPID** | Identification du promoteur | Section identifiant l'organisme promoteur de l'étude | Sponsor identification | Section identifying the sponsor institution | section | 0-1 |
| E-022 | **PIDSchema** | Type d'identifiant du promoteur | Type d'identifiant de l'organisme promoteur | Sponsor identifier type | Type of identifier of the sponsor institution | [choix unique](https://portail-fresh.github.io/technical-documentation/fr/VocabulairesControles/PIDSchema/) | 1 |
| E-045 | **URL** | Identifiant du promoteur | Identifiant de l'organisme promoteur | Sponsor identifier | Identifier of the sponsor institution | url | 1 |
| S-026 | **Governance** | Gouvernance | Section qui décrit la gouvernance de l'étude | Governance | Section describing the governance of the study | section | 0-1 |
| E-046 | **Committee** | Comité scientifique ou de pilotage | Indique l'existance d’un comité scientifique ou d’un comité de pilotage associé au projet ou à l’étude | Scientific or steering committee | Indicates the existence of a scientific committee or steering committee associated with the project or study. | boolean | 1 |
| E-047 | **CommitteeDetail** | Comité, précisions | Précisions sur la comitologie associée à l'étude | Committee details | Details on the comitology associated with the study | string '' | 0-1 |
| E-048 | **OtherGovernance** | Autre modalité de gouvernance, précisions | Autres modalités de gouvernance | Other form of gouvernance, details | Other  forms of governance | string '' | 0-1 |
| S-027 | **Collaborations** | Collaborations | Section qui décrit les collaborations impliquées | Collaborations | Section describing the collaborations involved | section | 0-1 |
| E-049 | **NetworkConsortium** | Réseaux, consortiums | Indique si le projet fait partie d'un réseau ou d'un consirtium | Networks, consortia | Indicates whether the project is part of a network or consortium. | boolean | 1 |
| E-050 | **CollaborationsDetails** | Collaboration(s) impliquée(s), précisions | Précisions sur les collaborations impliquées | Collaboration(s) involved, details | Details on the collaborations involved | string '' | 1 |
| S-003 | **OtherStudyId** | Autre(s) identifiant(s) de l'étude | Autres identifiants connus de l'étude | Other(s) identifier(s) for the study | Other(s) study identifiers known | section | 0-n |
| E-013 | **IDSchema** | Type d'identifiant de l'étude | Type d'identifiant de l'étude (promoteur ou registre des essais cliniques) | Study identifier type | Type of study identifier (sponsor or clinical trial registry) | string '' | 1 |
| E-012 | **Identifier** | Identifiant de l'étude | Identifiant de l'étude | Study identifier | Study identifier | string '' | 1 |
