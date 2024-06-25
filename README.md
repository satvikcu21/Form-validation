# Form-validation

**Objective**

  The primary objective of this project is to implement client-side form validation using JavaScript. The validation ensures that user input is correctly formatted 
  and complete before the form is submitted, enhancing user experience and reducing server-side processing of invalid data.

**Functionality Overview**

 The form includes fields for the user's name, phone number, email address, and a message. Each field has specific validation criteria:
  1.Name: The user must provide their full name (first and last name) with a space separating them.
  2.Phone Number: The phone number must be exactly 10 digits long.
  3.Email: The email must follow a standard email format (e.g., example@domain.com).
  4.Message: The message must be at least 30 characters long.
**Validation Functions**

 1.**validateName():**
 
   Checks if the name field is empty.
   Ensures the name contains a first and last name separated by a space.
   Provides appropriate error messages or a success indicator.
   
 2.**validatePhone():**

    Ensures the phone field is not empty.
    Validates that the phone number is exactly 10 digits.
    Provides appropriate error messages or a success indicator.
 3.**validateEmail():**
 

    Checks if the email field is empty.
    Validates the email format using a regular expression.
    Provides appropriate error messages or a success indicator.
 4.**validateMes():**

    Ensures the message field has at least 30 characters.
    Provides the remaining character count needed if the input is insufficient.
    Provides a success indicator if the validation passes.
 5.**validateForm():**

    Calls the individual validation functions for each field.
    Displays a general error message if any of the fields fail validation.
    Prevents form submission until all fields are correctly validated.
**Implementation Details**

1.**Error Handling**: Each validation function updates an associated error message element in the DOM, guiding the user to correct their input.
2.**Success Indicators**: A checkmark icon (<i class="fa-solid fa-check"></i>) is displayed when a field passes validation. 
3.**User Feedback**: The validateForm function provides immediate feedback if the form cannot be submitted, enhancing user experience by guiding them to resolve errors promptly.

**Previews:**

![Screenshot 2024-06-25 183048](https://github.com/satvikcu21/Form-validation/assets/150938638/51b1e1cf-8ad5-4952-95fb-b59d32880d2b)

![Screenshot 2024-06-25 185300](https://github.com/satvikcu21/Form-validation/assets/150938638/3284d535-49c6-4778-b677-0b90cc24aac3)
