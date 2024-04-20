<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Money Tracker App - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            padding: 20px;
        }
        .container {
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        h1 {
            color: #333;
            text-align: center;
        }
        h2 {
            color: #333;
        }
        p {
            color: #666;
        }
        code {
            background-color: #f4f4f4;
            padding: 5px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Money Tracker App</h1>
        <p>A simple web application to track your expenses and incomes.</p>

        <h2>Description</h2>
        <p>
            The Money Tracker App is a simple web application that helps you keep track of your expenses and incomes.
            With this app, you can easily add new transactions, view your existing transactions, and monitor your total balance.
        </p>

        <h2>Installation</h2>
        <p>Follow these steps to run the Money Tracker App on your local machine:</p>

        <h3>Prerequisites</h3>
        <ul>
            <li><a href="https://nodejs.org/">Node.js</a> installed on your machine</li>
            <li><a href="https://www.mongodb.com/">MongoDB</a> installed and running on your machine</li>
        </ul>

        <h3>Clone the repository</h3>
        <pre><code>git clone https://github.com/yourusername/Money-Tracker-App.git<br>cd Money-Tracker-App</code></pre>

        <h3>Install dependencies</h3>
        <pre><code>npm install</code></pre>

        <h3>Run the application</h3>
        <pre><code>node index.js</code></pre>
        <p>Visit <a href="http://localhost:5000">http://localhost:5000</a> in your browser to view the app.</p>

        <h2>Usage</h2>
        <ul>
            <li>Select a category (Expense or Income).</li>
            <li>Enter the amount.</li>
            <li>Provide additional information (optional).</li>
            <li>Choose the date.</li>
            <li>Click on the "Add" button to add the transaction.</li>
            <li>View the list of expenses and incomes below the input form.</li>
        </ul>

        <h2>Technologies Used</h2>
        <ul>
            <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
            <li><strong>Backend:</strong> Node.js, Express.js</li>
            <li><strong>Database:</strong> MongoDB</li>
        </ul>

        <h2>Folder Structure</h2>
        <pre><code>
├── public
│   ├── index.html
│   ├── style.css
│   └── script.js
├── index.js
└── README.md
        </code></pre>

        <h2>License</h2>
        <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

        <h2>Author</h2>
        <p><a href="https://github.com/yourusername">Your Name</a></p>
        <p>Feel free to customize this README file to fit your project's specific needs.</p>
        <p>Remember to replace <code>Your Name</code> with your name and GitHub profile link.</p>
    </div>
</body>
</html>
