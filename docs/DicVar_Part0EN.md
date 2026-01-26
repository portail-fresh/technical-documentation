---
hide:
  - toc
---

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Adress</th>
            <th>Element</th>
            <th>Name</th>
            <th>Name in the FReSH form</th>
            <th>Allowed Data Types</th>
            <th>Description</th>
            <th>Constraints</th>
            <th>Allowed Values</th>
            <th>Cardinality</th>
            <th>Cardinality_End</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>E-001</th>
            <td>1.1.a</td>
            <td>Identifier</td>
            <td>Study ID code</td>
            <td>Study ID code</td>
            <td>string</td>
            <td>Identifier value</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-002</th>
            <td>1.1.b</td>
            <td>IDSchema</td>
            <td>Study ID source</td>
            <td>Study ID source</td>
            <td>string</td>
            <td>Source name</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-003</th>
            <td>1.a</td>
            <td>Provenance</td>
            <td>Provenance</td>
            <td>Provenance</td>
            <td>enumerated</td>
            <td>Indicates the source of the metadata</td>
            <td>nan</td>
            <td>PEF (Epidemiology France Portal);Clinical Trials;FReSH (France Recherche en Santé Humaine)</td>
            <td>0</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-004</th>
            <td>1.b</td>
            <td>VersionLang</td>
            <td>Version language</td>
            <td>Version language</td>
            <td>enumerated</td>
            <td>Language of the current version of the record</td>
            <td>nan</td>
            <td>French;English</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-005</th>
            <td>1.c</td>
            <td>OriginLang</td>
            <td>Original language</td>
            <td>Original language</td>
            <td>enumerated</td>
            <td>Language of the original record</td>
            <td>nan</td>
            <td>French;English</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-006</th>
            <td>1.d</td>
            <td>CreationDate</td>
            <td>First record date</td>
            <td>First record date</td>
            <td>date</td>
            <td>Indicates the date on which the record was first registered in the FReSH catalogue</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-007</th>
            <td>1.e</td>
            <td>LastUpdatedAuto</td>
            <td>Last automatic update date</td>
            <td>Last automatic update date</td>
            <td>date</td>
            <td>Indicates the date of the last automatic update (import) of the record</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-008</th>
            <td>1.f</td>
            <td>LastUpdatedManual</td>
            <td>Last manual update date</td>
            <td>Last manual update date</td>
            <td>date</td>
            <td>Indicates the date of the last manual update of the record</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-009</th>
            <td>1.g</td>
            <td>RespValidation</td>
            <td>Completion/validation by the responsible person</td>
            <td>Completion/validation by the responsible person</td>
            <td>boolean</td>
            <td>Indicates whether the record has been validated by the study&#39;s principal investigator</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-010</th>
            <td>1.h</td>
            <td>AutoTranslation</td>
            <td>Automatic translation</td>
            <td>Automatic translation</td>
            <td>boolean</td>
            <td>Indicates whether the record has been automatically translated</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-011</th>
            <td>1.i</td>
            <td>Status</td>
            <td>Status</td>
            <td>Status</td>
            <td>enumerated</td>
            <td>Current status of the metadata record in the catalogue</td>
            <td>nan</td>
            <td>Draft;Awaiting validation;Returned;Rejected;Published;Imported;Updated automatically;Updated manually</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-014</th>
            <td>1.2.a</td>
            <td>ContributorName</td>
            <td>Contributor Name</td>
            <td>Contributor Name</td>
            <td>string</td>
            <td>Full name of the person entering the metadata record</td>
            <td>nan</td>
            <td>nan</td>
            <td>1</td>
            <td>1</td>
        </tr>
        <tr>
            <th>E-015</th>
            <td>1.2.b</td>
            <td>ContributorAffiliation</td>
            <td>Contributor Affiliation</td>
            <td>Contributor Affiliation</td>
            <td>string</td>
            <td>Affiliation of the person entering the metadata record</td>
            <td>nan</td>
            <td>nan</td>
            <td>0</td>
            <td>1</td>
        </tr>
    </tbody>
</table>