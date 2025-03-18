<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>William Meyer - Financial Planner</title>
    <style>
        /* Resetting body margin and padding for full-page layout */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        
        /* Main container styling */
        .container {
            width: 95%; /* Wider container */
            max-width: 1400px; /* Max width increased */
            margin: 20px auto;
            background: #fff;
            padding: 40px;
            box-shadow: 0px 0px 15px #aaa;
            border-radius: 8px;
            text-align: center;
            font-size: 1.2em; /* Increase text size */
        }

        h1, h2 {
            color: #005B9F;
            font-size: 3.5em; /* Larger font size for headings */
        }

        .contact-info {
            background: #005B9F;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
            margin-bottom: 30px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            margin-bottom: 30px; /* Increase margin */
            text-align: left;
            font-size: 1.1em;
        }

        .section ul {
            list-style-type: none;
            padding: 0;
            font-size: 1.1em;
        }

        .section li {
            margin-bottom: 15px;
        }

        .button {
            display: inline-block;
            padding: 15px 30px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 30px;
            font-size: 1.2em; /* Larger button text */
        }

        .button:hover {
            background-color: #00407a;
        }

        .meeting-form {
            background: #e6f2ff;
            padding: 25px;
            border-radius: 5px;
            font-size: 1.1em;
        }

        label {
            font-weight: bold;
            font-size: 1.1em;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1.1em;
        }

        button {
            background: #005B9F;
            color: white;
            padding: 15px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 5px;
            font-size: 1.2em;
        }

        button:hover {
            background: #00407a;
        }

        /* Footer styling */
        footer {
            width: 100%;
            background: #f4f4f9;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        footer p {
            margin: 5px;
        }

        .disclaimer {
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>William Meyer</h1>
        <h2>Financial Planner</h2>
        <hr>

        <!-- Contact Info Section -->
        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
        </div>

        <!-- About Me Section -->
        <div class="section">
            <h2>About Me</h2> 
            <p>As a financial planner, I am dedicated to helping clients build wealth and create a lasting legacy through personalised strategies and informed decision making. I focus on understanding each client’s unique needs, offering clear, actionable advice, and building long-term plans for success. By providing tailored solutions, I empower clients to navigate life’s financial challenges with confidence and security.</p>
        </div>

        <!-- Qualifications Section -->
        <div class="section">
            <h2>Qualifications</h2>
            <ul>
                <li>BCom in Business Management</li>
                <li>2 Years of Experience in Financial Planning</li>
                <li>Authorised Financial Planner at <a href="https://www.sanlam.co.za/Pages/default.aspx" target="_blank">Sanlam</a></li>
            </ul>
        </div>

        <!-- Services Offered Section -->
        <div class="section">
            <h2>Services Offered</h2>
            <ul>
                <li>Life Insurance</li>
                <li>Retirement Planning</li>
                <li>Business Insurance</li>
                <li>Will & Estate Planning</li>
                <li>Investment Advice</li>
            </ul>
        </div>

        <!-- Location Section -->
        <div class="section">
            <h2>Location</h2>
            <p>Find me at: <strong><a href="https://www.google.com/maps?q=1st+Floor,+Century+Way,+The+Colosseum,+Cape+Town,+South+Africa" target="_blank">1st Floor, Century Way, The Colosseum, Cape Town, South Africa</a></strong></p>
        </div>

        <!-- Book a Meeting Form -->
        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:w.meyer@sanlam4u.co.za" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="surname">Surname:</label>
                <input type="text" id="surname" name="Surname" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Contact Number:</label>
                <input type="tel" id="contact" name="Contact" required>

                <label for="message">Additional Details (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <button type="submit">Send Meeting Request</button>
            </form>
        </div>

        <!-- Connect with Me Section -->
        <div class="section">
            <h2>Connect with Me</h2>
            <p><a href="https://www.linkedin.com/in/william-meyer-a86677235/" target="_blank" class="button">Connect on LinkedIn</a></p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 William Meyer. All rights reserved.</p>
        <p class="disclaimer">Disclaimer: This website is for informational purposes only and is not intended as professional financial advice. Always consult a qualified financial planner for personalized advice.</p>
    </footer>

</body>
</html>
