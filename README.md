# Email Password Validator

A simple web application that validates email and password inputs using JavaScript regular expressions with real-time feedback.

## Features

- **Email Validation**: Checks for proper email format (`@` and domain required)
- **Password Validation**: Ensures password meets security requirements:
  - Minimum 8 characters
  - At least one lowercase and uppercase letter
  - At least one digit
  - At least one special character (`@$!%*?&`)
- **Real-time Feedback**: Shows error messages and visual indicators (green/red borders)
- **Success Message**: Displays confirmation when all validations pass
- **Responsive Design**: Works on all screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/FAISAL-KHAN81/Email-Password-validator.git
   ```

2. Open `index.html` in your browser

## Usage

1. Enter email and password
2. Click **"Validate"** button
3. View error messages or success confirmation

### Validation Rules

**Email:**
- Must contain `@` symbol
- Must have a domain (e.g., `.com`)
- No spaces allowed

**Password:**
- Minimum 8 characters
- At least one lowercase letter
- At least one uppercase letter
- At least one digit
- At least one special character (`@$!%*?&`)

## Project Structure

```
Email-Password-validator/
├── index.html          # Main file with embedded CSS & JavaScript
└── README.md           # This file
```

## Customization

Modify validation rules in the JavaScript section of `index.html`:

```javascript
// Email pattern
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

// Password pattern (change {8,} to adjust minimum length)
const passwordRegex = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*?&])[A-Za-z\d@$!%*?&]{8,}$/;
```

## Contact

**Faisal Khan**  
GitHub: [@FAISAL-KHAN81](https://github.com/FAISAL-KHAN81)

Project Link: [https://github.com/FAISAL-KHAN81/Email-Password-validator](https://github.com/FAISAL-KHAN81/Email-Password-validator)
