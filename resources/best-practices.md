# GitHub Best Practices

## Commit Best Practices

### Writing Good Commit Messages
Your commit messages are like diary entries for your code. Make them count!

#### The Golden Rules
1. **Keep the subject line under 50 characters**
2. **Use imperative mood** ("Add feature" not "Added feature")
3. **Capitalize the subject line**
4. **Don't end subject line with a period**
5. **Use the body to explain what and why, not how**

#### Examples of Good Commit Messages
```
✅ Add user authentication system
✅ Fix login button alignment issue
✅ Update README with installation steps
✅ Remove deprecated API endpoints
✅ Refactor database connection logic
```

#### Examples of Bad Commit Messages
```
❌ fixed stuff
❌ Update
❌ asdfgh
❌ Final version
❌ This should work now
```

### Commit Frequency
- **Commit early, commit often** - Don't wait until everything is perfect
- **Test before committing** - Make sure your code works
- **Commit related changes together** - Group related modifications

## Branching Best Practices

### Branch Naming Conventions
Use descriptive names that indicate the purpose:

```
✅ feature/user-authentication
✅ bugfix/login-error-handling
✅ hotfix/security-vulnerability
✅ docs/update-readme
✅ refactor/database-queries
```

```
❌ new-branch
❌ fix
❌ temp
❌ branch1
❌ my-changes
```

### Branch Management
- **Keep branches focused** - One feature or fix per branch
- **Delete merged branches** - Keep your branch list clean
- **Update from main regularly** - Avoid large merge conflicts
- **Use pull requests** - Don't merge directly to main

## Pull Request Best Practices

### Creating Pull Requests
- **Write descriptive titles** - Summarize the change clearly
- **Include detailed descriptions** - Explain what, why, and how
- **Link related issues** - Use "Fixes #123" or "Closes #456"

### Team Workflow
1. **Create issue** for new work
2. **Create branch** from main
3. **Make changes** with good commits
4. **Open pull request** with description
5. **Request reviews** from team members
6. **Address feedback** and update PR
7. **Merge when approved** and CI passes
8. **Delete branch** to keep things clean

## Quick Reference Checklist

### Before Every Commit
- [ ] Code is tested and working
- [ ] Commit message is descriptive
- [ ] No sensitive data included
- [ ] Related files are included

### Before Every Pull Request
- [ ] Branch is up to date with main
- [ ] Description explains the changes
- [ ] Tests pass and code is reviewed

### Regular Maintenance
- [ ] Delete merged branches weekly
- [ ] Review and close old issues
