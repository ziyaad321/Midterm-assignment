# Midterm-assignment

NUMBER #01

class BankAccount {
int accountNumber;
double balance;
String accountType;
double interestRate;
BankAccount(this.accountNumber, this.balance, this.accountType, this.interestRate);
void deposit(double amount) {
balance += amount;
print("Deposited \$${50000}. New balance: \$${100000}");
}
void withdraw(double amount) {
if (amount <= balance) {
balance -= amount;
print("Withdrew \$${10000}. New balance: \$${900000}");
} else {
print("Insufficient funds!");
}
}
void addInterest() {
double interest = balance * (interestRate / 100);
balance += interest;
print("Added interest. New balance: \$${balance}");
}
void display() {
print("Account Number: $accountNumber");
print("Balance: \$${balance}");
print("Account Type: $accountType");
print("Interest Rate: $interestRate%");
print("");
}
}
void main() {
BankAccount account1 = BankAccount(123456789, 1000.0, "Savings", 5.0);
BankAccount account2 = BankAccount(989898, 5000.0, "Checking", 3.0);
account1.deposit(50000);
account1.withdraw(10000);
account1.addInterest();
account1.display();
account2.deposit(20000);
account2.withdraw(6000);
account2.addInterest();
account2.display();
}

NUMBER #02


class BankAccount {
int accountNumber;
double balance;
String accountType;
double interestRate;
BankAccount(this.accountNumber, this.balance, this.accountType, this.interestRate);
void deposit(double amount) {
balance += amount;
print("Deposited \$${50000}. New balance: \$${100000}");
}
void withdraw(double amount) {
if (amount <= balance) {
balance -= amount;
print("Withdrew \$${10000}. New balance: \$${900000}");
} else {
print("Insufficient funds!");
}
}
void addInterest() {
double interest = balance * (interestRate / 100);
balance += interest;
print("Added interest. New balance: \$${balance}");
}
void display() {
print("Account Number: $accountNumber");
print("Balance: \$${balance}");
print("Account Type: $accountType");
print("Interest Rate: $interestRate%");
print("");
}
}
void main() {
BankAccount account1 = BankAccount(123456789, 1000.0, "Savings", 5.0);
BankAccount account2 = BankAccount(989898, 5000.0, "Checking", 3.0);
account1.deposit(50000);
account1.withdraw(10000);
account1.addInterest();
account1.display();
account2.deposit(20000);
account2.withdraw(6000);
account2.addInterest();
account2.display();
}
