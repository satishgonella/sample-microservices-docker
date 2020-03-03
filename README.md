# sample-microservices-docker

## Usage

### createCustomer
http://BANK-CUSTOMER-INFO-SERVICE/CustomerInfo/CreateCustomer?strCustomerName=TestCustomerName2&strCustomerCity=TestCity2&intCustomerId=2
http://localhost:7072/CustomerInfo/CreateCustomer?strCustomerName=TestCustomerName3&strCustomerCity=TestCity3&intCustomerId=3

### Fetch all rows for customer  #FetachAllAccounts
http://localhost:7072/CustomerInfo/GetAllCustomerInformation

### FetchCustomerBy CustomerID
http://localhost:7072/CustomerInfo/2

### CreateBankAccount
http://localhost:7071/BankAccount/CreateBankAccount?intCustomerId=2

### DepositAmount
http://localhost:7071/BankAccount/DepositAmount?intCustomerId=2&intDepositAmount=1100

### WithdrawAmount
http://localhost:7071/BankAccount/WithdrawAmount?intCustomerId=2&intWithdrawAmount=5000
http://localhost:7071/BankAccount/WithdrawAmount?intCustomerId=2&intWithdrawAmount=750

### Tranascation Deposit
http://localhost:7073/Transaction/DepositAmount?intCustomerId=2&intDepositAmount=1100


