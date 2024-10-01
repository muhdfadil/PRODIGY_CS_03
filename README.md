# Password Complexity Checker

This project implements a tool to assess the strength of passwords based on various complexity criteria. It checks if the password meets recommended security standards and provides feedback on the password's strength.

## Features

- **Length Check**: Ensures the password meets a minimum length requirement.
- **Uppercase and Lowercase Check**: Validates the presence of both uppercase and lowercase letters.
- **Numeric Check**: Ensures the password contains numbers.
- **Special Character Check**: Verifies the presence of special characters (e.g., `!`, `@`, `#`, etc.).
- **Feedback**: Provides users with feedback on how strong or weak their password is based on the checks.

## Criteria for Password Strength

1. **Minimum Length**: The password must be at least 8 characters long.
2. **Uppercase and Lowercase**: The password must include at least one uppercase and one lowercase letter.
3. **Numbers**: The password must contain at least one digit.
4. **Special Characters**: The password must have at least one special character.
5. **Feedback**: Based on the checks, the program provides feedback (e.g., "Weak", "Moderate", "Strong").

## Example Usage

### Password Strength Test
```bash
$ python3 password_checker.py
Enter your password: Hello@123
Password Strength: Strong
