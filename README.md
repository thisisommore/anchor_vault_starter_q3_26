# Vault

This is simple solana program to store user SOL

## Accounts

### Vault

Stores user balace

### Vault state

stores bumps for vault and vault state account
this makes it gas effiecient since there is no need to calculate bump

## Instructions

### Initialize

Initialize accounts

### Deposit

Deposit sol into the vault account

### Withdraw

Withdraw sol from vault account to user
Note - it does not close account

### Close

It withdraws sol and closes vault account

## Tests
Tests are written in rust itself and uses SVM Lite

<img width="1171" height="525" alt="Screenshot 2026-09-11 at 12 04 21 PM" src="https://github.com/user-attachments/assets/eaf50cc7-e791-49f2-abc7-296f5491c665" />
