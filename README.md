This project is a simple Python-based shopping cart calculator that includes multiple discount rules, gift wrap fees, and shipping costs. It allows users to input product quantities, choose gift wrapping options, and calculates the final total based on applied discounts and fees.

# Features

Supports 3 predefined products with prices:

Product A – $20

Product B – $40

Product C – $50

Applies one best discount from multiple rules:

flat_10_discount: $10 off on orders above $10

bulk_5_discount: 5% off for >10 units of any product

bulk_10_discount: 10% off for >20 units of any product

tiered_50_discount: 50% off for units >15 if total quantity >30

Gift wrap fee: $1 per unit (optional)

Shipping fee: $5 per package (10 units per package)

# How It Works

Prompts user for quantity and gift wrap option for each product.

- Calculates:

- Subtotal

- Best applicable discount

- Shipping and gift wrap fees

- Final total

- Outputs a detailed breakdown per product and for the overall cart.
