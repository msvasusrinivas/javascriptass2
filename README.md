<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>button styles</title>
</head>
<body>
    4Q)Create different buttons as shown in figure below. And on clicking each button change the text size,font etc,
    respectively according to the buttons entered.
    <p id="head1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis aperiam in rerum repellendus doloremque
        reiciendis sequi numquam laudantium, fugiat beatae!</p>
    <button id="btn2" onclick="func2()">cilck to change text size</button>
    <button id="btn3" onclick="func3()">click to chenge font color</button>
    <button id="btn4" onclick="func4()">click to font style</button>
    <script>
        let var1 = document.getElementById('head1');
        let btn2 = document.getElementById('btn2');
        let btn3 = document.getElementById('btn3');
        let btn4 = document.getElementById('btn4');
        function func1() {
            let var1 = document.getElementById('head1');
        }
        function func2() {
            btn2.style.fontSize = "100px";
        }
        function func3() {
            btn3.style.color = "red";
            btn3.style.fontSize = "100px";
        }
        function func4() {
            btn4.style.fontStyle = "italic";
            btn4.style.fontSize = "100px";
        }
    </script>
</body>
