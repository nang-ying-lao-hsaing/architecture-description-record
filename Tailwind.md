# Tailwind

## Context
Currently, our project uses  CSS framework for styling our user interface. While it has served us well, we are looking for ways to improve our development workflow and maintain a consistent UI across the application.
Tailwind CSS is a utility-first framework that provides a collection of low-level utility classes for building responsive layouts and components. It promotes a composable approach to styling, allowing developers to combine classes to achieve the desired design.


## Decision 1
We propose adopting Tailwind CSS as the primary CSS framework for our project. This decision is based on the following benefits:
Improved development efficiency: Tailwind's utility classes eliminate the need for writing and maintaining large CSS files, leading to faster development and iteration cycles.
Enforced consistency: By relying on a single source of truth for styles, Tailwind helps maintain a consistent look and feel across the application.
Responsiveness by default: Tailwind's utility classes are responsive by default, making it easier to build responsive layouts and components.
Reduced bundle size: Tailwind allows you to only include the classes you use in your application, resulting in a smaller CSS bundle size.


## Rationale


## Consequences
Pros – What becomes easier?
Cons – What becomes more difficult?

## Sample code
<div class="flex justify-center items-center h-screen bg-gray-100">
  <div class="bg-white p-4 rounded shadow-md">
    <h1 class="text-2xl font-bold text-gray-800">Hello world!</h1>
    <p class="text-gray-600">This is a basic example using Tailwind CSS classes.</p>
  </div>
</div>


