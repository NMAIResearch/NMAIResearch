## Noel Milton · NM AI Research

Independent researcher and analyst working on AI assurance, model evaluation, and the operational systems behind AI deployment.

Manchester, UK · [nmairesearch.github.io](https://nmairesearch.github.io/) · [ORCID 0009-0003-4213-7769](https://orcid.org/0009-0003-4213-7769) · [Zenodo Archive](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22NM%20AI%20Research%22) · [Hugging Face](https://huggingface.co/NMAIResearch) · [Email](mailto:NMAIResearch@proton.me)

---

Research focuses on designing, evaluating, and auditing AI systems from first principles: finding where AI workflows break, testing model confidence against ground truth, and building reproducible data pipelines and zero-dependency analytical tools.

Across twenty open-access studies, twenty-two Zenodo DOIs, and eight interactive browser tools, every quantitative claim is backed by a standalone Python verification script and frozen citable data.

Earlier background is ten years in operations and process design, quality assurance, and KPI-driven performance evaluation. BA in Business Management (2024). Bilingual English and Hungarian (C2).

---

### Selected Work & Empirical Audits

- **What Actually Admits a Document to FineWeb-Edu.** Audited the data-quality filter used to curate training corpora across 84 million documents from 94 Common Crawl snapshots. Found the documented threshold operates on rounded integers (making the true admission boundary a raw score above 2.5), the classifier scores documents on a truncated prefix of 510 tokens, and bfloat16 tie-breaking cut 458,461 documents purely by rounding parity.  
  [Interactive Tool](https://nmairesearch.github.io/fineweb-edu-threshold/) · [Zenodo DOI 10.5281/zenodo.21740081](https://doi.org/10.5281/zenodo.21740081) · [Dataset on Hugging Face](https://huggingface.co/datasets/NMAIResearch/fineweb-edu-threshold) · [Source Code](https://github.com/NMAIResearch/fineweb-edu-threshold)

- **The Model Is a Dependency (Testing the Audit Case for Open Weights).** Evaluated whether open weights permit auditing or merely record what was run. Tested token entropy against 594 pinned local model runs on SEC XBRL ground truth. Standard uncertainty signals caught none of 106 source misattributions, showing that provenance alone is insufficient for verification without deterministic controls.  
  [Interactive Tool](https://nmairesearch.github.io/model-dependency/) · [Zenodo DOI 10.5281/zenodo.21543579](https://doi.org/10.5281/zenodo.21543579) · [Source Code](https://github.com/NMAIResearch/model-dependency)

- **Public Evidence under Article 50 (EU AI Act Transparency Snapshot).** The first public empirical audit of twelve consumer AI products conducted four days after the EU AI Act transparency obligations applied. Mapped eleven requirements to dated, motive-tagged provider artefacts, establishing a baseline to measure provider movements across transitional deadlines.  
  [Interactive Explorer](https://nmairesearch.github.io/article50-explorer/) · [Zenodo DOI 10.5281/zenodo.21819102](https://doi.org/10.5281/zenodo.21819102) · [Source Code](https://github.com/NMAIResearch/article50-scoreboard)

- **AI Infrastructure: Power, Water, and Grid Queues.** Rebuilt the Water Consumption Impact index across ten facilities, showing that closed-loop cooling shifts 92 to 95 per cent of the water footprint to the electrical grid. Modelled PJM and UK grid connection queue attrition, demonstrating that approximately one in five announced megawatts reaches final delivery.  
  [Water Tracker](https://nmairesearch.github.io/ai-water-tracker/) · [Zenodo DOI 10.5281/zenodo.21318960](https://doi.org/10.5281/zenodo.21318960) · [Power Demand Tool](https://nmairesearch.github.io/contingent-demand/)

- **The CEO Pay-vs-Delivery Scorecard.** Ingested SEC EDGAR Pay-vs-Performance disclosures across 495 S&P 500 issuers, separating granted from realised compensation against board performance targets and peer-relative returns.  
  [Scorecard](https://nmairesearch.github.io/ceo-pay-scorecard/) · [Zenodo DOI 10.5281/zenodo.20680108](https://doi.org/10.5281/zenodo.20680108) · [Source Code](https://github.com/NMAIResearch/ceo-pay-scorecard)

---

### Core Focus & Methods

- **AI Systems & Evaluation:** Model evaluations, uncertainty calibration (token entropy), agentic workflows and tool-calling interfaces (MCP), prompt injection and boundary testing, human-in-the-loop verification.
- **Governance & Assurance:** EU AI Act (Article 50 transparency clauses), Model Risk Management (MRM), content provenance (C2PA, machine-readable markings), ISO/IEC 42001 concepts.
- **Data Pipelines & Engineering:** Python (standard library, reproducible build.py and reproduce.py pipelines, SEC EDGAR and XBRL parsing), Vanilla JavaScript and HTML5 (zero-dependency interactive web tools), Git and GitHub Actions.
- **Operations & Quality Assurance:** Ten years in operational process design, compliance auditing (92 per cent annual audit rating), root-cause analysis, cross-functional standard operating procedures.

---

### Links & Verification

- Interactive portfolio: https://nmairesearch.github.io/
- Curriculum vitae: [Noel Milton CV (PDF)](https://nmairesearch.github.io/Noel_Milton_CV_Short.pdf)
- Zenodo archive: https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22NM%20AI%20Research%22
- Hugging Face datasets: https://huggingface.co/NMAIResearch
- ORCID record: https://orcid.org/0009-0003-4213-7769
- Contact: NMAIResearch@proton.me

---

AI disclosure: the research is the author's; this text was drafted with AI assistance and reviewed by the author. The model, and the conflict it creates, are named in the Conflict of interest section of each study.
