## Prerequisites

- **Python 3.11 or higher** installed on your system
- **Poetry** - Python's dependency manager

## Installation

1. **Clone or navigate to the project directory**
   ```powershell
   cd path\to\graph-and-map-creator
   ```

2. **Install dependencies with Poetry**
   ```powershell
   poetry install
   ```

   This creates a virtual environment and installs all required packages automatically.

## Running the Analysis

1. Start the jupyter lab environment:
```powershell
juptyer lab
```
2. Execute all cells 


## What happens when you run it?

The script will:
1. Load your csv data from `data\JSS-SLR`
2. Conducts calculations and creates the diagrams 
3. Creates output files for each diagram in `:data\cleaned_for_analysis\JSS-SLR\pdf_exports`:


## Project Structure

```
graph-and-map-creator/
├── data/
│   ├── JSS-SLR/
│   │   └── full_table_for_analysis.csv             # Input csv file
│   └── cleaned_for_analysis/
│       └── JSS-SLR/
│           └── pdf_exports/                        # Created files 
├── notebooks/
│   └── jss_slr_mapping_study_visualization.ipynb   # Main analysis script
├── src/
│   └── graph-and-map-creator/
│       └── __init__.py              
├── pyproject.toml                                  # Poetry configuration
└── README.md                                       # You are here!
```
