# Schéma de métadonnées FReSH

## Présentation

Le **schéma de métadonnées FReSH** définit la structure et les contraintes des métadonnées utilisées par le **catalogue de métadonnées FReSH**.  

Le schéma spécifie :
- Les champs de métadonnées et leur sémantique
- Les types de données et les valeurs autorisées
- La cardinalité et les contraintes obligatoires/facultatives


---


## Structure du schéma

Le schéma de métadonnées FReSH est organisé en une série de sections thématiques.  
Chaque section regroupe les champs de métadonnées qui décrivent un aspect spécifique d'une ressource dans le catalogue FReSH et est documentée dans un fichier dédié.

### Sections

0. **Métadonnées techniques**  
  Définit les caractéristiques techniques de l'enregistrement de métadonnées lui-même, y compris les identifiants, les versions du schéma et les propriétés lisibles par machine nécessaires au traitement et à la validation.  
  Voir : [`Métadonnées techniques`](Schema_0.md)

1. **Informations relatives à l'étude**  
  Décrit l'étude ou la ressource à un niveau conceptuel, y compris les titres, les résumés, les mots-clés, les classifications thématiques et les informations contextuelles de haut niveau.  
  Voir : [`Informations relatives à l'étude`](Schema_1.md)

2. **Renseignements administratifs**  
  Couvre les aspects liés à la gouvernance et à la responsabilité, tels que les créateurs, les éditeurs, les contacts, les rôles et les métadonnées administratives nécessaires à la gestion du catalogue.  
  Voir : [`Renseignements administratifs`](Schema_2.md)

3. **Méthodologie de l'étude**  
  Documente les aspects méthodologiques de l'étude, y compris la conception, les méthodes, les instruments et autres informations nécessaires pour comprendre comment les données ont été produites.  
  Voir : [`Méthodologie de l'étude`](Schema_3.md)

4. **Collecte et accès aux données**  
  Décrit comment les données ont été collectées, stockées et mises à disposition, y compris les conditions d'accès, les formats, les distributions et les informations relatives aux licences.  
  Voir : [`Collecte et accès aux données`](Schema_4.md)



---
## Cardinalité et types de données

La cardinalité est exprimée à l'aide de conventions standard :

- `1` – exactement une valeur (obligatoire)
- `0..1` – zéro ou une valeur (facultatif)
- `0..n` – zéro ou plusieurs valeurs
- `1..n` – une ou plusieurs valeurs

Les types de données suivent les définitions couramment adoptées (par exemple `string`, `boolean`, `date`, `URI`) et peuvent faire référence à des normes externes si nécessaire.

---

## Gestion des versions et compatibilité

Une représentation XSD du schéma de métadonnées est versionnée dans le [référentiel de schémas de métadonnées FReSH](https://github.com/portail-fresh/fresh-metadata-schema).
