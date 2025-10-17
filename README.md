# Sales Summary Web App

This is a simple web application that fetches data from a `data.csv` file, calculates the total sales, and displays it on the page.

## Features

- Fetches data from a CSV file.
- Calculates the sum of the 'sales' column.
- Displays the total sales in a designated HTML element.
- Handles potential errors during data fetching and processing.

## Technologies Used

- HTML
- JavaScript
- CSS (for basic styling)

## Setup

1.  Create `index.html` and `data.csv` in the same directory.
2.  Open `index.html` in your web browser.

## Data Format

The `data.csv` file should have the following format:

```csv
product,sales
1,100
2,150
3,50
...
```

The first line is the header, and subsequent lines contain product and sales data.

## Implementation Details

The JavaScript code fetches the `data.csv` file using the `fetch` API. It then parses the CSV data, skips the header row, and calculates the sum of the 'sales' column.  Error handling is included to catch potential issues during fetching or parsing the data. The total sales amount is then displayed in an HTML element with the ID `total-sales`.
