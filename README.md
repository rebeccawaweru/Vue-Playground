# client-personal-portfolio

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


VUE BEST PRACTICES<br>
Component-based architecture. Break down your application into small, reusable components. This promotes maintainability, readability, and testability.

Single-file components. Use .vue files to encapsulate the template, script, and styles for each component. This keeps your code organized and easy to understand.

Naming conventions. Adopt a consistent naming convention for components, such as PascalCase or kebab-case. This makes it easier to identify and reference components in your project.

Props validation. Define and validate props for components to ensure correct data types and values are passed. This helps catch errors early and improves code readability.

Computed properties. Use computed properties instead of methods for calculations that depend on reactive data. Computed properties are cached and only re-evaluated when their dependencies change, improving performance.

Watchers. Use watchers sparingly and only when necessary. Prefer computed properties or methods for reacting to data changes.

Event handling. Use Vue’s built-in event handling system (v-on or @) instead of directly manipulating the DOM. This ensures your code is more maintainable and less prone to errors.

Scoped CSS. Scope your component styles using the scoped attribute in the style tag. This prevents styles from leaking to other components and ensures proper encapsulation.

Vuex for state management. Use Vuex to manage your application’s state when dealing with complex data flows or shared state between components. This centralizes state management and makes your code more predictable and maintainable.

Testing. Write unit tests for your components and end-to-end tests for your application. This ensures the stability of your code and helps catch errors early.



COMMON PITFALLS TO AVOID IN VUE <br>
Overusing v-if and v-for. Avoid using v-if and v-for on the same element, as it can lead to performance issues. Instead, use computed properties to filter the list before rendering.

Directly modifying props. Never modify a prop directly within a child component. Instead, emit an event to the parent component to update the prop.

Not using key attribute with v-for. Always use the key attribute with v-for to help Vue track the identity of each node. This improves performance and prevents unexpected behavior.

Overusing global mixins. Use global mixins sparingly, as they can introduce unintended side effects and make your code harder to understand. Prefer local mixins or utility functions.

Overusing $refs. Avoid using $refs to manipulate child components directly. Instead, use props and events to communicate between components.

Not optimizing for production. Ensure you build your application for production using Vue’s build tools. This minimizes the bundle size and optimizes the application for better performance.

Ignoring accessibility. Pay attention to accessibility best practices, such as using semantic HTML, ARIA attributes, and keyboard navigation. This ensures your application is usable by a wider audience.
