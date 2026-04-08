# Entity Truth Set: Search Database Metadata

This document provides deep-dive details for each entity in the truth set to assist in the development of robust search and disambiguation logic.

## Toyota Motor Corporation
- **Legal Name:** Toyota Motor Corporation
- **Ultimate Parent:** Toyota Motor Corporation
- **ISIN/Ticker:** JP3633400001 | 7203 (Tokyo Stock Exchange)
- **Search Considerations:**
  - **Global Presence:** Often searched as 'Toyota'. Parent and operational entity share name.
  - **Notes:** N/A

## JPMorgan Chase
- **Legal Name:** JPMorgan Chase & Co.
- **Ultimate Parent:** JPMorgan Chase & Co.
- **ISIN/Ticker:** US46625H1005 | JPM (NYSE)
- **Search Considerations:**
  - **Notes:** N/A

## Royal Dutch Shell
- **Legal Name:** Shell plc
- **Ultimate Parent:** Shell plc
- **ISIN/Ticker:** GB00BP6MXD84 | SHEL (LSE)
- **Search Considerations:**
  - **Suffixes:** Search should account for 'Shell', 'Shell plc', and 'Royal Dutch Shell'.
  - **Notes:** Renamed from Royal Dutch Shell plc to Shell plc in Jan 2022.

## Tata Consultancy Services
- **Legal Name:** Tata Consultancy Services Limited
- **Ultimate Parent:** Tata Sons Private Limited
- **ISIN/Ticker:** INE467B01029 | TCS (NSE)
- **Search Considerations:**
  - **Notes:** Parent (Tata Sons) is private; TCS is public.

## Petrobras
- **Legal Name:** Petróleo Brasileiro S.A. - Petrobras
- **Ultimate Parent:** Government of Brazil
- **ISIN/Ticker:** BRPETRACNPR6 | PETR4 (B3)
- **Search Considerations:**
  - **Notes:** State-controlled entity.

## AIA Group
- **Legal Name:** AIA Group Limited
- **Ultimate Parent:** AIA Group Limited
- **ISIN/Ticker:** HK0000069689 | 1299 (HKEX)
- **Search Considerations:**
  - **Notes:** N/A

## Nokia Oyj
- **Legal Name:** Nokia Oyj
- **Ultimate Parent:** Nokia Oyj
- **ISIN/Ticker:** FI0009000681 | NOKIA (Nasdaq Helsinki)
- **Search Considerations:**
  - **Notes:** N/A

## Credit Suisse
- **Legal Name:** Credit Suisse AG
- **Ultimate Parent:** UBS Group AG
- **ISIN/Ticker:** CH0244767585 | UBSG (SIX)
- **Search Considerations:**
  - **Notes:** Acquired by UBS Group AG in June 2023.

## Instagram
- **Legal Name:** Instagram, LLC
- **Ultimate Parent:** Meta Platforms, Inc.
- **ISIN/Ticker:** US30303M1027 | META (NASDAQ)
- **Search Considerations:**
  - **Alias Logic:** Handle 'Facebook' as a high-confidence synonym for 'Meta Platforms'.
  - **Notes:** Subsidiary of Meta Platforms, Inc.

## YouTube
- **Legal Name:** YouTube, LLC
- **Ultimate Parent:** Alphabet Inc.
- **ISIN/Ticker:** US02079K3059 | GOOGL (NASDAQ)
- **Search Considerations:**
  - **Parent-Subsidiary:** Queries for 'Google' or 'YouTube' must link to Alphabet Inc. but retain product-specific context.
  - **Notes:** Subsidiary of Alphabet Inc.

## Fidelity International
- **Legal Name:** FIL Limited
- **Ultimate Parent:** FIL Limited
- **ISIN/Ticker:** N/A | N/A (N/A)
- **Search Considerations:**
  - **Notes:** Private; independent from US-based Fidelity Investments (FMR).

## Skype Technologies
- **Legal Name:** Skype Communications S.à r.l.
- **Ultimate Parent:** Microsoft Corporation
- **ISIN/Ticker:** US5949181045 | MSFT (NASDAQ)
- **Search Considerations:**
  - **Notes:** Subsidiary of Microsoft Corporation.

## LinkedIn Corporation
- **Legal Name:** LinkedIn Corporation
- **Ultimate Parent:** Microsoft Corporation
- **ISIN/Ticker:** US5949181045 | MSFT (NASDAQ)
- **Search Considerations:**
  - **Notes:** Subsidiary of Microsoft Corporation.

## Aramco
- **Legal Name:** Saudi Arabian Oil Company
- **Ultimate Parent:** Government of Saudi Arabia
- **ISIN/Ticker:** SA14TG012N13 | 2222 (Tadawul)
- **Search Considerations:**
  - **Notes:** State-controlled entity.

## Infosys Limited
- **Legal Name:** Infosys Limited
- **Ultimate Parent:** Infosys Limited
- **ISIN/Ticker:** INE009A01021 | INFY (NSE)
- **Search Considerations:**
  - **Notes:** N/A

## Banco Santander
- **Legal Name:** Banco Santander, S.A.
- **Ultimate Parent:** Banco Santander, S.A.
- **ISIN/Ticker:** ES0113900J37 | SAN (BMAD)
- **Search Considerations:**
  - **Notes:** N/A

## BHP Group
- **Legal Name:** BHP Group Limited
- **Ultimate Parent:** BHP Group Limited
- **ISIN/Ticker:** AU000000BHP4 | BHP (ASX)
- **Search Considerations:**
  - **Notes:** Unified dual-listed structure in 2022.

## ICBC
- **Legal Name:** Industrial and Commercial Bank of China Limited
- **Ultimate Parent:** Central Huijin Investment
- **ISIN/Ticker:** CNE1000003G1 | 1398 (HKEX)
- **Search Considerations:**
  - **Notes:** State-controlled (China).

## Warner Bros Discovery
- **Legal Name:** Warner Bros. Discovery, Inc.
- **Ultimate Parent:** Warner Bros. Discovery, Inc.
- **ISIN/Ticker:** US9344231026 | WBD (NASDAQ)
- **Search Considerations:**
  - **Notes:** Formed via merger of WarnerMedia and Discovery in 2022.

## Raytheon Technologies
- **Legal Name:** RTX Corporation
- **Ultimate Parent:** RTX Corporation
- **ISIN/Ticker:** US74965L1008 | RTX (NYSE)
- **Search Considerations:**
  - **Notes:** Rebranded from Raytheon Technologies to RTX in 2023.

## Daimler AG
- **Legal Name:** Mercedes-Benz Group AG
- **Ultimate Parent:** Mercedes-Benz Group AG
- **ISIN/Ticker:** DE0007100000 | MBG (XETRA)
- **Search Considerations:**
  - **Notes:** Renamed from Daimler AG to Mercedes-Benz Group AG in 2022.

## Facebook
- **Legal Name:** Meta Platforms, Inc.
- **Ultimate Parent:** Meta Platforms, Inc.
- **ISIN/Ticker:** US30303M1027 | META (NASDAQ)
- **Search Considerations:**
  - **Alias Logic:** Handle 'Facebook' as a high-confidence synonym for 'Meta Platforms'.
  - **Notes:** Renamed from Facebook, Inc. to Meta Platforms, Inc. in 2021.

## Refinitiv
- **Legal Name:** Refinitiv US Holdings Inc.
- **Ultimate Parent:** London Stock Exchange Group plc
- **ISIN/Ticker:** GB00B0SWJX34 | LSEG (LSE)
- **Search Considerations:**
  - **Notes:** Acquired by London Stock Exchange Group in 2021.

## Houlihan Lokey Inc
- **Legal Name:** Houlihan Lokey, Inc.
- **Ultimate Parent:** Houlihan Lokey, Inc.
- **ISIN/Ticker:** US4415931038 | HLI (NYSE)
- **Search Considerations:**
  - **Notes:** Global investment bank; focus on M&A, restructuring, and valuation.

## ExxonMobil Corporation
- **Legal Name:** Exxon Mobil Corporation
- **Ultimate Parent:** Exxon Mobil Corporation
- **ISIN/Ticker:** US30231G1022 | XOM (NYSE)
- **Search Considerations:**
  - **Notes:** Formed via merger of Exxon and Mobil in 1999. Largest US oil major.

## Haleon plc
- **Legal Name:** Haleon plc
- **Ultimate Parent:** Haleon plc
- **ISIN/Ticker:** GB00BMX86B70 | HLN (LSE)
- **Search Considerations:**
  - **Notes:** Consumer healthcare giant; spun off from GSK in July 2022.

## AIG
- **Legal Name:** American International Group, Inc.
- **Ultimate Parent:** American International Group, Inc.
- **ISIN/Ticker:** US0268747849 | AIG (NYSE)
- **Search Considerations:**
  - **Notes:** Global insurance organization. Spun off Corebridge Financial (CRBG) in 2022-2024.

## Murata Manufacturing Co Ltd
- **Legal Name:** Murata Manufacturing Co., Ltd.
- **Ultimate Parent:** Murata Manufacturing Co., Ltd.
- **ISIN/Ticker:** JP3914400001 | 6981 (Tokyo Stock Exchange)
- **Search Considerations:**
  - **Notes:** Leading manufacturer of electronic components, especially ceramic capacitors.

## UPM-Kymmene Oyj
- **Legal Name:** UPM-Kymmene Oyj
- **Ultimate Parent:** UPM-Kymmene Oyj
- **ISIN/Ticker:** FI0009005987 | UPM (Nasdaq Helsinki)
- **Search Considerations:**
  - **Notes:** Finnish forest industry company; leading producer of graphic papers.

## Holcim Ltd
- **Legal Name:** Holcim Ltd
- **Ultimate Parent:** Holcim Ltd
- **ISIN/Ticker:** CH0012214059 | HOLN (SIX)
- **Search Considerations:**
  - **Notes:** Building materials leader. Formerly LafargeHolcim; reverted to Holcim name in 2021.

## Telstra Group Limited
- **Legal Name:** Telstra Group Limited
- **Ultimate Parent:** Telstra Group Limited
- **ISIN/Ticker:** AU000000TLS2 | TLS (ASX)
- **Search Considerations:**
  - **Notes:** Australia's largest telecommunications company; restructured into 'Telstra Group' in 2022.

## Woolworths Group Limited
- **Legal Name:** Woolworths Group Limited
- **Ultimate Parent:** Woolworths Group Limited
- **ISIN/Ticker:** AU000000WOW2 | WOW (ASX)
- **Search Considerations:**
  - **Notes:** Major Australian retail conglomerate. Spun off Endeavour Group in 2021.

## TC Energy Corporation
- **Legal Name:** TC Energy Corporation
- **Ultimate Parent:** TC Energy Corporation
- **ISIN/Ticker:** CA87807B1076 | TRP (TSX)
- **Search Considerations:**
  - **Notes:** Formerly TransCanada. Spun off South Bow (Liquids Pipelines) in Oct 2024.

## Saint-Gobain SA
- **Legal Name:** Compagnie de Saint-Gobain S.A.
- **Ultimate Parent:** Compagnie de Saint-Gobain S.A.
- **ISIN/Ticker:** FR0000125007 | SGO (Euronext Paris)
- **Search Considerations:**
  - **Notes:** Founded in 1665; leading French multinational in construction and high-performance materials.

## Fresenius SE & Co KGaA
- **Legal Name:** Fresenius SE & Co. KGaA
- **Ultimate Parent:** Else Kröner-Fresenius-Stiftung
- **ISIN/Ticker:** DE0005785604 | FRE (XETRA)
- **Search Considerations:**
  - **Notes:** Healthcare conglomerate. Majority owner of Fresenius Medical Care (FME).

## State Bank of India
- **Legal Name:** State Bank of India
- **Ultimate Parent:** Government of India
- **ISIN/Ticker:** INE062A01020 | SBIN (NSE)
- **Search Considerations:**
  - **Notes:** Largest public sector bank in India. Statutory body under the SBI Act 1955.

## Samsung Biologics Co Ltd
- **Legal Name:** Samsung Biologics Co., Ltd.
- **Ultimate Parent:** Samsung Electronics / Samsung C&T
- **ISIN/Ticker:** KR7207940008 | 207940 (KRX)
- **Search Considerations:**
  - **Notes:** Major biopharmaceutical CDMO within the Samsung Group.

## America Movil SAB de CV
- **Legal Name:** América Móvil, S.A.B. de C.V.
- **Ultimate Parent:** América Móvil, S.A.B. de C.V.
- **ISIN/Ticker:** MXP001691213 | AMX (BMV)
- **Search Considerations:**
  - **Notes:** Mexican telecom giant controlled by the Slim family. Spun off Sitios Latinoamérica in 2022.

## Qatar National Bank
- **Legal Name:** Qatar National Bank (Q.P.S.C.)
- **Ultimate Parent:** Qatar Investment Authority
- **ISIN/Ticker:** QA0006929895 | QNBK (QSE)
- **Search Considerations:**
  - **Notes:** Largest commercial bank in the Middle East and Africa. 50% state-owned.

## ING Group NV
- **Legal Name:** ING Groep N.V.
- **Ultimate Parent:** ING Groep N.V.
- **ISIN/Ticker:** NL0011821202 | INGA (Euronext Amsterdam)
- **Search Considerations:**
  - **Notes:** Global Dutch bank. Traces roots to NMB Postbank and Nationale-Nederlanden merger.

## Oracle Corporation
- **Legal Name:** Oracle Corporation
- **Ultimate Parent:** Oracle Corporation
- **ISIN/Ticker:** US68389X1054 | ORCL (NYSE)
- **Search Considerations:**
  - **Notes:** Tech giant. Moved HQ from Redwood City, CA to Austin, TX in 2020.

## Crocs Inc
- **Legal Name:** Crocs, Inc.
- **Ultimate Parent:** Crocs, Inc.
- **ISIN/Ticker:** US2270461096 | CROX (NASDAQ)
- **Search Considerations:**
  - **Notes:** Global casual footwear brand; acquired HEYDUDE in Feb 2022.

## Merck KGaA
- **Legal Name:** Merck KGaA
- **Ultimate Parent:** E. Merck KG
- **ISIN/Ticker:** DE0006599905 | MRK (XETRA)
- **Search Considerations:**
  - **Disambiguation:** Crucial distinction from US Merck (Merck & Co). Often requires country code or full legal name `Merck KGaA`.
  - **Notes:** German science and technology company. Not to be confused with US-based Merck & Co. (MSD).

## Mondelez International Inc
- **Legal Name:** Mondelez International, Inc.
- **Ultimate Parent:** Mondelez International, Inc.
- **ISIN/Ticker:** US6092071058 | MDLZ (NASDAQ)
- **Search Considerations:**
  - **Notes:** Successor to Kraft Foods snacks business. Brands include Oreo, Cadbury, and Nabisco.

## Eaton Corporation plc
- **Legal Name:** Eaton Corporation plc
- **Ultimate Parent:** Eaton Corporation plc
- **ISIN/Ticker:** IE00B8KQN827 | ETN (NYSE)
- **Search Considerations:**
  - **Notes:** Power management company headquartered in Dublin, Ireland (domiciled there since 2012).

## CK Asset Holdings Limited
- **Legal Name:** CK Asset Holdings Limited
- **Ultimate Parent:** Li Ka Shing Foundation
- **ISIN/Ticker:** KYG2177B1014 | 1113 (HKEX)
- **Search Considerations:**
  - **Notes:** Hong Kong real estate conglomerate; part of the CK Hutchison ecosystem.

## AMD
- **Legal Name:** Advanced Micro Devices, Inc.
- **Ultimate Parent:** Advanced Micro Devices, Inc.
- **ISIN/Ticker:** US0079031078 | AMD (NASDAQ)
- **Search Considerations:**
  - **Notes:** Major semiconductor manufacturer; acquired Xilinx in 2022.

## CLP Holdings Limited
- **Legal Name:** CLP Holdings Limited
- **Ultimate Parent:** CLP Holdings Limited
- **ISIN/Ticker:** HK0002007356 | 2 (HKEX)
- **Search Considerations:**
  - **Notes:** China Light and Power; one of the two main electricity generators in Hong Kong.

## GE Aerospace
- **Legal Name:** General Electric Company
- **Ultimate Parent:** General Electric Company
- **ISIN/Ticker:** US3696043013 | GE (NYSE)
- **Search Considerations:**
  - **Legacy Matching:** Map historical 'General Electric' queries here. Note that GE HealthCare and GE Vernova are now separate entities.
  - **Notes:** Primary remaining business of GE after spinning off GE HealthCare (2023) and GE Vernova (2024).

## HSBC
- **Legal Name:** HSBC Holdings plc
- **Ultimate Parent:** HSBC Holdings plc
- **ISIN/Ticker:** GB0005405286 | HSBA (LSE)
- **Search Considerations:**
  - **Notes:** One of the world's largest banking groups. Domiciled in the UK; major operations in Hong Kong.

## Siemens
- **Legal Name:** Siemens AG
- **Ultimate Parent:** Siemens AG
- **ISIN/Ticker:** DE0007236101 | SIE (XETRA)
- **Search Considerations:**
  - **Notes:** Largest industrial manufacturing company in Europe. Spun off Siemens Energy in 2020.

## Alibaba Group
- **Legal Name:** Alibaba Group Holding Limited
- **Ultimate Parent:** Alibaba Group Holding Limited
- **ISIN/Ticker:** KYG017191142 | 9988 (HKEX)
- **Search Considerations:**
  - **Notes:** E-commerce and cloud giant. Reorganized into six business groups in 2023.

## Zurich Insurance Group
- **Legal Name:** Zurich Insurance Group AG
- **Ultimate Parent:** Zurich Insurance Group AG
- **ISIN/Ticker:** CH0011075394 | ZURN (SIX)
- **Search Considerations:**
  - **Notes:** Swiss insurance giant. Operates globally in over 200 countries and territories.

## Unilever plc
- **Legal Name:** Unilever plc
- **Ultimate Parent:** Unilever plc
- **ISIN/Ticker:** GB00BVZK7T90 | ULVR (LSE)
- **Search Considerations:**
  - **Notes:** Unified under a single British parent (Unilever plc) in Nov 2020, ending dual-headed structure.

## Berkshire Hathaway
- **Legal Name:** Berkshire Hathaway Inc.
- **Ultimate Parent:** Berkshire Hathaway Inc.
- **ISIN/Ticker:** US0846707026 | BRK.B (NYSE)
- **Search Considerations:**
  - **Notes:** Diverse conglomerate led by Warren Buffett (Chairman) and Greg Abel (CEO as of 2026).

## LVMH
- **Legal Name:** LVMH Moët Hennessy Louis Vuitton SE
- **Ultimate Parent:** Financière Agache (Arnault Family)
- **ISIN/Ticker:** FR0000121014 | MC (Euronext Paris)
- **Search Considerations:**
  - **Notes:** Leading luxury goods group. Includes Louis Vuitton, Dior, and Tiffany & Co.

## Novartis AG
- **Legal Name:** Novartis AG
- **Ultimate Parent:** Novartis AG
- **ISIN/Ticker:** CH0012005267 | NOVN (SIX)
- **Search Considerations:**
  - **Notes:** Global pharma company. Spun off Alcon (2019) and Sandoz (2023).

## Rio Tinto Group
- **Legal Name:** Rio Tinto plc
- **Ultimate Parent:** Rio Tinto plc
- **ISIN/Ticker:** GB0007188757 | RIO (LSE)
- **Search Considerations:**
  - **Dual Structure:** Watch for both UK (LSE:RIO) and AU (ASX:RIO) listings. They represent the same group but different legal entities.
  - **Notes:** Dual-listed structure (PLC in UK, Ltd in AU). This record represents the UK parent.

## Ping An Insurance
- **Legal Name:** Ping An Insurance (Group) Company of China, Ltd.
- **Ultimate Parent:** Charoen Pokphand / Shenzhen Investment
- **ISIN/Ticker:** CNE1000003X6 | 2318 (HKEX)
- **Search Considerations:**
  - **Notes:** Chinese conglomerate; world's most valuable insurance brand as of 2024.

## Sony Group Corporation
- **Legal Name:** Sony Group Corporation
- **Ultimate Parent:** Sony Group Corporation
- **ISIN/Ticker:** JP3435000009 | 6758 (Tokyo Stock Exchange)
- **Search Considerations:**
  - **Notes:** Conglomerate. Renamed from Sony Corporation in 2021 to separate the group from electronics.

## Volkswagen AG
- **Legal Name:** Volkswagen Aktiengesellschaft
- **Ultimate Parent:** Porsche Automobil Holding SE
- **ISIN/Ticker:** DE0007664039 | VOW3 (XETRA)
- **Search Considerations:**
  - **Control Hierarchy:** While VW AG is a parent, Porsche SE (PAH3) holds majority voting rights. Search database should flag this cross-ownership.
  - **Notes:** Parent of Audi, Porsche, Bentley, etc. Controlled by the Porsche-Piëch family.

## UBS Group AG
- **Legal Name:** UBS Group AG
- **Ultimate Parent:** UBS Group AG
- **ISIN/Ticker:** CH0244767585 | UBSG (SIX)
- **Search Considerations:**
  - **Integration:** Credit Suisse (CS) should map to UBS records post-June 2023.
  - **Notes:** Swiss banking giant. Completed acquisition of Credit Suisse in 2023.

## Deutsche Bank AG
- **Legal Name:** Deutsche Bank Aktiengesellschaft
- **Ultimate Parent:** Deutsche Bank Aktiengesellschaft
- **ISIN/Ticker:** DE0005140008 | DBK (XETRA)
- **Search Considerations:**
  - **Notes:** Largest German banking group. Operates in nearly 60 countries.

