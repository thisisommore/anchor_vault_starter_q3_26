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