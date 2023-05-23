# SKU matcher

This project is for automation of SKU matching process. 

![image](https://github.com/hydramst/sku_matcher/assets/44744458/66ebe24d-9aa9-4822-8aba-ef5bd6ab484e)


## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Vectorization Techniques](#vectorization-techniques)
- [Results](#results)
- [Contributing](#contributing)

## Project Description

This project focuses on classifying sku presented as text data using different vectorization techniques.

## Installation

1. Clone the repository:

```
git clone https://github.com/hydramst/sku_matcher.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Prepare your data:
   - Ensure your text data is available in a suitable format (e.g., CSV, xlsx).
   - Modify the data loading code in `mathcer.ipynb` to load your dataset.

2. Configure the vectorization and classification settings:
   - Experiment with vectorization and choose best algorithm.
   - Adjust other parameters such as train-test split ratio, hyperparameters, etc., if needed.

3. Run the project:

```
run matcher.ipynb
```

4. Explore the results:
   - The project will output evaluation metrics and classification results.
   - Output file contains predicted SKU's, check it manually and correct model preprocessing if needed.

## Vectorization Techniques

- Term Frequency-Inverse Document Frequency (TF-IDF)
- Bag-of-Words (BoW)

You can select the desired technique by modifying the configuration in the "Vectorization" section of nb.

## Results

The project provides evaluation metrics such as accuracy to assess the performance of the classification models. The results of prediction on test descriptions can be found in the `output_file.xlsx` file.

![image](https://github.com/hydramst/sku_matcher/assets/44744458/15e822b6-af54-490a-9024-b52f2a2cff83)


## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.
