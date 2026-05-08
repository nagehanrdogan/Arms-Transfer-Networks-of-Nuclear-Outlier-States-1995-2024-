# Arms-Transfer-Networks-of-Nuclear-Outlier-States-1995-2024-
*Nagehan Reyhan Doğan** | PhD Candidate, Istanbul University | 2026

---

## Research Question
Do states outside or in tension with the NPT occupy structurally 
distinct positions in the global conventional arms transfer network?

## Data
This project uses the **SIPRI Arms Transfers Database**.  
Data is **not included** in this repository due to licensing restrictions.

**To download the data:**
1. Go to: https://armstransfers.sipri.org/ArmsTransfer/TransferRegister
2. Settings: Year 1995–2025 | Order by Buyer
3. Check: ✓ Register with deliveries broken down by year
4. Click **Download as CSV**
5. Save as `trade-register.csv` in the same folder as the notebook

## Requirements
pip install pandas numpy networkx matplotlib

## Usage
Open `NA-Outsider-NPT.ipynb` and run cells in order.  
Outputs are saved to the `outputs/` folder.

## Country Groups

| Country | NPT Status | Group |
|---------|-----------|-------|
| Israel, India, Pakistan, North Korea | Non-signatory / Withdrawn | Outlier |
| Iran | Member – Contentious | Outlier_NPT |
| Turkiye, South Korea, Brazil | Compliant | Control |

## Citation
Doğan, N. R. (2026). *Outside the Regime: Arms Transfer Networks of 
Nuclear Outlier States (1995–2024)*. Unpublished working paper, 
Istanbul University.
