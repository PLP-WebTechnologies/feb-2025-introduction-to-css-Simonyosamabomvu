/* style.css file that meets all your requirements, along with instructions for linking it to your HTML: */
/* style.css */
/* ===== Base Styles ===== */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    background-color: #f9f9f9;
}

/* ===== Class Selector ===== */
.header {
    color: #2c3e50;
    text-align: center;
    margin-bottom: 30px;
    padding-bottom: 15px;
    border-bottom: 2px solid #3498db;
}

/* ===== ID Selector ===== */
#main-content {
    background-color: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* ===== Element Selector ===== */
h2 {
    color: #2980b9;
    font-family: 'Georgia', serif;
    margin-top: 25px;
}

/* ===== Image Styling ===== */
.img-featured {
    width: 100%;
    max-width: 600px;
    height: auto;
    display: block;
    margin: 20px auto;
    border: 3px solid #ecf0f1;
    border-radius: 4px;
    box-shadow: 0 3px 6px rgba(0,0,0,0.1);
}

/* ===== Button Styling ===== */
.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border: none;
    border-radius: 4px;
    margin: 10px 5px;
    transition: background-color 0.3s;
}

.btn:hover {
    background-color: #2980b9;
}

/* ===== Card Styling ===== */
.card {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-left: 4px solid #3498db;
    border-radius: 0 4px 4px 0;
}


/*How to Link It to Your HTML*/

/*Add this in the <head> section of your HTML file */
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to external CSS -->
</head>
<body>
    <header class="header">
        <h1>Welcome to My Styled Page</h1>
    </header>
    
    <main id="main-content">
        <h2>Featured Image</h2>
        <img src="https://example.com/image.jpg" alt="Sample" class="img-featured">
        
        <div class="card">
            <h2>Content Card</h2>
            <p>This is a styled paragraph with proper spacing and typography.</p>
            <a href="#" class="btn">Learn More</a>
        </div>
    </main>
</body>
</html>
