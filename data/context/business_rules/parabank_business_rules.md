# ParaBank Business Rules

## Login

- Valid users should login successfully
- Invalid credentials should show error message
- Locked users cannot access the application
- Username and password are mandatory

---

## Fund Transfer

- User must have sufficient balance
- Source and destination accounts are mandatory
- Transfer amount should be greater than zero
- Transfer confirmation message should appear

---

## Bill Pay

- Payee details are mandatory
- Amount should be positive
- Successful payment confirmation required

---

## Open New Account

- User should be authenticated
- Account type selection mandatory
- New account number generated after success

---

## Transaction History

- Transactions displayed in descending order
- Date filters should work correctly
- Empty transactions should display proper message

---

## Loan Request

- User income details mandatory
- Loan amount should be within allowed limit
- Eligibility validation required