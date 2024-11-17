*HTML and CSS Implementation
index.html
This will serve as the homepage linking to the five pages.
HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS GRID Project</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>CSS Grid Example</h1>
    </header>
    <nav>
        <ul>
            <li><a href="pages/products.html">List of Products</a></li>
            <li><a href="pages/employees.html">List of Employees</a></li>
            <li><a href="pages/students.html">List of Students</a></li>
            <li><a href="pages/services.html">List of Services</a></li>
            <li><a href="pages/clients.html">List of Clients</a></li>
        </ul>
    </nav>
</body>
</html>


CSS CODE
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    text-align: center;
    background-color: #4CAF50;
    color: white;
    padding: 20px;
}

nav ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
    background-color: #333;
    padding: 10px;
    margin: 0;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    padding: 20px;
}

.grid-item {
    background-color: #f4f4f4;
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
}



# CSS_GRID

This project demonstrates the use of CSS Grid for creating responsive layouts. The repository includes a homepage and five example pages: 

1. **List of Products**  
2. **List of Employees**  
3. **List of Students**  
4. **List of Services**  
5. **List of Clients**  

## Features

- **Responsive Design**: The grid layout adapts to different screen sizes.  
- **Modern CSS**: Utilizes CSS Grid for layout management.  
- **Clean Code**: Modular structure with reusable styles.  

