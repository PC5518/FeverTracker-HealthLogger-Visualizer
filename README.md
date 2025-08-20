# Fever Tracker 

## Overview

I created this tool during a 19-day persistent bacterial infection where I suffered from a continuous 24-hour fever around 102°F. The fever would not go away and caused me to lose a lot of productive time I normally spent studying Physics.

I built this tracker to log my temperature, symptoms, medicines, and additional notes, so I could show detailed data to doctors and health professionals. This helped them understand how my fever fluctuated, especially at night, and provided a clear record of my health during a very challenging time.

This project was written with a sense of personal necessity, born from experiencing a long, unrelenting fever, and the need for a simple, user-friendly way to track health at home without requiring advanced devices.

It was very painful experience I had .

I made this by realising If someone is suffering health issues and having fever, he does and he doesn't have realtime fever tracking Advanced machine which is normally not available at everyone's home He can just do data entry at home by measuring it with the thermometer and it will just take the Input. 

## Features

### Automatic Timestamping
- The date and time are automatically recorded whenever you enter new data.
- No need to manually write down the time or date.

### Easy Data Entry
- Input your temperature, feelings, medicines, and notes.
- The script handles all data storage and formatting automatically.

### Excel Storage
- All entries are saved to an Excel file (`fever_tracker.xlsx` by default).
- The Excel file is fully customizable: you can change columns, formatting, or use your own template.

### Temperature Visualization
- Generates a clear trend plot of your temperature over time.
- Shaded background zones indicate:
  - Normal temperature
  - Low-grade fever
  - Moderate-grade fever
  - High-grade fever

### Latest Temperature Highlight
- The most recent temperature reading is displayed in a summary box on the plot for quick reference.

### User-Friendly Design
- No specialized devices are required.
- Ideal for home use to track fever or health conditions.

### Data Insights
- Doctors and health professionals can use the logged data to:
  - Track fever patterns
  - Monitor fluctuations, especially at night
  - Make better-informed health decisions

## How It Works

1. Run the script and enter your temperature, feelings, medicines, and notes.
2. The date and time are automatically recorded.
3. The script appends the new entry to the Excel file(WHICH IS MANDATORY).
4. A temperature trend plot is generated, with shaded fever zones and the latest temperature highlighted.
5. The Excel file can be customized to suit your preferences or personal template.

## Purpose and Motivation

This project was created out of necessity and personal experience. During a long, persistent bacterial infection with a high, continuous fever, I wanted a way to show doctors exactly how my body was reacting, including the timing of fever spikes at night.

It also serves as a personal productivity tool, letting me track my health without losing focus on other important tasks like studying Physics.

## Requirements

- Python 3.x
- pandas
- openpyxl
- matplotlib

## Usage

1. Clone the repository:
```bash
git clone <repository_url>
Install required packages:

pip install pandas openpyxl matplotlib


Run the script:

python fever_tracker.py


Enter your temperature and notes when prompted.

A plot of your fever trend will be displayed automatically.


FINAL OUTPUT
<img width="1919" height="947" alt="Screenshot 2025-07-31 221911" src="https://github.com/user-attachments/assets/fea407f4-b24e-4812-a5a8-a1f462cbb4df" />

