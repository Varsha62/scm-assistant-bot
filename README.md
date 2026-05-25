# scm-assistant-bot
# public chatbot URL
https://cloud.flowiseai.com/chatbot/109eeccc-dd97-4ab9-a768-5cbd8985763f

#LLM and embeddings used
1. LLM Model Used:
Name: Google Gemini
Model Name: gemini-2.5-flash
Temperature: 0

2. Embeddings Used:
Name: Google Gemini Embedding
Model Name: gemini-embedding-01
Task Type: RETRIEVAL_QUERY

#two chunk configs tried
Configuration 1: For PDF Document
Document Type: PDF (SupplyChain_Governance_Policy_v3.2 1.pdf)
Text Splitter: Recursive Character Text Splitter
Chunk Size: 2000
Chunk Overlap: 400
Total Chunks Produced: 13

Configuration 2: For CSV Data File
Document Type: CSV (supplier_performance_data.csv)
Text Splitter: Recursive Character Text Splitter
Chunk Size: 1000
Chunk Overlap: 0 


# all 5 Q&A answers verbatim 
1. Which Tier-3 suppliers have an active disruption flag, and what response level applies per policy?
The Tier-3 suppliers with an active disruption flag are:
Bohai Electronics (Supplier_ID: SUP-010) with "Typhoon season disruption"
Dravex Components India (Supplier_ID: SUP-011) with "Typhoon season disruption"
Sahyadri Alloy Tech (Supplier_ID: SUP-017) with "Export license risk"
Deltaforge Vietnam (Supplier_ID: SUP-018) with "Port congestion risk"
MeKong Pack Co (Supplier_ID: SUP-020) with "Geopolitical tension flag"
DaNang Metal Works (Supplier_ID: SUP-022) with "Typhoon season disruption"
Archipelago PCB Corp (Supplier_ID: SUP-041) with "Labour strike risk"
Visayas Textile Co (Supplier_ID: SUP-042) with "Port congestion risk"

AI Assistant: Here are the Tier-3 suppliers with an active disruption flag and their applicable response levels:

SUP-007 (Longhua Polymer Works): Active Disruption: Labour strike risk (High Risk). Response Level: Level 3 (mandatory for active labour strikes).
SUP-010 (Bohai Electronics): Active Disruption: Regulatory enforcement pending (High Risk). Response Level: Level 3 (mandatory for regulatory enforcement actions).
SUP-011 (Dravex Components India): Active Disruption: Typhoon season disruption (High Risk). Response Level: Level 3.
SUP-014 (Deccan Polymer Mfg): Active Disruption: Currency volatility flag (High Risk). Response Level: Level 3.
SUP-017 (Sahyadri Alloy Tech): Active Disruption: Export license risk (High Risk). Response Level: Level 3 (mandatory for export control restrictions).
SUP-018 (Deltaforge Vietnam): Active Disruption: Port congestion risk (Medium Risk). Response Level: Level 2.
SUP-020 (MeKong Pack Co): Active Disruption: Typhoon season disruption (High Risk). Response Level: Level 3.
SUP-022 (DaNang Metal Works): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-041 (Archipelago PCB Corp): Active Disruption: Labour strike risk (High Risk). Response Level: Level 3 (mandatory for active labour strikes).
SUP-042 (Visayas Textile Co): Active Disruption: Regulatory enforcement pending (High Risk). Response Level: Level 3 (mandatory for regulatory enforcement actions).
SUP-045 (Sibertek Molding): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-075 (Vistula Pack Sp): Active Disruption: Regulatory enforcement pending (High Risk). Response Level: Level 3 (mandatory for regulatory enforcement actions).
SUP-078 (Varna Electronics EAD): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-079 (Helios Pack Greece): Active Disruption: Labour strike risk (High Risk). Response Level: Level 3 (mandatory for active labour strikes).
SUP-080 (Maghreb Castworks): Active Disruption: Regulatory enforcement pending (High Risk). Response Level: Level 3 (mandatory for regulatory enforcement actions).
SUP-089 (Yucatan Polymer Mfg): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-090 (Plataforma Metales SA): Active Disruption: Export license risk (High Risk). Response Level: Level 3 (mandatory for export control restrictions).
SUP-091 (Patagonia Alloys SRL): Active Disruption: Labour strike risk (High Risk). Response Level: Level 3 (mandatory for active labour strikes).
SUP-092 (Buenos Aires Pack): Active Disruption: Audit overdue; compliance review (High Risk). Response Level: Level 3.
SUP-094 (Bogota Pack Ltda): Active Disruption: Labour strike risk (High Risk). Response Level: Level 3 (mandatory for active labour strikes).
SUP-095 (Cerromax Mineria): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-096 (Lima Polymer SA): Active Disruption: Port closure risk (High Risk). Response Level: Level 3 (mandatory for port closure events exceeding 72 hours).
SUP-100 (Orinoco Pack SAPI): Active Disruption: Audit overdue; compliance review (High Risk). Response Level: Level 3.
SUP-101 (Quetzal Textiles): Active Disruption: Seasonal flood risk (Medium Risk). Response Level: Level 2.


2.  Which suppliers qualify for the annual Volume Rebate Program and how many are there?

google limit exit.
3.   Which region has the highest total PO value, and does it breach the concentration limit?
google limit exit.
4.    Which suppliers are on Supplier Watch List (SWL) status and what does it restrict?
SCM Assistant (Bot):
The product category with the highest average defect rate is Mechanical Components, with an average defect rate of 1.935%.
Regarding whether this exceeds the Tier-2 limit, I'm not sure, as the provided context does not contain information about specific defect rate limits for different contract tiers.

5. Which product category has the highest average defect rate and does it exceed the Tier-2 limit?
SCM Assistant (Bot):
The product category with the highest average defect rate is Mechanical Components, with an average defect rate of 1.761%.
According to the policy (Doc 4, Section 3.2), the Tier-2 maximum permissible defect rate is 2.50%. Since 1.761% is below 2.50%, it does not exceed the Tier-2 limit.


Custom Separator: ["\n"]

Total Chunks Produced: 2,000
