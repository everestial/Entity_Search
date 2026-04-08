# Entity Truth Set: The Original 23

This documentation focuses on the core 23 entities, providing the granular search database metadata required for robust entity resolution.

## Quick Reference Table

| Entity Name | Legal Name | Ultimate Parent | Parent Domicile (ISO alpha-2) | Is Public (Y/N) | Stock Exchange (N/A if private) | Ticker | ISIN (N/A if unavailable) | Source | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Toyota Motor Corporation | Toyota Motor Corporation | Toyota Motor Corporation | JP | Y | Tokyo Stock Exchange | 7203 | JP3633400001 | Public Filings | Global automotive leader; pioneer in hybrid technology. |
| JPMorgan Chase | JPMorgan Chase & Co. | JPMorgan Chase & Co. | US | Y | NYSE | JPM | US46625H1005 | SEC Filings | Largest US bank by assets. Formed via merger of Chase Manhattan and J.P. Morgan & Co. |
| Royal Dutch Shell | Shell plc | Shell plc | GB | Y | LSE | SHEL | GB00BP6MXD84 | LSE Filings | Rebranded from Royal Dutch Shell plc to Shell plc in Jan 2022; moved tax residence to UK. |
| Tata Consultancy Services | Tata Consultancy Services Limited | Tata Sons Private Limited | IN | Y | NSE | TCS | INE467B01029 | NSE India | Flagship subsidiary of the Tata Group; world's second largest IT services brand. |
| Petrobras | Petróleo Brasileiro S.A. - Petrobras | Government of Brazil | BR | Y | B3 | PETR4 | BRPETRACNPR6 | B3 Filings | State-controlled Brazilian multinational petroleum industry corporation. |
| AIA Group | AIA Group Limited | AIA Group Limited | HK | Y | HKEX | 1299 | HK0000069689 | HKEX Filings | Largest independent publicly listed pan-Asian life insurance group. |
| Nokia Oyj | Nokia Oyj | Nokia Oyj | FI | Y | Nasdaq Helsinki | NOKIA | FI0009000681 | Nasdaq | Finnish telecommunications, information technology, and consumer electronics company. |
| Credit Suisse | Credit Suisse AG | UBS Group AG | CH | Y | SIX | UBSG | CH0244767585 | UBS Filings | Merged into UBS Group AG in 2023 following a Swiss government-brokered rescue. |
| Instagram | Instagram, LLC | Meta Platforms, Inc. | US | Y | NASDAQ | META | US30303M1027 | SEC Filings | Visual social media platform; major revenue driver for Meta. |
| YouTube | YouTube, LLC | Alphabet Inc. | US | Y | NASDAQ | GOOGL | US02079K3059 | SEC Filings | World's largest video-sharing platform; primary subsidiary of Alphabet. |
| Fidelity International | FIL Limited | FIL Limited | BM | N | N/A | N/A | N/A | Company Website | Global investment manager; private and operationally independent from US Fidelity. |
| Skype Technologies | Skype Communications S.à r.l. | Microsoft Corporation | US | Y | NASDAQ | MSFT | US5949181045 | Microsoft Filings | Voice and video call service; integrated into Microsoft's software ecosystem. |
| LinkedIn Corporation | LinkedIn Corporation | Microsoft Corporation | US | Y | NASDAQ | MSFT | US5949181045 | Microsoft Filings | Professional networking site; acquired by Microsoft for $26.2 billion in 2016. |
| Aramco | Saudi Arabian Oil Company | Government of Saudi Arabia | SA | Y | Tadawul | 2222 | SA14TG012N13 | Tadawul Filings | World's largest oil producer; 2019 IPO was the largest in history. |
| Infosys Limited | Infosys Limited | Infosys Limited | IN | Y | NSE | INFY | INE009A01021 | NSE India | Multinational IT consulting and services; pioneer in India's software export boom. |
| Banco Santander | Banco Santander, S.A. | Banco Santander, S.A. | ES | Y | BMAD | SAN | ES0113900J37 | CNMV Filings | Largest Spanish banking group; major presence in Europe and the Americas. |
| BHP Group | BHP Group Limited | BHP Group Limited | AU | Y | ASX | BHP | AU000000BHP4 | ASX Filings | One of the world's largest mining companies; unified dual-listed structure in 2022. |
| ICBC | Industrial and Commercial Bank of China Limited | Central Huijin Investment | CN | Y | HKEX | 1398 | CNE1000003G1 | HKEX Filings | World's largest bank by total assets and market capitalization. |
| Warner Bros Discovery | Warner Bros. Discovery, Inc. | Warner Bros. Discovery, Inc. | US | Y | NASDAQ | WBD | US9344231026 | SEC Filings | Media giant formed via the 2022 merger of WarnerMedia and Discovery Inc. |
| Raytheon Technologies | RTX Corporation | RTX Corporation | US | Y | NYSE | RTX | US74965L1008 | SEC Filings | Defense and aerospace leader; rebranded as RTX in July 2023. |
| Daimler AG | Mercedes-Benz Group AG | Mercedes-Benz Group AG | DE | Y | XETRA | MBG | DE0007100000 | Company Filings | Renamed in 2022 to focus on luxury cars/vans; spun off Daimler Truck. |
| Facebook | Meta Platforms, Inc. | Meta Platforms, Inc. | US | Y | NASDAQ | META | US30303M1027 | SEC Filings | Rebranded to Meta in Oct 2021 to reflect focus on the metaverse. |
| Refinitiv | Refinitiv US Holdings Inc. | London Stock Exchange Group plc | GB | Y | LSE | LSEG | GB00B0SWJX34 | LSEG Filings | Financial market data provider; acquired by LSEG in early 2021. |

---

## Deep-Dive Search Metadata

### Toyota Motor Corporation
- **Primary Search Query:** Toyota Motor Corporation
- **Canonical Legal Name:** Toyota Motor Corporation
- **Corporate Parent:** Toyota Motor Corporation
- **Financial Identifier:** JP3633400001 | 7203 (Tokyo Stock Exchange)
- **Database Logic & Disambiguation:**
  - **Notes:** Global automotive leader; pioneer in hybrid technology.

### JPMorgan Chase
- **Primary Search Query:** JPMorgan Chase
- **Canonical Legal Name:** JPMorgan Chase & Co.
- **Corporate Parent:** JPMorgan Chase & Co.
- **Financial Identifier:** US46625H1005 | JPM (NYSE)
- **Database Logic & Disambiguation:**
  - **Disambiguation:** Distinguish between the commercial bank and the holding company 'JPMorgan Chase & Co.'
  - **Notes:** Largest US bank by assets. Formed via merger of Chase Manhattan and J.P. Morgan & Co.

### Royal Dutch Shell
- **Primary Search Query:** Royal Dutch Shell
- **Canonical Legal Name:** Shell plc
- **Corporate Parent:** Shell plc
- **Financial Identifier:** GB00BP6MXD84 | SHEL (LSE)
- **Database Logic & Disambiguation:**
  - **Alias Logic:** High importance. Update database to prefer 'Shell plc'. Map 'Royal Dutch Shell' as a high-confidence redirect.
  - **Notes:** Rebranded from Royal Dutch Shell plc to Shell plc in Jan 2022; moved tax residence to UK.

### Tata Consultancy Services
- **Primary Search Query:** Tata Consultancy Services
- **Canonical Legal Name:** Tata Consultancy Services Limited
- **Corporate Parent:** Tata Sons Private Limited
- **Financial Identifier:** INE467B01029 | TCS (NSE)
- **Database Logic & Disambiguation:**
  - **Notes:** Flagship subsidiary of the Tata Group; world's second largest IT services brand.

### Petrobras
- **Primary Search Query:** Petrobras
- **Canonical Legal Name:** Petróleo Brasileiro S.A. - Petrobras
- **Corporate Parent:** Government of Brazil
- **Financial Identifier:** BRPETRACNPR6 | PETR4 (B3)
- **Database Logic & Disambiguation:**
  - **Notes:** State-controlled Brazilian multinational petroleum industry corporation.

### AIA Group
- **Primary Search Query:** AIA Group
- **Canonical Legal Name:** AIA Group Limited
- **Corporate Parent:** AIA Group Limited
- **Financial Identifier:** HK0000069689 | 1299 (HKEX)
- **Database Logic & Disambiguation:**
  - **Notes:** Largest independent publicly listed pan-Asian life insurance group.

### Nokia Oyj
- **Primary Search Query:** Nokia Oyj
- **Canonical Legal Name:** Nokia Oyj
- **Corporate Parent:** Nokia Oyj
- **Financial Identifier:** FI0009000681 | NOKIA (Nasdaq Helsinki)
- **Database Logic & Disambiguation:**
  - **Notes:** Finnish telecommunications, information technology, and consumer electronics company.

### Credit Suisse
- **Primary Search Query:** Credit Suisse
- **Canonical Legal Name:** Credit Suisse AG
- **Corporate Parent:** UBS Group AG
- **Financial Identifier:** CH0244767585 | UBSG (SIX)
- **Database Logic & Disambiguation:**
  - **Lifestage:** Defunct/Acquired. Map all historical entity lookups to 'UBS Group AG'.
  - **Notes:** Merged into UBS Group AG in 2023 following a Swiss government-brokered rescue.

### Instagram
- **Primary Search Query:** Instagram
- **Canonical Legal Name:** Instagram, LLC
- **Corporate Parent:** Meta Platforms, Inc.
- **Financial Identifier:** US30303M1027 | META (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Parent Link:** Product entity. Search database must resolve 'Instagram' to 'Meta Platforms, Inc.' for financial reporting.
  - **Notes:** Visual social media platform; major revenue driver for Meta.

### YouTube
- **Primary Search Query:** YouTube
- **Canonical Legal Name:** YouTube, LLC
- **Corporate Parent:** Alphabet Inc.
- **Financial Identifier:** US02079K3059 | GOOGL (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Parent Link:** Product entity. Resolve to 'Alphabet Inc.' / 'Google'.
  - **Notes:** World's largest video-sharing platform; primary subsidiary of Alphabet.

### Fidelity International
- **Primary Search Query:** Fidelity International
- **Canonical Legal Name:** FIL Limited
- **Corporate Parent:** FIL Limited
- **Financial Identifier:** N/A | N/A (N/A)
- **Database Logic & Disambiguation:**
  - **Notes:** Global investment manager; private and operationally independent from US Fidelity.

### Skype Technologies
- **Primary Search Query:** Skype Technologies
- **Canonical Legal Name:** Skype Communications S.à r.l.
- **Corporate Parent:** Microsoft Corporation
- **Financial Identifier:** US5949181045 | MSFT (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Notes:** Voice and video call service; integrated into Microsoft's software ecosystem.

### LinkedIn Corporation
- **Primary Search Query:** LinkedIn Corporation
- **Canonical Legal Name:** LinkedIn Corporation
- **Corporate Parent:** Microsoft Corporation
- **Financial Identifier:** US5949181045 | MSFT (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Notes:** Professional networking site; acquired by Microsoft for $26.2 billion in 2016.

### Aramco
- **Primary Search Query:** Aramco
- **Canonical Legal Name:** Saudi Arabian Oil Company
- **Corporate Parent:** Government of Saudi Arabia
- **Financial Identifier:** SA14TG012N13 | 2222 (Tadawul)
- **Database Logic & Disambiguation:**
  - **Notes:** World's largest oil producer; 2019 IPO was the largest in history.

### Infosys Limited
- **Primary Search Query:** Infosys Limited
- **Canonical Legal Name:** Infosys Limited
- **Corporate Parent:** Infosys Limited
- **Financial Identifier:** INE009A01021 | INFY (NSE)
- **Database Logic & Disambiguation:**
  - **Notes:** Multinational IT consulting and services; pioneer in India's software export boom.

### Banco Santander
- **Primary Search Query:** Banco Santander
- **Canonical Legal Name:** Banco Santander, S.A.
- **Corporate Parent:** Banco Santander, S.A.
- **Financial Identifier:** ES0113900J37 | SAN (BMAD)
- **Database Logic & Disambiguation:**
  - **Notes:** Largest Spanish banking group; major presence in Europe and the Americas.

### BHP Group
- **Primary Search Query:** BHP Group
- **Canonical Legal Name:** BHP Group Limited
- **Corporate Parent:** BHP Group Limited
- **Financial Identifier:** AU000000BHP4 | BHP (ASX)
- **Database Logic & Disambiguation:**
  - **Notes:** One of the world's largest mining companies; unified dual-listed structure in 2022.

### ICBC
- **Primary Search Query:** ICBC
- **Canonical Legal Name:** Industrial and Commercial Bank of China Limited
- **Corporate Parent:** Central Huijin Investment
- **Financial Identifier:** CNE1000003G1 | 1398 (HKEX)
- **Database Logic & Disambiguation:**
  - **Notes:** World's largest bank by total assets and market capitalization.

### Warner Bros Discovery
- **Primary Search Query:** Warner Bros Discovery
- **Canonical Legal Name:** Warner Bros. Discovery, Inc.
- **Corporate Parent:** Warner Bros. Discovery, Inc.
- **Financial Identifier:** US9344231026 | WBD (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Notes:** Media giant formed via the 2022 merger of WarnerMedia and Discovery Inc.

### Raytheon Technologies
- **Primary Search Query:** Raytheon Technologies
- **Canonical Legal Name:** RTX Corporation
- **Corporate Parent:** RTX Corporation
- **Financial Identifier:** US74965L1008 | RTX (NYSE)
- **Database Logic & Disambiguation:**
  - **Rebrand Logic:** Flag 'RTX Corporation' as the current canonical name.
  - **Notes:** Defense and aerospace leader; rebranded as RTX in July 2023.

### Daimler AG
- **Primary Search Query:** Daimler AG
- **Canonical Legal Name:** Mercedes-Benz Group AG
- **Corporate Parent:** Mercedes-Benz Group AG
- **Financial Identifier:** DE0007100000 | MBG (XETRA)
- **Database Logic & Disambiguation:**
  - **Rebrand Logic:** 'Daimler AG' is now 'Mercedes-Benz Group AG'. Ensure cross-reference with 'Daimler Truck' to avoid ambiguity.
  - **Notes:** Renamed in 2022 to focus on luxury cars/vans; spun off Daimler Truck.

### Facebook
- **Primary Search Query:** Facebook
- **Canonical Legal Name:** Meta Platforms, Inc.
- **Corporate Parent:** Meta Platforms, Inc.
- **Financial Identifier:** US30303M1027 | META (NASDAQ)
- **Database Logic & Disambiguation:**
  - **Parent Link:** Product entity. Search database must resolve 'Facebook' to 'Meta Platforms, Inc.' for financial reporting.
  - **Notes:** Rebranded to Meta in Oct 2021 to reflect focus on the metaverse.

### Refinitiv
- **Primary Search Query:** Refinitiv
- **Canonical Legal Name:** Refinitiv US Holdings Inc.
- **Corporate Parent:** London Stock Exchange Group plc
- **Financial Identifier:** GB00B0SWJX34 | LSEG (LSE)
- **Database Logic & Disambiguation:**
  - **Acquisition Logic:** Subsidiary of London Stock Exchange Group (LSEG).
  - **Notes:** Financial market data provider; acquired by LSEG in early 2021.

