# br<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Schedule</title>
    <style>
        /* Internal CSS styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
        }
        table {
            width: 80%;
            margin: auto;
            border-collapse: collapse;
            background-color: #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        th {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
        }
        td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:hover {
            background-color: #ddd;
        }
        .important {
            font-weight: bold;
            color: #ff0000;
        }
    </style>
</head>
<body>
    <h1>My Busy Day Schedule</h1>
    <table>
        <thead>
            <tr>
                <th>Time</th>
                <th>Event</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>7:00 AM</td>
                <td>Wake up</td>
            </tr>
            <tr>
                <td>8:00 AM</td>
                <td>Breakfast</td>
            </tr>
            <tr>
                <td>9:00 AM</td>
                <td>Grocery shopping</td>
            </tr>
            <tr>
                <td>11:00 AM</td>
                <td class="important">Meeting with client</td>
            </tr>
            <tr>
                <td>1:00 PM</td>
                <td>Lunch</td>
            </tr>
            <tr>
                <td>2:00 PM</td>
                <td>Project work</td>
            </tr>
            <tr>
                <td>5:00 PM</td>
                <td>Exercise</td>
            </tr>
            <tr>
                <td>7:00 PM</td>
                <td>Dinner with friends</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
