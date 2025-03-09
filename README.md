# Commit-Smart
A simple and effective guide to writing semantic commit messages ✍️ for better Git history and collaboration. Improve your workflow with clear and structured commit messages!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Commit Messages</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #f4f4f4;
        }
        h1, h2 {
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #333;
            color: white;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
        }
        .best-practices {
            background: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0px 0px 5px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>
    <h1>Semantic Commit Messages</h1>
    <p>Using semantic commit messages keeps your Git history clear and structured. It helps you and your team understand changes at a glance and makes collaboration easier.</p>
    
    <h2>Format</h2>
    <pre>
&lt;type&gt;(&lt;scope&gt;): &lt;short description&gt;

[optional body]

[optional footer(s)]
    </pre>
    
    <h2>Example:</h2>
    <pre>
feat(auth): add JWT authentication
fix(ui): resolve button alignment issue
docs(readme): update installation instructions
    </pre>

    <h2>Commit Types</h2>
    <table>
        <tr>
            <th>Type</th>
            <th>Purpose</th>
        </tr>
        <tr><td><b>feat</b></td><td>Introduces a new feature</td></tr>
        <tr><td><b>fix</b></td><td>Fixes a bug</td></tr>
        <tr><td><b>docs</b></td><td>Documentation updates</td></tr>
        <tr><td><b>style</b></td><td>Code style changes (formatting, missing semicolons, etc.)</td></tr>
        <tr><td><b>refactor</b></td><td>Code restructuring without changing behavior</td></tr>
        <tr><td><b>perf</b></td><td>Performance improvements</td></tr>
        <tr><td><b>test</b></td><td>Adds or modifies tests</td></tr>
        <tr><td><b>chore</b></td><td>Maintenance tasks (e.g., build process, dependencies)</td></tr>
        <tr><td><b>ci</b></td><td>Changes to CI/CD pipeline</td></tr>
    </table>

    <h2>Examples</h2>
    <ul>
        <li><b>Adding a Feature:</b>
            <pre>feat(search): add vehicle model search functionality</pre>
        </li>
        <li><b>Fixing a Bug:</b>
            <pre>fix(backend): correct database query for vehicle prices</pre>
        </li>
        <li><b>Refactoring Code:</b>
            <pre>refactor(api): optimize database connection handling</pre>
        </li>
        <li><b>Updating Documentation:</b>
            <pre>docs(README): update setup instructions for Next.js frontend</pre>
        </li>
    </ul>

    <h2>Best Practices</h2>
    <div class="best-practices">
        ✅ Use the imperative mood (e.g., "add" instead of "added").<br>
        ✅ Keep your messages concise but informative.<br>
        ✅ Include a body if additional explanation is needed.<br>
        ✅ Use the scope (in parentheses) to specify the affected part of the project.<br>
    </div>

    <p>By following semantic commit messages, you’ll maintain a clean and understandable Git history, making collaboration and project management much smoother. 🚀</p>
</body>
</html>


