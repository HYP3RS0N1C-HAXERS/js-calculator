# js-calculator

A calculator in JavaScript, and HTML. I used no CSS.

Click the buttons to use the calculator.



	<head>
		<title>Calculator</title>
		<script>
			var eq = "";
			var text;
			var text2;
			function changeTextColor() {
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add1() {
				eq = eq + "1"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add2() {
				eq = eq + "2"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add3() {
				eq = eq + "3"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add4() {
				eq = eq + "4"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add5() {
				eq = eq + "5"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add6() {
				eq = eq + "6"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add7() {
				eq = eq + "7"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add8() {
				eq = eq + "8"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add9() {
				eq = eq + "9"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function Add() {
				eq = eq + "+"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function subt() {
				eq = eq + "-"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function add0() {
				eq = eq + "0"
				text = document.getElementById("textcolor").innerHTML = eq;
			}  
			function mult() {
				eq = eq + "*"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function divide() {
				eq = eq + "/"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function Tan() {
				eq = eq + "Math.tan("
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function Cos() {
				eq = eq + "Math.cos("
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function Sin() {
				eq = eq + "Math.sin("
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function Sqrt() {
				eq = eq + "Math.sqrt("
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function LeftBraket() {
				eq = eq + "("
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function RightBraket() {
				eq = eq + ")"
				text = document.getElementById("textcolor").innerHTML = eq;
			}
			function calculate() {
				text2 = document.getElementById("answer").innerHTML = eval(eq);
			}
		</script>
	</head>
	<body>
		<font id="textcolor"></font><br>
		<font id="answer"></font><br>
		<input type="button" value="1" onclick="add1();">
		<input type="button" value="2" onclick="add2();">
		<input type="button" value="3" onclick="add3();"><br>
		<input type="button" value="4" onclick="add4();">
		<input type="button" value="5" onclick="add5();">
		<input type="button" value="6" onclick="add6();"><br>
		<input type="button" value="7" onclick="add7();">
		<input type="button" value="8" onclick="add8();">
		<input type="button" value="9" onclick="add9();"><br>
		<input type="button" value="0" onclick="add0();">
		<input type="button" value="+" onclick="Add();">
		<input type="button" value="-" onclick="subt();"><br>
		<input type="button" value="*" onclick="mult();">
		<input type="button" value="/" onclick="divide();">
		<input type="button" value="=" onclick="calculate();"><br>
		<input type="button" value="tan" onclick="Tan();">
		<input type="button" value="cos" onclick="Cos();"><br>
		<input type="button" value="sin" onclick="Sin();">
		<input type="button" value="(" onclick="LeftBraket();">
		<input type="button" value=")" onclick="RightBraket();"><br>
		<input type="button" value="sqrt" onclick="Sqrt();">
		<input type="button" value="Clear" onclick="eq='';text = document.getElementById('textcolor').innerHTML = eq;"><br>
	</body>
