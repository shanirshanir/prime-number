# prime-number
python code for prime number identification
# prompt: python code for prime number identification


  if is_prime(i):def is_prime(n):
  """
  Check if a number is prime.

  Args:
    n: The number to check.

  Returns:
    True if the number is prime, False otherwise.
  """

  # If n is 1, it is not prime.
  if n == 1:
    return False

  # Iterate over all numbers from 2 to the square root of n.
  for i in range(2, int(n**0.5) + 1):
    # If n is divisible by any number from 2 to its square root, it is not prime.
    if n % i == 0:
      return False

  # If n is divisible by no number from 2 to its square root, it is prime.
  return True

# Print the first 100 prime numbers.
for i in range(1, 101):
    print(i)
