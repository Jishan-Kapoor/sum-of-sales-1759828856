# Sales Summary Test

## Summary
This static web application fetches data from a CSV file, calculates the total sales amount, and displays it on a single-page site titled 'Sales Summary Test'. It uses Bootstrap 5 from jsdelivr to ensure a responsive design.

## Setup
To deploy this application on GitHub Pages, follow these steps:
1. Fork the repository
2. Upload the CSV file containing the sales data
3. Enable GitHub Pages in the repository settings
4. Access the deployed site at `https://your-username.github.io/repository-name`

## Usage
- Access the page by navigating to the GitHub Pages link after deployment.
- There are no additional query parameters or configuration options required.
- Key features:
  - Fetching data from a CSV file
  - Calculating and displaying total sales amount
  - Utilizing Bootstrap 5 for responsive design

## Code Explanation
The implementation of this application involves:
- Fetching and processing data from a CSV file using JavaScript
- Calculating the sum of the sales column
- Utilizing Bootstrap 5 for styling and layout

Key libraries used:
- Bootstrap 5 from jsdelivr

The logic for summing the sales column is implemented in JavaScript as follows:
```javascript
// Fetch data from CSV file
// Process data and extract sales column
let totalSales = 0;
// Calculate sum of sales column
data.forEach(row => {
    totalSales += parseInt(row.sales);
});
// Display total sales amount
document.getElementById('total-sales').textContent = totalSales;
```

## License
This project is licensed under the MIT License.