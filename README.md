# project-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Landing Page</title>
</head>
<body>
    <header>
        <h1>Service Name</h1>
        <p>FitnessFuel Pro.</p>
    </header>

    <section id="features">
        <h2>Key Features</h2>
        <div class="feature">
            <h3>Feature 1</h3>
            <p> Personalized Workout Plans:
         Unlock your fitness potential with tailor-made workout plans crafted to meet your individual goals and preferences. .</p>
        </div>
        <div class="feature">
            <h3>Feature 2</h3>
            <p> Advanced Training Metrics:
           Track your progress with cutting-edge metrics, including heart rate monitoring, calories burned, and more.</p>
        <!-- Add more features as needed -->
    </section>

    <section id="cta">
        <h2>Get Started Today</h2>
        <p>Sign up now to experience the benefits.</p>
        <button>Sign Up</button>
    </section>

    <footer>
        <p>&copy; 2024 Your Company Name. All rights reserved.</p>
    </footer>
</body>
</html>




CSS (styles.css):

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header, section, footer {
    text-align: center;
    padding: 40px 20px;
    background-color: #333;
    color: #fff;
}

h1, h2, h3 {
    margin: 0;
}

section {
    margin: 20px 0;
}

.feature {
    margin-top: 20px;
}

button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: #fff;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

footer {
    background-color: #555;
}
