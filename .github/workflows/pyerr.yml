def fibonacci(n):
    """
    Generate a list containing the Fibonacci sequence up to n terms.
    """
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2:
        return [0, 1]
    
    # Start with the first two Fibonacci numbers.
    sequence = [0, 1]
    while len(sequence) < n:
        next_value = sequence[-1] + sequence[-2]
        sequence.append(next_value)
    return sequence

def main():
    print("Welcome to the Simple Fibonacci Program!")
    
    try:
        num = int(input("Enter a positive integer for the number of Fibonacci terms: "))
        if num <= 0:
            print("Please enter a positive integer.")
            return
        
        seq = fibonacci(num)
        print("Fibonacci sequence:")
        print(seq)
    except ValueError:
        print("Invalid input. Please enter a valid integer.")

if __name__ == "__main__":
    main()
