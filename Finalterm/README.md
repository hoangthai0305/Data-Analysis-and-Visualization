## Project Structure & Implementation Note

Due to the extensive amount of code and markdown content in each task, combining everything into a single Jupyter Notebook (`.ipynb`) would result in an excessively large file, making it difficult to process and navigate.

Therefore, we have decided to **split the project into separate files** for better performance and manageability.

---

## Critical Instructions (Please Read Carefully)

### 1. Execution Order
It is **mandatory** to execute the tasks sequentially. The output of the previous task is required for the next one.

**Required Order:**
`Task 1` -> `Task 2` -> `Task 3` -> `Task 4` -> `Task 5`

### 2. Data Integrity Warning
During execution, the scripts will generate intermediate files (e.g., images, `.csv` files, etc.).

**DO NOT modify, rename, move, delete, or edit these generated files.**

These files serve as essential **inputs** for subsequent tasks. Any alteration to file names or paths will cause errors in the following steps.

---

## Installation & Prerequisites

Please ensure you have the following libraries installed to run the project successfully:
* pandas
* numpy
* matplotlib
* seaborn
* scipy
* scikit-learn
* dcor
* warnings (standard library)

You can install the required packages using the command below:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
pip install dcor #(make sure you run this alone)