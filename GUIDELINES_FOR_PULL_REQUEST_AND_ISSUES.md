# Guidelines for Creating Issues and Pull Requests

## Creating Issues  

An issue helps us track bugs, feature requests, or other discussions. Please follow the steps below to ensure clarity and efficiency:

### Steps to Create an Issue

1. **Navigate to the Issues Tab**  
   - Open the repository on GitHub and click the **Issues** tab.

2. **Click "New Issue"**  
   - Click the green **New Issue** button.

3. **Choose a Template**  
   - If templates are available, select the appropriate one (e.g., "Bug Report" or "Feature Request").  
   - If no templates exist, use the following structure:

### Issue Description Template  

```markdown
### Summary  
Provide a concise description of the issue.  

### Steps to Reproduce (For Bugs)  
1. Step-by-step instructions to reproduce the problem.  
2. Include any relevant screenshots or logs.  

### Expected Behavior  
Explain what should happen.  

### Actual Behavior  
Describe what is currently happening.  

### Environment Details  
- Operating System:  
- Browser/Version:  
- Relevant Dependencies/Tools:  

### Additional Context  
Add any other context or files that might be relevant.
```

4. **Labels and Assignments**  
   - Add relevant labels (e.g., `bug`, `enhancement`, `help wanted`) to categorize the issue.  
   - Assign it to yourself or a team member if possible.

---

## Creating Pull Requests  

Pull requests are used to merge your contributions into the main project. Follow these steps to ensure a smooth process:

### Steps to Create a Pull Request  

1. **Push Your Changes**  
   - Ensure you’ve pushed your changes to your branch:
     ```bash
     git push origin your-branch-name
     ```

2. **Open the Pull Request**  
   - Go to the repository on GitHub.  
   - Click the **Pull Requests** tab and then the **New Pull Request** button.  

3. **Select Branches**  
   - Base: `main` or another target branch as specified.  
   - Compare: Select the branch you worked on.  

4. **Add a Clear Title and Description**  
   - Use a concise, descriptive title (e.g., "Fix: Navbar responsiveness issue").  
   - Follow the template below for the description:

### Pull Request Description Template  

```markdown
### Summary  
Provide a short summary of the changes made.  

### Related Issues  
Link any related issues (e.g., "Fixes #123").  

### Changes Made  
- List the changes made in this pull request.  
- Example:  
  - Fixed the navbar layout issue on mobile.  
  - Improved color contrast for accessibility.  

### Checklist  
- [ ] My code follows the project style guidelines.  
- [ ] I have tested my changes and ensured they work as expected.  
- [ ] Relevant documentation has been updated (if necessary).  
```

5. **Request Reviewers**  
   - Tag relevant reviewers to examine your changes.  

6. **Resolve Comments and Conflicts**  
   - Respond to feedback or resolve merge conflicts if reviewers point them out.  
