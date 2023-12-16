**Welcome to the EKOH Token Vault!**

This document provides an overview of the smart contract deployed on the EKH network at **0xBBfCE55AD100b5bEd880083fCE366120347Af872**. It serves as a secure and transparent storage for your ERC-20 tokens, allowing deposits, withdrawals, and efficient token management.

**Key Features:**

- **Safely deposit and withdraw:** Lock your ERC-20 tokens in exchange for shares, and redeem those shares back for tokens anytime.
- **Proportional share-based system:** Deposits are reflected in minted shares, ensuring fair and transparent allocation of funds.
- **ERC-20 compatibility:** Integrates seamlessly with ERC-20 tokens, leveraging their standard functionalities for transfers and approvals.

**Functionality Overview:**

**Deposit:**

- Call the `deposit(uint _amount)` function.
- The function calculates and mints shares proportional to the deposited amount.

**Withdraw:**

- Call the `withdraw(uint _shares)` function.
- The function burns shares and returns the corresponding amount of tokens based on the current share value.

**ERC-20 Interface:**

- Provides standard ERC-20 functionalities like checking balances, transferring tokens, and approving token transfers.

**Usage Guidelines:**

- **Token Approval:** Before depositing, grant the vault permission to spend your tokens using the ERC-20 `approve` function.
- **Deposit:** Call `deposit` with the desired amount to mint corresponding shares.
- **Withdraw:** Call `withdraw` with the number of shares to burn and receive proportional tokens.
- **Monitor Balances:** Track your token balances and shares to manage your holdings effectively.

**Disclaimer:**

- This smart contract is provided under the MIT license. Review the code before interacting.
- Exercise caution and test thoroughly when using smart contracts on the blockchain.
- Confirm compatibility with the EKOH network before interacting.

**Get Started:**

- Explore the contract's functions and events on a block explorer like EKOHScan.
- Interact with the contract through a compatible wallet that supports ERC-20 tokens and smart contract interactions.

**We hope this README provides a clear understanding of the EKOH Token Vault. If you have any questions or feedback, feel free to reach out.**

**Happy vaulting!**
