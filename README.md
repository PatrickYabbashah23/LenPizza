# LenPizza
#This Program simulates a list of Pizzas and collected sales data

#List of pizza toppings

toppings = ["pepperoni", "pineapple", "cheese", "sausage", "olives", "anchovies", "mushrooms"]

#Price of each pizza topping

prices = [2, 6, 1, 3, 2, 7, 2]

#Finds the length of the number of toppings in the 'toppings' list and then prints the number of pizzas that are currently on the menu for sale

num_pizzas = len(toppings)
print("We sell " + str(num_pizzas) + " different types of pizza!")

#Combines the toppings list and prices list into one whole new list which prints out the toppings alongside the prices on how much the toppings cost

pizzas = list(zip(prices, toppings))
print(pizzas)

#Sorts the types of pizzas so that the lowest prices will start at the top of the list

pizzas.sort()

#Finds the most expensive type of pizza

priciest_pizza = pizzas[-1]
print(priciest_pizza)

#FInds the most cheapest type of pizza

three_cheapest = pizzas[:3]
print(three_cheapest)

#Counts the number of times the dollar amount of $2 appears

num_two_dollar_slices = prices.count(2)
print(num_two_dollar_slices)


