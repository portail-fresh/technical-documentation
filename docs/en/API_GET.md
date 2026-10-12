---
hide:
  - toc
---


# FReSH GET API



The FReSH GET API allows you to:

- Search for studies
- Filter results
- View study details
- Download data

## Endpoint


- Method: **GET**
- Server URL: **https://nada.portail-fresh.fr/index.php/api/catalog**
- Export URL: **https://nada.portail-fresh.fr/index.php/metadata/export/**



## Parameters



### Content Filters

<table>
    <thead>
        <tr>
            <th>Parameter</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>sk</th>
            <td>string</td>
            <td>Keywords used to search within study metadata.</td>
        </tr>
        <tr>
            <th>country</th>
            <td>string</td>
            <td>Country name or ISO3 code. Separate multiple countries with a vertical bar (|) (e.g., afg|ind).</td>
        </tr>
        <tr>
            <th>collection</th>
            <td>string</td>
            <td>Filter by collections. Separate multiple collections with commas (e.g., coll1, coll2).</td>
        </tr>
        <tr>
            <th>dtype</th>
            <td>string</td>
            <td>Access type: open, direct, public, licensed, enclave, remote, or other.</td>
        </tr>
    </tbody>
</table>



### Time Filters

<table>
    <thead>
        <tr>
            <th>Parameter</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>from</th>
            <td>int</td>
            <td>Start year of data collection.</td>
        </tr>
        <tr>
            <th>to</th>
            <td>int</td>
            <td>End year of data collection.</td>
        </tr>
        <tr>
            <th>created</th>
            <td>string</td>
            <td>Creation date (YYYY-MM-DD). Use YYYY/MM/DD for "from a specific date", or date1-date2 for a date range.</td>
        </tr>
    </tbody>
</table>



### Pagination and Export

<table>
    <thead>
        <tr>
            <th>Parameter</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>ps</th>
            <td>int</td>
            <td>Page size (number of results). Default: 15.</td>
        </tr>
        <tr>
            <th>page</th>
            <td>int</td>
            <td>Page number to return.</td>
        </tr>
        <tr>
            <th>sort_by</th>
            <td>enum</td>
            <td>Sort by: rank, title, nation, year.</td>
        </tr>
        <tr>
            <th>sort_order</th>
            <td>enum</td>
            <td>Order: asc (ascending) or desc (descending).</td>
        </tr>
        <tr>
            <th>format</th>
            <td>string</td>
            <td>Response format: json or xml.</td>
        </tr>
        <tr>
            <th>inc_iso</th>
            <td>boolean</td>
            <td>Set to true to include ISO3 country codes in the results.</td>
        </tr>
    </tbody>
</table>