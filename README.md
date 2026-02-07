# Yellow Bank GenAI Assistant

## Objective
Build a GenAI-powered banking assistant that authenticates users and fetches loan details using multi-step workflows.

---

## Features
- User authentication using Phone Number, DOB, and OTP
- Modular workflow design using Yellow.ai Flows
- Secure loan account retrieval
- Dynamic loan selection and detailed view
- Token-optimized responses using data projection

---

## Architecture
User → Agent → Authentication (OTP) → Loan Accounts → Loan Details

---

## Tools / Workflows
| Workflow | Description |
|--------|-------------|
| triggerOTP | Sends OTP to user phone |
| getLoanAccounts | Fetches list of loan accounts |
| loanDetails | Fetches selected loan details |

---

## Agent Flow
1. User requests loan details
2. Agent collects phone number and DOB
3. OTP is triggered for verification
4. Loan accounts are fetched
5. User selects a loan
6. Loan details are displayed

---

## Technology Used
- Yellow.ai Conversational AI Platform
- Event-driven workflows
- REST APIs (mocked for assignment)

---

## Demo
See demo video link in `demo-video-link.txt`
