# STUDENTFORM
# Student Enrollment Form

## Overview

This project is a simple HTML-based student enrollment form. It allows users to enter student details such as Roll Number, Name, Class, Birth Date, Address, and Enrollment Date. The form interacts with a backend database to save, update, and reset student records. It also ensures that the Roll Number is unique and acts as the primary key.

## Features

- **Form Validation**: Ensures all fields are filled before submission.
- **Database Interaction**: Saves and updates student records in a JSON-based database.
- **Roll Number Check**: Verifies if the Roll Number already exists in the database.
- **Dynamic Form Update**: Displays existing data if Roll Number exists, and allows updates.
- **Button Functionality**: Includes Save, Update, and Reset buttons with appropriate functionality.
- **Initial State**: On page load, the form is empty with only the Roll Number field enabled.

## Getting Started

### Prerequisites

- Web browser
- Internet connection (for accessing external libraries and services)

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/student-form.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd student-form
    ```
3. **Open the HTML File**: Open `index.html` in your preferred web browser.

## Usage

1. **Enter Roll Number**: Input a Roll Number and click outside the field to check if it already exists in the database.
2. **Fill Out Form**: Enter student details and click "Save" to add a new record.
3. **Update Existing Record**: If the Roll Number exists, the form will populate with existing data. You can update the details and click "Update."
4. **Reset Form**: Click "Reset" to clear the form and re-enable the Roll Number field.

## Code Structure

- `index.html`: The main HTML file containing the form and script.
- `README.md`: This file, providing an overview and instructions.

## Contributions

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue in the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Bootstrap](https://getbootstrap.com) for the styling.
- [jQuery](https://jquery.com) for simplifying JavaScript operations.

