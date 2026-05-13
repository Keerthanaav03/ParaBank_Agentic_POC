# ParaBank Functional Knowledge

## Registration Module

Page:
Register New Account

Fields:
- First Name
- Last Name
- Address
- City
- State
- Zip Code
- Phone Number
- SSN
- Username
- Password
- Confirm Password

Actions:
- User enters registration details
- User submits registration form
- Account gets created successfully

Validations:
- Mandatory fields cannot be empty
- Password and Confirm Password should match
- Username should be unique

Success Message:
- Welcome <username>

---

## Update Contact Info Module

Page:
Update Contact Info

Fields:
- First Name
- Last Name
- Address
- City
- State
- Zip Code
- Phone Number

Actions:
- User updates profile details
- User submits updated information

Validations:
- Mandatory fields required
- Phone number should be valid

Success Message:
- Profile Updated Successfully

---

## Transfer Funds Module

Page:
Transfer Funds

Fields:
- From Account
- To Account
- Amount

Actions:
- User selects source account
- User selects destination account
- User enters transfer amount
- User submits transfer

Validations:
- Amount cannot be empty
- Amount should be greater than zero
- Source and destination account cannot be same
- Transfer amount should not exceed balance

Success Message:
- Transfer Complete