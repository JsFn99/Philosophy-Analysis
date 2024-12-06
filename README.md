# Philosophy-Analysis

This project uses Natural Language Processing (NLP) techniques and statistical analysis to explore the works of Friedrich Nietzsche and other philosophers.

## Project Structure

- `NLP_Nietzsche.ipynb`: Jupyter Notebook for analyzing the texts of Friedrich Nietzsche.
- `Philo.ipynb`: Jupyter Notebook for statistical analysis of philosophers.
- `Beyond_Good_and_Evil.txt`: Extracted text from "Beyond Good and Evil" by Friedrich Nietzsche.
- `Thus_Spoke_Zarathustra.txt`: Extracted text from "Thus Spoke Zarathustra" by Friedrich Nietzsche.
- `philosophers.csv`: CSV file containing information about various philosophers.
- `philosophers2.csv`: Second CSV file with additional information about philosophers.
- `README.md`: This file.

## Prerequisites

- Python 3.12.4
- Jupyter Notebook
- Python libraries: `fitz`, `nltk`, `pandas`, `matplotlib`, `plotly`, `gensim`, `wordcloud`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/JsFn99/Philosophy-Analysis
    cd Philosophy-Analysis
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Analyzing Nietzsche's Texts

1. Open the `NLP_Nietzsche.ipynb` notebook in Jupyter Notebook.
2. Run the cells to extract text from PDF files, clean the text, and perform NLP analyses such as tokenization, lemmatization, sentiment analysis, and word cloud generation.

### Statistical Analysis of Philosophers

1. Open the `Philo.ipynb` notebook in Jupyter Notebook.
2. Run the cells to load philosopher data, create graphs showing distribution by country, century, and domain, and obtain detailed information about philosophers from a specific country.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss the changes you wish to make.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- Fnine Jasser
