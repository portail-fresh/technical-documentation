# FReSH Metadata Schema

## Overview

The **FReSH Metadata Schema** defines the structure and constraints of the metadata used by the **FReSH metadata catalog**.  

The schema specifies:
- Metadata fields and their semantics
- Data types and allowed values
- Cardinality and mandatory/optional constraints


---


## Schema Structure

The FReSH Metadata Schema is organized into a set of thematic sections.  
Each section groups metadata fields that describe a specific aspect of a resource in the FReSH catalog and is documented in a dedicated file.

### Sections

0. **Technical metadata**  
  Defines the technical characteristics of the metadata record itself, including identifiers, schema versioning, and machine-readable properties required for processing and validation.  
  See: [`Schema_0.md`](Schema_0.md)

1. **Study related information**  
  Describes the study or resource at a conceptual level, including titles, abstracts, keywords, thematic classifications, and high-level contextual information.  
  See: [`Study related information`](Schema_1.md)

1. **Administrative information**  
  Covers governance and responsibility aspects, such as creators, publishers, contacts, roles, and administrative metadata needed for catalog management.  
  See: [`Administrative information`](Schema_2.md)

1. **Study methodology**  
  Documents methodological aspects of the study, including design, methods, instruments, and other information necessary to understand how the data were produced.  
  See: [`Study methodology`](Schema_3.md)

1. **Data collection and access**  
  Describes how data were collected, stored, and made available, including access conditions, formats, distributions, and licensing information.  
  See: [`Data collection and access`](Schema_4.md)


---

## Cardinality and Data Types

Cardinality is expressed using standard conventions:

- `1` – exactly one value (mandatory)
- `0..1` – zero or one value (optional)
- `0..n` – zero or more values
- `1..n` – one or more values

Data types follow commonly adopted definitions (e.g. `string`, `boolean`, `date`, `URI`) and may reference external standards where appropriate.

---

## Versioning and Compatibility

An XSD representation of the metadata schema is versioned under the [FReSH metadata schema repository](https://github.com/portail-fresh/fresh-metadata-schema).