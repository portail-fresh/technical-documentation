# Variables Dictionnary    

## Overview

The **FReSH Metadata Schema** defines the structure and constraints of the metadata used by the **FReSH metadata catalog**.  

The schema specifies:
- Metadata fields and their semantics,  
- Data types and allowed values,  
- Cardinality and mandatory/optional constraints.  


---


## Dictionnary Structure

The FReSH Metadata Schema is organized into a set of thematic sections.  
Each section groups metadata fields that describe a specific aspect of a resource in the FReSH catalog and is documented in a dedicated file.  
  
* [**Technical Metadata**](Section_0.md)   
  Defines the technical characteristics of the metadata record itself, including identifiers, schema versioning, and machine-readable properties required for processing and validation.  


* [**Study related information**](Section_1.md)  
  Describes the study or resource at a conceptual level, including titles, abstracts, keywords, thematic classifications, and high-level contextual information.    


* [**Administrative information**](Section_2.md)  
  Covers governance and responsibility aspects, such as creators, publishers, contacts, roles, and administrative metadata needed for catalog management.   
  

* [**Study methodology**](Section_3.md)  
  Documents methodological aspects of the study, including design, methods, instruments, and other information necessary to understand how the data were produced.  


* [**Data collection and access**](Section_4.md)  
  Describes how data were collected, stored, and made available, including access conditions, formats, distributions, and licensing information.   



---
## Cardinality

Cardinality is expressed using standard conventions:  

- `1` – exactly one value (mandatory)  
- `0..1` – zero or one value (optional)  
- `0..n` – zero or more values (optional)   
- `1..n` – one or more values (mandatory)     

---

## Data Types

Data types follow commonly adopted definitions (e.g. `string`, `boolean`, `date`, `URI`) and may reference external standards or controlled vocabularies where appropriate.  

---
