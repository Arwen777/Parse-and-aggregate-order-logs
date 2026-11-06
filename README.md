# Parse-and-aggregate-order-logs
1-topshiriq
# Order Pipeline & Revenue Aggregator

Python script that reads `orders.csv` using memory-efficient generators (`yield`), validates rows, and calculates revenue per customer per month sorted by revenue.

## How to run
1. Ensure Python 3.x is installed.
2. Place your `orders.csv` file in the same directory.
3. Run the script:
   ```bash
   python main.py
