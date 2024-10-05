<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
            max-width: 600px;
            margin: 20px auto;
            background: #16213e;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }
        h1 {
            font-size: 2.5em;
            color: #00adb5;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.1em;
            color: #bfc0c0;
            margin-bottom: 20px;
        }
        input[type="text"] {
            padding: 10px;
            width: calc(100% - 20px); /* Adjusted for full width minus padding */
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
            padding: 12px 25px;
            background: #00adb5;
            color: #ffffff;
            font-size: 1em;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s ease, transform 0.2s;
            box-shadow: 0 6px 15px rgba(0, 173, 181, 0.3);
        }
        button:hover {
            background: #ff2e63;
            transform: translateY(-3px);
        }
        .result {
            margin-top: 25px;
            padding: 20px;
            background: #0f3460;
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }
        .motivational {
            margin-top: 15px;
            font-size: 1.2em;
            color: #4ce1e6;
            font-weight: bold;
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
                // Add other cases as needed...
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

