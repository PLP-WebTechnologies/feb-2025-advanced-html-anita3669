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
    <title>Index Page</title>
</head>
<body>
    <!-- Ordered list with Roman numerals -->
    <h1>Roman Numerals List</h1>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>

    <!-- External image from pexels -->
    <h1>External Image</h1>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Pexels Image" width="500">

    <!-- Table of contacts -->
    <h1>Contacts</h1>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John okode</td>
            <td>123 lubao</td>
            <td>0724376459</td>
            <td>johnokode@gmail.com</td>
        </tr>
        <tr>
            <td>Sharon masinza</td>
            <td>456 langas</td>
            <td>0706868724</td>
            <td>sharonmasinza@gmail.com</td>
        </tr>
        <tr>
            <td>Pricilla shilaho</td>
            <td>789 mukumu</td>
            <td>0724222171</td>
            <td>pricillashilaho@gmail.com</td>
        </tr>
        <tr>
            <td>Anita kasiti</td>
            <td>321 Ruiru</td>
            <td>0113128837</td>
            <td>anitakasiti@gmail.com</td>
        </tr>
        <tr>
            <td>Velma Musavi</td>
            <td>345 githurai</td>
            <td>0714582021</td>
            <td>velmamusavi@gmail.com</td>
        </tr>
    </table>

   <!-- Registration form -->
    <h1>Registration Form</h1>
    <form action="/submit" method="POST">
        <!-- Name field -->
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

        <!-- Email field -->
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password field -->
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Enter a strong password" required><br><br>

        <!-- Date field -->
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown field -->
        <label for="country">Country:</label><br>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="kenya">Kenya</option>
            <option value"nigeria">Nigeria</option>
            <option value="south africa">South africa</option>
            <option value="canada">Canada</option>
            <option value="australia">Australia</option>
        </select><br><br>

        <!-- Radio buttons -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br>
        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label><br>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label><br>
        <input type="checkbox" id="travel" name="interests" value="travel">
        <label for="travel">Travel</label><br><br>

        <!-- Submit button -->
        <button type="submit">Register</button>
    </form>
</body>
</html>
