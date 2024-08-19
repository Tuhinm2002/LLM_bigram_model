<p align="left">
  <img src="https://img.freepik.com/premium-vector/pixel-art-illustration-robot-head-pixelated-robot-robot-head-icon-pixelated-game_1038602-733.jpg?w=740" width="100" />
</p>

# 📖 LLM Bigram Model from Scratch Inspired by Andrej Karpathy

Welcome to the **LLM Bigram Model from Scratch** repository! This project demonstrates the process of building a basic bigram language model using a large language model (LLM) approach, implemented entirely from scratch.

<p align="left">
		<em>Developed with the software and tools below.</em>
</p>
<p align="left">
	<img src="https://img.shields.io/badge/GNU%20Bash-4EAA25.svg?style=default&logo=GNU-Bash&logoColor=white" alt="GNU%20Bash">
  <img src="https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=NumPy&logoColor=white" alt="NumPy">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=default&logo=Python&logoColor=white" alt="Python">
</p>


## 📚 Overview

A bigram model is a type of language model that predicts the occurrence of a word based on the previous word. In this project, we build a bigram model to understand the underlying mechanics of language modeling, without relying on any pre-built libraries or frameworks.

### 🔧 Key Features

- **Pure Python Implementation:** No external NLP libraries used—everything is built from the ground up.
- **Text Preprocessing:** Custom tokenization and text normalization.
- **Bigram Probability Calculation:** Compute the probability distribution of bigram occurrences.
- **Text Generation:** Generate text based on the trained bigram model.
- **Model Evaluation:** Assess the performance of the model using perplexity and other relevant metrics.

## 🛠️ How It Works

### 1. Data Preprocessing

The text data is first cleaned, tokenized, and normalized to prepare it for the bigram model. This step includes:

- Lowercasing text
- Removing punctuation and special characters
- Tokenizing the text into words

### 2. Building the Bigram Model

The bigram model is constructed by:

- Counting the occurrences of each word pair (bigram) in the text.
- Calculating the conditional probability of each word given the previous word.

### 3. Text Generation

Using the trained bigram model, we generate text by predicting the next word based on the current word, iteratively building a sequence of text.

### 4. Model Evaluation

We evaluate the model using perplexity, which measures how well the model predicts a sample of text. A lower perplexity indicates better performance.


## 🚀 Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

### ⚙️ Installation

<h4>From <code>source</code></h4>

> 1. Clone the pyflink-poc repository:
>
> ```console
> $ git clone ../    LLM_bigram_model
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd     LLM_bigram_model
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://local/pyflink-poc/issues)**: Submit bugs found or log feature requests for the `nlp_preprocessing` project.
- **[Submit Pull Requests](https://local/pyflink-poc/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://local/pyflink-poc/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your local account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone ../nlp_preprocessing
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to local**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>


## 📄 License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 👏 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)
