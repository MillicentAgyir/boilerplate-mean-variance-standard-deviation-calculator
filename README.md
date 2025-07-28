# Mean-Variance-Standard Deviation Calculator


This is a Python project that calculates the **mean**, **variance**, **standard deviation**, **maximum**, **minimum**, and **sum** of the rows, columns, and flattened version of a 3x3 matrix using **NumPy**.

## 📂 Project Structure

├── mean_var_std.py # Main module containing the calculate() function
├── main.py # Entrypoint for manual testing and test execution
├── test_module.py # Unit tests for the calculate() function
└── README.md # Project documentation (this file)



##  What It Does

- Takes a list of **9 numbers** as input.
- Converts the list into a **3x3 NumPy array**.
- Returns a dictionary containing statistical calculations:
  - Mean
  - Variance
  - Standard deviation
  - Max
  - Min
  - Sum

Each of the above metrics is computed:
- Across **columns** (axis 0)
- Across **rows** (axis 1)
- Across the **entire matrix** (flattened)

If fewer than 9 numbers are provided, the function raises a `ValueError`.


🧑‍💻 Author
Project provided by freeCodeCamp. Solution implemented by Millicent Ama Agyir!

🔗 License


---

