git clone <đường_dẫn_repository>
cd English-Skill-Test
mkdir css js images
touch index.html style.css app.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>English Skill Test</title>
</head>
<body>
    <h1>English Skill Test</h1>
    <div id="quiz">
        <p>Question 1: What is the synonym of "happy"?</p>
        <input type="radio" name="q1" value="sad">Sad<br>
        <input type="radio" name="q1" value="joyful">Joyful<br>
        <button onclick="submitQuiz()">Submit</button>
    </div>
    <div id="result"></div>
    <script src="app.js"></script>
</body>
</html>
