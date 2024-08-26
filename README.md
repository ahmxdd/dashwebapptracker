

# Dash Finance Tracker

## Overview

Ever wondered where your money really goes? The Dash Finance Tracker is designed to give you a clear picture of your spending habits.

![screenshot](https://github.com/joshsia/personal-finance/blob/main/app-screenshot.png)

## Purpose

As a computer science student, I created this project to showcase my skills in web development and data analysis. This app not only tracks expenses but also helps me apply what I've learned in a real-world scenario, from designing user interfaces to handling data visualization.

## How to Use

1. **Clone the Repository**
2. **Install Dependencies**  
   Run in the terminal:
   ```sh
   conda env create -f personal-finance.yaml
   ```
3. **Prepare Your Data**  
   Replace or edit `sample-finances.csv` with your own `finances.csv`.
4. **Activate the Environment**  
   ```sh
   conda activate personal-finance
   ```
5. **Run the App**  
   ```sh
   python app.py
   ```
   Access it at `http://127.0.0.1:8050/`.
6. **Customize if Needed**  
   Modify line 71 in `app.py` to use your `finances.csv` file.

If you see "All merchants accounted for" in the terminal, you're good to go! Otherwise, update `categories.json` with any new merchants.
