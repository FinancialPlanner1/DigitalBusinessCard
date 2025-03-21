<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Financial Planner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 90%;
            margin: 65px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px #aaa;
            border-radius: 8px;
            text-align: center;
        }

        h1, h2 {
            color: #005B9F;
        }

        .highlight {
            background-color: #e6f2ff;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #005B9F;
        }

        .highlight h2 {
            color: #00407a;
        }

        .contact-info {
            background: #005B9F;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            margin-bottom: 20px;
            text-align: left;
        }

        .section ul {
            list-style-type: none;
            padding: 0;
        }

        .section li {
            margin-bottom: 10px;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }

        .button:hover {
            background-color: #00407a;
        }

        footer {
            text-align: center;
            background-color: #f4f4f9;
            padding: 10px;
            margin-top: 40px;
            font-size: 0.9em;
        }

        .disclaimer {
            color: #777;
        }

        .meeting-form {
            background: #e6f2ff;
            padding: 15px;
            border-radius: 5px;
            margin-top: 20px;
        }

        label {
            font-weight: bold;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background: #005B9F;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }

        button:hover {
            background: #00407a;
        }

        /* Slow Motion Scroll */
        html {
            scroll-behavior: smooth;
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
        <div class="section highlight" id="about-me">
            <h2>About Me</h2>
            <p>As a financial planner, I am dedicated to helping clients build wealth and create a lasting legacy through personalised strategies and informed decision making. I focus on understanding each client’s unique needs, offering clear actionable advice and building long term plans for success. By providing tailored solutions, I empower clients to navigate life’s financial challenges with confidence and security.</p>
        </div>

        <!-- Qualifications Section -->
        <div class="section highlight" id="qualifications">
            <h2>Qualifications</h2>
            <ul>
                <li>BCom in Business Management</li>
                <li>2 Years of Experience in the Financial Planning industry</li>
                <li>Financial Planner at <a href="https://lonfingroup.co.za/index.php?option=com_sppagebuilder&view=page&id=2" target="_blank">Lonfin Group</a></li>
                <li>Authorised by <a href="https://www.sanlam.co.za/Pages/default.aspx" target="_blank">Sanlam</a></li>
            </ul>
        </div>

        <!-- Services Offered Section -->
        <div class="section highlight" id="services-offered">
            <h2>Services Offered</h2>
            <ul>
                <li>Risk Planning (Life, Disability, Severe Illness, Funeral)</li>
                <li>Investment Planning</li>
                <li>Education Planning</li>
                <li>Retirement Planning (Pre and Post Retirement)</li>
                <li>Business Assurance</li>
                <li>Wills and Estate Planning</li>
                <li>Corporate Pension, Provident Fund and Group Life Cover</li>
                <li>Car and Home Insurance</li>
                <li>Commercial, Professional Indemnity and Specialty Insurance</li>
                <li>Health Insurance (Medical Aid and GAP Cover)</li>
            </ul>
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
        <div class="section" id="connect-with-me">
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
