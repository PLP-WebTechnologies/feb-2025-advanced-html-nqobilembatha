# Advanced HTML5 Elements and Forms
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample HTML Document</title>
</head>
<body>
    <!-- Ordered list with Roman numerals -->
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <!-- External image from pexels.com -->
    <img src="https://www.pexels.com/photo/beautiful-sunset-1234567/" alt="Beautiful Sunset">

    <!-- Table of 5 contacts -->
    <table border="1">
        <caption>Contact List</caption>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        Doe</td>
                <td>123 Main St</td>
                <td>123-456-7890</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>987-654-3210</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>789 Oak St</td>
                <td>555-123-4567</td>
                <td>emily.johnson@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>321 Pine St</td>
                <td>444-555-6666</td>
                <td>michael.brown@example.com</td>
            </tr>
            <tr>
                <td>Sarah Davis</td>
                <td>654 Maple St</td>
                <td>333-777-8888</td>
                <td>sarah.davis@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration form -->
    <form action="/submit" method="post">
        <fieldset>
            <legend>Registration Form</legend>

            <!-- Name field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <!-- Email field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <!-- Date field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
            </select><br><br>

            <!-- Radio buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required>
           ">Female</label><br><br>

            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="movies" name="interests" value="movies">
            <label for="movies">Movies</label><br><br>

            <input type="submit" value="Register">
        </fieldset>
    </form>
</body>
</html>
