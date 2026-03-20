# Pull Request Template

### Title
[PR] Brief description of the change  
(e.g., Auto-populate birthdate when selecting user in patient form)

### Issue Reference
- Closes #[issue-number]  
- Related to #[issue-number] (if applicable)

### Description
Provide a clear and concise description of what this PR does.  
Example: This PR implements auto-population of the *Date of Birth* field when a user is selected from the dropdown in the **Create Patient** form.

### Changes Made
- Added logic to fetch birthdate from the database when a user is selected.
- Updated patient form UI to auto-fill the *Date of Birth* field.
- Ensured manual editing of the field is still possible.
- Added unit tests for data population.

### Steps to Test
1. Go to **Create Patient** form.
2. Select a user from the dropdown (e.g., Juan Dela Cruz).
3. Verify that the *Date of Birth* field is automatically populated.
4. Save the record and confirm the birthdate persists.

### Screenshots / Proof
_Add screenshots or screen recordings to show the feature/bug fix working._  
![Screenshot](link-to-screenshot.png)

### Dependencies
- None (or list any dependencies this PR introduces)

### Checklist
- [ ] Code follows project style guidelines
- [ ] Tests added or updated
- [ ] Documentation updated (if needed)
- [ ] Verified locally

### Type of Change
- [ ] Bug fix  
- [ ] New feature  
- [ ] Enhancement  
- [ ] Documentation update
