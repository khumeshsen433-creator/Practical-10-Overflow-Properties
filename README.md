# Practical-10-Overflow-Properties

<!DOCTYPE html>
<html>
<head>
    <title>Overflow Demo</title>
    <style>
        .box {
            width: 250px;
            height: 100px;
            border: 2px solid black;
            margin: 15px;
            padding: 5px;
        }

        .visible { overflow: visible; }
        .hidden { overflow: hidden; }
        .scroll { overflow: scroll; }
        .auto { overflow: auto; }
    </style>
</head>
<body>
    <h1>News and Notice Box</h1>

    <div class="box visible">
        <b>Visible:</b> College examination notice.
        Classes will resume soon. Check the timetable.
        Submit all assignments before the last date.
    </div>

    <div class="box hidden">
        <b>Hidden:</b> College examination notice.
        Classes will resume soon. Check the timetable.
        Submit all assignments before the last date.
    </div>

    <div class="box scroll">
        <b>Scroll:</b> College examination notice.
        Classes will resume soon. Check the timetable.
        Submit all assignments before the last date.
    </div>

    <div class="box auto">
        <b>Auto:</b> College examination notice.
        Classes will resume soon. Check the timetable.
        Submit all assignments before the last date.
    </div>
</body>
</html>
