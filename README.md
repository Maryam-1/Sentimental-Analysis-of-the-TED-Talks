
# TED Talks Text Analysis

This project provides an in-depth text analysis of TED Talks by speakers Gabriel Barcia-Colombo and Neil Gershenfeld. Utilizing techniques like tokenization, stopword removal, word frequency analysis, and sentiment analysis, this analysis aims to uncover thematic patterns, emotional tones, and key insights from the talks "Capturing Memories in Video Art" and "The Future of Fab Labs."

## Installation

To run this analysis, ensure you have R and RStudio installed on your system. Then, install the necessary R packages.

```R
install.packages("tidytext")
install.packages("dplyr")
install.packages("ggplot2")
install.packages("wordcloud")
```





## Running the Analysis

### Open the Project
- Begin by opening the RStudio project file (`MA331-Report.Rproj`).

### Load the Scripts
- Open the `analysis_script.R` file in RStudio.

### Execute the Code
- Run the script in RStudio to perform the analysis. Make sure the TED Talks dataset is located in the specified directory as mentioned in the script comments.

## What the Analysis Covers

- **Tokenization and Stopword Removal**: This step breaks down the talks into individual words, removing common stopwords to highlight significant terms.
- **Word Frequency Analysis**: Identifies and visualizes the most frequently mentioned words in each talk to provide insights into the core themes.
- **Sentiment Analysis**: Utilizes the NRC lexicon to analyze the emotional content of each talk, offering a window into the speakers' emotional delivery.
- **Odds Ratio Analysis**: Compares the usage of emotional terms between the two speakers, pinpointing significant differences in their speaking styles.
- **Word Clouds**: Offers a visual representation of the most common words used by each speaker, underlining key topics at a glance.

## Conclusions

This project uncovers distinct thematic and emotional disparities between the talks by Gabriel Barcia-Colombo and Neil Gershenfeld. Through the examination of word frequencies and sentiments, coupled with the analysis of overall engagement (reflected by views), we gain valuable insights into how each speaker structures their narrative and connects with their audience. For a more comprehensive exploration of our findings and methodology, please refer to the `MA331-Report.pdf` document included in this repository.

## Contributing

We welcome contributions to this project! If you have suggestions for improvements or have identified issues, please feel free to fork this project and submit pull requests. For substantial changes or discussions, we encourage you to open an issue first to discuss your ideas or concerns.

Thank you for your interest and support in enhancing the TED Talks Text Analysis project.
