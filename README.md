<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>William Meyer - Financial Planner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            color: #333;
            scroll-behavior: smooth;
            transition: background-color 0.5s;
        }
        body:hover {
            background-color: #e9f0f8;
        }
        .container {
            width: 80%;
            margin: 50px auto;
            background: #fff;
            padding: 30px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
            transition: transform 0.3s;
        }
        .container:hover {
            transform: scale(1.01);
        }
        h1, h2 {
            color: #005B9F;
        }
        .contact-info {
            background: linear-gradient(45deg, #005B9F, #00407a);
            color: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
        }
        .contact-info a {
            color: #f0f0f0;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            margin-bottom: 30px;
            padding: 10px;
            background: #f9f9f9;
            border-radius: 8px;
            transition: background-color 0.3s;
        }
        .section:hover {
            background-color: #e0e8f0;
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
            padding: 12px 25px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 8px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #00407a;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #005B9F;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #00407a;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>William Meyer</h1>
        <h2>Financial Planner</h2>

        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:w.meyer@sanlam4u.co.za">w.meyer@sanlam4u.co.za</a></p>
            <p>Cell: <a href="tel:+27634229601">+27 63 422 9601</a></p>
        </div>

        <div class="section">
            <h2>About Me</h2>
            <p>I am dedicated to helping clients build wealth and create a lasting legacy through personalised strategies and informed decision-making. I offer clear actionable advice and build long-term plans for success.</p>
        </div>

        <div class="section">
            <h2>Qualifications</h2>
            <ul>
                <li>BCom in Business Management</li>
                <li>2 Years of Experience in Financial Planning</li>
                <li>Financial Planner at <a href="https://lonfingroup.co.za/index.php?option=com_sppagebuilder&view=page&id=2" target="_blank">Lonfin Group</a></li>
                <li>Authorised by <a href="https://www.sanlam.co.za/Pages/default.aspx" target="_blank">Sanlam</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>Services Offered</h2>
            <ul>
                <li>Risk Planning (Life, Disability, Severe Illness, Funeral)</li>
                <li>Investment Planning</li>
                <li>Education Planning</li>
                <li>Retirement Planning (Pre and Post Retirement)</li>
                <li>Business Assurance</li>
                <li>Wills and Estate Planning</li>
                <li>Corporate Pension, Provident Fund & Group Life Cover</li>
                <li>Car and Home Insurance</li>
                <li>Commercial, Professional Indemnity & Specialty Insurance</li>
                <li>Health Insurance (Medical Aid & GAP Cover)</li>
            </ul>
        </div>

        <div class="section">
            <h2>Book a Meeting</h2>
            <form action="mailto:w.meyer@sanlam4u.co.za" method="post" enctype="text/plain">
                <label>Name:</label>
                <input type="text" name="Name" required>
                <label>Surname:</label>
                <input type="text" name="Surname" required>
                <label>Email:</label>
                <input type="email" name="Email" required>
                <label>Contact Number:</label>
                <input type="tel" name="Contact" required>
                <label>Message (Optional):</label>
                <textarea name="Message" rows="4"></textarea>
                <button type="submit">Send Meeting Request</button>
            </form>
        </div>

        <div class="section">
            <h2>Connect with Me</h2>
            <a href="https://www.linkedin.com/in/william-meyer-a86677235/" target="_blank" class="button">Connect on LinkedIn</a>
        </div>
    </div>
</body>
</html>
