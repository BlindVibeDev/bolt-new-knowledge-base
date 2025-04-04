# Bolt.new Best Practices

## Prompt Engineering

### Be Specific About Your Stack

- **Specify Frameworks**: Always mention specific frameworks or libraries you want to use (React, Next.js, Tailwind, etc.)
- **Example**: Instead of "Create a blog" use "Create a blog using Next.js, Tailwind CSS, and Supabase for the database"
- **Prioritize**: List the most important technologies first

### Detail Your Requirements

- **Feature Specificity**: Clearly describe the features you need
- **Data Structure**: Outline your data model when applicable
- **User Flows**: Describe key user journines through your application
- **Examples**: Provide examples of similar applications or references

### Use the Enhance Prompt Feature

- Click the enhance icon before submitting your prompt
- Review and edit the enhanced prompt for accuracy
- Add any additional details the enhancement missed

## Development Workflow

### Start Simple, Then Iterate

1. **Basic Scaffold First**: Begin with a minimal working version
2. **Verify Foundation**: Ensure the basic application works
3. **Add Features Incrementally**: Build complexity gradually
4. **Test Each Addition**: Verify each new feature before adding more

### Batch Related Instructions

- Combine related changes into a single prompt to save tokens
- Example: "Update the color scheme to dark mode, add mobile responsiveness, and fix the navigation bar"
- Keep batches logically related for best results

### Handle Errors Effectively

- When errors occur, copy the exact error message in your follow-up
- Ask for specific solutions rather than general debugging
- Let Bolt troubleshoot one issue at a time for complex problems

## Token Optimization

### Minimize Context Switching

- Complete one component or feature before moving to another
- Avoid jumping between unrelated parts of your application
- Build in logical sequences to reduce token wastage

### Reuse Generated Code

- For similar components, ask Bolt to adapt existing code
- Reference previous parts of the conversation
- Example: "Create a similar card component to the one we made earlier, but for user profiles"

### Control Project Scope

- Start with a Minimum Viable Product (MVP)
- Add complexity only after core functionality works
- For large projects, consider breaking into multiple sessions

## Framework-Specific Best Practices

### React/Next.js

- Start with component structure and data flow
- Define state management approach early
- Consider server-side rendering needs upfront

### Backend Development

- Define API endpoints clearly
- Specify authentication requirements early
- Detail data validation rules

### Database Integration

- Provide entity relationship diagrams when possible
- Define schema clearly with field types
- Specify indexing requirements for performance

## Deployment Best Practices

### Pre-Deployment Checklist

- Verify all core functionality works
- Check for environment variables and configuration
- Consider SEO and metadata for production sites

### Netlify Deployment

- Ensure build commands are correctly configured
- Check for proper environment variable setup
- Consider using Netlify specific features (Functions, Forms, etc.)

## Troubleshooting Tips

### When Bolt Gets Stuck

- Refresh the page and start a new session
- Break down complex requests into simpler steps
- Provide more context or examples

### Handling Large Codebases

- Focus on one area of the application at a time
- Use specific file references in your prompts
- Ask for architecture decisions before implementation details

## Security Considerations

### API Keys and Secrets

- Never hardcode sensitive information
- Use environment variables for all secrets
- Consider using .env files for local development

### Authentication Implementation

- Specify security requirements clearly
- Consider using established auth providers
- Verify proper implementation of auth flows

## Performance Optimization

### Code Efficiency

- Request code reviews and optimization passes
- Specify performance concerns upfront
- Ask for specific optimizations for bottlenecks

### Asset Optimization

- Request proper image optimization
- Consider lazy loading for media-heavy sites
- Implement code splitting for larger applications

## Collaboration Best Practices

### Sharing Projects

- Use the share link feature to collaborate with others
- Provide context when sharing for better collaboration
- Consider version management for collaborative projects

### Documentation

- Ask Bolt to generate documentation for complex features
- Request inline code comments for maintainability
- Consider generating a README for the project