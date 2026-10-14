# Bootstrap Interview Questions and Answers

A beginner-friendly set of common Bootstrap interview questions with concise answers.
The breakpoint values below are Bootstrap 5 defaults.

## Fundamentals

### 1. What is Bootstrap?

Bootstrap is a free, open-source front-end toolkit for building responsive,
mobile-first websites. It provides CSS, JavaScript plugins, layout tools, and
ready-made interface components.

### 2. What are the main features of Bootstrap?

- A mobile-first responsive design system
- A 12-column grid
- Prebuilt components such as buttons, cards, and navbars
- Utility classes for common styling and layout needs
- Consistent form styles
- JavaScript plugins for interactive components

### 3. What is the difference between Bootstrap and CSS?

CSS is the language used to style web pages. Bootstrap is a front-end toolkit
built on CSS (and JavaScript for interactive behavior) that provides reusable
styles, layout conventions, utilities, and components. You can also write
custom CSS alongside Bootstrap.

### 4. What is a container in Bootstrap?

A container is a layout wrapper that centers and horizontally pads its content.
It can also constrain content to a maximum width at different screen sizes.

### 5. What is the difference between `.container` and `.container-fluid`?

`.container` has a responsive maximum width that changes at Bootstrap's
breakpoints. `.container-fluid` spans the full available width at every
breakpoint.

## Grid and responsive design

### 6. What is the Bootstrap grid system?

The grid is a responsive layout system for arranging content in rows and
columns. It is based on a 12-column layout and uses breakpoints to adjust the
layout for different screen sizes.

### 7. What is the difference between `.row` and `.col`?

`.row` groups columns horizontally and manages the gutters between them.
`.col` (or a responsive column class such as `.col-md-6`) defines a column
within a row.

### 8. What does `.col-md-6` mean?

It makes an element span 6 of the grid's 12 columns (half the row) at the
medium breakpoint and above. Below that breakpoint, the column typically
stacks at full width unless other column classes are applied.

### 9. What are responsive classes in Bootstrap?

Responsive classes apply layout or styling at specified breakpoints. For
example, `.col-md-6` changes a column's width at the medium breakpoint and
continues to apply at larger breakpoints unless overridden.

### 10. What are Bootstrap's default responsive breakpoints?

In Bootstrap 5, the default breakpoints are `sm` at 576px, `md` at 768px,
`lg` at 992px, `xl` at 1200px, and `xxl` at 1400px. The extra-small (`xs`)
range is below 576px and is the default when no breakpoint infix is specified.

| Breakpoint | Minimum width |
| --- | ---: |
| `xs` (default) | Below 576px |
| `sm` | 576px |
| `md` | 768px |
| `lg` | 992px |
| `xl` | 1200px |
| `xxl` | 1400px |

### 11. How do you make an image responsive in Bootstrap?

Add the `.img-fluid` class to the image. It applies a maximum width of 100% and
an automatic height so the image scales with its parent while preserving its
aspect ratio.

## Components

### 12. What are Bootstrap components?

Components are reusable interface elements provided by Bootstrap, such as
buttons, cards, navbars, alerts, dropdowns, and modals.

### 13. What is a Bootstrap navbar?

A navbar is a responsive navigation component used to display a site's brand,
navigation links, and menus. It can be expanded or collapsed at chosen
breakpoints.

### 14. What is a Bootstrap card?

A card is a flexible content container that can combine text, images, titles,
links, and buttons in a consistent layout.

### 15. What is a Bootstrap modal?

A modal is a dialog displayed above the current page. It is commonly used for
forms, confirmations, or additional information and requires Bootstrap's
JavaScript behavior to open and close.

## Utilities and forms

### 16. What are Bootstrap utility classes?

Utility classes apply a specific style directly in markup, often without
writing custom CSS. Examples include `.text-center` for text alignment,
`.d-flex` for flex display, `.m-3` for margin, and `.p-2` for padding.

### 17. What is the difference between margin and padding?

Margin creates space outside an element's border. Padding creates space
between the element's content and its border.

### 18. What is the difference between `.form-control` and `.form-select`?

`.form-control` styles text-based form controls such as inputs and textareas.
`.form-select` styles select dropdowns.

### 19. What is Bootstrap form validation?

Bootstrap provides styles for displaying valid and invalid form controls, often
used with HTML validation attributes or JavaScript. These styles do not
validate submitted data on their own: the server must independently validate
all submitted data.

## JavaScript and behavior

### 20. Do all Bootstrap components require JavaScript?

No. Layout, cards, and most utility classes work with CSS alone. Interactive
components such as modals, dropdowns, and collapsible navbars require Bootstrap
JavaScript. In Bootstrap 5, these plugins do not require jQuery; include the
Bootstrap JavaScript bundle and use the component's documented data attributes
or JavaScript API.