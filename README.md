# Replication Package

This replication package accompanies our submission to **TOCE**. It provides all materials necessary for reviewers to understand our study design, participant materials, and analysis workflow. Identifying information (institutional details, participant identifiers, and compensation procedures) has been removed or anonymized in accordance with double-blind review requirements.

---

## Package Structure

### `Code Snippets and Requirements/`
Contains the code snippets and associated requirements used as debugging tasks in the experiment. Each snippet includes the seeded logical fault that participants were asked to localize.

### `Figures/`
All figures presented in the paper, provided in high-resolution formats. These can be regenerated using the scripts provided (see `Scripts/`).

### `G2-G3-G4-Instructions/`
Instructional materials provided to participants in Groups 2, 3, and 4.  
- **G2**: Abstract guidelines.  
- **G3**: Concrete but context-agnostic steps.  
- **G4**: Concrete and context-specific steps.  

These instructions are shown exactly as participants received them.

### `Scripts/`
Python scripts used for all analyses, including generation of figures and tables.  
- Scripts are written in Python 3.x.  
- Standard scientific libraries are used (e.g., pandas, numpy, matplotlib, seaborn).  
- No installation files are included; reviewers may use a standard Python scientific environment.

### `Surveys/`
Example post-task survey used in the study.  
- Since the experiment included five sessions, each with slightly different survey variants (e.g., start/end of session questions), this folder includes one representative survey file showing the **core set of questions and logic**.  
- This example reflects the actual wording and branching logic presented to participants, with identifying information removed for double-blind review.

### `Tables/`
Complete tables of results. Some tables were partially shown in the paper due to space constraints; here we provide the full versions.


---

## Reproducibility

To reproduce analyses and figures:  

1. Ensure Python 3.x with pandas, numpy, and matplotlib installed.  
2. Run scripts in the `Scripts/` folder.  
3. Input data are embedded within the package; outputs (figures and tables) will match those in the paper.  

