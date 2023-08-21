# Join Saving Account Smart Contract

## The project is to create a smart contract to automate the creation of joint savings accounts with deposit and withdraw functions.

### Step 1: Create a Joint Savings Account Contract in Solidity
* Define a new contract named `JointSavings.sol`
* Define variables in the new contract:
  - type `address payable` named `accountOne` and `accountTwo`
  - type `address public` named `lastToWithdraw`
  - type `uint public` named `lastWithdrawAmount` and `contractBalance`
* Define a function named withdraw:
  - Use `require` statement
  - Add `if` statement
  - Call the `transfer` function
  - Use `address(this).balance`
* Define a `public payable` function named `deposit`
* Define a `public function` named `setAccounts`
* Add a `fallback` function to store ether that’s sent from outside the deposit function

### Step 2: Compile and Deploy Your Contract in the JavaScript VM
* Compile my smart contract - no error
* Navigate to the “Deploy & Run Transactions” pane, select “JavaScript VM” (Remix VM)
* Click the "Deploy" button to deploy my smart contract - successfully deployed

### Step 3: Interact with Your Deployed Smart Contract
* Test its functionality - capture a screenshot of the execution
  - save it in a folder named `Execution_Results`
