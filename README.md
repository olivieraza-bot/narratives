PromptLogicML

PromptLogicML is a semantic prompt engineering framework for large language models (LLMs), designed to model regulatory timelines and decision logic using XML-like syntax paired with MathML. It enables structured, interpretable prompts for high-stakes domains such as financial reporting, AI governance, and compliance automation.

________________________________________
Folder Structure Overview
PromptLogicML/
│
├── prompts/                        	→ XML/MathML prompt templates
│   ├── finance/                    	→ Scenarios for financial reporting (e.g., IFRS, FINREP)
│   └── ai_regulation/         		→ Scenarios for AI governance (e.g., EU AI Act)
│
├── schemas/                      		 → XML tag definitions and MathML condition structures
│   ├── tags.xml                  		 → Core tag vocabulary for semantic overlays
│   └── conditions.mathml        	 → MathML logic blocks for threshold and rule modeling
│
├── examples/                     		 → Rendered outputs and annotated walkthroughs
│   ├── finance_timeline.md      	→ Example: quarterly reporting with logic triggers
│   └── ai_compliance_map.md       → Example: EU AI Act lifecycle with decision logic
│
├── docs/                         	 → Technical documentation and semantic overlay guides
│   ├── architecture.md            → Overview of prompt structure and logic layering
│   └── integration.md             → Guidelines for LLM orchestration and dashboard embedding
│
├── dashboards/                    	→ Modular dashboard logic and mutation-tagged models
│   ├── ledger_mutations.xml       	→ Compliance ledger with mutation tracking
│   └── overlay_templates.xml    	→ Reusable semantic overlays for visual logic
│
├── tests/                         		→ Prompt validation and logic consistency checks
│   ├── schema_validation.py       	→ XML/MathML schema integrity tests
│   └── threshold_assertions.py   	→ Unit tests for logic triggers and escalation paths
│
├── CONTRIBUTING.md            	→ Contribution guidelines and formatting standards
├── LICENSE                        	→ Project license (e.g., MIT)
└── README.md                      	→ Project overview and onboarding instructions
________________________________________

Features
- XML-tagged prompt scaffolding with embedded MathML conditions
- Timeline modeling across multi-phase regulatory workflows
- Mutation-tagged logic for thresholds, escalation triggers, and audit checkpoints
- Modular overlays for domain-specific semantic enrichment
Advantages
- Supports both financial and AI regulatory use cases (e.g., IFRS, FINREP, EU AI Act)
- Enables machine-readable logic for traceability, reproducibility, and auditability
- Compatible with compliance dashboards, structured documentation, and LLM orchestration pipelines

Benefits
- Reduces ambiguity in LLM outputs for regulated environments
- Facilitates interdisciplinary synthesis across legal, technical, and operational teams
- Accelerates deployment of interpretable, scalable prompt systems for enterprise-grade governance

License
This project is licensed under the [MIT License](LICENSE) — © 2025 Olivier RAZANAJATOVO.  
You are free to use, modify, and distribute this software with proper attribution.  
See the full license text in the `LICENSE` file.




