# Task A1 — Python Setup and Basics

This project sets up a reproducible Python environment (3.10+)
and demonstrates:
- Basic Python refresher (lists, dicts, comprehensions)
- Fast I/O using pandas
- Mean/Variance (pure Python vs NumPy)
- Notebook skills and reproducibility

### Observations
- NumPy is **hundreds of times faster** for large datasets.
- The speedup comes from **vectorized operations** in C (no Python loops).
- Variance formula same, but NumPy is optimized for memory layout and SIMD.
- For real-world data processing, always use NumPy or Pandas vector ops.
