# **E. coli Protein Visualization and Analysis**

## **Overview**
This project focuses on visualizing and analyzing *Escherichia coli* protein structures to uncover their structural and functional properties. Using tools such as MDAnalysis and Biopython, the project highlights critical features like active sites and ligand interactions, providing insights into protein functionality and potential applications.

---

## **Key Features**
1. **Protein Visualization**:
   - High-quality 3D visualizations using MdAnalysis.
   - Highlighting of specific residues (e.g., active sites and binding pockets).

2. **Structural Analysis**:
   - Distance calculations between residues.
   - Insights into protein structure-function relationships.

3. **Documentation**:
   - Detailed methodology and results summaries.
   - Organized output files for reproducibility.

---

## **Tools and Software**
1. **PyMOL**: For 3D molecular visualization.
2. **Biopython**: For computational analysis of protein structures.
3. **Matplotlib**: For plotting structural metrics.
4. **Protein Data Bank (PDB)**: Source for protein structure datasets.

---

## **Project Structure**
```plaintext
Ecoli-Protein-Visualization/
├── data/
│   ├── protein_models/    # Raw PDB files
│   ├── processed_results/ # Outputs (visualizations, analysis results)
├── scripts/
│   ├── analysis.ipynb     # Jupyter notebook for structural analysis
│   ├── visualization.py   # PyMOL visualization script
├── docs/
│   ├── methodology.md     # Methodology description
│   ├── results.md         # Results summary
├── README.md              # Project overview and instructions
```

---

## **Dataset**
Protein structures were selected from the RCSB Protein Data Bank:
1. **Beta-Galactosidase** (PDB ID: 1JZC)
2. **Multidrug Efflux Pump AcrB** (PDB ID: 1IWG)
3. **DNA Gyrase** (PDB ID: 6RKS)
4. **Hemolysin Core Complex** (PDB ID: 1QOY)
5. **Type III Secretion System Needle** (PDB ID: 3TUL)
6. **Beta-Lactamase** (PDB ID: 1M40)

These proteins represent key functional categories:
- Metabolic enzymes.
- Virulence factors.
- Antibiotic resistance mechanisms.

---

## **Getting Started**

### **1. Prerequisites**
Ensure the following software is installed:
1. [PyMOL](https://pymol.org/2/)
2. [Python](https://www.python.org/) with the following libraries:
   ```bash
   pip install biopython matplotlib
   ```

### **2. Clone the Repository**
```bash
git clone https://github.com/your-username/Ecoli-Protein-Visualization.git
cd Ecoli-Protein-Visualization
```

### **3. Run Analysis and Visualization**
1. Place your PDB files in `data/protein_models/`.
2. Run the analysis notebook:
   ```bash
   jupyter notebook scripts/analysis.ipynb
   ```
3. Use the visualization script:
   ```bash
   python scripts/visualization.py
   ```

---

## **Results**
- High-quality visualizations of proteins, highlighting active sites and ligand interactions.
- Structural metrics such as residue distances and ligand-binding insights.
- Results are saved in the `processed_results/` directory.

---

## **Future Work**
1. Extend analysis to additional *E. coli* proteins.
2. Integrate molecular docking simulations for drug-binding studies.
3. Automate large-scale protein structure analysis.

---

## **References**
1. [RCSB Protein Data Bank](https://www.rcsb.org/)
2. [PyMOL Documentation](https://pymol.org/2/)
3. [Biopython Documentation](https://biopython.org/)
4. [Matplotlib Documentation](https://matplotlib.org/)
