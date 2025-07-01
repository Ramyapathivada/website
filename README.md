<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Student Repository</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f0f8ff;
        }
        h1 {
            color: #2e8b57;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #aaa;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: #e0f7fa;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .add-student {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Student Repository</h1>

    <table>
        <thead>
            <tr>
                <th>Student ID</th>
                <th>Full Name</th>
                <th>Course</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>202501</td>
                <td>Ayesha Khan</td>
                <td>Computer Science</td>
                <td>ayesha.khan@example.com</td>
            </tr>
            <tr>
                <td>202502</td>
                <td>Rohan Mehta</td>
                <td>Information Technology</td>
                <td>rohan.mehta@example.com</td>
            </tr>
            <!-- Add more students here -->
        </tbody>
    </table>

    <div class="add-student">
        <h2>Add New Student</h2>
        <form>
            <label>Student ID: <input type="text" name="studentId"></label><br><br>
            <label>Full Name: <input type="text" name="fullName"></label><br><br>
            <label>Course: <input type="text" name="course"></label><br><br>
            <label>Email: <input type="email" name="email"></label
