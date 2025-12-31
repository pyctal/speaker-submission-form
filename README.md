# HTML Forms

![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Mobile--First_Responsive_Design-blue)

## Description

This project is a responsive speaker submission form for a fictional conference, built to master the fundamentals of collecting user input on the web.

Following the tutorial from _Interneting Is Hard_, this project focuses exclusively on the frontend implementation of HTML forms. It demonstrates how to style tricky form elements, handle various input types (text, email, radio, select, etc.), and implement a mobile-first layout that adapts to desktop screens using media queries.

## Features

- **Semantic Form Structure:** Utilizes semantic elements like `<form>`, `<fieldset>`, `<legend>`, and `<label>` to create an accessible and logical document structure.

- **Various Input Types:** Implements a wide range of form controls:

  - **Text & Email Inputs:** Includes validation styling for email addresses using the `type='email'` attribute.
  - **Radio Buttons:** Groups related options ("Type of Talk") using fieldsets and legends.
  - **Dropdown Menus:** Uses `<select>` and `<option>` elements for selecting T-shirt sizes.
  - **Textareas:** Captures multi-line text input for the talk abstract, with resize disabled for better layout control.
  - **Checkboxes:** Features a single-choice checkbox for availability confirmation.

- **Responsive Design:** Built with a "mobile-first" approach. The base styles serve mobile devices, while a media query (`min-width: 700px`) adjusts the layout for desktop screens, switching from a column-based flex layout to a row-based one.

- **Advanced CSS Selectors:** Uses attribute selectors (e.g., `input[type='text']`) and pseudo-classes (`:invalid`, `:focus`, `:hover`) to target specific form states and types without relying entirely on classes.

## Skills Demonstrated

By completing this project, I have demonstrated proficiency in the following areas:

### 1. Form Architecture

- **Frontend-Backend Connection:** Understood the role of the `action` and `method` attributes in sending data to a server (using `GET` to inspect URL parameters).
- **Input Association:** Correctly linked `<label>` elements to their corresponding inputs using the `for` and `id` attributes to ensure accessibility.

### 2. Advanced CSS Styling

- **Attribute Selection:** Used CSS attribute selectors to style specific input types differently (e.g., differentiating text fields from radio buttons).
- **State-Based Styling:** Applied styles based on user interaction, such as `:invalid` for incorrect email formats and `:focus` for the active field.
- **Legacy Fallbacks:** utilized floats to layout elements that are notoriously difficult to style, like radio buttons and fieldsets, where Flexbox support is inconsistent.

### 3. Responsive Layouts

- **Flexbox for Forms:** Used Flexbox to organize form rows, switching `flex-direction` from `column` (mobile) to `row` (desktop) to optimize space.
- **Media Queries:** Implemented `min-width` media queries to progressively enhance the layout for larger screens.
