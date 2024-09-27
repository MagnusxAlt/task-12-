# Registration Form Project

This is a simple registration form web project consisting of an HTML form with fields for user registration details. It includes external CSS for styling and JavaScript for form validation.

## Project Structure

The project includes the following files:
- `index.html`: Main HTML file containing the form.
- `style.css`: External CSS file for styling the form.
- `script.js`: External JavaScript file for validating password matching.

### File Breakdown:
- **index.html**: The main web page with a registration form containing the following fields:
  - First Name
  - Last Name
  - Email ID
  - Phone Number
  - Password
  - Confirm Password
  
  The form uses the `GET` method for submission to `submit.html`, which is currently a placeholder.

- **style.css**: Provides the basic styling for the form, including spacing, font, and button styles.

- **script.js**: Handles the form's password validation. If the password and confirmation password fields do not match, an alert is displayed, and form submission is prevented.

## Setup Instructions

1. Clone or download the project folder.
2. Open the folder in **VS Code** or any code editor.
3. Make sure to install the **Live Server** extension in VS Code.
4. Right-click on `index.html` and select **"Open with Live Server"** to view the form in your browser.

### Running the Project

1. After opening with Live Server, the form will be displayed in your browser.
2. Fill in the fields, and ensure the passwords match before submission. If the passwords do not match, an alert will pop up, and the form will not submit.

### Example Form Fields:
- **First Name**: Enter your first name.
- **Last Name**: Enter your last name.
- **Email ID**: Enter your email address.
- **Phone Number**: Enter your phone number.
- **Password**: Enter a password.
- **Confirm Password**: Confirm the password.

### Functionality
- Upon clicking the submit button, if the passwords do not match, an error message is shown, and form submission is blocked.
- When the form is successfully submitted, it directs the user to a page `submit.html` (placeholder) with a success message.

## Customization

- You can update the CSS styles in the `style.css` file to change the look and feel of the form.
- If you want to add more form fields or functionality, you can modify `index.html` and add more JavaScript code in `script.js`.

## Future Improvements

- Use the POST method for form submission once you have a server-side handling process in place.
- Add more form validation checks such as validating the email format or checking the length of the password.

