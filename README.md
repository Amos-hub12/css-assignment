# css-assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    <section>
        <div class="content">
            <h2>About Me</h2>
            <p>This is a brief introduction about myself. I enjoy coding, design, and learning new things.</p>
        </div>
        <div class="form-container">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 My Web Page</p>
    </footer>
</body>
</html>
