## Time-to-close: an analysis of GitHub Issue/Pull Request Templates

### Abstract

This research paper explores the usage and characteristics of GitHub templates in open-source projects. We examined a dataset of 538 repositories with both Issue and Pull Request templates using the GitHub API. We discovered some valuable insights for effective communication among the community. On average, repositories had ≈ 2.68 and 1 issue and pull request templates respectively. Contents of Templates contained labels such as welcoming contributors, project guidelines, and additional data. We also investigated variations and differences in templates across different languages. Javascript and Go repositories exhibited distinct trends, whereas Assembly language despite fewer repositories, had the highest average number of issue templates. This research analysis gives us an understanding of templates for better effective communication. Future directions include evaluating the impact of templates, template customization, and understanding the coherence between template usage and community engagement.

### Data Collection

We have created a dataset using GitHub API, please refer [`data-creation.ipynb`](./data-creation.ipynb) which resulting dataset comprised 538 repositories, a total of 6574 individual issue files and 2601 pull request templates.

### How to run the code.

1. Clone the repository.
2. Install the dependencies using `pip install -r requirements.txt`
3. Add `.env` file with `GITHUB_TOKEN` variable.
4. For data collection, run [`data-creation.ipynb`](./data-creation.ipynb) notebook.
5. For Research Questions, run `RQ-{number}.ipynb` notebook.

### Research Questions

1. [RQ1](./RQ1.ipynb): What are the common types of GitHub issue and pull request templates used in the OSS Projects?
2. [RQ-2]](./RQ-2.ipynb): What are the contents/taxonomy of GitHub templates?
3. [RQ3](./RQ3.ipynb): How do the contents of GitHub templates differ across programming languages?
