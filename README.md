# Task 1 - Basic Flutter Application

## Overview

This Flutter application provides a straightforward login flow followed by page navigation. It was built specifically to fulfill a demonstration of basic UI creation, user input forms, input validation, and inter-page navigation.

## Deliverables Met

- **Basic UI:** Includes a Login Screen constructed with `Container`, `Column`, and `Row` widgets.
- **Input Fields:** Contains two `TextFormField` widgets for collecting the user's `Email` and `Password`.
- **Button Elements:** Accommodates a "Forgot Password?" Text widget as well as a Login action element (implemented with `TextButton` substituting the deprecated `FlatButton`).
- **Screen Navigation:** Effectively connects the successful Login workflow to the app's secondary view (`HomeScreen`) applying `Navigator.push()`.
- **Form Validation:** Validates that the submitted email string adheres to a general regex format. Additionally, ensures the password property restricts empty submissions.

## Launch

1. Obtain flutter dependencies, navigate to this project, and execute:

   ```bash
   flutter pub get
   ```

2. Start the project

   ```bash
   flutter run
   ```
