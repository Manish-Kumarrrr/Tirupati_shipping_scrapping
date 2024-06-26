## Tirupati Shipping Scrapping Readme

### Introduction
This project aims to fetch details of each AWB (Airway Bill) number from an input Excel file and extract relevant information such as status, booking date, and last update date from the Shree Tirupati Shipping site. Additionally, it calculates the number of days spent between the last update and booking date to provide insights into the shipping duration. The data is then categorized into four types: Booked, Delivered, Invalid, and Return. Finally, the categorized data is written to an Excel file along with a pie chart and a summary table.

![alt text](<Screenshot 2024-03-29 124516.png>)
### Setup Instructions
1. Ensure Python is installed on your system.
2. Install necessary libraries using pip:(optional because  these are already included in the project)
    ```
    pip install pandas openpyxl beautifulsoup4 requests matplotlib
    ```

### Usage
1. Prepare an input Excel file (`input.xlsx`) containing AWB numbers.
2. Run the Python script `Shree_Tirupati_Scrapping_Script.ipynb` or  RunAll cell in vscode or jupyter notebook.
3. The script will fetch data from the Shree Tirupati Shipping site for each AWB number.
4. It will calculate the days spent between the last update and booking date.
5. The data will be categorized into four types: Booked, Delivered, Invalid, and Return.
6. Finally, the categorized data will be written to an output Excel file along with a pie chart and a summary table.

### File Structure
- `input.xlsx`: Input file containing AWB numbers.
- `Shree_Tirupati_Scrapping_Script.ipynb`: Python script for fetching data and performing analysis.
- `output.xlsx`: Output file containing categorized data, along with a pie chart and a summary table.

### Additional Notes
- Ensure a stable internet connection while running the script to fetch data from the Shree Tirupati Shipping site.
- The script may take some time depending on the number of AWB numbers and the speed of the website.
- Make sure to review the output Excel file for the categorized data, pie chart, and summary table.

### Contributors
- [Manish Kumar]

### Contact
For any inquiries or support, please contact me.
