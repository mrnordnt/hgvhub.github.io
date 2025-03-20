<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Design Template</title>
    <style>
        /* Basic Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        /* Headings */
        h1 { font-size: 2.5rem; color: #333; }
        h2 { font-size: 2rem; color: #444; }
        h3 { font-size: 1.75rem; color: #555; }
        p { font-size: 1rem; line-height: 1.6; }

        /* Navigation */
        nav {
            background-color: #007BFF;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* Table */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #007BFF;
            color: white;
        }

        /* Form */
        form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            width: 50%;
            margin: 20px auto;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #007BFF;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* Card */
        .card {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            width: 60%;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <!-- Headings -->
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <p>This is a sample paragraph demonstrating text styling.</p>

    <!-- Table -->
    <table>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
    </table>

    <!-- Form -->
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter your name">
        
        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email">

        <label for="message">Message:</label>
        <textarea id="message" placeholder="Write something..." rows="4"></textarea>

        <button type="submit">Submit</button>
    </form>

    <!-- Card -->
    <div class="card">
        <h2 class="card-title">Card Title</h2>
        <p class="card-content">This is an example of a card component.</p>
    </div>

    <!-- Footer -->
    <footer>
        &copy; 2025 Your Website. All Rights Reserved.
    </footer>

</body>
</html>

