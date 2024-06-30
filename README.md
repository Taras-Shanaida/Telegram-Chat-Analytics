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
Usage and Output
Place the JSON file: Ensure the JSON file containing the chat data (result.json) is placed in the specified directory (D:\\My files\\python\\Work&Study\\telegram\\).

Run the script: Execute the script to process the data, generate the summary, and create the visualizations.

Output
summary.csv: A CSV file containing the summary statistics for each participant.
[category]_chart.png: High-resolution bar charts for each category of data, saved in the current working directory.
Example of summary.csv:
actor	messages	words	stickers	links	images	video_files	video_messages	voice_messages	forwards	gifs
User1	50	350	5	2	10	1	2	3	4	0
User2	40	300	3	4	8	0	1	2	1	1
User3	60	400	4	3	12	2	3	1
