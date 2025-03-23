# Web Project: Anniversary Password Prompt

This project is a simple web application that prompts the user for their anniversary date as a password. Upon successful entry, the user is redirected to a second page with a personalized message.

## Project Structure

```
web-project
├── src
│   ├── index.html          # Password prompt page
│   ├── password.html       # Page displayed after successful password entry
│   ├── styles
│   │   └── styles.css      # CSS styles for the project
│   └── scripts
│       ├── password.js     # JavaScript for password validation
│       └── main.js         # Additional JavaScript functionality
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the Repository**: 
   Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**: 
   Change into the project directory:
   ```
   cd web-project
   ```

3. **Open the Project**: 
   Open the `src/index.html` file in your web browser to view the password prompt.

## Usage

- Enter your anniversary date in the format `MM/DD/YYYY` in the password prompt.
- If the entered date matches the predefined anniversary date in the JavaScript file, you will be redirected to the `password.html` page.
- Customize the anniversary date in `src/scripts/password.js` as needed.

## Technologies Used

- HTML
- CSS
- JavaScript

## License

This project is open-source and available under the MIT License.