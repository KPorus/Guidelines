# Convention Guidelines for Website Development

## 1. Folder Structure
- Organize folders based on features or modules.
- Keep a clear separation between components, pages, styles, utilities, and data fetching logic.
- Group related files together within their respective folders.
- Separate files for web mobile version and web browser version.
- Store common files in a separate folder to promote reuse and maintainability.
- Store Data fetching files in a separate folder

## 2. CSS
- Utilize a CSS preprocessor like SCSS for easier maintenance and organization.
- Follow a consistent naming convention for classes, such as BEM (Block Element Modifier).
- Use utility classes where appropriate to avoid bloating your CSS with repetitive styles.
- Be mindful of unnecessary CSS to optimize performance.
- Ensure to use the latest version of Tailwind CSS (v3) for modern utility-first styling.

## 3. Data Fetching
- Use server-side rendering (SSR) or static site generation (SSG) for optimal SEO and performance.
- Prefer server-side data fetching using methods in Next.js.

## 4. TypeScript
- Utilize TypeScript for static type checking and improved code quality.
- Define interfaces for data structures to ensure consistency and type safety.
- Leverage TypeScript's features such as enums, union types, and generics for better type definitions.

## 5. Component Management
- Break down UI components into smaller, reusable components.
- Follow a consistent naming convention for components.
- Use composition and props to pass data and behavior between components.
- Consider using state management libraries like Redux or Recoil for managing complex application state.

## 6. Documentation
- Document code using inline comments for complex logic or non-obvious functionality.
- Write clear and concise README files explaining project structure, installation steps, and how to contribute.
- Utilize tools like Storybook for documenting and showcasing UI components.

## 7. Rendering
- Optimize rendering performance by minimizing unnecessary re-renders.
- Use React's `memo` or PureComponent for optimizing client component rendering.
- Leverage React's context API for passing down global data to deeply nested components without prop drilling.
- Use server-side rendering for constantly changing backend data to ensure up-to-date content.
- Be cautious in using client-side rendering for client action-based interaction or server-side rendering.
- Utilize static site generation for caching pages in memory, but be mindful of the potential impact on performance with a large number of pages.

## 8. Naming Convention
- Follow a consistent naming convention for variables, functions, and states (camelCase, PascalCase, etc.).
- Use descriptive and meaningful names to improve code readability.
- Prefix variables or functions with their context or type to avoid naming collisions.

## 9. Version Maintenance
- Use Node version v18.17 or higher
- Use npm version v10.1.0 or higher

## 10. Type Interface
- Utilize TypeScript's type inference whenever possible.
- Define clear and explicit type interfaces for complex data structures.
- Consider using type aliases for simplifying complex type definitions.
