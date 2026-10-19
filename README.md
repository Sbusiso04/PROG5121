
# QuickChat Messaging Application - PoE Part 2

## Description
QuickChat is a console-based application designed to manage, format, and track outgoing user messages. It provides a secure login interface, menu navigation, input validation (message character limits and international phone number formatting), and custom hash generation for message tracking.

This project was built as part of the Portfolio of Evidence (PoE) for Rosebank College (The IIE).

---

## Features
- **User Authentication:** Secure console-based login.
- **Interactive Menu:** Navigation options to send messages, view status, or exit.
- **Input Validation:**
  - Enforces a **250-character limit** per message.
  - Validates recipient cell numbers to ensure they contain international codes (e.g., starting with `+`) and stay within length limits.
- **Message Hash Generation:** Automatically creates an uppercase unique Message Hash (`ID:Number:FirstAndLastWord`).
- **Message Status Actions:** Supports sending, deleting/disregarding, and storing messages for later.

---

## Technologies & Tools
- **Language:** JavaScript (Node.js) / Java
- **Version Control:** Git & GitHub
- **Automation/CI:** GitHub Actions (Automated Unit Testing)

---

## How to Run the Application

### Prerequisites
Make sure you have Node.js installed on your machine.

### Execution Steps
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git)
