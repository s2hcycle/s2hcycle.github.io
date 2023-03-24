# Price Calculator Web Application

This web application calculates the retail price of a product based on its cost price and the order amount. The application ensures that the discounted retail price meets a minimum gross margin requirement according to the provided specifications.

## How to Use

1. Open the `price_calculator.html` file in a web browser.
2. Enter the cost price of the product.
3. Enter the order amount.
4. Click the "Calculate Retail Price" button.
5. The retail price will be displayed on the page.

## Calculation Details

The application calculates the retail price based on the following rules:

1. Discount Rates:
   - Order amount ≤ 5,000: 30% discount
   - 5,001 ≤ Order amount ≤ 30,000: 33% discount
   - 30,001 ≤ Order amount ≤ 100,000: 36% discount
   - 100,001 ≤ Order amount ≤ 200,000: 40% discount
   - Order amount > 200,000: 45% discount

2. Minimum Gross Margin Rates:
   - Cost price < 1,000: 45% gross margin
   - 1,000 ≤ Cost price < 3,000: 40% gross margin
   - 3,000 ≤ Cost price < 10,000: 35% gross margin

The retail price is calculated using the following formula:

Retail Price = Cost Price / (1 - Discount Rate) * (1 - Gross Margin Rate)

## License

This project is available under the [MIT License](https://opensource.org/licenses/MIT).

