# 🧬 Epitope Prediction for Vaccine Design

This project focuses on the **in silico identification of B-cell and T-cell epitopes** from the Dengue virus NS1 protein using Python. The goal is to shortlist potential peptide candidates for vaccine design using a basic bioinformatics and immunoinformatics workflow.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/epitope-prediction/blob/main/Epitope_Prediction_20250625.ipynb)

---

## 📂 Project Structure

| File                             | Description |
|----------------------------------|-------------|
| `Epitope_Prediction_20250625.ipynb` | Main Google Colab notebook with full workflow |
| `dengue_ns1.fasta`               | Input protein sequence file |
| `README.md`                      | Project documentation |
| (optional) `requirements.txt`   | Python packages used |

---

## 🧠 Objectives

- Load and parse a viral protein sequence (FASTA format)
- Predict B-cell epitopes using hydrophilicity scoring
- Import T-cell epitope predictions from IEDB
- Visualize and rank epitope candidates
- Generate a heatmap based on immunogenicity

---

## 🧰 Tools & Technologies

- Python
- Google Colab
- BioPython
- pandas
- matplotlib
- seaborn
- IEDB NetMHC (external)

---

## 📊 Key Outputs

- Line plot of hydrophilicity scores for B-cell epitope regions
- Table of high-scoring B-cell peptide windows
- Sample MHC-I T-cell epitope table
- Heatmap of immunogenicity scores

---

## ✅ How to Run

1. Clone the repo or [Download the notebook](https://github.com/YOUR_USERNAME/epitope-prediction/blob/main/Epitope_Prediction_20250625.ipynb)
2. Upload the `dengue_ns1.fasta` file in Google Colab
3. Run all cells sequentially
4. Use [IEDB NetMHC](http://tools.iedb.org/mhci/) to get actual MHC binder data

---

## 📌 Conclusion

- Predicted B-cell and T-cell epitopes from the Dengue NS1 protein
- Visualized antigenic potential of candidate peptides
- Demonstrated how computational immunology accelerates vaccine research
- This framework can be extended to any protein for vaccine target mining

---

## 👨‍🔬 Author

**Shubkarandeep Singh Judge**  

---

