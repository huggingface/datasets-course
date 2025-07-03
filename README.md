# The 🤗 Datasets Course

This is a practical course on working with datasets using the 🤗 Datasets library and data curation tools. Learn how to load, process, and curate datasets for your machine learning projects, from basic data loading to advanced techniques like semantic search and collaborative annotation.

<a href="http://hf.co/join/discord">
<img src="https://img.shields.io/badge/Discord-7289DA?&logo=discord&logoColor=white"/>
</a>

<div style="background: linear-gradient(to right, #e0f7fa, #e1bee7, orange); padding: 20px; border-radius: 5px; margin-bottom: 20px; color: purple;">
    <h2>Participation is open, free, and now!</h2>
    <p>This course is open and peer reviewed. To get involved with the course <strong>open a pull request</strong> and submit your work for review. Here are the steps:</p>
    <ol>
        <li>Fork the repo <a href="https://github.com/huggingface/datasets-course/fork">here</a></li>
        <li>Read the material, make changes, do the exercises, add your own examples.</li>
        <li>Open a PR and contribute to the course</li>
        <li>Get it reviewed and merged</li>
    </ol>
    <p>This should help you learn and to build a community-driven course that is always improving.</p>
</div>

## Course Outline

This course provides a comprehensive guide to working with datasets, from basic loading and processing to advanced curation and annotation techniques.

| Chapter | Description | Content |
|---------|-------------|---------|
| [Introduction and Setup](./chapters/en/chapter0/1.mdx) | Learn how to set up your environment for working with datasets | Environment setup, Google Colab, Python virtual environments |
| [The 🤗 Datasets Library](./chapters/en/chapter1/) | Master the core functionality of the 🤗 Datasets library | Dataset loading, local/remote files, data processing, FAISS search, custom datasets |
| [Building and Sharing Datasets with Argilla](./chapters/en/chapter2/) | Learn to curate and annotate datasets using Argilla | Dataset annotation, curation workflows, human feedback, collaborative annotation |

### Chapter 1: The 🤗 Datasets Library

1. **[Introduction](./chapters/en/chapter1/1.mdx)** - Overview of the 🤗 Datasets library
2. **[What if my dataset isn't on the Hub?](./chapters/en/chapter1/2.mdx)** - Loading local and remote datasets
3. **[Time to slice and dice](./chapters/en/chapter1/3.mdx)** - Data processing and manipulation techniques
4. **[Big data? 🤗 Datasets to the rescue!](./chapters/en/chapter1/4.mdx)** - Working with large datasets efficiently
5. **[Creating your own dataset](./chapters/en/chapter1/5.mdx)** - Building custom datasets from scratch
6. **[Semantic search with FAISS](./chapters/en/chapter1/6.mdx)** - Implementing semantic search capabilities
7. **[Datasets and DataLoaders](./chapters/en/chapter1/7.mdx)** - Integration with PyTorch DataLoaders
8. **[End-of-chapter quiz](./chapters/en/chapter1/8.mdx)** - Test your knowledge

### Chapter 2: Building and Sharing Datasets with Argilla

1. **[Introduction to Argilla](./chapters/en/chapter2/1.mdx)** - Overview of Argilla for dataset curation
2. **[Getting started with Argilla](./chapters/en/chapter2/2.mdx)** - Setting up your Argilla instance
3. **[Curating a dataset for classification](./chapters/en/chapter2/3.mdx)** - Text classification annotation workflows
4. **[Curating a dataset for token classification](./chapters/en/chapter2/4.mdx)** - Named entity recognition and token-level tasks
5. **[Gathering human feedback](./chapters/en/chapter2/5.mdx)** - Collecting human annotations and feedback
6. **[Putting it all together](./chapters/en/chapter2/6.mdx)** - Complete dataset curation workflow
7. **[End-of-chapter quiz](./chapters/en/chapter2/7.mdx)** - Test your knowledge

## Why Focus on Datasets?

High-quality datasets are the foundation of successful machine learning projects. This course teaches you:

- **Data Loading**: Load datasets from various sources (Hub, local files, remote URLs)
- **Data Processing**: Clean, transform, and prepare data for machine learning
- **Large-scale Data**: Handle datasets that don't fit in memory
- **Data Curation**: Improve dataset quality through annotation and validation
- **Collaboration**: Work with teams to build and maintain datasets
- **Best Practices**: Follow industry standards for data management

## Prerequisites

Before starting, ensure you have the following:
- Basic understanding of Python programming
- Familiarity with machine learning concepts
- Basic knowledge of natural language processing (helpful but not required)

## Installation

We maintain the course dependencies so you can install them easily via a package manager. We recommend [pip](https://pip.pypa.io/) for this purpose.

### Using `pip`

Create a virtual environment and install the required packages:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install datasets argilla pandas numpy
```

### Google Colab

If you're using Google Colab, you can install the required packages directly in a notebook cell:

```bash
!pip install datasets argilla pandas numpy
```

## Getting Started

1. **[Start with the Introduction](./chapters/en/chapter0/1.mdx)** to set up your environment
2. **[Begin Chapter 1](./chapters/en/chapter1/1.mdx)** to learn the fundamentals of the 🤗 Datasets library
3. **[Progress to Chapter 2](./chapters/en/chapter2/1.mdx)** to master dataset curation with Argilla

## Course Structure

Each chapter includes:
- **Theoretical explanations** of key concepts
- **Hands-on examples** with code snippets
- **Practical exercises** to reinforce learning
- **End-of-chapter quizzes** to test your understanding

## Community and Support

- Join the [Hugging Face Discord](http://hf.co/join/discord) for discussions
- Create issues and pull requests to improve the course
- Share your datasets and experiences with the community

---

*This course is part of the Hugging Face educational initiative to democratize machine learning and make high-quality AI education accessible to everyone.*

