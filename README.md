# Robot Control Panel

This project is a web-based control panel for managing the movement of a robot. The control panel allows the user to send commands to move the robot in different directions (forward, backward, left, right) and to stop it. The commands are stored in a phpMyAdmin database.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Design Notes](#design-notes)

## Installation

![image](https://github.com/user-attachments/assets/0d5501f0-2ba3-495a-a3e5-21efd622a0a7)


## Usage

- Open the control panel in your browser.
- Use the buttons to send commands to the robot. The available commands are Forward, Backward, Left, Right, and Stop.
- The commands are stored in the phpMyAdmin database and can be viewed in phpMyAdmin or any other MySQL client.

## Code Explanation

### HTML & CSS

- The HTML structure is located in the `indexre.php` file.
- The CSS is embedded in the HTML file within a `<style>` tag to provide the styling for the control panel.

### PHP

- The PHP code in `process.php` handles the form submission and inserts the commands into the phpMyAdmin database.

### Database

- A phpMyAdmin database named `commands` is used to store the direction commands sent from the control panel.

![image](https://github.com/user-attachments/assets/4d9497aa-348d-40f6-aa92-3196101efc58)


## Design Notes

- The initial design idea was inspired by a video demonstrating a user interface. The video design was extracted and converted into JavaScript code, but it didn't work as expected.

![image](https://github.com/user-attachments/assets/b7dd58ca-9bca-48fa-ba6d-2756cd70b581)

- Therefore, the design was modified to the current version, as shown in the screenshot above.
- The control panel features a simple and intuitive design, with clearly labeled buttons for each direction and stop command.

## Video Demonstration

A video demonstration of the initial design and the final working version is available:

https://github.com/user-attachments/assets/23abb4c6-0c36-4609-932c-ce5f7316eede

---

This project provides a simple and effective way to control a robot's movement through a web interface, storing each command in a phpMyAdmin database for tracking and analysis.
