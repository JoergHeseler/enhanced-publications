# SIP Example: UrbanHistory4D_Dresden_Enhanced_Publication_SIP

This repository contains a complete Submission Information Package (SIP) for the long-term digital preservation of the **UrbanHistory4D – City of Dresden Enhanced Publication**, including the 4D Browser, 3D models, historical photographs, spatial datasets, database exports, and a virtualized WebGL application.

## Background

This SIP is part of the accompanying materials to the guideline  
[**“Digitale Langzeitarchivierung von Enhanced Publications”**](https://doi.org/10.5281/zenodo.17476461),  
published within the NFDI4Culture community’s recommendations.

It demonstrates how complex, multimodal research objects—here the UrbanHistory4D Enhanced Publication—can be packaged sustainably for long-term digital preservation. Components represented in this SIP include:

- the 4D Browser web application,
- glTF-based 3D models of historic buildings,
- high-quality digitised and born-digital photographs,
- GeoTIFF map layers,
- a SIARD database export,
- an emulated legacy browser environment (QCOW2),
- accompanying documentation, articles, and media assets,
- and semantic documentation via **RO-Crate 1.1**.

## Repository Contents

The SIP is located in the folder:  
[`UrbanHistory4D_Dresden_Enhanced_Publication_SIP`](./UrbanHistory4D_Dresden_Enhanced_Publication_SIP/)

It contains:

### Web Application
`data/webapp/`
- 3D building models (glTF + binary + textures)  
- historical and contemporary photographs (TIFF)  
- relational database export (`urbanhistory4d.siard`)  
- emulation environment (`urbanhistory4d.qcow2`)  
- browser capability record and run instructions  
- interaction video (MKV)  
- map layers (GeoTIFF)  
- related PDF/A-3 articles

### Project Website
`data/website/`
- reduced and preservable HTML5 version  
- images, logos, and embedded tutorial video  
- partner, workshop, and project description pages  

### Metadata
`meta/`
- rights information  
- provenance links  
- technical metadata (e.g., PREMIS)

### Semantic Documentation
- **`ro-crate-metadata.json`** – machine-actionable RO-Crate 1.1 description of all components

### BagIt Structure
Includes:
- `bag-info.txt`  
- `bagit.txt`  
- manifest and tagmanifest files (MD5 + SHA-256)

## Related Projects

- **UrbanHistory4D**  
  https://urbanhistory4d.org/

- **NFDI4Culture – Reference Implementations for 3D/Enhanced Publications**  
  https://git.slub-dresden.de/nfdi4culturedigitalpreservation/

- **Guideline Repository: Digitale Langzeitarchivierung von Enhanced Publications**  
  https://github.com/nfdi4culture/enhanced-publications-lza-guideline

## Acknowledgments

This SIP was created with support from:

- **SLUB Dresden**, Division for Infrastructure and Long-Term Availability  
- the **UrbanHistory4D research group**, for providing data, software, and documentation  
- colleagues from **NFDI4Culture** in Dresden and Heidelberg, for technical feedback and preservation expertise  

Their contributions to workflow modelling, preservation validation, and technical review are gratefully acknowledged.

## Imprint

[NFDI4Culture](https://nfdi4culture.de/) – Consortium for Research Data on Material and Immaterial Cultural Heritage.  
Funded by the German Research Foundation (DFG), Project No. [441958017](https://gepris.dfg.de/gepris/projekt/441958017).

**Author:** [Jörg Heseler](https://orcid.org/0000-0002-1497-627X)  
**License:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

### Licensing Notes

Licensing conditions follow the statements in `meta/rights.xml` and in the RO-Crate metadata.  
Historical photographs are provided by **Deutsche Fotothek / SLUBArchiv.digital**, with identifiers and IIIF references preserved in the SIP.  
3D models, maps, and software components originate from the UrbanHistory4D project and are included for preservation and research purposes.