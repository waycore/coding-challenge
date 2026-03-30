# Backend Challenge

Build a process that logs into a demo banking application, extracts balances and all transactions across the full available history, and stores them in a database.

## Objective

Create a solution that can:

1. Log in to the demo bank application.
2. Complete the OTP step.
3. Retrieve all transactions and balances.
4. Persist those into a database (any database, your call).

The solution must be implemented in Python.

## Demo Application

- URL: [https://demo-bank-2.vercel.app/](https://demo-bank-2.vercel.app/)
- Username: `user`
- Password: `pass`
- OTP: `123456`

## Submission

Please hand over your solution as a GitHub repository.

Your repository should include clear instructions for how to run the project locally, including any setup steps, dependencies, configuration, and commands required to execute the process end to end. 

Quality matters. A few things we want to see:
- Good repo hygiene. No dead code or useless boilerplate.
- Excellent system architecture. Ask yourself: 
  - What type of workload is this?
  - What's the best way to execute this workload?
  - Could this solution scale horizontally?
- Great data model.
- Modern stack. Think `uv` vs plain old `pip`.
