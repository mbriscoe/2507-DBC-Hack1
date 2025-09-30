# GitHub Copilot Instructions for 2507-DBC-Hack1

## Project Overview
This is a hackathon project (2507-DBC-Hack1) that showcases innovative solutions and creative problem-solving. The project is actively being developed and serves as a demonstration of web development skills.

## Technology Stack
- **HTML5**: Standard markup for web pages
- **CSS3**: Styling with Bootstrap framework
- **Bootstrap 3.3.7**: Primary CSS framework for responsive design
- **Font Awesome 5.15.4**: Icon library
- **jQuery 3.5.1**: JavaScript library for DOM manipulation

## Project Structure
```
2507-DBC-Hack1/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── copilot-instructions.md
├── assets/
│   └── css/
│       └── style.css
├── index.html
└── README.md
```

## Coding Standards

### HTML
- Use semantic HTML5 elements where appropriate
- Maintain proper indentation (4 spaces)
- Include appropriate meta tags for viewport and compatibility
- Use descriptive comments for major sections

### CSS
- Follow Bootstrap conventions for class naming
- Place custom styles in `assets/css/style.css`
- Use responsive design principles
- Maintain consistency with Bootstrap 3.3.7 grid system

### JavaScript
- Use jQuery for DOM manipulation (version 3.5.1 is loaded)
- Follow ES5 syntax for compatibility with older Bootstrap version
- Add comments for complex logic

## File Organization
- Main entry point: `index.html`
- Custom styles: `assets/css/style.css`
- Documentation: `README.md`
- Issue templates: `.github/ISSUE_TEMPLATE/`

## Best Practices
1. **Responsive Design**: Ensure all changes work across mobile, tablet, and desktop
2. **Accessibility**: Include appropriate ARIA labels and semantic HTML
3. **Browser Compatibility**: Test for compatibility with IE11+ (as indicated by meta tag)
4. **CDN Resources**: Continue using CDN links for Bootstrap, Font Awesome, and jQuery
5. **Documentation**: Update README.md when adding new features or changing project structure

## Contributing Guidelines
When making changes:
1. Fork the repository
2. Create a feature branch with descriptive name (e.g., `feature/YourFeature`)
3. Make changes following the coding standards above
4. Commit with clear, descriptive messages (e.g., `'Add feature description'`)
5. Push to your branch
6. Open a Pull Request

## Common Patterns
- Bootstrap 3 uses older class naming (e.g., `col-xs-`, `col-sm-`, `col-md-`, `col-lg-`)
- jQuery is available globally as `$` or `jQuery`
- Font Awesome icons use `<i class="fa fa-icon-name"></i>` or `<i class="fas fa-icon-name"></i>`

## Notes for AI Assistants
- This is a hackathon project, so be open to creative solutions
- The project is actively being developed - new features and structure changes are expected
- Maintain backward compatibility with Bootstrap 3.3.7 and jQuery 3.5.1
- When suggesting new features, consider the hackathon context and innovative solutions
- Always update the README.md to reflect any structural or feature changes
