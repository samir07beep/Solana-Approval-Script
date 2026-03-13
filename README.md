# Solana Token Approval Script

Simple web interface to approve a delegate for a SPL token using Phantom wallet.

This tool allows a user to approve another wallet to spend a specified amount of tokens.

---

## Features

• Phantom wallet connection  
• Approve SPL token delegate  
• Simple HTML + JavaScript interface  
• Runs entirely in the browser  

---

## How It Works

1. User connects Phantom wallet.
2. User enters:
   - Token Mint Address
   - Delegate Wallet Address
   - Amount to approve
3. The script creates a `ApproveInstruction` transaction.
4. Phantom prompts the user to sign the transaction.
5. Transaction is sent to the Solana network.

---

## Usage

Open the `index.html` file in a browser with Phantom installed.

Steps:

1. Click **Connect Wallet**
2. Enter the **Token Mint Address**
3. Enter the **Delegate Wallet**
4. Enter the **Amount**
5. Click **Approve Token**
6. Confirm the transaction in Phantom.

---

## Requirements

• Phantom Wallet  
• Modern Browser (Chrome / Brave / Edge)

---

## Disclaimer

This project is for educational purposes only.

Always review any transaction before signing.  
The authors are not responsible for any misuse or loss of funds.

---

## License

MIT
