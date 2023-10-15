# Log Splitter
A program I created for my dad's company in the Summer of 2023.

Log Splitter is a project that splits single large inaccessible Log files filled with diagnostic data into accessible CSV files.

### Table of Contents
- [How it Works](#how-it-works)
- [Capabilities](#capabilities)
- [How to Install](#how-to-install)
- [Improvements](#improvements)

## How it Works:

The program begins by creating a CSV file and then searches each line in the Log file for the "Input String" keyword. Once the keyword is found that line is copied into the new CSV file. The readable Excel line limit is 1,040,000 lines and is the default cutoff in this program for a single CSV file. Once the program reaches the 1,040,000 line limit it creates a new CSV file automatically and continues the process. Once the program is finished there is a notification in the GUI.

## Capabilities:

The program uses a GUI that allows the user to select the Log file to be split, the output destination of the CSV files, and the "Search String" keyword by which to split the lines.

The program is used in order to split Log files of up to 16GB into accessible CSV files.

The program was built using Python and converted into an executable program.

## How to Install:

To run this program locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/CollinLTT/Log-Splitter.git
   
2. Run the Log Splitter.exe file as administrator and follow the directions in HOWTORUN.txt

## Improvements:

Since this was my first time making a GUI in Python I would like to improve how it looks and give it better features.

I would also like to add more specific options for how the Log file is split and how the CSV files are created.
