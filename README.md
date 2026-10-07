# HUST Ontology T-Box

Public vocabulary: <https://samnn152.github.io/hust-ontology-tbox/>

Under development. Information is incomplete. This is a student project, not an official HUST publication.

## Contents

- [Use the vocabulary](#use-the-vocabulary)
- [Schema structure](#schema-structure)
- [Publication boundary](#publication-boundary)
- [License](#license)

## Use the vocabulary

Browse and filter definitions on the [vocabulary page](https://samnn152.github.io/hust-ontology-tbox/). Download [Turtle](ontology.ttl), [RDF/XML](ontology.rdf) or [JSON-LD](ontology.jsonld), or open an RDF file in Protégé.

Term identifiers use `https://samnn152.github.io/hust-ontology-tbox/#`. For example: [https://samnn152.github.io/hust-ontology-tbox/#Person](https://samnn152.github.io/hust-ontology-tbox/#Person). The HTML document also embeds the schema as JSON-LD. No application server is required to browse the static release.

## Schema structure

| Node type | Count |
|---|---:|
| Named classes | 337 |
| Object properties | 93 |
| Datatype properties | 83 |
| A-Box individuals | 0 |

The schema combines People, Organization/Place, Research/Resources, University/Academic and supplementary knowledge/evidence definitions. Academic namespace terms use `academic_` to avoid collisions. Existing mappings link to W3C ORG, Schema.org and other vocabularies. The original working ontology identifiers remain in the private project.

## Publication boundary

Only allowlisted schema files are published. A-Box records, profiles, harvested documents, source-claim records and the private repository history are excluded. `manifest.json` records release counts and RDF file hashes.

The website displays English descriptions. Machine-readable RDF preserves source language-tagged annotations. A schema restriction may reference a controlled constant without publishing its instance assertions.

## License

The published schema is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [NOTICE](NOTICE) for attribution. External vocabularies retain their respective authorship and terms; the license does not publish private instance data or harvested documents.
