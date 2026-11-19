Debug a Donation Form
A local charity has built a donation form website, but there are several issues that need to be fixed. The form isn't accessible and has some HTML syntax errors.

Your job is to fix all of the errors so the form works correctly and is accessible to all users. Complete the items in the user stories below and click "Check Your Code" to see if you fixed all the errors.

User Stories:

The input elements are void elements and should not have closing tags. Remove all </input> closing tags from the form.
Add label elements for each form input field so users know what each field is for. The label text should match what's currently next to each input.
The Email Address: input type should be an email instead of text.
You should associate each label element with its corresponding input element using the for attribute on the label and a matching id attribute on the input.
Add the required attribute to the text, email, and number input fields (but not the checkbox or submit button) to ensure users fill in the required information.
Tests:
Waiting:1. You should not have any </input> closing tags in your code.
Waiting:2. You should have exactly five input elements in your form.
Waiting:3. Your first input element should have a name attribute with a value of name.
Waiting:4. Your second input element should have a name attribute with a value of email.
Waiting:5. Your third input element should have a name attribute with a value of amount.
Waiting:6. Your fourth input element should have a name attribute with a value of newsletter.
Waiting:7. Your fifth input element should have a type attribute with a value of submit.
Waiting:8. You should have exactly four label elements in your form.
Waiting:9. Your first label should have the text Full Name:.
Waiting:10. Your first input should have a required attribute.
Waiting:11. Your second label should have the text Email Address:.
Waiting:12. Your second input should have a required attribute.
Waiting:13. Your third label should have the text Donation Amount ($):.
Waiting:14. Your third input should have a required attribute.
Waiting:15. Your fourth label should have the text Subscribe.
Waiting:16. You should associate every input element with a label element using the for and id attributes.
Waiting:17. Your input for the email address should be of type email.
Waiting:18. Your checkbox input should not have a required attribute.
Waiting:19. Your submit button should not have a required attribute.