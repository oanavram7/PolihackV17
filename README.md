# 🧬 GeneChain

GeneChain is a bioinformatics project that helps users explore detailed information about specific genes, including:

- 🔍 Gene details (e.g., function, pathways)
- 💊 Medicines associated with the gene
- 🦠 Diseases linked to the gene
- 🧪 Other genes related to or interacting with the input gene

This tool is useful for researchers, healthcare developers, and anyone interested in genomics and precision medicine.


## 🚀 Features
- Search a gene using its ID (e.g., from KEGG)
- Fetch associated diseases and syndromes
- Get recommended or related drugs
- Display similar or related genes from the same pathway or network
- Store and reuse pathway objects for faster querying

## 🧠 Tech Stack

- *Frontend:* HTML, CSS, JavaScript
- *Backend:* Python, Flask
- *Database:* SQLite3
- *Data Source:* KEGG REST API
- *Libraries:* requests, json, and bioinformatics utilities

## 🛠 Usage
- **Start the application:  python app.py
- **Open your web browser and navigate to:http://localhost:5000


## 🌐 KEGG API Examples

Here are some useful KEGG API endpoints used by the application:

- 🔗 [Pathway Details (hsa00982)](https://rest.kegg.jp/get/path:hsa00982)  
- 🔗 [Link a Gene to Pathways (TP53 - hsa:7157)](https://rest.kegg.jp/link/pathway/hsa:7157)  
- 🔗 [Get Gene Info (BRCA1 - hsa:672)](https://rest.kegg.jp/get/hsa:672)