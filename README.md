<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Strona z ramkami</title>
    <style>
        body { margin: 0; }
        .container {
            display: grid;
            grid-template-columns: 1fr 2fr;
            grid-template-rows: 1fr 1fr;
            height: 100vh;
        }
        #okno1 { grid-column: 2; grid-row: 1; }
        #okno2 { grid-column: 1; grid-row: 1; }
        #okno3 { grid-column: 1 / span 2; grid-row: 2; }
    </style>
</head>
<body>
    <div class="container">
        <iframe src="okno1.html" id="okno1" name="okno1"></iframe>
        <iframe src="okno2.html" id="okno2" name="okno2"></iframe>
        <iframe src="okno3.html" id="okno3" name="okno3"></iframe>
    </div>
</body>
</html>
