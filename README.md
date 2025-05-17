# Python-Capstone
Here’s a GitHub repository description tailored for the Python-based data processing project you described:

---

## 🐍 Data Processing & Transformation using Pandas – Project & Employee Dataset

This project demonstrates practical data cleaning, transformation, and analysis using **Python and Pandas** on three interrelated datasets — **Employee**, **Project**, and **Status**.

### 📋 Tasks Overview:

#### 🔧 Task 1: DataFrame Creation

* Create three DataFrames from raw data.
* Save each as a `.csv` file for consistent use in future tasks.

#### 🧮 Task 2: Missing Value Imputation

* Handle missing `cost` values in the `Project` DataFrame using a **running average**, implemented with a `for` loop.

#### 🧍 Task 3: Name Splitting

* Split the `name` column into `First Name` and `Last Name` in the `Employee` DataFrame.
* Remove the original `name` column.

#### 🔗 Task 4: Merging Data

* Merge the three DataFrames into a single consolidated DataFrame named `Final`.

#### 💰 Task 5: Bonus Calculation

* Add a `bonus` column (5% of project cost) for employees with **completed** projects.

#### 📉 Task 6: Designation Demotion

* Demote designation level by 1 for employees with **failed** projects.
* Remove records where designation level exceeds 4.

#### 🧑‍💼 Task 7: Title Formatting

* Add gendered titles (`Mr.` / `Mrs.`) to `First Name`.
* Remove the `gender` column.

#### 📈 Task 8: Promotion Logic

* Promote employees by 1 level if their **age > 29**, using an `if` condition.

#### 🧾 Task 9: Project Cost Summary

* Aggregate and save total project cost per employee into a new DataFrame `TotalProjCost`.

#### 🏙️ Task 10: City Filter

* Print all employee records where the `city` name contains the letter **"o"**.

---

### 🛠 Tech Stack:

* **Python**
* **Pandas**
* **CSV I/O Operations**
* **Conditional Logic & Loops**
* **Data Merging & Filtering**

### 📂 Deliverables:

* `.csv` files for processed data
* Python script (`.py` or Jupyter notebook `.ipynb`)
* Optionally: README with output screenshots or summaries
