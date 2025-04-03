<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasbeeh Counter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: url('https://source.unsplash.com/1600x900/?islamic,tasbeeh') no-repeat center center/cover;
            color: white;
        }
        .container {
            margin-top: 50px;
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
        }
        h1 {
            margin-bottom: 20px;
        }
        .counter {
            font-size: 40px;
            margin: 20px 0;
        }
        button {
            padding: 10px 20px;
            margin: 5px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .increment { background: green; color: white; }
        .reset { background: red; color: white; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Digital Tasbeeh Counter</h1>
        <p class="counter" id="count">0</p>
        <button class="increment" onclick="increment()">+1</button>
        <button class="reset" onclick="reset()">Reset</button>
    </div>
    
    <script>
        let count = 0;
        function increment() {
            count++;
            document.getElementById("count").innerText = count;
        }
        function reset() {
            count = 0;
            document.getElementById("count").innerText = count;
        }
    </script>
</body>
</html>index.io


