# Bobby-Tables
This project is a simple form to practice some validation and sanitization of form data

This is a form for a user to create a profile on our site. We want to collect the user’s name, character, email and birth year. Our users have been having a field day with this and we need to clean up our form.

## Safety Checkpoints! 📌
 
 * Allow users to use HTML characters in their names, but don’t want to interpret them.
 * Remove any leading or trailing whitespace from the name.
 * Prevent people impersonating other users. To do this, we need to check the name from the input against the contents of the array $existing_users.
 * We intend for users to be a wizard, mage, or orc. Even though the character is a radio button selection, users can set themselves to something besides these options!
 * Prevent users from entering email addresses that aren’t…. well… email addresses.
 * Limit the range of years that users can submit.
