
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Package Tracking System">
    <title>Package Tracking System</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico">
</head>
<body>
    <header class="header">
        <nav class="nav">
            <ul class="nav-list">
                <li class="nav-item"><a href="#" class="nav-link">Track Package</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Login</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Register</a></li>
            </ul>
        </nav>
    </header>
    <main class="main">
        <section class="hero">
            <h1 class="hero-title">Track Your Packages Easily</h1>
            <form class="track-form">
                <input type="text" id="tracking-number" placeholder="Tracking Number" required>
                <select id="carrier" required>
                    <option value="">Select Carrier</option>
                    <option value="usps">USPS</option>
                    <option value="ups">UPS</option>
                    <option value="fedex">FedEx</option>
                </select>
                <button id="track-btn" class="track-btn">Track</button>
            </form>
        </section>
        <section class="tracking-results">
            <!-- tracking results will be displayed here -->
        </section>
    </main>
    <footer class="footer">
        <p>&copy; 2024 Package Tracking System. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```

