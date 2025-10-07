# Sales Summary Test

## Summary
This static web application fetches data from a CSV file, calculates the total sales amount, and displays it on a single-page site titled 'Sales Summary Test'. It uses Bootstrap 5 from jsdelivr to ensure a responsive design. Additionally, it now includes a Bootstrap table #product-sales listing each product with its sales.

## Setup
To deploy this application on GitHub Pages, follow these steps:
1. Fork the repository
2. Upload the CSV file containing the sales data
3. Enable GitHub Pages in the repository settings
4. Access the deployed site at `https://your-username.github.io/repository-name`

## Usage
- Access the page by navigating to the GitHub Pages link after deployment.
- There are no additional query parameters required. The page now includes the #product-sales table listing each product with its sales.
- Key features:
  - Fetching data from a CSV file
  - Calculating and displaying total sales amount
  - Displaying each product with its sales in a Bootstrap table

## Code Explanation
The implementation of this application involves:
- Fetching and processing data from a CSV file using JavaScript
- Calculating the sum of the sales column
- Displaying each product with its sales in a Bootstrap table
- Utilizing Bootstrap 5 for styling and layout

Key libraries used:
- Bootstrap 5 from jsdelivr

The logic for summing the sales column remains accurate and is implemented in JavaScript as follows:
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