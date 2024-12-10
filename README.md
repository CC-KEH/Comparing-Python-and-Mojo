# Comparing Python and Mojo: Performance in AI and Computational Tasks 🐍⚡

This project explores the **comparison between Python** and the emerging **Mojo programming language**, focusing on their application in machine learning (ML) and other computationally intensive tasks. The study highlights Mojo's potential as a high-performance alternative to Python for AI and computational workloads while evaluating its practical limitations.

---

## 📝 Project Overview

The research conducted as part of an **in-house summer internship** examines the following key aspects:

1. **Performance**: Speed, memory management, and efficiency.  
2. **Compatibility**: Mojo's ability to integrate with Python libraries.  
3. **Usability**: Learning curve, ecosystem maturity, and developer experience.  
4. **Practical Applications**: Implementation of ML algorithms and general computational tasks.

---

## 📊 Key Comparisons

### **Python**
- **Strengths**:
  - User-friendly with a vast ecosystem of libraries (e.g., NumPy, scikit-learn).
  - Ideal for rapid prototyping and complex model development.
  - Backed by a large and active community.
- **Limitations**:
  - Slower due to its interpreted nature.
  - Limited control over memory management.

### **Mojo**
- **Strengths**:
  - **Speed**: Up to 10–53 times faster in benchmarks (e.g., ML models, Sudoku solver).
  - **Memory Efficiency**: Enhanced control over memory usage.
  - **Interoperability**: Seamless integration with Python libraries.
- **Limitations**:
  - Steeper learning curve and a smaller ecosystem.
  - Limited community support compared to Python.
  - Immature for complex AI model development.

---

## 🔬 Methodology

1. **Implementation of ML Algorithms**:
   - Supervised ML algorithms like logistic regression, decision trees, SVM, kNN, and Naive Bayes.
   - Hyperparameter tuning and K-fold cross-validation.

2. **Advanced Statistical Analysis**:
   - Concepts like hypothesis testing and confidence intervals for model evaluation.

3. **Performance Evaluation**:
   - Benchmarks comparing execution time and memory utilization for ML tasks and computational problems like Fibonacci calculations and Sudoku solving.

---

## 📂 Project Structure

```
Comparing-Python-and-Mojo/
│
├── Python-Examples/      # Implementations of ML algorithms in Python
├── Mojo-Examples/        # Equivalent implementations in Mojo
├── Benchmarks/           # Performance results and analysis
├── Docs/                 # Detailed documentation and findings
└── README.md             # Project overview (this file)
```

---

## 🛠️ Tools and Technologies

- **Languages**: Python, Mojo  
- **Libraries**: scikit-learn (Python), Mojo's standard library  
- **Tasks Benchmarked**:
  - Hyperparameter tuning
  - Fibonacci sequence calculation
  - Sudoku solving

---

## 📈 Benchmark Results

- **Machine Learning Models**: Mojo demonstrated up to **10x speedup** for ML tasks like hyperparameter tuning.  
- **Fibonacci Sequence (n=40)**: Mojo achieved a **42x speedup** compared to Python.  
- **Sudoku Solver**: Mojo outperformed Python with a **53x speedup** in execution time.

---

## 🚀 How to Run

### Prerequisites

- Install Python 3.8+  
- Install Mojo (Refer to [Mojo documentation](https://docs.modular.com/mojo/))  

### Steps

1. Clone the repository:  
   ```bash
   git clone https://github.com/CC-KEH/Comparing-Python-and-Mojo.git
   ```
   
2. Navigate to the directory:  
   ```bash
   cd Comparing-Python-and-Mojo
   ```

3. Run examples in Python:  
   ```bash
   python3 Python-Examples/example1.py
   ```
   
4. Run examples in Mojo:
   ```bash
   mojo run Mojo-Examples/example1.mojo
   ```

---

## 📚 Findings

1. Mojo's compiled nature provides significant performance advantages over Python in computationally intensive tasks.  
2. Despite its strengths, Mojo’s practical use is limited by:
   - A steep learning curve.
   - Immature ecosystem and smaller community.
3. Python remains more versatile and developer-friendly for large-scale ML and AI development.

---

## 🤝 Contributions

Contributions are welcome to enhance the project!  

1. Fork the repository.  
2. Create a new branch for your changes.  
3. Submit a pull request describing your contributions.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 📧 Contact

For any questions or feedback:  
- **GitHub**: [CC-KEH](https://github.com/CC-KEH)

Explore the power of Mojo and Python, and decide what works best for your projects! 🚀🐍

---
