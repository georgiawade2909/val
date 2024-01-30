<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine, Connor!</title>
    <style>
        body {
            text-align: center;
            padding: 50px;
            font-family: Arial, sans-serif;
            background-color: #ffc0cb; /* Pink background color */
        }
        h1 {
            color: #e60000;
        }
        p {
            font-size: 1.2em;
        }
        button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 1.2em;
            cursor: pointer;
        }
        #response {
            font-size: 1.2em;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Connor, Will You Be My Valentine?</h1>
    <p>Dear Connor,</p>
    <p>I love you so much - you are the stars in my sky(rack). Can’t wait to spend our first Valentine’s together. So will you be my valentine? 💖</p>

    <button onclick="response('yes')">Yes</button>
    <button onclick="response('no')">No</button>

    <p id="response"></p>

    <script>
        function response(answer) {
            document.getElementById('response').innerHTML = (answer === 'yes') ? 'That makes me so happy! 😊' : 'Maybe next time. 💔';
        }
    </script>
</body>
</html>
