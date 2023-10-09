# Define a global variable account_balance and set it to an initial balance of 1000.
account_balance <- 1000

# Function to deposit money
deposit <- function(amount) {
  # Access the global variable using the <<- operator
  account_balance <<- account_balance + amount
  cat("Deposited:", amount, "\nNew Balance:", account_balance, "\n\n")
}

# Function to withdraw money
withdraw <- function(amount) {
  # Check if there's enough balance
  if (amount <= account_balance) {
    # Access the global variable using the <<- operator
    account_balance <<- account_balance - amount
    cat("Withdrawn:", amount, "\nNew Balance:", account_balance, "\n\n")
  } else {
    cat("Error: Insufficient funds! Current Balance:", account_balance, "\n\n")
  }
}

# Function to check balance
check_balance <- function() {
  cat("Current Balance:", account_balance, "\n\n")
}

# Test the banking system

# Check initial balance
check_balance()

# Make a deposit of 500
deposit(500)

# Withdraw 200
withdraw(200)

# Try withdrawing an amount greater than the balance
withdraw(1500)

# Check balance after transactions
check_balance()
