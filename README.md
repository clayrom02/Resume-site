<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Resume Portal</title>
</head>
<body>
    <!-- Employee Portal -->
    <div id="employee-portal">
        <!-- Employee Registration Form -->
        <form id="employee-registration-form">
            <!-- Input fields for resume information -->
            <!-- Add sections for past experience, recommendations, contact info, education, strengths/weaknesses, awards/accolades, etc. -->
            <input type="text" placeholder="Username" id="employee-username">
            <input type="password" placeholder="Password" id="employee-password">
            <!-- Add more input fields for resume sections -->

            <!-- Submit button -->
            <button type="button" onclick="submitEmployeeInfo()">Submit</button>
        </form>
    </div>

    <!-- Employer Portal -->
    <div id="employer-portal">
        <!-- Employer Registration Form -->
        <form id="employer-registration-form">
            <input type="text" placeholder="Username" id="employer-username">
            <input type="password" placeholder="Password" id="employer-password">
            <!-- Add more input fields for employer registration -->

            <!-- Submit button -->
            <button type="button" onclick="submitEmployerInfo()">Submit</button>
        </form>
    </div>

    <!-- JavaScript for handling form submissions -->
    <script src="script.js"></script>
</body>
</html>
