# Contributing to Phy-Coach 🤝

Thank you for wanting to contribute! We welcome all contributions from students and developers.

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button on GitHub to create your own copy.

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/Phy-coach.git
cd Phy-coach
```

### 3. Create a Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

### 4. Make Your Changes
- Edit files in the `src/` directory
- Follow the code style of the project
- Add comments for complex logic
- Test your changes locally

### 5. Commit Your Changes
```bash
git add .
git commit -m "Add: Descriptive message about your changes"
```

**Commit message format:**
- `Add:` - New features
- `Fix:` - Bug fixes
- `Docs:` - Documentation updates
- `Style:` - Code style changes
- `Refactor:` - Code refactoring
- `Test:` - Test additions/changes

### 6. Push to Your Fork
```bash
git push origin feature/your-feature-name
```

### 7. Open a Pull Request
1. Go to the original repository
2. Click "New Pull Request"
3. Select your branch
4. Fill in the PR template
5. Submit!

## PR Guidelines

### Before Submitting
- ✅ Code works locally
- ✅ No console errors
- ✅ Follows code style
- ✅ Updated documentation if needed
- ✅ Tests pass (if applicable)
- ✅ Accessibility considered

### PR Description Should Include
- What does this change do?
- Why is it needed?
- How to test it
- Any breaking changes?
- Screenshots (if UI changes)

### Example PR Title
```
Add: New exercise database schema
Fix: Button accessibility issue
Docs: Update installation guide
```

## Code Style Guidelines

### Python
```python
# Use meaningful variable names
# Keep functions small and focused
# Add docstrings
def calculate_bmi(weight, height):
    """Calculate Body Mass Index"""
    return weight / (height ** 2)
```

### JavaScript
```javascript
// Use camelCase for variables
// Use PascalCase for components
// Add comments for complex logic
const getUserProfile = () => {
  // Fetch user data
};
```

### CSS
```css
/* Use kebab-case for class names */
.button-primary {
  padding: 10px 20px;
  /* Comment complex rules */
}
```

## Accessibility Requirements

All contributions should consider:
- ♿ Keyboard navigation
- 🔊 Screen reader support
- 🎨 Color contrast (WCAG AA minimum)
- 📱 Mobile responsiveness
- 🏷️ Proper semantic HTML

## Testing

### Run Tests
```bash
pytest                 # Python
npm test              # Node.js
```

### Add Tests for Your Changes
- Unit tests for functions
- Component tests for UI
- Integration tests if applicable

## Documentation

### Update These if Needed
- README.md - If changing project overview
- docs/getting-started.md - If changing setup
- docs/architecture.md - If changing structure
- Code comments - Always!

## Commit Best Practices

✅ **Good:**
```bash
git commit -m "Add: Exercise form validation"
git commit -m "Fix: Progress tracker calculation error"
git commit -m "Docs: Update installation steps"
```

❌ **Avoid:**
```bash
git commit -m "fixes"
git commit -m "changed stuff"
git commit -m "asdf"
```

## Common Issues

### "My changes aren't showing"
1. Hard refresh browser (Ctrl+Shift+R)
2. Restart dev server
3. Check for console errors

### "Git says I have conflicts"
1. Pull latest from main: `git pull origin main`
2. Resolve conflicts in your editor
3. Commit: `git commit -m "Resolve merge conflicts"`
4. Push again

### "My PR has been rejected"
- Read the feedback carefully
- Ask questions in comments
- Make requested changes
- Push updates (no need to reopen)

## Getting Help

- 📖 Read docs/getting-started.md
- ❓ Check docs/faq.md
- 🐛 Search existing Issues
- 💬 Open a Discussion
- 📞 Comment on related Issues

## Types of Contributions Welcome

### Code
- New features
- Bug fixes
- Performance improvements
- Refactoring

### Documentation
- README updates
- Tutorial improvements
- FAQ additions
- Architecture explanations

### Design
- UI improvements
- Accessibility enhancements
- Responsive design fixes
- Styling tweaks

### Content
- New exercises
- New lessons
- Example scenarios
- Student testimonials

### Testing
- Test coverage
- Bug reports
- Performance testing
- Accessibility audits

## First Time Contributing?

Don't worry! Here are some easy ways to start:
1. Look for issues labeled "good first issue"
2. Fix typos in documentation
3. Improve README or docs
4. Add code comments
5. Write tests

## Community Standards

We follow a Code of Conduct. Be respectful and inclusive:
- ✅ Be kind and supportive
- ✅ Welcome diverse perspectives
- ✅ Provide constructive feedback
- ❌ No discrimination or harassment
- ❌ No spam or self-promotion

## Questions?

- Open a GitHub Issue
- Start a Discussion
- Comment on relevant PRs
- Ask in code review

---

**Thank you for contributing to Phy-Coach! Together we're making fitness education accessible to everyone! 🚀**
