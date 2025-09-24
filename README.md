# Movie-Sentiment-Analysis-Scikit-Learn
# 使用Scikit-Learn进行电影评论情感分析
这是一个经典的机器学习入门项目，旨在对IMDB电影评论进行情感（正面/负面）分类。项目完整地展示了自然语言处理（NLP）中的一个基础工作流程。

---

## 📖 项目概述 (Project Overview)

本项目使用Python及核心的Scikit-learn库，对一份包含5万条电影评论的数据集进行处理和分析。我们实现了一个完整的机器学习流程，最终训练出一个能够判断新评论情感倾向的模型。

最终成果展示：<img width="858" height="651" alt="Image" src="https://github.com/user-attachments/assets/c63bd84f-98a3-4c89-9412-abb6cea0c35c" />
---

## 🚀 工作流程 (Workflow)

1.  **数据加载与预处理 (Data Loading & Preprocessing)**:
    * 从CSV文件中加载IMDB数据集。
    * 对文本数据进行基础的清洗。

2.  **特征工程 (Feature Engineering)**:
    * 利用 **"词袋模型" (Bag-of-Words)** 的思想，通过`CountVectorizer`将文本评论转换为机器学习模型可以理解的数字向量。

3.  **模型训练 (Model Training)**:
    * 将数据集划分为训练集和测试集。
    * 选择经典的 **逻辑回归 (Logistic Regression)** 算法，在训练集上对模型进行训练。

4.  **效果评估 (Evaluation)**:
    * 使用测试集来评估模型的性能，计算其准确率（Accuracy）。
    * 用全新的、未见过的句子来测试模型的实际预测能力。

---

## 🛠️ 如何使用 (How to Use)

1.  **克隆或下载本仓库**:
    ```bash
    git clone [https://github.com/](https://github.com/)[你的GitHub用户名]/Movie-Sentiment-Analysis-Scikit-Learn.git
    ```
2.  **安装依赖库**:
    ```bash
    pip install pandas scikit-learn jupyterlab
    ```
3.  **下载数据集**:
    * 本项目使用的数据集来自Kaggle。请从以下链接下载：
        [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
    * 下载并解压后，将 `IMDB Dataset.csv` 文件放置在项目根目录下。
4.  **运行Jupyter Notebook**:
    * 启动Jupyter Notebook/Lab，并打开`.ipynb`文件，按顺序执行所有单元格。

---

## 💻 技术栈 (Tech Stack)

* **Python 3**
* **Scikit-learn**: 用于模型训练与数据处理。
* **Pandas**: 用于数据读取和管理。
* **Jupyter Notebook**: 用于交互式开发和展示。
