# Intergration-Testing

perform top down integration testing on the FeesCalculator and DBHandler classes (i.e. create stubs for them and then replace one by one with the actual code).

For each of the operations Withdrawal, Deposit and Transfer have a class under you src/test/java/bank/transactions directory (say a BankWithdrawalTest.java class) where a) in its initialization method before each test (i.e. method annotated with @BeforeEach) you will create the stubs for the FeesCalculator and DBHandler classes and create a new transaction (say a BankWithdrawal  transaction) using the stubs you just created, and b) in its test() method you will use these stubs to make a “integration” call (say for a withdrawal). You will gradually have to test all the Withdrawal, Deposit and Transfer operations. For your tests assume you have one user, with one card and a PIN.
Perform the same tests, but this time replace the FeesCalculator with the actual class.
Perform the same tests, but this time replace the FeesCalculator and the DBHandler with the actual classes.
