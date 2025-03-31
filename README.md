# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Advanced Elements and Forms</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/beautiful-sunset-over-sea-1028598/" alt="Sunset over the sea" width="600">

    <!-- Table of Contacts -->
    <h2>Contact Information</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>1234 Elm Street</td>
                <td>(555) 123-4567</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>5678 Oak Avenue</td>
                <td>(555) 234-5678</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>91011 Pine Blvd</td>
                <td>(555) 345-6789</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>1213 Maple Rd</td>
                <td>(555) 456-7890</td>
                <td>michael@example.com</td>
            </tr>
            <tr>
                <td>Sarah White</td>
                <td>1415 Birch Drive</td>
                <td>(555) 567-8901</td>
                <td>sarah@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="submit_form.php" method="POST">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <!-- Date of Birth Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="usa">USA</option>
            <option value="canada">Canada</option>
            <option value="uk">UK</option>
            <option value="australia">Australia</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label
