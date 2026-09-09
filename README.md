# Vault Program - Turbin3 Q3 2026

Simple personal SOL vault built with Anchor for the Turbin3 Builders Cohort.

## Features

- Initialize a personal vault (PDA)
- Deposit SOL into the vault
- Withdraw SOL from the vault
- Close the vault and reclaim rent

## Instructions

| Instruction   | Description                                      |
|---------------|--------------------------------------------------|
| `initialize`  | Creates the vault state and vault account        |
| `deposit`     | Deposits SOL into the vault                      |
| `withdraw`    | Withdraws SOL from the vault                     |
| `close`       | Closes the vault and returns remaining SOL + rent|

## How to Build & Test

```bash
anchor build
anchor test
```

## Tests

All instructions are tested using **LiteSVM**.

- Initialize
- Deposit
- Withdraw
- Close

All tests are passing.

## Program ID

```
Cx3C4HVsWYJQqNKcEyUFtqVnoMNzcRoZz81zLYissi1G
```

## Author

Gopichand  
Turbin3 Builders Cohort - Q3 2026
