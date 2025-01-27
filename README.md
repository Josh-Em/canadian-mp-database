# Canadian MP Data Analysis using AI

This project demonstrates how to use AI to create a structured database of Canadian Members of Parliament (MPs) by scraping their Wikipedia pages and analyzing the resulting dataset. The pipeline extracts information such as educational backgrounds, previous occupations, policy stances, and controversial statements.

[![Watch the Tutorial](https://img.youtube.com/vi/aD3IOG5772s/maxresdefault.jpg)](https://www.youtube.com/watch?v=aD3IOG5772s)


## Overview

The notebook creates a pipeline that:
1. Scrapes Wikipedia pages for all 337 Canadian MPs
2. Uses GPT-4o to extract structured information from the unstructured text
3. Saves the data to CSV files and pandas DataFrames
4. Performs data analysis and visualization

## Getting Started

1. Open the notebook in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/REPO_NAME/blob/main/NOTEBOOK_NAME.ipynb)

2. You'll need to provide your own OpenAI API key to run the notebook. You can get one from [OpenAI's website](https://platform.openai.com/).

3. The notebook is self-contained and includes all necessary package installations.

## Required API Keys

- OpenAI API key (for GPT-4o access)

## Data Analysis Examples

The notebook includes visualizations for:
- Most common universities attended by MPs
- Previous occupations before entering politics
- MPs with most controversial statements
- Educational background distribution

## Relevant Resources

- [Tutorial Video](https://www.youtube.com/watch?v=VIDEO_ID)
- [House of Commons Members List](https://www.ourcommons.ca/members/en/search)
- [Hansard Transcripts](https://www.ourcommons.ca/DocumentViewer/en/house/latest/hansard)
- [OpenAI API Documentation](https://platform.openai.com/docs/api-reference)
- [Anthropic Console](https://console.anthropic.com/) - Used for pair programming
- [OpenAI Playground](https://platform.openai.com/playground) - Used for testing prompts

## Data Sources

The project uses publicly available data from:
- Wikipedia pages of Canadian MPs
- Official House of Commons website

## Limitations

- Data quality depends on Wikipedia page completeness
- AI-generated responses may contain inconsistencies
- Some MPs may have ambiguous Wikipedia URLs
- Manual verification needed for some edge cases

## Future Applications

This notebook demonstrates principles that can be applied to various business use cases:
- Processing customer support tickets
- Analyzing product reviews
- Extracting information from unstructured documents
- Creating structured databases from text data

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

- OpenAI for providing the GPT-4o API
- Wikipedia for the source content
- Canadian Parliament for public data access
- Anthropic for Claude access (used in pair programming)
