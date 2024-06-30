# Telegram Chat Analyzer

This script processes a JSON file containing Telegram chat history and generates summary statistics for each participant. It then visualizes these statistics in bar charts, saving both the summary data and the charts to files.

## Features

- **Load JSON Data**: Reads the chat data from a JSON file.
- **Summarize Chat Data**: Generates summary statistics for each participant, including the number of messages, words, stickers, links, images, video files, video messages, voice messages, forwards, and GIFs.
- **Save Summary**: Stores the summary statistics in a CSV file.
- **Visualize Data**: Creates bar charts for each category of data, displaying both the count and percentage of contributions by each participant. The charts are saved as high-resolution PNG files.

## Requirements

- Python 3.x
- `pandas`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install pandas matplotlib
