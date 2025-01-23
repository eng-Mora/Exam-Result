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
    resource = "<a href='https://drive.google.com/file/d/1iiNJqMrDUKkTptUQVymPbMqEyf0UowBB/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
    break;
    case "92758":
        name = "Mazen Abdelwahab Ahmed Ali";
        degree = "52+2=<span style='color:#ff2e63;'>54</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1uBP22dh6NJj3df7CVuoCA9BtNRo-gBQf/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "48389":
        name = "Sondos Salah";
        degree = "35+2=<span style='color:#ff2e63;'>37</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1lRHdAju5U2GHjKsXsSfLXyWqvArTtLGn/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "28411":
        name = "Rahiq Sayed Hassan";
        degree = "40+2=<span style='color:#ff2e63;'>42</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/13bM-EClqL2vKtTfqThuFuQfQKlSOJAs1/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "85459":
        name = "Yousef Mohamed";
        degree = "40+2=<span style='color:#ff2e63;'>42</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1LZAaIIEzssEl0Vxn6TL4yDN_v4CAfwog/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "75014":
        name = "Noura Ahmed Mostafa Nagy";
        degree = "35+2=<span style='color:#ff2e63;'>37</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1tjG7not559txdoMTw-ofB0Gx6AmCEaia/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "32532":
        name = "Mariam Atef";
        degree = "31+2=<span style='color:#ff2e63;'>33</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1uObeUzHdMiHyu40_-IOCC8U-V5c9T8ee/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "41596":
        name = "Nour Eldeen";
        degree = "42+2=<span style='color:#ff2e63;'>44</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/15FEDhKzMc-ezb0tiAgxZ49rD91WT_Qd9/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "50808":
        name = "Ahmed Mohamed Houssein";
        degree = "30+2=<span style='color:#ff2e63;'>32</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1c-XWqHMnL17z9he6WMnFaclknPb6B6lN/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "80135":
        name = "Mohamed Ashraf Abdelaleem";
        degree = "53+2=<span style='color:#ff2e63;'>55</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/15tgsoqypAKWBxgKxcqkertRbzjA3jEk4/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "06467":
        name = "Zeinab Mohamed Ali";
        degree = "26+2=<span style='color:#ff2e63;'>28</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1zK8wB2XU0J0B8F1rveoXMOFvBrMSLU6h/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "63855":
        name = "Abdelrahman Mahmoud Abdelhaseeb";
        degree = "41+2=<span style='color:#ff2e63;'>43</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1MxAYhazzEnr-2j7aLJEX1tIO8chCO5uT/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "69756":
        name = "Ahmed Yasser Abosriea";
        degree = "52+2=<span style='color:#ff2e63;'>54</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1NvGG0RcSNkEOQdMQaqintuqaK9W7dNZU/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "04596":
        name = "Ahmed Sameh";
        degree = "23+2=<span style='color:#ff2e63;'>25</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1eQRiqQYtqf7bNRXAgBP-2GYe1Ygr7Ppp/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "23069":
        name = "Youssef Hassan";
        degree = "46+2=<span style='color:#ff2e63;'>48</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1XSo4FGdnKdw2xxfqn9e00romc_y-eMfp/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "72137":
        name = "Rodina Ayman";
        degree = "37+2=<span style='color:#ff2e63;'>39</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1VP9zAfazqYANftnvR9FF0beDTTbTafuz/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "73057":
        name = "Omar Hany";
        degree = "35+2=<span style='color:#ff2e63;'>37</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1YmsHB5KeSDjRUMWbryk5RZrFkFt6Zn7j/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "88105":
        name = "Sandy Essam Mohamed";
        degree = "30+2=<span style='color:#ff2e63;'>32</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1G6seba1jn0b1W9zQgpwgYEto8v-PPYgt/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "41729":
        name = "Moamen Ghareb";
        degree = "28+2=<span style='color:#ff2e63;'>30</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/15TeLxKwgJpnsEhVU0dpOloq7wBFJo7SA/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "69897":
        name = "Arwa Ahmed";
        degree = "37+2=<span style='color:#ff2e63;'>39</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1iajTf-eYsUavg1wsY-2ToCtofRFtIL9m/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "15032":
        name = "Tasneem";
        degree = "44+2=<span style='color:#ff2e63;'>46</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1VIh6yBBK06yauU2a2aDueLQM8OSCaxzz/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "80650":
        name = "Ahmed Ayman Raafat";
        degree = "48+2=<span style='color:#ff2e63;'>50</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1evQdYoPuMX33Gyiz3rvwbAPxBOcPjs_5/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "81463":
        name = "Ahmed Nagih Anwar";
        degree = "35+2=<span style='color:#ff2e63;'>37</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1-aj6RjPaxd91PiHDzswP-IvLlbAWD5Sf/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "23849":
        name = "Farah Emad";
        degree = "37+2=<span style='color:#ff2e63;'>39</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1uz7iLl9gUtv-Zw5p-7gyb1vtTpr7OTBO/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "15290":
        name = "Mohamed Amr";
        degree = "29+2=<span style='color:#ff2e63;'>31</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1Yo6bO6vzk9sEaCuHEcx2NTj-LKBvu7cx/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "66908":
        name = "Ahmed Mohammed Abdullatief";
        degree = "54+2=<span style='color:#ff2e63;'>56</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1vyD3rtpd9TGEy6YSCyKOmHN5To_TIQeH/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "45645":
        name = "Omnia";
        degree = "38+2=<span style='color:#ff2e63;'>40</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1iRYEjEcToNkR2vOPpjYOU6jukiggn90A/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "91846":
        name = "Sara Emad";
        degree = "27+2=<span style='color:#ff2e63;'>29</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1Nj9iEsf3LvxIwcMlP8H5tOvgfnPedCvO/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "80546":
        name = "Mazen Ahmed Samir";
        degree = "42+2=<span style='color:#ff2e63;'>44</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1sNoQkQDVEdntcOXYlxukhohdvLoJXYW1/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "22030":
        name = "Habiba Ahmed Abdelraouf Mostafa";
        degree = "35+2=<span style='color:#ff2e63;'>37</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1_gkyH1UPFCATYhxjCAhwzJGTLd8YsT7B/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "19153":
        name = "Shahd Saeed";
        degree = "25+2=<span style='color:#ff2e63;'>27</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1romSgW7unvpzvxsw-3GdPz_6XA5ARrGf/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "25695":
        name = "Vera Essam Adly";
        degree = "25+2=<span style='color:#ff2e63;'>27</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/14Zz3zXtuWZqpoiRBeAOkJwNXznt2OUrD/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "56302":
        name = "Yassin Mohamed";
        degree = "33+2=<span style='color:#ff2e63;'>33</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1gEZj8dPZGyrpzD3G2kNNF42Kd0CJV3ff/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "16840":
        name = "Sama Ibrahim";
        degree = "30+2=<span style='color:#ff2e63;'>32</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1a4wc1dBKVQXgUYpZT0fJr-0DIAMK7iyC/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "68450":
        name = "Malak Ashraf";
        degree = "29+2=<span style='color:#ff2e63;'>31</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1jY43bzf5-VqLOKoI-uYkucbm54c1C3cf/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "70126":
        name = "Mazen Mohamed";
        degree = "40+2=<span style='color:#ff2e63;'>42</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1HfhZLMR-O1VwornqmVYBCCv8yGwG3POS/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
        break;
    case "08724":
        name = "Abdel-wahab Abdel-rahman";
degree = "39+2=<span style='color:#ff2e63;'>41</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1-vdO8_rHoQMHARsOAuXgkSA9TkKUcDOl/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
                break;
       case "64159":
        name = "Ziad Mohamed";
        degree = "22+2=<span style='color:#ff2e63;'>24</span>/60";
        motivationalMessage = "Great job! You're on your way to amazing things!🤩";
        resource = "<a href='https://drive.google.com/file/d/1detmq0OUs3-a1C0gzAalQ_vf8US_1O_g/view?usp=drive_link' target='_blank' style='color: red;'>Download your answers (PDF)</a>";
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
