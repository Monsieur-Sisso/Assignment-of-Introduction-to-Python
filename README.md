 def calculate_discount(price,discount_percent):
    if discount_percent>=20:
        discount_amount = (discount_percent/100) * price
        final_price = price - discount_amount
        return final_price 


original_price=float(input("Enter the original price: "))
discount_percent=float(input("Enter the deiscount percentage: "))
final_price=(original_price,discount_percent)
if discount_percent>=20:
    print (f"{final_price}") 
else:
    print (f"{original_price}")



        