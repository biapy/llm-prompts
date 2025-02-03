# Copilot Instructions for Expert Prompt Engineer

## Purpose

To help developers create clear, effective, and maintainable prompts
for GitHub Copilot that produce optimal results.

## Guidelines

1. **Simple**: Ensure the prompt is easy to understand and straightforward.
   Example: "Create a function to validate email addresses"
2. **Specific**: Be clear and precise about what is required.
   Example: "Generate a TypeScript function that validates email addresses using RFC 5322 standards"
3. **Short**: Keep the prompt brief and to the point.
   Example: Instead of combining multiple tasks, break them down
4. **Contextual**: Provide relevant context for the task.
   Example: "Given a REST API endpoint that receives user data..."
5. **Actionable**: Frame prompts to drive specific outcomes.
   Example: "Write a function that..." instead of "Can you maybe..."

## Best Practices

- Use clear and action-oriented language
- Break complex tasks into smaller steps
- Include expected input/output formats
- Specify programming language when relevant
- Use consistent terminology
- Include error handling requirements

## Structure

1. Task Description

   - Clear objective
   - Scope definition
   - Expected behavior

2. Required Input

   - Data types
   - Format
   - Constraints

3. Expected Output

   - Return values
   - Side effects
   - Error states

4. Constraints/Requirements

   - Performance criteria
   - Memory limits
   - Coding standards

5. Success Criteria
   - Test cases
   - Edge cases
   - Error conditions

## Response Quality

- Verify output matches requirements
- Check code style consistency
- Ensure proper error handling
- Validate edge cases
- Review performance implications

## Common Pitfalls

- Vague or ambiguous requirements
- Missing error handling specifications
- Unclear input/output formats
- Incomplete context
- Over-complicated prompts

## Version Control

- Document prompt versions
- Track successful variations
- Note context dependencies
- Record edge cases
- Keep prompt history

## Testing Prompts

- Verify prompt produces consistent results
- Test edge cases and limitations
- Validate against different scenarios
- Iterate based on results

## Examples

Good prompt:

```md
Generate a function that sorts an array of numbers in ascending order.

- Input: `number[]`
- Output: `number[]`
- Language: TypeScript

Include input validation and error handling.
```

Bad prompt:

```md
Make something that sorts numbers
```

Good prompt:

```md
Generate a TypeScript function that validates user input:

Input:

- username: string (3-20 chars, alphanumeric)
- email: string (valid email format)
- age: number (18-120)

Output:

- boolean
- Error message for invalid input

Requirements:

- Use type safety
- Include unit tests
- Handle edge cases
- Follow SOLID principles
```

Bad prompt:

```md
Check if user data is ok
```

Good prompt:

```md
Create an async function to fetch and cache API data:

Input:

- endpoint: string
- cacheTime: number (minutes)

Output:

- Promise<Data>
- Cached response if available
- Error handling for network issues

Language: TypeScript
Use: axios, node-cache
```

Bad prompt:

```md
Get API data with caching
```
