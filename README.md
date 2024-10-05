<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Exam Results</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a2e;
            color: #ffffff;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 95%;
            width: 100%;
            margin: 20px auto;
            background: #16213e;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }
        h1 {
            font-size: 2em;
            color: #00adb5;
            margin-bottom: 20px;
        }
        p {
            font-size: 1em;
            color: #bfc0c0;
            margin-bottom: 15px;
        }
        input[type="text"] {
            padding: 12px;
            width: 100%;
            font-size: 1em;
            background: #0f3460;
            border: 2px solid #00adb5;
            border-radius: 8px;
            color: #ffffff;
            margin-bottom: 15px;
            transition: all 0.3s ease;
        }
        input[type="text"]:focus {
            border-color: #ff2e63;
            outline: none;
            box-shadow: 0 0 10px rgba(255, 46, 99, 0.5);
        }
        button {
            padding: 10px 20px;
            background: #00adb5;
            color: #ffffff;
            font-size: 1em;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s ease, transform 0.2s;
            box-shadow: 0 6px 15px rgba(0, 173, 181, 0.3);
            width: 100%;
        }
        button:hover {
            background: #ff2e63;
            transform: translateY(-3px);
        }
        .result {
            margin-top: 20px;
            padding: 20px;
            background: #0f3460;
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }
        .motivational {
            margin-top: 10px;
            font-size: 1.2em;
            color: #4ce1e6;
            font-weight: bold;
        }
        footer {
            margin-top: 20px;
            padding: 10px 0;
            color: #00adb5;
            font-size: 1em;
        }
    </style>
    <script>
        function getResult() {
            const code = document.getElementById("codeInput").value.trim();
            const resultDiv = document.getElementById("result");

            let name = "";
            let degree = "";
            let motivationalMessage = "";

            switch (code) {
                case "2526":
                    name = "Amro Mohamed";
                    degree = "60/60";
                    motivationalMessage = "Great job! You're on your way to amazing things!";
                    break;
                case "41715":
                    name = "Ahmed Hossam";
                    degree = "0/0";
                    motivationalMessage = "Keep working hard! Improvement is always possible!";
                    break;
                case "39472":
                    name = "Mohamed Abdelazeem";
                    degree = "0/0";
                    motivationalMessage = "Don't give up! Keep pushing forward!";
                    break;
                case "52182":
                    name = "Omar Waleed";
                    degree = "0/0";
                    motivationalMessage = "You're capable of achieving great results!";
                    break;
                case "70126":
                    name = "Mazen Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Every setback is a setup for a comeback!";
                    break;
                case "63855":
                    name = "Abdelrahman Mahmoud";
                    degree = "0/0";
                    motivationalMessage = "Keep striving for your goals!";
                    break;
                case "80650":
                    name = "Ahmed Ayman";
                    degree = "0/0";
                    motivationalMessage = "Believe in yourself and all that you are!";
                    break;
                case "80546":
                    name = "Mazen Ahmed";
                    degree = "0/0";
                    motivationalMessage = "Your hard work will pay off!";
                    break;
                case "23069":
                    name = "Youssef Hassan";
                    degree = "0/0";
                    motivationalMessage = "Stay focused and keep moving forward!";
                    break;
                case "73057":
                    name = "Omar Hany";
                    degree = "0/0";
                    motivationalMessage = "Keep your head high and trust your capabilities!";
                    break;
                case "35804":
                    name = "Reem Khaled";
                    degree = "0/0";
                    motivationalMessage = "Stay positive and keep learning!";
                    break;
                case "21687":
                    name = "Rowan Ehab";
                    degree = "0/0";
                    motivationalMessage = "Great things take time, keep going!";
                    break;
                case "75934":
                    name = "Diya Abdelaleem";
                    degree = "0/0";
                    motivationalMessage = "Your determination will lead you to success!";
                    break;
                case "15032":
                    name = "Tasneem Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Don't stop now, you are getting closer!";
                    break;
                case "16840":
                    name = "Sama Ibrahim";
                    degree = "0/0";
                    motivationalMessage = "Keep moving forward, success is ahead!";
                    break;
                case "18054":
                    name = "Haneen El-Sayed";
                    degree = "0/0";
                    motivationalMessage = "You're doing great, keep it up!";
                    break;
                case "20321":
                    name = "Basant Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Believe in the power of your dreams!";
                    break;
                case "39639":
                    name = "Eman Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Don't stop believing, you're almost there!";
                    break;
                case "28411":
                    name = "Raheeq Sayed";
                    degree = "0/0";
                    motivationalMessage = "Hard work always pays off in the end!";
                    break;
                case "69756":
                    name = "Ahmed Yasser";
                    degree = "0/0";
                    motivationalMessage = "Stay determined and keep aiming high!";
                    break;
                case "80135":
                    name = "Mohamed Ashraf";
                    degree = "0/0";
                    motivationalMessage = "You're stronger than you think, keep going!";
                    break;
                case "29474":
                    name = "Mohamed Ehab";
                    degree = "0/0";
                    motivationalMessage = "Stay motivated, great things are coming!";
                    break;
                case "58471":
                    name = "Abdelrahman Shaaban";
                    degree = "0/0";
                    motivationalMessage = "Believe in yourself, you are capable of greatness!";
                    break;
                case "49696":
                    name = "Adam Amr";
                    degree = "0/0";
                    motivationalMessage = "Success is on the way, keep pushing!";
                    break;
                case "25695":
                    name = "Vera Essam";
                    degree = "0/0";
                    motivationalMessage = "You're almost there, don't give up now!";
                    break;
                case "41596":
                    name = "Nour Eldin";
                    degree = "0/0";
                    motivationalMessage = "Focus on your goals, you are unstoppable!";
                    break;
                case "72137":
                    name = "Rodina Ayman";
                    degree = "0/0";
                    motivationalMessage = "You're on the right path, keep going!";
                    break;
                case "48261":
                    name = "Ziad Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Don't look back, your future is bright!";
                    break;
                case "48389":
                    name = "Sundus Salah";
                    degree = "0/0";
                    motivationalMessage = "Stay motivated, you're doing great!";
                    break;
                case "66908":
                    name = "Ahmed Mohamed";
                    degree = "0/0";
                    motivationalMessage = "Keep working towards your goals, success is near!";
                    break;
                case "30693":
                    name = "Rahma Maged";
                    degree = "0/0";
                    motivationalMessage = "You've got this, keep pushing forward!";
                    break;
                case "81659":
                    name = "Nour Abdelrahman";
                    degree = "0/0";
                    motivationalMessage = "Every effort you make brings you closer to success!";
                    break;
                case "16075":
                    name = "Omnia Ayman";
                    degree = "0/0";
                    motivationalMessage = "Stay determined, your hard work will pay off!";
                    break;
                case "32859":
                    name = "Mariam Atef";
                    degree = "0/0";
                    motivationalMessage = "You're on the path to greatness, keep going!";
                    break;
                case "23849":
                    name = "Farah Emad";
                    degree = "0/0";
                    motivationalMessage = "Keep believing in yourself, success will follow!";
                    break;
                case "88105":
                    name = "Sandy Essam";
                    degree = "0/0";
                    motivationalMessage = "You are closer to success than you think!";
                    break;
                case "69897":
                    name = "Arwa Ahmed";
                    degree = "0/0";
                    motivationalMessage = "Stay focused and keep moving forward!";
                    break;
                case "15290":
                    name = "Mohamed Amr";
                    degree = "0/0";
                    motivationalMessage = "You're capable of amazing things, keep pushing!";
                    break;
                case "92758":
                    name = "Mazen Abdelwahab";
                    degree = "0/0";
                    motivationalMessage = "Your hard work and dedication will pay off soon!";
                    break;
                default:
                    name = "Unknown";
                    degree = "N/A";
                    motivationalMessage = "Invalid code. Please try again.";
            }



            resultDiv.innerHTML = `
                <div class="result">
                    <p><strong>Name:</strong> ${name}</p>
                    <p><strong>Degree in Exam:</strong> ${degree}</p>
                    <p class="motivational">${motivationalMessage}</p>
                </div>
            `;
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>Exam Results Checker</h1>
        <p>Enter your code to see your exam results:</p>
        <input type="text" id="codeInput" placeholder="Enter your code here">
        <br>
        <button onclick="getResult()">Check Result</button>
        <div id="result"></div>
    </div>
    <footer>
        Developed by Eng: Amr Mohamed
    </footer>
