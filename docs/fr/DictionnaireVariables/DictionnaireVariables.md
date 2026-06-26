# Dictionnaire des variables  

## Présentation

Le **dictionnaire des variables** définit les métadonnées utilisées par le **catalogue FReSH**.  

Le dictionnaire spécifie :  
  - Les champs de métadonnées et leur sémantique,  
  - Les types de données et les valeurs autorisées,  
  - La cardinalité et les contraintes obligatoires/facultatives.  


---


## Structure du dictionnaire

Les métadonnées FReSH sont organisées en une série de sections thématiques.  
Chaque section regroupe les champs de métadonnées qui décrivent un aspect spécifique d'une ressource dans le catalogue FReSH et est documentée dans un fichier dédié.
  
* [**Métadonnées techniques**](Section_0.md)   
  Définit les caractéristiques techniques de l'enregistrement de métadonnées lui-même, y compris les identifiants, les versions du schéma et les propriétés lisibles par machine nécessaires au traitement et à la validation.  


* [**Informations relatives à l'étude**](Section_1.md)  
  Décrit l'étude ou la ressource à un niveau conceptuel, y compris les titres, les résumés, les mots-clés, les classifications thématiques et les informations contextuelles de haut niveau.  


* [**Renseignements administratifs**](Section_2.md)  
  Couvre les aspects liés à la gouvernance et à la responsabilité, tels que les créateurs, les éditeurs, les contacts, les rôles et les métadonnées administratives nécessaires à la gestion du catalogue.  
  

* [**Méthodologie de l'étude**](Section_3.md)  
  Documente les aspects méthodologiques de l'étude, y compris la conception, les méthodes, les instruments et autres informations nécessaires pour comprendre comment les données ont été produites.  


* [**Collecte et accès aux données**](Section_4.md)  
  Décrit comment les données ont été collectées, stockées et mises à disposition, y compris les conditions d'accès, les formats, les distributions et les informations relatives aux licences.  



---
## Cardinalité

La cardinalité est exprimée à l'aide de conventions standard :

- `1` – exactement une valeur (obligatoire)
- `0..1` – zéro ou une valeur (facultatif)
- `0..n` – zéro ou plusieurs valeurs (facultatif)  
- `1..n` – une ou plusieurs valeurs (obligatoire)   

---

## Types de données

Les types de données suivent les définitions couramment adoptées (par exemple `string`, `boolean`, `date`, `URI`) et peuvent faire référence à des normes externes ou à des vocabulaires contrôlés si nécessaire.

---
