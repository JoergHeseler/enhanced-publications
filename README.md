# SIP Example: UrbanHistory4D_Dresden_Enhanced_Publication
 
This repository contains a **demonstration-only Submission Information Package (SIP)** for the long-term digital preservation of the **UrbanHistory4D – City of Dresden Enhanced Publication**.
 
⚠️ **Important Note**  
All files included in this SIP are **dummy / placeholder files**.  
They contain **no original research data**, **no real UrbanHistory4D software**, and **no authentic media assets**.  
The purpose of this repository is solely to **demonstrate the SIP structure and the RO-Crate metadata model** for educational and reference use.
 
## Background
 
This SIP accompanies the guideline:  
[**“Digitale Langzeitarchivierung von Enhanced Publications”**](https://doi.org/10.5281/zenodo.17476461)  
published within the NFDI4Culture community’s recommendations.
 
It illustrates:
 
- how a complex Enhanced Publication can be packaged as a **BagIt-based SIP**,  
- how its components can be **semantically documented** using **RO-Crate 1.1**,  
- how provenance, preservation state, and external archival links can be modelled,  
- and how workflow examples for preserving multimodal research objects can be implemented.
 
The SIP structure is therefore intended as a **teaching and demonstration resource**,  
not as a functional reproduction of the original UrbanHistory4D system.
 
## Repository Contents
 
The full SIP is located in:  
[`UrbanHistory4D_Dresden_Enhanced_Publication_SIP`](./UrbanHistory4D_Dresden_Enhanced_Publication_SIP/)
 
It includes the following **placeholder** components:
 
### Semantic Documentation (core of this repository)
`data/`
- **`ro-crate-metadata.json`** – complete demonstration of RO-Crate 1.1 modelling  
  describing the full SIP structure, preservation states, and interrelations.
 
### Web Application (dummy content)
`data/webapp/`
- placeholder 3D building models (glTF + bin + textures)  
- placeholder photographs (TIFF)  
- dummy SIARD database export  
- dummy emulation environment (`urbanhistory4d.qcow2`)  
- placeholder map layers (GeoTIFF)  
- example video (MKV, dummy)  
- placeholder PDF/A-3 articles  
 
### Project Website (dummy static HTML)
`data/website/`
- reduced and preservable static HTML5 version (structure only)  
- placeholder images and video  
- project description, partner, and workshop pages  
 
### Metadata
`meta/`
- rights metadata (example)  
- provenance links  
- technical metadata (PREMIS-inspired)
 
### BagIt Structure
Includes:
- `bag-info.txt`  
- `bagit.txt`  
- `manifest-md5.txt`, `manifest-sha256.txt`  
- tagmanifests for metadata and root directory
 
This provides a fully valid **BagIt + RO-Crate demonstrator**.
 
## Purpose of the Dummy Files
 
Using placeholder files ensures:
 
- no licensing or copyright issues,
- a lightweight and shareable repository,
- full transparency of the preservation modelling,
- easy reuse of the SIP structure in training and tooling contexts,
- focus on the **RO-Crate metadata**, which is the main subject of this example.
 
## Related Projects
 
- **UrbanHistory4D (original project)**  
  https://urbanhistory4d.org/
 
- **NFDI4Culture – Reference Implementations for 3D & Enhanced Publications**  
  https://git.slub-dresden.de/nfdi4culturedigitalpreservation/
 
## Imprint
 
[NFDI4Culture](https://nfdi4culture.de/) – Consortium for Research Data on Material and Immaterial Cultural Heritage.  
Funded by the German Research Foundation (DFG), Project No. [441958017](https://gepris.dfg.de/gepris/projekt/441958017).
 
**Author:** [Jörg Heseler](https://orcid.org/0000-0002-1497-627X)  
**License:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)