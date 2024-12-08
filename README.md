# week3


def calculate_discount(price, discount_percent):
    # Check if the discount is 20% or higher
    if discount_percent >= 20:
        # Calculate the final price after applying the discount
        final_price = price - (price * discount_percent / 100)
        return final_price
    else:
        # Return the original price if no discount is applied
        return price

# Prompt the user for the original price and discount percentage
price = float(input("Enter the original price of the item: "))
discount_percent = float(input("Enter the discount percentage: "))

# Calculate and print the final price after applying the discount
final_price = calculate_discount(price, discount_percent)
print(f"The final price is: {final_price}")

 original price of the item: 100
discount percentage: 25
The final price is: 75.0
