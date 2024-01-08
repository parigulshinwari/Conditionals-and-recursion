# Conditionals-and-recursion

import math
result=10/3
new_result=math.ceil(result)
print(result)
#float division = /
#integre division= // (math.floor)

**#Boolean expression**

This code is a simple example of checking the presence of a specific value in a list and printing different messages based on the result.


client_one = ["dog", "max", "9:30am"]
client_two = ["turtle", "shelly", "10am"]

# For the first client
if "dog" in client_one:  # Corrected: "dog" should be a string
    print(f"There is a dog named {client_one[1]} coming in at {client_one[2]}")
else:
    print(f"There is a {client_one[0]} named {client_one[1]} coming in at {client_one[2]}")

**what this code means:**
The code defines two lists, client_one and client_two, where each list represents information about a client (animal type, name, and time).
The code then checks if the string "dog" is present in the client_one list.
If "dog" is found in client_one, it prints a message indicating that a dog named "max" is coming at 9:30 am.
If "dog" is not found in client_one, it prints a generic message indicating the type of animal, its name, and the scheduled time.




