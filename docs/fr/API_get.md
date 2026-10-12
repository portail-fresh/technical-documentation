---
hide:
  - toc
---

# API GET FReSH

L’API GET FReSH permet de :
- Rechercher des études
- Filtrer les résultats
- Consulter les détails
- Télécharger les données

## Endpoint

- Méthode : **GET**
- URL du serveur : **https://nada.portail-fresh.fr/index.php/api/catalog**
- URL d'export : **https://nada.portail-fresh.fr/index.php/metadata/export/** 

## Paramètres

### Filtres de contenu
<table>
    <thead>
        <tr>
            <th>Paramètre </th>
            <th>Type </th>
            <th>Description </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>sk</th>
            <td>string</td>
            <td>Mots-clés pour la recherche dans les métadonnées de l&#39;étude. </td>
        </tr>
        <tr>
            <th>country</th>
            <td>string</td>
            <td>Nom du pays ou code ISO3. Séparez par une barre verticale (|) pour plusieurs pays (ex: afg|ind).</td>
        </tr>
        <tr>
            <th>collection</th>
            <td>string</td>
            <td>Filtrer par collections. Séparez par des virgules (ex: coll1, coll2).</td>
        </tr>
        <tr>
            <th>dtype</th>
            <td>string</td>
            <td>Type d&#39;accès : open, direct, public, licensed, enclave, remote, other.</td>
        </tr>
    </tbody>
</table>

### Filtres temporels
<table>
    <thead>
        <tr>
            <th>Paramètre </th>
            <th>Type </th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>from</th>
            <td>int</td>
            <td>Année de début de la collecte des données.</td>
        </tr>
        <tr>
            <th>to</th>
            <td>int</td>
            <td>Année de fin de la collecte des données.</td>
        </tr>
        <tr>
            <th>created</th>
            <td>string</td>
            <td>Date de création (YYYY-MM-DD). Format YYYY/MM/DD pour "à partir de", ou date1-date2 pour une plage.</td>
        </tr>
    </tbody>
</table>

### Mise en page et export
<table>
    <thead>
        <tr>
            <th>Paramètre </th>
            <th>Type </th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>ps</th>
            <td>int</td>
            <td>Taille de la page (Nombre de résultats). Par défaut :
15.</td>
        </tr>
        <tr>
            <th>page</th>
            <td>int</td>
            <td>Numéro de la page à retourner.</td>
        </tr>
        <tr>
            <th>sort_by</th>
            <td>enum</td>
            <td>Trier par: rank, title, nation, year.</td>
        </tr>
                <tr>
            <th>sort_order</th>
            <td>enum</td>
            <td>Ordre : asc (croissant) ou desc (décroissant).</td>
        </tr>
                <tr>
            <th>format</th>
            <td>string</td>
            <td>Format de réponse : json ou xml.</td>
        </tr>
                <tr>
            <th>inc_iso</th>
            <td>boolean</td>
            <td>True pour inclure les codes ISO3 dans les résultats.
</td>
        </tr>
    </tbody>
</table>
