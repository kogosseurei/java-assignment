public class Main {

    // Inner class: BankAccount
    static class BankAccount {
        private String accountNumber;
        private String accountName;
        private double balance;

        // Constructor
        public BankAccount(String accountNumber, String accountName, double balance) {
            this.accountNumber = accountNumber;
            this.accountName = accountName;
            this.balance = balance;
        }

        // Deposit method
        public void deposit(double amount) {
            if (amount > 0) {
                balance += amount;
                System.out.println(amount + " deposited. New balance: " + balance);
            } else {
                System.out.println("Deposit amount must be positive.");
            }
        }

        // Withdrawal method
        public void withdrawal(double amount) {
            if (amount > 0 && amount <= balance) {
                balance -= amount;
                System.out.println(amount + " withdrawn. New balance: " + balance);
            } else {
                System.out.println("Invalid withdrawal amount.");
            }
        }

        // Getter for balance
        public double getBalance() {
            return balance;
        }
    }

    // Main method
    public static void main(String[] args) {
        BankAccount myAccount = new BankAccount("001", "Louis Kogos", 1000.0);

        myAccount.deposit(5000.0);      // Adds 500 to balance
        myAccount.withdrawal(2000.0);   // Removes 200 from balance
        System.out.println("Final Balance: " + myAccount.getBalance());
    }
}
