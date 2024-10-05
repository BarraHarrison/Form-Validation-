## Form-Validation

This JavaScript code ensures that all the necessary information is filled out correctly before a form can be submitted.
It checks for errors in the user's input for their name, phone number, email, and message, and gives feedback if anything is wrong.

Name Validation: The form checks if the user has provided a full name (first and last name).
If not, it shows an error saying either "Name is required" or "Write full name" if the format is incorrect.

Phone Validation: The phone number must be exactly 10 digits, and only numbers are allowed.
If this isn’t followed, an error appears stating "Phone no. should be 10 digits" or "Only digits please."

Email Validation: The form checks that the email is written correctly with the standard format (e.g., example@domain.com).
If not, it displays an "Email invalid" message.

Message Validation: The message must have a minimum of 30 characters.
If it's too short, the code informs the user how many more characters are needed.

If all the inputs are correct, a checkmark appears beside the input fields.
If there are errors, a message "Please fix error to submit" is displayed, prompting the user to correct them.
