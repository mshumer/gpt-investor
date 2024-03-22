# gpt-investor

[![Twitter Follow](https://img.shields.io/twitter/follow/mattshumer_?style=social)](https://twitter.com/mattshumer_)
# Claude-Investor | The first release in the gpt-investor repo

Claude-Investor is an experimental investment analysis agent that utilizes the Claude 3 Opus and Haiku models to provide comprehensive insights and recommendations for stocks in a given industry. It retrieves financial data, news articles, and analyst ratings for companies, performs sentiment analysis, and generates comparative analyses to rank the companies based on their investment potential.

## Workflow

- Generates a list of ticker symbols for major companies in a specified industry
- Retrieves historical price data, balance sheets, financial statements, and news articles for each company
- Performs sentiment analysis on news articles to gauge market sentiment
- Retrieves analyst ratings and price targets for each company
- Conducts industry and sector analysis to understand market trends and competitive landscape
- Generates comparative analyses between the selected company and its peers
- Provides a final investment recommendation for each company based on the comprehensive analysis, including price targets
- Ranks the companies within the industry based on their investment attractiveness

## Requirements

To run Claude-Investor, you need an Anthropic API key for accessing the Claude AI model.

## Usage

1. Open the `claude_investor.ipynb` notebook in Google Colab or Jupyter Notebook.

2. Replace the placeholder for `ANTHROPIC_API_KEY` in the notebook with your Anthropic API key.

3. Run the notebook cells sequentially to execute the code.

4. When prompted, enter the industry you want to analyze.

5. Wait for the AI system to produce a report.

## Disclaimer

Claude-Investor is an educational and informational tool designed to assist in investment analysis. It should not be considered as financial advice or a substitute for professional investment guidance. Always conduct thorough research and consult with a qualified financial advisor before making any investment decisions.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Some known improvement areas:
- improve the industry analysis module to use real-time data

## Contact

Matt Shumer - [@mattshumer_](https://twitter.com/mattshumer_)

Lastly, if you want to try something even cooler than this, sign up for [HyperWrite Personal Assistant](https://app.hyperwriteai.com/personalassistant) (most of my time is spent on this). It's basically an AI with access to real-time information that a) is incredible at writing naturally, and b) can operate your web browser to complete tasks for you.
