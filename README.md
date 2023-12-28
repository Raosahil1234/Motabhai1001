<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submit Information</title>
</head>
<body>
    <h1>Submit Your Information</h1>
    <form action="submit_process.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>

        <label for="address">Address:</label>
        <input type="text" id="address" name="address" required><br>

        <label for="wife_name">Wife's Name:</label>
        <input type="text" id="wife_name" name="wife_name" required><br>

        <label for="receipt">Receipt of Payment:</label>
        <input type="file" id="receipt" name="receipt" accept=".pdf, .jpg, .png" required><br>

        <p><input type="checkbox" id="own_risk" name="own_risk" required> I'm going to Mars at my own risk.</p>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
