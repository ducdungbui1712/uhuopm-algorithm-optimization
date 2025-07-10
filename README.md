# UHUOPM Algorithm Implementation & Optimization

## Overview

Implementation of UHUOPM algorithm from paper "High Utility Occupancy Pattern Mining in Uncertain Data" (IEEE SMC 2020) with performance optimizations achieving 68.5% runtime improvement.

## Files

- `code.ipynb` - Main Jupyter notebook containing all code blocks

## Setup

### 1. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn psutil collections-extended
```

### 2. Prepare Datasets

- Create folder `sample_data/` in same directory as notebook
- Place your datasets in the folder:
  - `mushroom.csv`
  - `retail.csv`
  - `foodmart.csv`

### 3. Dataset Format

Each line should contain items in format: `item:quantity,probability`

Example:

```
1:2,0.6 3:4,0.8 4:7,0.5
2:2,0.7 3:3,0.4
```

## Usage

### Run Jupyter Notebook

1. Open `uhuopm_implementation.ipynb`
2. Run blocks sequentially from Block 1 to Block 11:
   - **Block 1:** Paper definitions implementation
   - **Block 2:** Core algorithms implementation
   - **Block 3:** Pruning strategies implementation
   - **Block 4:** Paper examples validation
   - **Block 5:** Real dataset loading & processing
   - **Block 6:** Shared testing functions
   - **Block 7:** Original algorithm testing
   - **Block 8:** Original algorithm visualization
   - **Block 9:** Improved algorithm implementation
   - **Block 10:** Improved algorithm testing
   - **Block 11:** Comprehensive comparison

### Important Notes

- **Run blocks in order** - each block depends on previous ones
- **Wait for completion** before running next block
- Some blocks may take several minutes on large datasets

## Expected Results

- **Runtime Improvement:** 68.5% faster overall
- **Memory Usage:** 1.2% reduction
- **Pattern Accuracy:** 100% identical results with original algorithm
- **Visualization:** Performance comparison charts

## Key Achievements

- ✅ Complete original UHUOPM algorithm implementation
- ✅ 5 major optimizations implemented
- ✅ Comprehensive testing on real datasets
- ✅ Performance improvements validated
- ✅ Algorithm correctness preserved

## Requirements

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Minimum 4GB RAM recommended
- Datasets in correct format
