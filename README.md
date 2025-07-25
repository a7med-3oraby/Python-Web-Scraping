# 🕸️ Yallakora Web Scraper

This project is a Python script that scrapes football match data from the **Yallakora** website for a specific date entered by the user. It collects match details including team names, scores, match times, and championship titles, then exports the data into a CSV file.

## 📌 Features

- Scrapes all football matches for a user-defined date.
- Extracts key match data:
  - Championship name
  - Competing teams
  - Match time
  - Final score
- Saves the data into a CSV file for further analysis or use.

## 🛠️ Technologies Used

- Python
- `requests` for sending HTTP requests
- `BeautifulSoup` with `lxml` parser for parsing HTML
- `csv` for writing the output to a file

## 📦 Output

The script generates a CSV file named `football_dataa.csv` with the following columns:

- `champoinShip`
- `teamA`
- `teamB`
- `matchTime`
- `score`
