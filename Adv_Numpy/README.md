# Advanced NumPy – Notebook Overview

## Introduction
This Jupyter Notebook provides an in-depth exploration of **NumPy**, the fundamental package for scientific computing in Python.
It compares **NumPy arrays** with Python lists in terms of **speed**, **memory usage**, and **convenience**, and covers several advanced topics:
- Fancy & Boolean Indexing
- Broadcasting
- Mathematical operations with NumPy
- Implementation of key ML formulas (Sigmoid, MSE, BCE)
- Handling missing values
- Basic plotting with Matplotlib

---

## Notebook Structure

### 1. **NumPy vs Python List**
- **Speed Test** – Adding two large lists vs. NumPy arrays
- **Memory Usage** – Measuring memory consumed by lists & arrays
- **Convenience** – NumPy’s vectorized operations for efficiency

### 2. **Advanced Indexing**
- **Fancy Indexing** – Selecting particular rows/columns with index arrays
- **Boolean Indexing** – Filtering arrays with boolean conditions:
  - Values > 50
  - Even numbers
  - Multiple conditions (AND/OR)
  - Divisibility checks

### 3. **Broadcasting**
- Broadcasting between arrays of the same and different shapes
- Explanation of **broadcasting rules**
- Examples for row/column-wise addition

### 4. **Working with Mathematical Formulas**
- **Sigmoid Function** – Implementation & demonstration
- **Mean Squared Error (MSE)** – Custom function with NumPy
- **Binary Cross Entropy (BCE)** – Custom implementation with clipping for stability

### 5. **Handling Missing Values**
- Representing missing data (`np.nan`)
- Filtering out missing values using `np.isnan`

### 6. **Plotting Examples**
- Basic 2D plots with Matplotlib:
  - `y = x`
  - `y = x^2`

---

# Advanced NumPy Part 2 – Notebook Overview

## Introduction
This Jupyter Notebook explores a wide range of **NumPy functions** through practical examples.
It serves as a **hands-on reference guide** for key NumPy operations, covering **array creation, manipulation, mathematical operations, sorting, indexing, statistical functions, and set operations**.
Each concept is explained with clear examples, outputs, and short notes, making it useful for **learning, revision, or quick lookup** in data science and numerical computing tasks.

---

## Notebook Structure

### 1. **Array Creation and Basic Setup**
- Generating random arrays (`np.random.randint`)
- Reshaping arrays using `.reshape()`

### 2. **Sorting with `np.sort()`**
- Default (row-wise) sorting
- Column-wise sorting using `axis`
- Sorting in descending order

### 3. **Appending and Concatenation**
- Adding elements with `np.append()`
- Combining arrays with `np.concatenate()` (row/column-wise)

### 4. **Unique Values and Dimensional Expansion**
- Finding unique elements with `np.unique()`
- Expanding dimensions using `np.expand_dims()`

### 5. **Conditional Selection and Replacement**
- Using `np.where()` for filtering and conditional replacement

### 6. **Finding Index of Extreme Values**
- Maximum (`np.argmax()`) and minimum (`np.argmin()`) indices (row/column-wise)

### 7. **Cumulative Operations**
- Cumulative sum (`np.cumsum()`)
- Cumulative product (`np.cumprod()`)

### 8. **Statistical Functions**
- Percentiles (`np.percentile()`)
- Histograms (`np.histogram()`)
- Correlation coefficients (`np.corrcoef()`)

### 9. **Membership and Flipping**
- Checking membership (`np.isin()`)
- Reversing arrays with `np.flip()` (row/column-wise)

### 10. **Modifying Arrays**
- Setting values at specific indices (`np.put()`)
- Removing elements (`np.delete()`)

### 11. **Set Operations**
- Intersections (`np.intersect1d()`)
- Differences (`np.setdiff1d()`)
- Symmetric differences (`np.setxor1d()`)
- Unions (`np.union1d()`)

### 12. **Value Clipping**
- Limiting array values within a range using `np.clip()`



