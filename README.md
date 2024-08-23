# Lyrics Word Frequency Counter

## Project Overview

This project is a Jupyter Notebook that counts the frequency of words in song lyrics. The notebook allows you to paste the lyrics directly into a cell, and it processes the text to analyze the word frequency.

## How It Works

- The notebook allows users to input lyrics directly into a Python variable.
- It processes the lyrics to count the occurrence of each word, ignoring case and punctuation.
- The results are displayed as a sorted list of words along with their frequency.

## Features

- **Simple Input:** You can easily substitute the example lyrics with any lyrics you want to analyze by modifying the `lyrics` variable in the notebook.
- **Word Counting:** The script normalizes the text by converting all words to lowercase and removing punctuation for an accurate count.

## Getting Started

### Prerequisites

- Jupyter Notebook
- Python 3.x
- Required Python libraries:
  - `collections`
  - `string`
  - `matplotlib` (for visualizations, if used)

### Installation

1. **Clone or download the repository:**
   - You can clone this repository using the following command:
     ```bash
     git clone https://github.com/ilazan/word-freq-counter.git
     ```
   - Alternatively, you can download the notebook file directly.

2. **Open the Notebook:**
   - Navigate to the directory where you saved the notebook and open it using Jupyter Notebook:
     ```bash
     jupyter notebook word_freq_counter.ipynb
     ```

### Usage

1. **Copy and Paste Lyrics:**
In the first cell of the notebook, replace the text inside the `lyrics` variable with your desired song lyrics.

   ```python
   lyrics = """
   Here are the lyrics of your song. 
   Copy and paste your song lyrics here, and the notebook will analyze the word frequency.
   """

2. **Run the Cells:**
Execute the cells in the notebook to process the lyrics and generate the word frequency count.

3. **View the Results:**
The notebook will display a sorted list of words with their frequencies. If visualizations are included, you will also see a bar chart representing the word frequencies.

### Contributing
This notebook is a simple educational script and is not actively maintained. However, if you'd like to contribute, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

This project was created as part of a school assignment to practice Python programming and text processing.
