<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breakpoints</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            text-align: center;
            padding: 50px;
            transition: all 0,5s ease;
        }
        h1 {
            font-size: 70px;
        }
        p {
            font-size: 20px;
        }
        body {
            background-color: yellow;
        }
        @media (min-width: 1199px) {
            body {
                background-color: yellow;
            }
        }
    </style>
</head>
<body>
    <h1> Responsive Breakpoints</h1>
    <p> Resize the window for opening in mobile/tablet</p>
</body>
</html>
