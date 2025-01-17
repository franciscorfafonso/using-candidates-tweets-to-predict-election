# Using Candidates' Tweets to Predict Election Outcome

This repository contains the code and data used for the extraction, manipulation, modeling, and results analysis in the research paper titled **"Using Candidates' Tweets to Predict Election Outcome"**, published in *Political Research Quarterly*.

For a more detailed understanding of the methodology and findings, you can read the research paper, which is available in [Political Research Quarterly](https://journals.sagepub.com/home/prq).

---

## Repository Structure

This repository is organized into four main folders, each representing a different stage of the research process. Here's an overview of each folder:

### 1. **Data Extraction and Manipulation** (`DataExtractionAndManip`)

- This folder contains code for extracting Tweets using the Twitter API (with Academic Research privileges) and other data that was manually collected from various sources.
- Files in this folder include raw Tweet data (`.xlsx` or `.pkl` files), which are later used for data preparation and modeling.

### 2. **Data Preparation** (`DataPrep`)

- This folder includes the code used for cleaning and manipulating the extracted Tweets.
- The notebooks in this folder generate the processed datasets that are used in the subsequent stages of the research.

### 3. **Topic Modeling** (`TopicModeling`)

- Here you will find the code for performing topic modeling on the prepared dataset.
- Both Latent Dirichlet Allocation (LDA) and Correlated Topic Model (CTM) approaches are explored in this folder, with comparisons between the two methods.

### 4. **Result Analysis** (`ResultsAnalysis`)

- This folder contains the analysis code used to test the study's hypotheses (H1a, H1b, and H2) and address the research question (RQ).
- The files in this folder will analyze and visualize the results, helping to interpret the findings related to predicting election outcomes from social media data.

---

## Guide to Using This Repository

- **Decompress Files**: Before running the Python notebooks, all compressed files (e.g., `.gz`, `.bz2`) must be decompressed.
- **File Dependencies**: Each folder contains `.xlsx` or `.pkl` files that are directly used by the notebooks within that folder. Files generated by one notebook and needed by another are located in the destination folder.
- **Comments for Clarity**: The code is well-commented to help you follow along with the decisions made throughout the analysis.

---

## How to Run

To run the code in this repository:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-url.git
   cd your-repository-url
2. Install the necessary Python dependencies
3. Ensure that all data files are decompressed and placed in their respective folders.
4. Open the Jupyter notebooks and run the cells in sequence to replicate the analysis.


---
## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

- You are free to share and adapt the materials as long as you provide attribution.
- Commercial use of the data and code is **not permitted**.
- If you modify or build upon this work, you must distribute your contributions under the same license.

For more information, see the full license [here](LICENSE).

---

## Citation

If you use this project in your research or academic work, please cite the original research paper:

*Afonso, Francisco, Rita, Paulo, and António, Nuno*. (2024). **Using Candidates' Tweets to Predict Election Outcome**. *Political Research Quarterly*. [Link to paper](https://journals.sagepub.com/home/prq).
