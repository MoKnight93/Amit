# ONL4_AIS2_G3 - Python for Machine Learning Learning Program

A comprehensive 7-week learning program focused on Python programming fundamentals and Machine Learning basics for the AIS (Artificial Intelligence & Information Systems) course.

## 📚 Course Overview

This repository contains weekly learning materials, assignments, and practical tasks designed to build a strong foundation in Python programming with applications towards Machine Learning and Data Science.

**Program Duration:** 7 Weeks  
**Target Audience:** Beginners to Intermediate Python Learners  
**Focus Areas:** Python Fundamentals, OOP, NumPy, Pandas, and Data Analysis

---

## 📂 Repository Structure

```
.
├── Week 1/          # Python Fundamentals Setup
│   └── Tasks/
│       └── python-for-ml/        # Virtual environment & initial setup
│
├── Week 2/          # String Manipulation & Pattern Recognition
│   └── Tasks/
│       ├── Assignment 1.ipynb    # Email validation & string operations
│       └── Assignment 2.ipynb    # Advanced string manipulation
│
├── Week 3/          # Functions & Object-Oriented Programming (OOP)
│   └── Tasks/
│       ├── Task 1.ipynb          # Calculator program (Functions)
│       ├── Task 2.ipynb          # File operations & Random selection
│       ├── Task 3.ipynb          # [Task content]
│       ├── Task 4.ipynb          # [Task content]
│       └── Task 4 OOP.ipynb      # OOP implementation
│
├── Week 4/          # Advanced Python & Data Structures
│   └── Tasks/
│       ├── Task 1.ipynb          # [Task content]
│       ├── Task 2.ipynb          # [Task content]
│       ├── Task 3.ipynb          # [Task content]
│       ├── Task 4.ipynb          # [Task content]
│       ├── Task 5.ipynb          # [Task content]
│       └── Task 6.ipynb          # [Task content]
│
├── Week 5/          # NumPy & Pandas Libraries
│   └── Tasks/
│       ├── NumPy Task.ipynb      # NumPy array operations & manipulation
│       └── Pandas Task.ipynb     # Data manipulation with Pandas
│
├── Week 6/          # [Week 6 Content]
│   └── Tasks/
│
├── Week 7/          # [Week 7 Content]
│   └── Tasks/
│
└── README.md        # This file
```

---

## 📋 Weekly Breakdown

### Week 1: Python & ML Environment Setup
- **Topic:** Development Environment Configuration
- **Content:** Setting up Python virtual environment for Machine Learning development
- **Key Materials:** 
  - Virtual environment (ml-env) with pip dependencies
  - Initial project structure
  - Python package management

### Week 2: String Manipulation & Pattern Recognition
- **Topics:** String operations, pattern validation, text processing
- **Assignments:**
  - **Assignment 1:** Email validation with domain classification
    - Validate email format (must have @ and .)
    - Classify domains (.com, .edu, etc.)
    - String parsing and conditional logic
  - **Assignment 2:** Advanced text manipulation and transformation
    - Character replacement operations
    - Word processing
    - String transformations

### Week 3: Functions & Object-Oriented Programming
- **Topics:** Functions, modularity, OOP concepts
- **Tasks:**
  - **Task 1:** Simple Calculator Program
    - Arithmetic operations (add, subtract, multiply, divide)
    - Menu-driven interface
    - Input validation and error handling
    - Use of functions for code organization
  - **Task 2:** File System Operations
    - Working with file directories
    - Random file selection
    - File manipulation (Inspired by "Thanos" random deletion concept)
  - **Task 3:** [Additional Task]
  - **Task 4:** [Additional Task]
  - **Task 4 OOP:** Object-Oriented Implementation
    - Classes and objects
    - Encapsulation principles
    - OOP design patterns

### Week 4: Advanced Python Concepts
- **Topics:** Advanced data structures, algorithms, problem-solving
- **Tasks:** Task 1-6 covering various Python programming challenges
  - Data structure manipulation
  - Algorithm implementation
  - Complex problem-solving scenarios

### Week 5: Data Science Libraries
- **NumPy Task:** Array operations and numerical computing
  - Array creation and manipulation
  - Mathematical operations
  - Array indexing and slicing
  - Statistical operations
- **Pandas Task:** Data manipulation and analysis
  - DataFrames and Series
  - Data cleaning and preprocessing
  - Data aggregation and grouping
  - CSV file handling

### Week 6: Data Analysis with Python
- **Topics:** Advanced data analysis using NumPy & Pandas, exploratory data analysis (EDA), statistical methods
- **Libraries & Tools:**
  - **Pandas:** DataFrames, groupby operations, pivot tables, merging & joining datasets
  - **NumPy:** Advanced array operations, statistical functions, linear algebra
  - **SciPy:** Statistical analysis, hypothesis testing, distributions
- **Key Content:**
  - Data cleaning and preprocessing with Pandas
  - Missing value handling (dropna, fillna, interpolation)
  - Outlier detection and removal using NumPy
  - Descriptive statistics (mean, median, std, quantiles)
  - Data aggregation with groupby and pivot_table
  - Correlation and covariance analysis (corr(), cov())
  - Time series analysis basics (resampling, rolling windows)
  - Real-world dataset exploration and profiling
- **Skills Developed:**
  - Manipulate large datasets efficiently with Pandas
  - Perform numerical computations with NumPy
  - Handle and clean messy real-world data
  - Generate statistical insights from data

### Week 7: Data Visualization with Python
- **Topics:** Creating effective visualizations using Python libraries, interactive dashboards, storytelling with data
- **Libraries & Tools:**
  - **Matplotlib:** Line plots, bar charts, histograms, scatter plots, subplots, customization
  - **Seaborn:** Statistical visualizations, heatmaps, distribution plots, categorical plots, regression plots
  - **Plotly:** Interactive charts, hover effects, zoom/pan, 3D plots, web-ready visualizations
  - **Dash:** Building interactive web-based dashboards, callbacks, real-time updates
- **Key Content:**
  - Matplotlib fundamentals (figure, axes, subplots)
  - Seaborn styling and color palettes
  - Statistical plot types (violin plots, box plots, KDE plots)
  - Plotly interactive features and animations
  - Dash app structure (layout, callbacks, server)
  - Creating multi-panel dashboards with Dash
  - Best practices for data visualization design
  - Storytelling techniques with visualizations
  - Performance optimization for large datasets
- **Skills Developed:**
  - Design meaningful and informative visualizations
  - Choose appropriate chart types for different data
  - Create interactive dashboards with Dash
  - Build professional-grade visualizations with Plotly
  - Communicate insights effectively through visuals

---

## 🛠️ Prerequisites & Setup

### System Requirements
- Python 3.7 or higher
- pip (Python package manager)
- Virtual environment support

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MoKnight93/ONL4_AIS2_G3.git
   cd ONL4_AIS2_G3
   ```

2. **Create and activate virtual environment:**
   ```bash
   # Windows
   python -m venv ml-env
   ml-env\Scripts\activate
   
   # macOS/Linux
   python3 -m venv ml-env
   source ml-env/bin/activate
   ```

3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

   **Common packages needed:**
   - NumPy: Numerical computing
   - Pandas: Data manipulation and analysis
   - Jupyter: Interactive notebook environment
   - Matplotlib: Data visualization

---

## 📖 How to Use This Repository

### For Students:
1. **Navigate to the desired week** in the repository
2. **Open the task/assignment files** (`.ipynb` files) using Jupyter Notebook:
   ```bash
   jupyter notebook "Week X/Tasks/Task Name.ipynb"
   ```
3. **Read the task requirements** carefully
4. **Implement the solution** in the notebook cells
5. **Test your code** and verify outputs
6. **Compare with solutions** (if available)

### For Instructors:
- Use this repository as a reference for course structure
- Modify tasks based on student needs
- Add additional weeks or tasks as required
- Track progress through Git commits

---

## 🎯 Learning Objectives

By completing this program, students will be able to:

✅ **Python Fundamentals**
- Understand Python syntax and data types
- Work with variables, operators, and control structures
- Create and use functions effectively

✅ **String & Data Processing**
- Manipulate and validate strings
- Work with patterns and regular expressions
- Process text data efficiently

✅ **Object-Oriented Programming**
- Design classes and objects
- Implement encapsulation and inheritance
- Apply SOLID principles

✅ **Data Science Basics**
- Use NumPy for numerical operations
- Manipulate data with Pandas
- Prepare data for machine learning

✅ **Problem Solving**
- Break down complex problems
- Write clean, readable code
- Debug and test code effectively

---

## 💡 Key Concepts Covered

| Concept | Week | Status |
|---------|------|--------|
| Variables & Data Types | 1 | ✅ |
| String Manipulation | 2 | ✅ |
| Functions & Modularity | 3 | ✅ |
| Object-Oriented Programming | 3 | ✅ |
| Advanced Data Structures | 4 | ✅ |
| NumPy & Arrays | 5 | ✅ |
| Pandas & DataFrames | 5 | ✅ |
| Data Analysis | 6 | ✅ |
| Data Visualistion | 7 | ⏳ |

---

## 📝 File Formats

- **`.ipynb`** - Jupyter Notebook files (interactive Python notebooks with code, output, and documentation)
- **`.py`** - Python script files (executable Python programs)
- **`.md`** - Markdown documentation files

### Running Notebooks:
```bash
jupyter notebook "path/to/notebook.ipynb"
```

### Running Scripts:
```bash
python script.py
```

---

## 🤝 Contribution Guidelines

If you're a student contributor:
1. Create a new branch for your changes: `git checkout -b feature/your-feature`
2. Commit your work: `git commit -m "Add task solution"`
3. Push to your branch: `git push origin feature/your-feature`
4. Submit a pull request for review


## 👥 Contributors

- **Course Instructor/Creator:** DEPI - AMIT
- **Repository Owner:** MoKnight93 - Mohamed Samir

---

## 📄 License

This project is part of an educational program. Please refer to your institution's policies regarding code usage and distribution.

---

## 📞 Contact & Support

- **GitHub Issues:** Report issues or ask questions via GitHub Issues
- **Instructor Contact:** [To be updated]
- **Course Platform:** [To be updated]

---

## 🚀 Getting Started

```bash
# Clone repository
git clone https://github.com/MoKnight93/ONL4_AIS2_G3.git

# Navigate to directory
cd ONL4_AIS2_G3

# Setup environment
python -m venv ml-env
source ml-env/bin/activate  # On Windows: ml-env\Scripts\activate

# Install dependencies
pip install jupyter numpy pandas

# Start learning!
jupyter notebook
```

---

**Last Updated:** January 22, 2026  
**Repository:** [ONL4_AIS2_G3](https://github.com/MoKnight93/ONL4_AIS2_G3)

---

**Happy Learning! 🎓**