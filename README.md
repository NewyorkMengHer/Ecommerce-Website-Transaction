# Ecommerce Website Transaction

## Description
The "Ecommerce Website Transaction" project is a collaborative effort between two teams to simulate and analyze ecommerce transaction data. Both teams generate a vast amount of simulated data based on a predefined schema, stream it to each other, clean and transform the data, and finally perform analytical queries. The results are visualized using Tableau and Zeppelin and presented to an audience with diverse backgrounds.

Click [here](https://drive.google.com/file/d/13EnXR1t0JLOYI8LY9EOjFcxR0lCpiTWw/view?usp=drive_link) to see the demo

## Schema
The schema used to generate the transaction data includes:
- `order_id`: Order ID
- `customer_id`: Customer ID
- `customer_name`: Customer Name
- `product_id`: Product ID
- `product_name`: Product Name
- `product_category`: Product Category
- `payment_type`: Payment Type
- `qty`: Quantity Ordered
- `price`: Price of Product
- `datetime`: Date & Time when Order was Placed
- `country`: Customer Country
- `city`: Customer City
- `ecommerce_website_name`: Site where Order was Placed
- `payment_txn_id`: Payment Transaction ID
- `payment_txn_success`: Payment Success/Failure
- `failure_reason`: Reason for Payment Failure

## Features
- Generates over 2 million rows of transaction data spanning 10 years.
- Uses base data on products, companies, and customers stored in files for transaction generation.
- Highly customizable data generation.
- Generates customers from over 20 different countries with region-accurate names.
- Converts transaction prices from USD to the customer's local currency.
- Introduces bad data at a rate of 3% for testing and validation.
- Simulates logistic growth for each company at different rates.

## Workflow
1. Both teams generate transaction data based on the schema.
2. Data is streamed to the opposite team via Kafka and stored in a CSV file.
3. Each team cleans and transforms the received data.
4. Analytical queries are performed on the cleaned data.
5. Results are visualized using Tableau and Zeppelin.
6. Teams come together to share findings and present to a mixed audience.

## Technologies
- Apache Spark
- Spark SQL
- Kafka
- Scala 2.12.11
- Zeppelin

## Contributors
A big thank you to all our contributors who made this project possible:

- [Caleb Reid](https://github.com/calebreid2829)
- [Jaceguai De Magalhaes](https://github.com/jaceguaidemagalhaes)
- [Dare Fatade](https://github.com/ofatade)
- [Theodore Karl](https://github.com/TK-Rev)
- [Youngjung Kim](https://github.com/YoungjungKim016)
- [Aaron Schomer](https://github.com/AarSchoSkIg)
- [Jack Nguyen](https://github.com/Jackeywawa)
- [Newyork Her](https://github.com/newyorkher)
