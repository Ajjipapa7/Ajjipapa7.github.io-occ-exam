<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Result</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #F0F0F0;
        }

        .result-card {
            background-color: #fff;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 400px;
        }

        .score-circle {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: #007bff;
            color: #fff;
            font-size: 36px;
            line-height: 150px;
            margin: 0 auto 20px;
        }

        .summary {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .summary-item {
            text-align: center;
        }

        .summary-item p {
            margin: 5px 0;
        }

        .summary-item span {
            font-weight: bold;
        }

        .continue-button {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .continue-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="result-card">
        <h2>Your Result</h2>
        <div class="score-circle">76<br>of 100</div>
        <h3>Great</h3>
        <p>You scored higher than 65% of the people who have taken these tests.</p>

        <div class="summary">
            <div class="summary-item">
                <p>Reaction</p>
                <span>80/100</span>
            </div>
            <div class="summary-item">
                <p>Memory</p>
                <span>92/100</span>
            </div>
            <div class="summary-item">
                <p>Verbal</p>
                <span>61/100</span>
            </div>
            <div class="summary-item">
                <p>Visual</p>
                <span>72/100</span>
            </div>
        </div>

        <button class="continue-button">Continue</button>
    </div>
</body>
</html>
