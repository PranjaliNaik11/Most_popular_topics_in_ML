# NIPS Conference Research Analysis

**Description:**
This repository hosts code and resources for analyzing research papers from the Neural Information Processing Systems (NIPS) conference. The primary objective is to identify the hottest topics in machine learning (ML) by leveraging natural language processing (NLP) techniques.

**Usage:**
1. **Data Collection**: Ensure the dataset of NIPS conference research papers is available in CSV format within the `data/` directory.
2. **Preprocessing**: Use the provided scripts in the code employing regular expressions for cleaning.
3. **Analysis**:
   - Utilize the Jupyter notebook for exploratory data analysis.
   - Generate word clouds using the wordcloud library to visualize popular words in the paper titles.
   - Prepare text for Latent Dirichlet Allocation (LDA) analysis, identifying the ten most common words.
4. **Trend Analysis**:
   - Experiment with different values of the `n_components` parameter in LDA to uncover trends and hot topics within the ML domain.

**Additional Notes:**
- Contributions and feedback are encouraged! Feel free to contribute enhancements or provide feedback via issues or pull requests.
- This repository facilitates easy adaptation for analyzing other text datasets by following a similar preprocessing and analysis pipeline.
- For optimal analysis, consider adjusting parameters such as `n_components` in the LDA algorithm to refine topic identification.
