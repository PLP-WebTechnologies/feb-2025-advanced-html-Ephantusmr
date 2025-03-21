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
    <title>Ephy Collecttion</title>
</head>
<body>
    <h1>Welcome to Ephy Collection</h1>
    <p>Your one-stop shop for clothes and jewelry!</p>

    <!-- Ordered List -->
    <h2>Roman Numerals List</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
    </ol>

    <!-- External Image -->
    <h2>Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Beautiful Jewelry Display" width="500">

    <!-- Contact Table -->
    <h2>Contact Information</h2>
    <table>
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
                <td>Nakuru, City</td>
                <td>0712345678</td>
                <td>johnte@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>Kenyatta Rd, JujaTown</td>
                <td>071654321</td>
                <td>jayh@gmail.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>Nairobi</td>
                <td>011234455</td>
                <td>mitch@gmail.com</td>
            </tr>
            <tr>
                <td>Susan Brown</td>
                <td>101 Main St, Town</td>
                <td>077889900</td>
                <td>susan@example.com</td>
            </tr>
            <tr>
                <td>Emma Davis</td>
                <td>202 Suburb Ln, Village</td>
                <td>075667788</td>
                <td>emma@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="POST">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <!-- Dropdown -->
        <label for="category">Category:</label>
        <select id="category" name="category" required>
            <option value="">Select your category</option>
            <option value="clothes">Clothes</option>
            <option value="jewelry">Jewelry</option>
            <option value="accessories">Accessories</option>
        </select>

        <!-- Radio Buttons -->
        <label>Preference:</label>
        <input type="radio" id="clothes" name="preference" value="clothes" required>
        <label for="clothes">Clothes</label>
        <input type="radio" id="jewelry" name="preference" value="jewelry" required>
        <label for="jewelry">Jewelry</label>

        <!-- Checkboxes -->
        <label>Interested in:</label>
        <input type="checkbox" id="discounts" name="interests" value="discounts">
        <label for="discounts">Discounts</label>
        <input type="checkbox" id="new-arrivals" name="interests" value="new-arrivals">
        <label for="new-arrivals">New Arrivals</label>
        <input type="checkbox" id="sales" name="interests" value="sales">
        <label for="sales">Sales</label>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
    
</body>
</html>
