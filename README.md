<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Password Generator</title>

    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <script src="main.js"></script>

</head>

<body>
    
    <nav>
        <a> Random Password Generator

        </a>

    </nav>
    <div class="container">
        <div class="row" > </div>
        <div class="col-lg-8 colsm-12 mx-auto">

        <div class="content">
            <h1>Random Password Generator</h1>
            <br />
            <input type="text" id="display">
            <br />
            <button onclick= "pleasework()">Generate</button>
            <button onclick="">Copy Them</button>
            <div id="length"></div>
            
        </div>

        <div class="previous_passwords">
            <b>Previously Generated Passwords</b>
            <br />
            <div id="lastpasswords"></div>
        </div>

</body>

</html>
