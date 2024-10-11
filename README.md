# Decentralized Voting System using Blockchain (E-Voting)
The "Blockchain-based Decentralized E-Voting System" ensures secure, anonymous internal elections for private institutions using blockchain. Developed with ReactJS, Node.js, and Solidity, it manages voter registration, ballot creation, and results publishing. Future upgrades include biometric security and email verification.

## Workflow

1. **Admin Setup**:
   - The administrator launches the system on a blockchain network (EVM).
   - They build a voting instance, create an election, and fill in election details, including candidates.
   
2. **Voter Registration**:
   - Voters register to vote by connecting to the blockchain network.
   - Once registered, voter information is forwarded to the admin for verification.

3. **Admin Verification**:
   - Admin reviews registration data (name, blockchain account address, and phone number).
   - Upon verification, the admin approves the voter to cast their ballot.

4. **Voting**:
   - Approved voters cast their vote for their candidate of choice via the voting page.

5. **Election End**:
   - The admin ends the election, after which results are displayed, including the winner.

## Roles

- **Admin**: Responsible for managing the election process.
- **Voters**: Multiple users who register and vote.

## Tech Stack

- **Frontend**: JavaScript (React.js), HTML, CSS
- **Backend**: Node.js
- **Smart Contracts**: Solidity

## Software Used

- **Ganache**: Local blockchain for testing
- **Truffle**: Development framework for Ethereum
- **Visual Studio Code**: Code editor

## Applications Used

- **MetaMask**: Ethereum wallet browser extension for voter registration and transactions.

## How to Run

1. Install [Ganache](https://www.trufflesuite.com/ganache) and [Truffle](https://www.trufflesuite.com/truffle).
2. Clone the repository.
   ```bash
   git clone <repository-url>

3. Install dependencies
   ```bash
   npm install
   
4. Start Ganache and run the development server.
   ```bash
   npm start
   
5. Access the admin panel to create an election, and voters can register via the MetaMask extension.

##Future Enhancements


- **Email verification**: For voter validation and vote confirmations.
- **Biometric security**: Adding facial recognition for voter authentication.
- **Multiple elections**: Managing multiple elections simultaneously.
