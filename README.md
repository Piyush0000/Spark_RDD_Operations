
## 📝 Operations Covered

### 📌 RDD Creation
- Creating RDDs from Python lists using `parallelize()`
- Understanding partitions with `getNumPartitions()`

### 🔄 Transformations (Lazy)
| Operation | Description | Example |
|-----------|-------------|---------|
| `filter()` | Remove unwanted records | Remove header row |
| `map()` | Apply function to each element | Parse CSV strings to tuples |
| `distinct()` | Get unique values | List all unique cities |
| `reduceByKey()` | Aggregate by key | Count customers per city |

### ⚡ Actions (Eager)
| Operation | Description | Example |
|-----------|-------------|---------|
| `first()` | Get first element | View header |
| `collect()` | Return all elements | View parsed data |
| `take(n)` | Return first n elements | Preview data |
| `countByValue()` | Count occurrences | (Demonstrated) |

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Upload the notebook to Google Colab
2. Run the first cell to install dependencies (if needed)
3. Execute cells sequentially

### Option 2: Local Setup
```bash
# Install PySpark
pip install pyspark

# Run Jupyter
jupyter notebook spark_rdd_operations.ipynb
