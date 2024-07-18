# cost
# Function to calculate the total cost of planets
def calculate_total_cost(cost_per_planet, num_planets):
    return cost_per_planet * num_planets

# Input cost per planet and number of planets from the user
cost_per_planet = float(input("Enter the cost of one planet: "))
num_planets = int(input("Enter the number of planets you want to buy: "))

# Calculate the total cost using the function
total_cost = calculate_total_cost(cost_per_planet, num_planets)

# Print the total cost
print(f"The total cost for {num_planets} planets, each costing {cost_per_planet}, is {total_cost}")
