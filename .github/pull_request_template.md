






## Pull Request Title:
### [Ticket Number] ticket_type/short description
- Ticket number: OXY-100
- Ticket types: feature, hotfix, bugfix, release, refactoring, etc;
- Short Description: what has been done;

## Pull Request Description:
What was done. How is expected to work now. How does it look (in case of visual change). How to test it (in case of new scenario).

## Pull Request Requirements

- Before opening Pull Request make sure you reviewed your code, covered it with tests, updated documentation in case that is required and followed style guide;
- Title required and should not be a default one. The title of Pull Request should be clear, self-explanatory and contain the ticket number;
- Make a short and useful description. Describe 'why' and 'what' was been changed in Pull Request. For visual changes add screenshot to demonstrate changes. Would be nice to add test steps in case of new scenario;
- Whenever possible, break pull request into smaller ones;
- Please add link to your ticket/task in case Ticket Number in the title can't reflect it.

## Example

- **Title:** [OXY-100] feature/add customer_admin role
- **Description:** Add customer_admin role to existing list of roles. Customer_admins are able to create, delete and modify user profiles. No more admin permissions allowed. To test and reproduce add customer_admin role to your test user, login under that user and navigate to Admin tab -> User Maintenance tab.

(CI test successful)
