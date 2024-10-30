# Ontologies for CRC 1218

## Notes on resources related to ontologies

Repositories for biomedical ontologies:

- [BioPortal](https://bioportal.bioontology.org/)
- [Ontology Lookup Service (OLS)](https://www.ebi.ac.uk/ols4/index)

Combination of parts of several biological ontologies - multi-domain ontologies*:

- [Experimental Factor Ontology (EFO)](https://www.ebi.ac.uk/efo/)

*Depending on the context, it can make more sense to use a multi-domain ontology with suitbale coverage to improve consistency and interoperability ([The FAIR Cookbook > 5. Selecting terminologies and ontologies](https://w3id.org/faircookbook/FCB020)).

For cross-referencing terms from ontologies, vocabularies and coding standards:

- [Ontology Mapping (OxO)](https://www.ebi.ac.uk/spot/oxo/), imports mappings from a variety of sources including the [OLS](https://www.ebi.ac.uk/ols4/index) and a subset of mappings provided by the [Unified Medical Language System (UMLS)](https://www.nlm.nih.gov/research/umls/index.html).

In the field of Biology and Biomedicine, the OBO Foundry coordinates the development of interoperable ontologies:

- [Open Biological and Biomedical Ontology Foundry (OBO)](https://obofoundry.org/)

Potentially relevant domain ontologies:

- [The data analysis and management ontology (EDAM)](https://github.com/edamontology/edamontology?tab=readme-ov-file)
- [Protein Ontology (PRO)](https://proconsortium.org/)
- [Gene Ontology (GO)](https://geneontology.org/)

## Evaluation of Domain-Specific and Multi-Domain Ontologies for Best Practices

Not all of the listed ontologies fully meet best practices for ontology selection and use, though most adhere to many of the core principles. Let’s look at how each of these domain-specific and multi-domain ontologies align with best practices such as **interoperability**, **adherence to the FAIR principles**, and **alignment with community standards**:

---

### Proteomics-Focused Ontologies

1. **Protein Ontology (PRO)**
   - **Interoperability**: Compatible with other ontologies, especially those describing genes and proteins.
   - **FAIR Principles**: PRO is well-maintained and uses standardized identifiers, improving data accessibility and reusability.
   - **Community Standards**: Widely accepted in proteomics research and integrates well with major ontologies like GO.

2. **Gene Ontology (GO)**
   - **Interoperability**: Highly interoperable, designed for cross-dataset use, and has mappings to other ontologies.
   - **FAIR Principles**: GO exemplifies the FAIR principles, with comprehensive metadata and a robust governance structure.
   - **Community Standards**: One of the most widely used and recognized standards in biological research.

3. **PSI-MOD**
   - **Interoperability**: Integrates well with the PSI (Proteomics Standards Initiative) formats widely used in proteomics.
   - **FAIR Principles**: Adheres closely to FAIR principles, especially around reusability due to its standardized nomenclature.
   - **Community Standards**: Accepted as the standard for protein modifications in the proteomics community.

4. **PeptideAtlas and PRIDE Ontology**
   - **Interoperability**: Primarily used within PRIDE and PeptideAtlas but compatible with other data standards.
   - **FAIR Principles**: Supports FAIR principles within its primary repositories but is less commonly applied outside these systems.
   - **Community Standards**: Recognized within the PRIDE and PeptideAtlas communities, with limited recognition outside proteomics.

---

### Metabolomics-Focused Ontologies

1. **ChEBI (Chemical Entities of Biological Interest)**
   - **Interoperability**: Highly interoperable, with cross-references to other databases and ontologies (e.g., KEGG, GO).
   - **FAIR Principles**: ChEBI’s data is well-curated and widely accessible, aligning strongly with FAIR.
   - **Community Standards**: A cornerstone ontology in metabolomics and chemistry research, broadly accepted as a standard.

2. **Metabolomics Society Ontology (MSO)**
   - **Interoperability**: Still evolving in terms of interoperability with broader ontologies and standards.
   - **FAIR Principles**: Works towards FAIR principles, but as a newer ontology, its broad application is still limited.
   - **Community Standards**: Gaining acceptance within metabolomics but is not yet as universally adopted as ChEBI or KEGG.

3. **HMDB Ontology**
   - **Interoperability**: Primarily designed for use within the Human Metabolome Database (HMDB), with some cross-links to ChEBI.
   - **FAIR Principles**: Meets FAIR principles within the context of HMDB but may be less accessible outside this framework.
   - **Community Standards**: Well-respected within human metabolomics but has limited applicability to other datasets.

4. **KEGG (Kyoto Encyclopedia of Genes and Genomes)**
   - **Interoperability**: Widely interoperable, with extensive cross-references and connections to other ontologies.
   - **FAIR Principles**: KEGG aligns closely with FAIR, especially for findability and reusability.
   - **Community Standards**: Widely accepted as a standard for pathway and metabolic data, often used alongside other major ontologies.

---

### Imaging (Microscopy)-Focused Ontologies

1. **Ontology for Biomedical Investigations (OBI)**
   - **Interoperability**: Broadly interoperable and integrates well with other biomedical ontologies.
   - **FAIR Principles**: Strong adherence to FAIR principles, with structured metadata supporting data discovery and reuse.
   - **Community Standards**: Well-accepted as a standard ontology for experimental protocols and methods in biomedical research.

2. **Biological Imaging Data Ontology (BIM)**
   - **Interoperability**: Limited interoperability with broader ontologies, as it is highly specialized.
   - **FAIR Principles**: BIM is relatively new and evolving in terms of FAIR compliance.
   - **Community Standards**: Not yet widely accepted, though gaining attention within the biological imaging community.

3. **Cell Ontology (CL)**
   - **Interoperability**: Highly interoperable, used alongside GO and other ontologies for cell-type classification.
   - **FAIR Principles**: Strongly aligned with FAIR principles due to its structure and standardized terms.
   - **Community Standards**: A widely accepted standard, often used for annotating cell types in imaging and other omics.

4. **Foundational Model of Anatomy (FMA)**
   - **Interoperability**: Interoperable with other anatomical and imaging ontologies, though primarily anatomy-focused.
   - **FAIR Principles**: FMA aligns well with FAIR principles, with accessible and standardized descriptions of anatomy.
   - **Community Standards**: Recognized as a standard in anatomical and imaging research.

---

### Multi-Domain and Integrative Ontologies

1. **BioAssay Ontology (BAO)**
   - **Interoperability**: Interoperable with other ontologies, supporting diverse assay descriptions.
   - **FAIR Principles**: BAO aligns with FAIR principles but is limited to data in bioassay contexts.
   - **Community Standards**: Established as a standard for bioassays, but its application is limited outside assay-related projects.

2. **Experimental Factor Ontology (EFO)**
   - **Interoperability**: Integrates well across multiple domains, making it highly interoperable.
   - **FAIR Principles**: Strongly aligns with FAIR principles and supports extensive experimental metadata.
   - **Community Standards**: Widely used in multi-domain projects, making it a recognized standard.

3. **Phenotype and Trait Ontology (PATO)**
   - **Interoperability**: Often used in conjunction with other ontologies to describe phenotypic traits.
   - **FAIR Principles**: Strongly aligns with FAIR principles for phenotypic data, though its use in other contexts may be limited.
   - **Community Standards**: Well-established in phenotypic and trait-based studies but less common outside these areas.

4. **NCBI Taxonomy Ontology**
   - **Interoperability**: Broadly interoperable across biological datasets, facilitating cross-species comparisons.
   - **FAIR Principles**: Strongly FAIR-compliant and accessible.
   - **Community Standards**: The primary standard for taxonomy across biological domains.

5. **Ontology for Biomedical Investigations (OBI)**
   - **Interoperability**: Broadly interoperable across biomedical fields.
   - **FAIR Principles**: Strongly FAIR, supports metadata-rich descriptions of experiments.
   - **Community Standards**: Universally accepted as a standard for describing biomedical investigations.

---

### Summary

- **Most-Compliant Ontologies**: Gene Ontology (GO), ChEBI, KEGG, OBI, and EFO are highly compliant with best practices for ontology use and selection across interoperability, FAIR principles, and community standards.

- **Evolving Compliance**: Ontologies like MSO, HMDB Ontology, and BIM are valuable for specific data types but are newer or less widely integrated, affecting their interoperability and broader community adoption.

For comprehensive data management, focusing on the well-established ontologies and integrating evolving ones where necessary will ensure strong adherence to best practices while allowing room for specialization.
