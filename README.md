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
        let resource = ""; 

switch (code) {
    case "2526":
    name = "Amro Mohamed";
    degree = "58+2=<span style='color:#ff2e63;'>60</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
    case "08724":
    name = "Abdelwahab";
    degree = "40+2=<span style='color:#ff2e63;'>42</span>/60";
    motivationalMessage = "Keep pushing forward, you're doing great! 💪";
    break;
case "41715":
    name = "Ahmed Hossam El Deen";
    degree = "32+4=<span style='color:#ff2e63;'>36</span>/60";
    motivationalMessage = "Your hard work will pay off soon! 🌟";
    break;
case "23069":
    name = "Youssef Hassan";
    degree = "40+0=<span style='color:#ff2e63;'>40</span>/60";
    motivationalMessage = "Stay determined, success is near! 🚀";
    break;
case "39472":
    name = "Mohamed Abdelazeem El Hefnawy";
    degree = "42+4=<span style='color:#ff2e63;'>46</span>/60";
    motivationalMessage = "You're capable of amazing things! 🌈";
    break;
case "44746":
    name = "Saeed Saad Mohamed Saeed";
    degree = "33+0=<span style='color:#ff2e63;'>33</span>/60";
    motivationalMessage = "Believe in yourself and keep moving! ✨";
    break;
case "37144":
    name = "Abdallah Ahmed Salah El Helw";
    degree = "45+4=<span style='color:#ff2e63;'>49</span>/60";
    motivationalMessage = "Stay strong, you're doing well! 💫";
    break;
case "39639":
    name = "Eman";
    degree = "31+0=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Every step you take brings you closer to success! 🌟";
    break;
case "35365":
    name = "Hatem Amin Mohamed";
    degree = "50+4=<span style='color:#ff2e63;'>54</span>/60";
    motivationalMessage = "Keep aiming high, you're almost there! 🚀";
    break;
case "94758":
    name = "Mazen Abdelwahab";
    degree = "53+2=<span style='color:#ff2e63;'>55</span>/60";
    motivationalMessage = "Your persistence is inspiring! 🌈";
    break;
case "18054":
    name = "Haneen Elsayed";
    degree = "31+0=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Chase your dreams and never give up! 💪";
    break;
case "73057":
    name = "Omar Hany";
    degree = "35+0=<span style='color:#ff2e63;'>35</span>/60";
    motivationalMessage = "Great effort! Keep shining! ✨";
    break;
case "73394":
    name = "Mahmoud Hesham";
    degree = "39+0=<span style='color:#ff2e63;'>39</span>/60";
    motivationalMessage = "You have the power to achieve greatness! 🌟";
    break;
case "64743":
    name = "Mohamed Salah";
    degree = "0=<span style='color:#ff2e63;'>0</span>/60";
    motivationalMessage = "You're on the right track, keep going! 🚀";
    break;
case "63855":
    name = "Abdelrahman Mahmoud";
    degree = "43+0=<span style='color:#ff2e63;'>43</span>/60";
    motivationalMessage = "Stay focused and determined! 💫";
    break;
case "75014":
    name = "Noura Ahmed Mostafa Nagi";
    degree = "33+3=<span style='color:#ff2e63;'>36</span>/60";
    motivationalMessage = "You're making great progress! 🌈";
    break;
case "48273":
    name = "Ahmed Hassan Tawfik";
    degree = "40+4=<span style='color:#ff2e63;'>44</span>/60";
    motivationalMessage = "Success is built on perseverance! 💪";
    break;
case "69756":
    name = "Ahmed Yasser Abosarea Hussein";
    degree = "55+0=<span style='color:#ff2e63;'>55</span>/60";
    motivationalMessage = "Keep going, you're doing great! ✨";
    break;
case "72137":
    name = "Rodina";
    degree = "42+0=<span style='color:#ff2e63;'>42</span>/60";
    motivationalMessage = "Believe in your journey! 🌟";
    break;
case "80546":
    name = "Mazen Ahmed Samir";
    degree = "50+0=<span style='color:#ff2e63;'>50</span>/60";
    motivationalMessage = "You're unstoppable! 🚀";
    break;
case "32532":
    name = "Mariam Atef";
    degree = "29+4=<span style='color:#ff2e63;'>33</span>/60";
    motivationalMessage = "Keep going, you're doing great! ✨";
    break;
case "41596":
    name = "Nour El-Din Haitham Ramadan";
    degree = "52+4=<span style='color:#ff2e63;'>56</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "50808":
    name = "Ahmed Mohamed Hussein Mohamed";
    degree = "33+0=<span style='color:#ff2e63;'>33</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "81463":
    name = "Ahmed Nagih Anwar";
    degree = "46+6=<span style='color:#ff2e63;'>50</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "19734":
    name = "Kareem Elyamany";
    degree = "27+0=<span style='color:#ff2e63;'>27</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "15290":
    name = "Mohamed Amr";
    degree = "28+3=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "04596":
    name = "Ahmed Sameh";
    degree = "25+0=<span style='color:#ff2e63;'>25</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "16840":
    name = "Sama";
    degree = "31+0=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "49696":
    name = "Adam Amr";
    degree = "39+2=<span style='color:#ff2e63;'>41</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "56193":
    name = "Habiba Mohamed";
    degree = "40+0=<span style='color:#ff2e63;'>40</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "28411":
    name = "Raheek Sayed Hassan Abdelnaser";
    degree = "33+0=<span style='color:#ff2e63;'>33</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "48389":
    name = "Sondos Salah Eldeen";
    degree = "33+4=<span style='color:#ff2e63;'>37</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "47916":
    name = "Abdallah Ahmed Mahmoud";
    degree = "38+4=<span style='color:#ff2e63;'>42</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "21687":
    name = "Rawan Ehab";
    degree = "29+4=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "30693":
    name = "Rahma";
    degree = "30+0=<span style='color:#ff2e63;'>30</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "29474":
    name = "Mohamed Ehab Abdel Fattah";
    degree = "49+1=<span style='color:#ff2e63;'>50</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "35804":
    name = "Reem Khaled Elmorsy";
    degree = "32+0=<span style='color:#ff2e63;'>32</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "22030":
    name = "Habiba Ahmed Abdelraouf";
    degree = "31+3=<span style='color:#ff2e63;'>33</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "75934":
    name = "Dai Abdelalim Mohamed";
    degree = "27+4=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

case "16075":
    name = "Omnia Ayman";
    degree = "36+0=<span style='color:#ff2e63;'>36</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "62831":
    name = "Abdelrahman Mustafa";
    degree = "28+4=<span style='color:#ff2e63;'>32</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "66908":
    name = "Ahmed Mohammed Abdullatief";
    degree = "52+0=<span style='color:#ff2e63;'>52</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "06467":
    name = "Zeinab Mohamed Ali";
    degree = "26+4=<span style='color:#ff2e63;'>30</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break; 
case "20531":
    name = "Sandy Essam Mohamed";
    degree = "39+0=<span style='color:#ff2e63;'>39</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

case "25695":
    name = "Vera Essam Adly";
    degree = "26+4=<span style='color:#ff2e63;'>30</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

case "19153":
    name = "Shahd Saeed";
    degree = "27+3=<span style='color:#ff2e63;'>30</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
    
case "41729":
    name = "momeen";
    degree = "39+2=<span style='color:#ff2e63;'>41</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;
case "52182":
    name = "Omar Walid";
    degree = "58+4=<span style='color:#ff2e63;'>60</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

case "69897":
    name = "Arwa Ahmed";
    degree = "42+0=<span style='color:#ff2e63;'>42</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

case "59112":
    name = "Basent Sobhy";
    degree = "31+0=<span style='color:#ff2e63;'>31</span>/60";
    motivationalMessage = "Great job! You're on your way to amazing things!🤩";
    break;

    default:
        name = "Unknown";
        degree = "N/A";
        motivationalMessage = "Keep going, you’ve got this!🤩";
}
        
            resultDiv.innerHTML = `
            <div class="result">
                <p><strong>Name:</strong> ${name}</p>
                <p><strong>Degree in Exam:</strong> ${degree}</p>
                <p class="motivational">${motivationalMessage}</p>
                ${resource ? `<div>${resource}</div>` : ""}
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
