
# Non-Euclidean Statistics: From Foundations to Theory

> **A systematic journey through the mathematics and statistics of non-Euclidean spaces.**
>
> 从数学基础出发，循序渐进地理解非欧空间的几何结构、统计理论与分析方法。

## 📖 About This Project

本项目是一套持续更新的 **非欧统计学（Non-Euclidean Statistics）系统学习课程**。

课程从欧氏空间、度量、范数与内积出发，逐步进入流形几何、Fréchet 均值、统计推断以及复杂非欧数据分析。

内容以中文讲解为主，保留必要的英文术语和数学符号，注重数学直觉、概念理解以及理论之间的联系。

本项目的目标不仅是介绍数学定义，更是建立一套连贯的知识体系，理解：

**当数据不再位于普通欧氏空间时，统计学应该如何改变？**

### Learning Philosophy

- **From Foundations to Theory** — 从基础概念逐步走向统计理论
- **Intuition Before Formalism** — 先建立直觉，再理解严格定义
- **Geometry Before Statistics** — 先理解数据空间，再构造统计方法
- **Examples and Derivations** — 通过例子与推导理解核心概念
- **One Concept at a Time** — 每一讲聚焦一个主要知识点

---

## 🗺️ Learning Roadmap

课程按照以下四个阶段组织。

### Part I. Mathematical Foundations

**数学基础：从欧氏空间到一般度量空间**

- Euclidean Spaces
- Sets and Metric Spaces
- Metric Axioms and Metric Balls
- Norms and Normed Spaces
- Inner Product Spaces
- Relations Between Inner Products, Norms, and Metrics

### Part II. Geometry of Non-Euclidean Spaces

**几何基础：从圆周与球面到黎曼几何**

- Circles and Spheres
- Intrinsic and Extrinsic Distances
- Geodesics and Shortest Paths
- Topological and Smooth Manifolds
- Local Coordinates and Atlases
- Tangent Spaces and Tangent Vectors
- Riemannian Metrics
- Exponential and Logarithm Maps
- Curvature and Geometric Structure

### Part III. Foundations of Non-Euclidean Statistics

**统计基础：从距离到估计与推断**

- Fréchet Mean
- Fréchet Variance
- Intrinsic and Extrinsic Means
- Existence and Uniqueness of Fréchet Means
- Consistency of Statistical Estimators
- Asymptotic Distributions
- Statistical Inference on Manifolds
- Fréchet Regression

### Part IV. Statistics for Complex Data Objects

**非欧数据分析：从理论到不同数据空间**

- Directional and Spherical Statistics
- Statistical Shape Analysis
- Symmetric Positive Definite Matrix Statistics
- Graph and Network Statistics
- Tree-Valued Data
- Wasserstein Spaces and Optimal Transport
- Distribution-Valued Data
- Geometric Statistical Learning

> The roadmap is a learning guide rather than a fixed syllabus. Additional foundational topics may be introduced when necessary.

---

## 📚 Lecture Notes

所有课程按照编号顺序组织，每一讲均可独立阅读，同时与前后章节保持知识衔接。

### Part I — Mathematical Foundations

| Lecture | Topic |
|---|---|
| [001](lessons/001-introduction.md) | Why Non-Euclidean Statistics? |
| [002](lessons/002-metric-space.md) | What Is a Metric Space? |
| [003](lessons/003-metric-balls.md) | Metric Balls and the Geometry of Distance |
| [004](lessons/004-norm-and-metric.md) | Norms and Metrics |
| [005](lessons/005-inner-product.md) | Inner Product Spaces |

### Part II — Geometry of Non-Euclidean Spaces

| Lecture | Topic |
|---|---|
| [006](lessons/006-circles-and-spheres.md) | Circles, Spheres, and Geometric Distances |
| [007](lessons/007-geodesics.md) | Geodesics and Shortest Paths |
| [008](lessons/008-manifolds.md) | Introduction to Manifolds |
| [009](lessons/009-tangent-spaces.md) | Tangent Vectors and Tangent Spaces |


---

## 📝 Lecture Structure

为了保持课程的系统性，每一讲采用相对统一的结构。

### 1. Motivation

为什么需要研究这个概念？

从已有知识或具体问题出发，引出新的数学对象。

### 2. Mathematical Intuition

建立直观理解。

通过几何解释、简单例子或与欧氏空间的比较，理解概念背后的思想。

### 3. Formal Definitions

给出必要的数学定义、公理与符号说明。

重点理解数学条件的含义，以及它们为什么重要。

### 4. Examples and Derivations

通过具体计算、数学推导与简单证明加深理解。

### 5. Key Insights and Common Misconceptions

总结核心结论，澄清常见误区，并建立与其他数学概念的联系。

### 6. Exercises

每一讲提供练习题，并附有可展开的参考答案。

### 7. Next Lecture

简要介绍下一讲的知识点，帮助建立连续的学习路线。

---

## 📐 Mathematical Notation

本项目使用 GitHub 原生 Markdown 数学公式。

### Inline Mathematics

简单数学表达式使用行内 LaTeX，例如：

- 欧氏空间：$`\mathbb{R}^p`$
- 单位球面：$`S^2`$
- 切空间：$`T_pM`$
- 范数：$`\lVert x\rVert_2`$

对于容易与 Markdown 语法冲突的表达式，也可以使用 GitHub 支持的特殊行内数学定界符。

### Display Mathematics

较长的公式采用独立的 `math` 代码围栏。

例如，Fréchet 函数定义为：

```math
F(\omega)
=
\mathbb E[d^2(X,\omega)]
```

### Diagrams

课程中的知识结构图和流程图主要使用 Mermaid 绘制。

### Exercise Solutions

参考答案使用 GitHub 的 `<details>` 折叠结构，便于先独立思考，再查看推导。

---

## 📂 Repository Structure

```text
non-euclidean-statistics-course/
│
├── README.md
│
├── lessons/
│   ├── 001-introduction.md
│   ├── 002-metric-space.md
│   ├── 003-metric-balls.md
│   ├── 004-norm-and-metric.md
│   ├── 005-inner-product.md
│   ├── 006-circles-and-spheres.md
│   ├── 007-geodesics.md
│   ├── 008-manifolds.md
│   └── 009-tangent-spaces.md
│
└── images/
```

---

## 🚀 How to Use

建议按照课程编号顺序学习。

**Step 1 — Understand the Motivation**

首先理解为什么需要引入当前概念。

**Step 2 — Learn the Mathematics**

掌握定义、公理、核心公式与基本推导。

**Step 3 — Work Through Examples**

独立完成课程中的计算例子，理解公式的实际含义。

**Step 4 — Solve the Exercises**

先尝试独立完成练习，再展开参考答案。

**Step 5 — Connect the Concepts**

思考当前知识如何连接到下一讲，以及它在非欧统计中的作用。

---

## 🎯 Project Goal

The goal of this project is to build a coherent understanding of non-Euclidean statistics, starting from elementary mathematical concepts and progressing toward geometric methods, statistical estimation, and inference.

Rather than treating mathematical definitions as isolated facts, the course emphasizes the connections between geometry, probability, and statistics.

**Statistics should respect the geometry of data.**

---

*From Euclidean foundations to non-Euclidean statistical theory.*
