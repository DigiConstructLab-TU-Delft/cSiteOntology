# CSite Ontology

The **CSite ontology** provides a modular semantic framework for integrating data related to production control in construction projects. It was developed as part of ongoing research at TU Delft, with use cases validated in live digital twin construction control rooms.

📖 **Online Documentation:**  
https://digiconstructlab-tu-delft.github.io/cSiteOntology/

🔗 **Permanent Identifier (W3ID):**  
https://w3id.org/cSite

---

## 🧠 Purpose

CSite enables the semantic integration of:

- Spatial hierarchy (site, building, storey, workspace) using BOT
- Project resources (agents, equipment, materials) aligned with PROV and BFO
- Planning and execution activities (engineering, procurement, QA) with spatial, temporal, and resource links
- Document control and planning workflows (submittals, week plans) based on DICE

It supports queries such as:

- “Which subcontractor had the lowest productivity this week?”
- “What activities were replanned and why?”
- “Which deliverables are pending due to missing submittals?”

---

## 📦 Repository Contents

```
cSiteOntology/
├── index-en.html           # Main WIDOCO-generated HTML page
├── ontology.ttl            # Turtle serialization of CSite ontology
├── ontology.owl            # RDF/XML serialization
├── ontology.jsonld         # JSON-LD serialization
├── resources/              # Images, CSS, JS used by documentation
├── sections/               # Editable HTML sections for WIDOCO
├── provenance/             # Provenance metadata about how the page was generated
├── README.md               # This file
```

---

## 📚 Citation

Farghaly, K., Soman, R., Whyte, J. (2024). *CSite ontology for production control of construction sites*. Automation in Construction, 158, 105224.  
Soman, R.K., Farghaly, K., Mills, G., Whyte, J. (2025). *Digital twin construction with a focus on human twin interfaces*. Automation in Construction, 170, 105924.

-
## 🛠 Developed With

- [WIDOCO](https://github.com/dgarijo/Widoco) – for automatic ontology documentation generation
- [BOT](https://w3id.org/bot), [PROV-O](https://www.w3.org/TR/prov-o/), [BFO](https://github.com/BFO-ontology/BFO), [DICE](https://digitalconstruction.github.io/Entities/)

---

## ❓ Questions or Issues?

Open an issue on this repository or contact the contributors via TU Delft.