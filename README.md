**International Affairs & Eurasian Risk Intelligence | Emerging Technologist**
📍 Washington D.C.

### Who I Am

I'm an international affairs analyst specializing in Eurasian political economy with native bilingual fluency in English and German and proficiency in Russian and Norwegian. In June 2026 I decided to teach myself Python.

From the Eurasian Entity Risk Screener onward, every line of code is mine. Earlier projects involved more guided instruction as I was learning syntax and structure from scratch. 

### What I'm Building

A technical portfolio at the intersection of financial crime intelligence, sanctions compliance, and geopolitical risk. These are the exact problems that Palantir, Sayari, Recorded Future, and the compliance divisions of major financial institutions work on every day.

### Projects

**[Sanctions Network Mapper](https://github.com/mino6225/sanctions-network-mapper)**
- Maps hidden connections between OFAC-sanctioned entities by analyzing shared physical addresses and ownership-adjacent data across the U.S. Treasury SDN list, the same kind of multi-tier relationship mapping used to trace ownership structures and single points of failure in supplier networks. Processes 19,015 sanctioned entities and built network graph analysis to detect entity clusters, then manually characterized cluster patterns (including a 147-entity shell shipping cluster consistent with dark fleet evasion structures) through entity-name review.
- Key finding: identified MONSOON SHIPPING LTD as the most connected sanctioned entity (113 network connections), consistent with Iranian dark fleet oil sanctions evasion infrastructure, and surfaced five distinct evasion networks including a 147-entity shell shipping cluster.
- Tech stack: Python, NetworkX, PyVis.

**[Eurasian Entity Risk Screener](https://github.com/mino6225/eurasian-risk-screener)**
- Screens companies against U.S. Treasury OFAC sanctions data and World Bank governance indicators to produce composite risk scores — directly analogous to vetting a supplier or third party against structured risk datasets. Integrates 19,015 OFAC-sanctioned entities (38,895 including alias/AKA names) with six World Bank Worldwide Governance Indicators across 215 countries. Sample output: ROSNEFT and WAGNER GROUP flagged CRITICAL (direct sanctions match, governance score -0.96); Gazprom flagged HIGH; Nokia and Siemens cleared LOW.
- Tech stack: Python, pandas, NumPy, matplotlib, seaborn.

**[Geopolitical News Sentiment Tracker](https://github.com/mino6225/geopolitical-news-sentiment)**
- Pulls live international news headlines via NewsAPI and runs NLP sentiment analysis to generate real-time geopolitical risk signals across high-risk countries and jurisdictions — turning unstructured open-source reporting into a structured risk feed. Analyzes up to 50 live headlines per country, classifies sentiment using VADER compound scoring (-1.0 to +1.0).
- Tech stack: Python, VADER Sentiment Analysis, pandas, matplotlib, seaborn, python-dotenv.

**[Loan Default Prediction Model](https://github.com/mino6225/loan-default-predictor)**
- Forked and modernized a classic loan-approval classification benchmark for current Python/sklearn compatibility; implemented and compared four algorithms (Logistic Regression, Decision Tree, Random Forest, XGBoost).
- Key finding: credit history is the dominant predictive feature, with applicants lacking credit history denied at ~92%.
- Tech stack: Python, scikit-learn, XGBoost, pandas, NumPy, seaborn, matplotlib.

 **[AML Transaction Surveillance Engine](https://github.com/mino6225/aml-surveillance-engine)**
- End-to-end Python AML detection system: synthetic transaction data generator with planted structuring, rapid movement, and round-trip patterns; five-rule detection engine (HRJ-001, STR-001, RMV-001, RRT-001, VEL-001); weighted risk scoring and High/Medium/Low tier classification; NetworkX transaction graph with PyVis interactive visualization; SAR report generator producing structured narrative summaries (triggered rules, risk score, associated accounts) for high-risk flagged accounts
- Tech stack: Python, pandas, NetworkX, PyVis, uuid, datetime, dataclasses.
  
### Currently Building
**Eurasian Illicit  Finance & Sanctions Evasion Intelligence Platform** 
Multi-source intelligence fusion platform combining OFAC sanctions data, World Bank governance indicators, network relationship analysis, and live news sentiment into a single composite risk score per entity. Extends prior work (Eurasian Risk Screener, Sanctions Network Mapper, AML Surveillance Engine) into one unified pipeline — introducing fuzzy name matching for transliterated entity names, betweenness centrality for identifying network "broker" entities, and weighted multi-signal risk fusion. Output: a ranked entity watchlist with automated intelligence report generation, modeled on real OFAC/FinCEN analytical products. 

### Background

- B.A. Global Affairs, Business Minor | CU Boulder → George Mason University
- Dean's List, Spring 2024
- Native: English, German | Proficiency: Russian, Norwegian

### Connect

💼 www.linkedin.com/in/mia-noll-jones-5953583b5
