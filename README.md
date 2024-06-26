**What is Testing?**

Testing is the process of evaluating a system or its component(s) with the intent to find whether it satisfies the specified requirements or not. Testing is executing a system in order to identify any gaps, errors, or missing requirements in contrary to the actual requirements.

**Why Testing?**

- Testing is important because software bugs could be expensive or even dangerous. Software bugs can potentially cause monetary and human loss.
- Testing is important because software needs to be reliable. It should work correctly the first time and every time.
- Testing is important because customers expect software to be reliable. Customers expect software to be reliable and secure. If the software does not work correctly, customers will not want to use it.

**What is Automation Testing?**

Automation testing is a Software testing technique to test and compare the actual outcome with the expected outcome. This can be achieved by writing test scripts or using any automation testing tool. Test automation is used to automate repetitive tasks and other testing tasks which are difficult to perform manually.

**Why Automation Testing?**

- Automation testing is very useful in the long run for testing the software applications. It is very helpful in the regression testing.
- Automation testing is very fast and it is very effective in testing the software applications.
- Automation testing is very reliable and it is very helpful in testing the software applications.

**Requirements for Testing React Applications**

- Node.js
- npm
- React
- Jest
- Enzyme

**How to Test React Applications?**

- Testing React Components
- Testing React Hooks
- Testing React Redux
- Testing React Router
- Testing React Forms
- Testing React Events
- Testing React Lifecycle
- Testing React Performance
- Testing React Security

**How to Test React Components?**

- Testing React Components with Jest
- Testing React Components with Enzyme
- Testing React Components with React Testing Library

**Testing Components**

- How they render
- How they respond to user interactions

> "Write test that are maintainable, readable, rbooust and trustworthy."

> "Having no test is better than having bad tests."

> "Test the behavior, not the implementation."

**Testing Pyramid**

- Unit Testing
- Integration Testing
- End-to-End Testing

The Testing Pyramid is a concept that helps you to balance your test suite. The pyramid is divided into three layers: the bottom layer represents unit tests, the middle layer represents integration tests, and the top layer represents end-to-end tests. The pyramid is a way of thinking about how different kinds of automated tests should be used to create a balanced portfolio.

**Unit Testing**

- A unit test is a test that verifies the behavior of a single unit of code. A unit of code is the smallest piece of code that can be logically isolated in a system. In object-oriented programming, a unit of code is often a method. In functional programming, a unit of code is often a function. In procedural programming, a unit of code is often a procedure or function.

**Integration Testing**

- Integration testing is a type of testing that tests the integration between two or more units of code. Integration testing is a type of testing that tests the integration between two or more units of code. Integration testing is a type of testing that tests the integration between two or more units of code. Integration testing is a type of testing that tests the integration between two or more units of code.

**End-to-End Testing**

- End-to-end testing is a type of testing that tests the entire system from end to end. End-to-end testing is a type of testing that tests the entire system from end to end. End-to-end testing is a type of testing that tests the entire system from end to end. End-to-end testing is a type of testing that tests the entire system from end to end.

# React Testing Library

The React Testing Library is a very light-weight solution for testing React components. It provides light utility functions on top of react-dom and react-dom/test-utils, in a way that encourages better testing practices. Its primary guiding principle is:

> The more your tests resemble the way your software is used, the more confidence they can give you.

**Installation**

```bash
npm install --save-dev @testing-library/react
```

**Usage**

```javascript
import { render, screen } from '@testing-library/react';
import App from './App';

test('renders learn react link', () => {
  render(<App />);
  const linkElement = screen.getByText(/learn react/i);
  expect(linkElement).toBeInTheDocument();
});
```

The `render` function is used to render a React component. The `screen` object is used to query the rendered component. The `getByText` function is used to query the rendered component by text content. The `toBeInTheDocument` function is used to check if the element is in the document.

**Queries**

Queries are used to query the rendered component. The following queries are available:

To extend the queries available in the vitest library, you can use the `@testing-library/jest-dom` library.

```bash
npm install --save-dev @testing-library/jest-dom
```

```javascript
import '@testing-library/jest-dom/vitest';
```

- getByLabelText
- getByPlaceholderText
- getByText
- getByDisplayValue

# queryByRole vs getByRole

The `queryByRole` function is used to query the rendered component by role. The `getByRole` function is used to query the rendered component by role. The `queryByRole` function returns null if the element is not found. The `getByRole` function throws an error if the element is not found.

# queryByLabelText vs getByLabelText

The `queryByLabelText` function is used to query the rendered component by label text. The `getByLabelText` function is used to query the rendered component by label text. The `queryByLabelText` function returns null if the element is not found. The `getByLabelText` function throws an error if the element is not found.
