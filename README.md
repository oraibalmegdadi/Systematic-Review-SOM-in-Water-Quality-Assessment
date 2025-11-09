# Self-Organizing Maps for Water Quality Assessment in Reservoirs and Lakes: A Systematic Literature Review  


This repository provides the **supplementary materials and extracted data** for the article:  

**Self-Organizing Maps for Water Quality Assessment in Reservoirs and Lakes: A Systematic Literature Review**  
Published in *XXXXX* (DOI to be added)  

**Authors:**  
Oraib Almegdadi<sup>1,2</sup>, Joao Marcelino<sup>2</sup>, Sarah Fakhreddine<sup>3</sup>, Joao Manso<sup>2</sup>, and Nuno C. Marques<sup>1</sup>  

<sup>1</sup> NOVA LINCS, Department of Computer Science, NOVA University Lisbon, Portugal  
<sup>2</sup> Laboratório Nacional de Engenharia Civil (LNEC), Department of Geotechnics, Lisbon, Portugal  
<sup>3</sup> Civil and Environmental Engineering, Carnegie Mellon University, Pittsburgh, USA  

---
### Overview  

This review **synthesises current research** on the application of **Self-Organizing Maps (SOM)** for assessing and monitoring water quality in lakes and reservoirs. It analyses how SOM has been used to reveal **patterns**, **spatial clusters**, and **ecological gradients** from physicochemical, biological, and watershed parameters, highlighting its role in advancing environmental monitoring and management.  

The study explores five main aspects:  
1. **Objectives and analysed parameters**  
2. **Datasets and sampling approaches**  
3. **Spatial and temporal scales**  
4. **Advantages and limitations of SOM**  
5. **Tools and implementation methods**

---
### Visual Abstract

![Review Visual Abstract](https://github.com/oraibalmegdadi/Systematic-Review-SOM-in-Water-Quality-Assessment/blob/main/Images/Abstarct.png)



---


### 📁 Repository Structure  
### Supplementary Material: Parameters

The supplementary Excel file [`SupplementaryMaterial-Parameters.xlsx`](https://github.com/oraibalmegdadi/Systematic-Review-SOM-in-Water-Quality-Assessment/blob/main/Materials/SupplementaryMaterial-Parameters.xlsx) contains two sheets:

| **Sheet** | **Name** | **Description** |
|------------|-----------|----------------|
| 1 | `Parameters-Acronym-Alphabet` | Lists all environmental and water-quality parameters extracted from the reviewed studies, arranged alphabetically with their corresponding acronyms. |
| 2 | `UnifiedParAcr-Freq-Class` | Aggregates parameters into unified groups, showing synonyms/acronyms, frequency of occurrence, and thematic classification (e.g., Nutrients and Oxygen Demand, Metals/Metalloids, Physicochemical). |

#### Example (Sheet 1 – Parameters-Acronym-Alphabet)

| **Parameter** | **Acronym** |
|----------------|-------------|
| Alkalinity | ALK |
| Aluminum | Al |
| Ammonia nitrogen | N-NH₄ |
| Ammoniacal Nitrogen | NH₃-N |
| Ammonium Nitrogen | NH₄⁺ |

#### Example (Sheet 2 – UnifiedParAcr-Freq-Class)

| **Unified Parameter Name** | **Synonyms / Acronyms** | **Unified Acronym (Treemap)** | **Frequency** | **Classification** |
|-----------------------------|--------------------------|-------------------------------|----------------|--------------------|
| Phosphorus | P, Pₜ, Pₐ, PₜD, Tₚₚ, PO₄³⁻ | P | 21 | Nutrients and Oxygen Demand |
| Water Temperature | Tₜʷ | Tₜʷ | 20 | Physicochemical |
| Chlorophyll-a | Chl-a | Chl-a | 19 | Physicochemical |


Full dataset available at:  
📄 [SupplementaryMaterial-Parameters.xlsx](https://github.com/oraibalmegdadi/Systematic-Review-SOM-in-Water-Quality-Assessment/blob/main/Materials/SupplementaryMaterial-Parameters.xlsx)
#### **File 2 – Metadata**
**`Metadata_Articles.xlsx`** contains two sheets:  
- **Sheet 1: `Articles-Metadata`**  
  Includes bibliographic metadata for all retrieved articles: author, year, region, study focus, dataset type, SOM configuration, and key findings.  
- **Sheet 2: `Selected-Articles-Analysis`**  
  Summarises the final set of included studies with concise notes on methodological approaches, SOM architecture, clustering tools, and interpretative outcomes.

---

### 🧩 Usage  
These materials support reproducibility and transparency in literature-based analyses of SOM applications. Users may reuse or expand the dataset for meta-analyses, comparative AI studies, or educational purposes in environmental modelling.

---

### 📄 Citation  


