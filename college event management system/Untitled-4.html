!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
</head>
<body>
    <h2>Student Login</h2>
    <form action="login.php" method="POST">
        <label for="student_name">Student Name:</label>
        <input type="text" id="student_name" name="student_name" required><br><br>

        <label for="college_name">College Name:</label>
        <input type="text" id="college_name" name="college_name" required><br><br>

        <button type="submit">Login</button>
    </form>
</body>
</html>
<?php
session_start();
include 'connection.php';

$student_name = $_POST['student_name'];
$college_name = $_POST['college_name'];

$sql = "SELECT * FROM students WHERE student_name = ? AND college_name = ?";
$stmt = $conn->prepare($sql);
$stmt->bind_param("ss", $student_name, $college_name);
$stmt->execute();
$result = $stmt->get_result();

if ($result->num_rows === 1) {
    $_SESSION['student_name'] = $student_name;
    echo "✅ Login successful! <a href='dashboard.html'>Go to Dashboard</a>";
} else {
    echo "❌ Login failed. Name or college not found.";
}
?>
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    student_name VARCHAR(100),
    college_name VARCHAR(150)
);
INSERT INTO students (student_name, college_name)
VALUES ('John Doe', 'ABC College');
