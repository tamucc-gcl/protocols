# protocols

Inventory of protocols used by the GCL

---

## Organization

```graphql
project_root/
├── README.md                         # Overview of the repository (list of protocols, how to navigate)
├── protocols/
│   ├── PCR_Sample_Prep/
│   │   ├── README.md                 # Brief overview of the PCR Sample Prep protocol
│   │   ├── protocol.md               # Detailed steps of the protocol
│   │   ├── data/
│   │   │   └── sample_data.xlsx
│   │   ├── images/
│   │   │   └── workflow_diagram.png
│   │   ├── scripts/
│   │   │   └── analysis_script.py
│   │   └── results/
│   │       └── example_output.csv
│   └── DNA_Extraction/
│       ├── README.md                # Overview of the DNA Extraction protocol
│       ├── protocol.md             # Detailed protocol steps
│       ├── data/
│       │   └── extraction_steps.csv
│       ├── images/
│       │   └── pipetting_guide.png
│       ├── scripts/                # (if any protocol-specific scripts)
│       └── results/                # (if any example outputs)
└── shared_resources/
    ├── scripts/
    │   ├── normalization_tool.py    # Script used across multiple protocols
    │   └── visualization.R          # Another common analysis/plotting script
    ├── accessory_files/
    │   ├── universal_calculator.xlsx   # Common spreadsheet or reference data
    │   └── general_protocol_guidelines.md  # General guidelines used by all protocols
    └── README.md                    # (Optional) Descriptions of shared tools and files

```

* The readme will provide an organized set of links and instructions for maintaining this repo.
* Each protocol will be detailed in a markdown document in the [protocols](./protocols) dir
* Files associated with each protocol will be stored in the [accessory_files](accessory_files) dir and must be linked in the protocol that uses them
* Scripts associated with the protocols will be stored in the [scripts](scripts) dir
* Each new protocol should be created from the [protocol template](protocols/protocol_template.md) markdown doc 
* If this organization scheme doesn't work for a particular protocol, bring this to the attention of @cbird808 to solve

---

 
