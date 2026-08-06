# Mathematical Algorithm Example
# Calculates the sum of numbers and analyzes the result

def analyze_numbers(numbers):
    """
    This function calculates:
    - Total sum
    - Average value
    - Maximum value
    - Minimum value
    """

    total = sum(numbers)
    average = total / len(numbers)
    maximum = max(numbers)
    minimum = min(numbers)

    return {
        "Sum": total,
        "Average": average,
        "Maximum": maximum,
        "Minimum": minimum
    }


# Example data
numbers = [3, 7, 12, 5, 9]

# Run the algorithm
result = analyze_numbers(numbers)

# Display results
print("Mathematical Analysis")
print("---------------------")

for key, value in result.items():
    print(key + ":", value)
