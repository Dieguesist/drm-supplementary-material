# A Digital Risk Metamodel: Supplementary Material

Anonymized supplementary material for the manuscript *A Digital Risk Metamodel*, under double-blind review at *Business & Information Systems Engineering* (BUIS-D-26-00193). This repository allows inspection and reproduction of the modeling and evaluation artifacts described in the manuscript.

## Contents

```
/models
    Digital Risk MetaModel v1.archimate    Preliminary metamodel (V1), ArchiMate 3.1, Archi format
    DRM V1 (Figure 2).xml                  V1 in the ArchiMate Model Exchange File Format
    Digital Risk Metamodel V2.archimate    Refined metamodel (V2), ArchiMate 3.1, Archi format
    Digital Risk Metamodel V2.xml          V2 in the ArchiMate Model Exchange File Format
    DRelements.csv                         Machine-readable element listing of V2 (Archi CSV export)
    DRrelations.csv                        Machine-readable relationship listing of V2
    DRproperties.csv                       Relationship properties of V2
/evaluation
    interview-guide.pdf                    Semi-structured interview protocol (three phases)
    aggregated-results.csv                 Likert-scale results, aggregated across the 23 participants
    archimate-familiarity.csv              Self-reported ArchiMate familiarity distribution
    results-by-archimate-familiarity.csv   Aggregated results split by ArchiMate familiarity group
/coding
    concept-coding-scheme.csv   Concept extraction and coding scheme (SLR/MLR to DRM concepts)
/figures
    models/                                Metamodel views: V1 (Figure 2) and V2 integrative view (Figure 6), vector PDF
    case-a/                                Case A instantiation views, vector PDF
    case-b/                                Case B instantiation views, vector PDF
    *.png                                  Expert evaluation charts, 300 dpi
README.md
LICENSE
```

## How to open the models

The `.archimate` files were created with the open-source tool [Archi](https://www.archimatetool.com/), version 5.5.0. Open them via *File > Open Model*. No plugins are required. The models conform to the ArchiMate 3.1 specification. The .xml files contain the same two models in the Open Group ArchiMate Model Exchange File Format, for import into other ArchiMate tools. The CSV files mirror the V2 model in tool-independent form (elements, relationships, and relationship properties).

## Structure of the artifact

The DRM is documented at three complementary levels, consistent with the manuscript. The V2 model file contains the integrative view, centered on the strategic and transformation dimensions and their connection to the risk management activities. The complete concept set, including the operational and governance concepts (Risk Source, Risk Event, Risk Owner, Interdependency, Governance Mechanism, Policy, Performance Indicator), is specified in the manuscript's concept tables with their ArchiMate mappings. The concrete modeling of those concepts is shown in the case instantiation views, provided as high-resolution figures in `/figures`.

## Evaluation data

The expert evaluation involved 23 professionals (28 invited, response rate approximately 82%). In accordance with the conditions of participant consent, results are provided in aggregated form only; no individual-level responses, demographic records, or free-text answers that could identify a participant are included. In addition to the overall score distributions, `results-by-archimate-familiarity.csv` provides the same aggregated distributions split by self-reported ArchiMate familiarity (14 participants with familiarity 2 or lower, 9 with 3 or higher), supporting the discussion of notation familiarity as a potential confound in the manuscript.

## Case material

The two case instantiations are derived from an interview with the cybersecurity and data protection officer of a European retail organization. They are provided as rendered high-resolution views in `/figures` rather than as model sources: the instantiations derive from case material covered by a confidentiality agreement, and the rendered views correspond exactly to the figures in the manuscript. Incident-level documentation from the case organization is not included for the same reason.
