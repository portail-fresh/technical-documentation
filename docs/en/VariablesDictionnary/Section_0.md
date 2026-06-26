---
hide:
  - toc
---

# 0. Technical Metadata

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
<td>S-001</td>
<td><strong>TechnicalInfo</strong></td>
<td>Métadonnées techniques de la fiche</td>
<td></td>
<td>Technical metadata</td>
<td></td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>S-002</td>
<td><strong>StudyID</strong></td>
<td>Identifiant de l'étude</td>
<td>Section contenant l'identifiant  provenant de la source des métadonnées importées</td>
<td>Study ID</td>
<td>Section containing the identifier  from the source of the imported metadata</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-001</td>
<td><strong>Identifier</strong></td>
<td>Code de l'identifiant</td>
<td>Valeur de l'identifiant</td>
<td>Study ID code</td>
<td>Identifier value</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-002</td>
<td><strong>IDSchema</strong></td>
<td>Source de l'identifiant</td>
<td>Nom de la source</td>
<td>Study ID source</td>
<td>Source name</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-003</td>
<td><strong>Provenance</strong></td>
<td>Provenance</td>
<td>Indique la source de provenance des métadonnées</td>
<td>Provenance</td>
<td>Indicates the source of the metadata</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Provenance/"><i>Provenance</i></a></td>
<td>0-1</td>
</tr>
<tr>
<td>E-004</td>
<td><strong>VersionLang</strong></td>
<td>Langue de la version</td>
<td>Langue de la version actuelle de la fiche</td>
<td>Version language</td>
<td>Language of the current version of the record</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Language/"><i>Language</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-005</td>
<td><strong>OriginLang</strong></td>
<td>Langue d'origine</td>
<td>Langue de la fiche d'origine</td>
<td>Original language</td>
<td>Language of the original record</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/ControlledVocabularies/Language/"><i>Language</i></a></td>
<td>1</td>
</tr>
<tr>
<td>E-006</td>
<td><strong>CreationDate</strong></td>
<td>Date du 1er enregistrement</td>
<td>Indique la date à laquelle la fiche a été enregistrée pour la première fois dans le catalogue FReSH</td>
<td>First record date</td>
<td>Indicates the date on which the record was first registered in the FReSH catalogue</td>
<td><i>date</i></td>
<td>1</td>
</tr>
<tr>
<td>E-007</td>
<td><strong>LastUpdatedAuto</strong></td>
<td>Date de la dernière MAJ automatique</td>
<td>Indique la date de la dernière mise à jour automatique (import) de la fiche</td>
<td>Last automatic update date</td>
<td>Indicates the date of the last automatic update (import) of the record</td>
<td><i>date</i></td>
<td>1</td>
</tr>
<tr>
<td>E-008</td>
<td><strong>LastUpdatedManual</strong></td>
<td>Date de la dernière MAJ manuelle</td>
<td>Indique la date de la dernière mise à jour manuelle de la fiche</td>
<td>Last manual update date</td>
<td>Indicates the date of the last manual update of the record</td>
<td><i>date</i></td>
<td>1</td>
</tr>
<tr>
<td>E-009</td>
<td><strong>RespValidation</strong></td>
<td>Complétion/validation par le responsable</td>
<td>Indique si la fiche a été validée par le responsable scientifique de l'étude</td>
<td>Completion/validation by the responsible person</td>
<td>Indicates whether the record has been validated by the study's principal investigator</td>
<td><i>boolean</i></td>
<td>1</td>
</tr>
<tr>
<td>E-010</td>
<td><strong>AutoTranslation</strong></td>
<td>Traduction automatique</td>
<td>Indique si la fiche a été traduite automatiquement</td>
<td>Automatic translation</td>
<td>Indicates whether the record has been automatically translated</td>
<td><i>boolean</i></td>
<td>1</td>
</tr>
<tr>
<td>E-011</td>
<td><strong>Status</strong></td>
<td>Statut</td>
<td>Statut actuel de la fiche des métadonnées dans le catalogue</td>
<td>Status</td>
<td>Current status of the metadata record in the catalogue</td>
<td><a href="https://portail-fresh.github.io/technical-documentation/en/VocabulairesControles/Status/"><i>Record status</i></a></td>
<td>1</td>
</tr>
<tr>
<td>S-004</td>
<td><strong>MetadataContributor</strong></td>
<td>Contributeur de la fiche de métadonnées</td>
<td>Personne ou organisation chargée de renseigner les informations d’une étude dans le catalogue FReSH en complétant le formulaire en ligne</td>
<td>Metadata Contributor</td>
<td>Person or organization responsible for submitting study information to the FReSH catalogue by completing the online form</td>
<td><i>section</i></td>
<td>1</td>
</tr>
<tr>
<td>E-014</td>
<td><strong>ContributorName</strong></td>
<td>Prénom NOM</td>
<td>Nom et prénom de la personne qui renseigne la fiche des métadonnées</td>
<td>Last name – First name</td>
<td>Full name of the person entering the metadata record</td>
<td><i>string</i></td>
<td>1</td>
</tr>
<tr>
<td>E-015</td>
<td><strong>ContributorAffiliation</strong></td>
<td>Affiliation</td>
<td>Affiliation de la personne qui renseigne la fiche des métadonnées</td>
<td>Affiliation</td>
<td>Affiliation of the person entering the metadata record</td>
<td><i>string</i></td>
<td>0-1</td>
</tr>
</tbody>
</table>