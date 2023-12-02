# Assignment 5: Architecture Redesign

### [CodeLabs](https://codelabs-preview.appspot.com/?file_id=1bxapYTqsC3TdIR0k2GHEqTF970M0YiDTwSU_bMdk3Wk#0)
### [Demo](https://youtu.be/cn2A8xZNjnw)

## Introduction
This project encapsulates the efforts undertaken in Assignment 5 to explore and design alternative technology stacks for our organization's production environment. In light of recent developments with OpenAI, we evaluated the feasibility of both open-source and enterprise component-based stacks, considering their suitability for our specific needs, scalability, and cost implications.

## Objectives

#### Redesign Architecture: To reevaluate our current architecture (based on Assignment 3) and propose two distinct alternatives:

- A stack primarily using Open Source Components.
- A stack composed of Primarily Enterprise Components as an alternative to the OpenAI stack.
Cost Analysis: To provide a detailed budget outlining the costs involved in building and maintaining these applications.

## Architecture Overviews

### Open Source Components Architecture
- Objective: To leverage the flexibility and cost-effectiveness of open-source technologies.
- Key Components: Hugging Face (for NLP), Luigi (for workflow orchestration), MongoDB (for database), etc.
- Hosting: Predominantly self-hosted with selected cloud services for specific functionalities.
- Cost Breakdown: Focus on computational resources and potential support costs.
- Suitability: Ideal for businesses looking for customizable and budget-friendly solutions.

### Enterprise Components Architecture
- Objective: To utilize enterprise solutions for enhanced support, reliability, and scalability.
- Key Components: Google Cloud Natural Language API, AWS Step Functions, Azure SQL Database, etc.
- Hosting: Primarily cloud-based services with managed hosting.
- Cost Breakdown: Emphasis on subscription fees, service-level agreements, and cloud service costs.
- Suitability: Suited for enterprises requiring robust, scalable, and supported solutions.
  
### Cost Analysis
#### Original Architecture (OpenAI Stack)
- Components: Airflow on GCP, FastAPI, Heroku, Streamlit, OpenAI API.
- Fixed Costs: Cloud hosting, maintenance contracts, and API subscription fees.
- Variable Costs: API access costs, data transfer, and storage fees.

#### New Architectures
- Open Source Stack: Lower fixed costs due to free software, offset by compute resources and potential support services.
- Enterprise Stack: Higher fixed costs (subscription and license fees), balanced by reduced maintenance needs and predictable pricing models.

## How to Use This Repository
- Architecture Diagrams: Found in the diagrams/ directory.
- Open AI Alternative Analysis Sheets: Detailed breakdowns available in the OpenAI Alternatives/ directory.
- Cost Analysis: Detailed Cost Analysis available in the Cost Analysis/ directory
- Documentation: In-depth explanations available in CodeLabs provided.

```
.
├── Cost Analysis
│   ├── Enterprise Cost Analysis.md
│   └── Open Source Cost Analysis.md
├── OpenAI Alternatives
│   └── Assignment_5.ipynb
├── README.md
└── diagrams
    ├── Enterprice Components Architecture.png
    ├── Open Source Components Architecture.png
    ├── Original Worflow Part-1.png
    └── Original Workflow Part 2.png
```

##### WE ATTEST THAT WE HAVEN’T USED ANY OTHER STUDENTS’ WORK IN OUR ASSIGNMENT AND ABIDE BY THE POLICIES LISTED IN THE STUDENT HANDBOOK

Contributions:
- Sumanayana Konda: 25%
- Akshatha Patil: 25%
- Ruthwik Bommenahalli Gowda: 25%
- Pavan Madhav Manikantha Sai Nainala: 25%


