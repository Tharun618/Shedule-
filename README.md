# Shedule-
<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>
<body>
    <h1>Welcome to My Website!</h1>
    <p>This is a basic website structure.</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schedule Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Weekly Schedule</h1>
        <div class="schedule">
            <div class="day" id="monday">
                <h2>Monday</h2>
                <ul class="tasks"></ul>
                <input type="text" placeholder="Add a task" class="task-input">
                <button class="add-task-button">Add Task</button>
            </div>
            <!-- Repeat similar blocks for other days -->
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
