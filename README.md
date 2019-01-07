<html>
<body bgcolor style="background-color:#E94196">
<head>
	<title>Javascript Activity 2 - [YOUR NAME HERE]</title>
		<link rel="stylesheet" type="text/css" href="style.css">
		<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
	<center><h1>Tangang  Calculator</h1></center>
<div class="container">
	<div class="row">
		<div class="col-sm-3"></div>
		<div class="col-sm-6">
			<form>
				<div class="form-group"><br><br>
					<label >Value1</label>
					<input type="text" class="form-control" id="Value1">
				</div>
				<div class="form-group">
					<label>Value2:</label>
					<input type="text" class="form-control" id="Value2">
				</div>
				
				<input type="button" class="btn btn-success" value="+ Add" onclick="add()">
				<input type="button" class="btn btn-warning" value="- Subtract" onclick="subtract()">
				<input type="button" class="btn btn-info" value="* Multiply" onclick="multiply()">
				<input type="button" class="btn btn-primary" value="/ Divide" onclick="divide()">


			</form>
			<h3>The answer is: </h3> <h3 id="answer"></h3>
		</div>
		<div class="col-sm-3">
	</div>
</div>
<script type="text/javascript">

	function add()
	{
		var Value1=document.getElementById('Value1').value;
		var Value2=document.getElementById('Value2').value;
		 Value1= Number(Value1);
		 Value2= Number(Value2);
		 var total= Value1+Value2;
		 document.getElementById('answer').innerHTML=total;
		 if(isNaN(Value1)==true || isNaN(value2)==true)
{
alert("Invalid Value")
}
else
{
document.getElementById('answer').innerHTML="Invalid value"
}

{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, hindi naging kayo";
}
if (isNaN(Value2))
{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, hindi naging kayo";
}
	}
	function subtract()
	{
		var Value1=document.getElementById('Value1').value;
		var Value2=document.getElementById('Value2').value;
		 Value1= Number(Value1);
		 Value2= Number(Value2);
		 var total= Value1-Value2;
		 document.getElementById('answer').innerHTML=total;
		if(isNaN(Value1)==true || isNaN(value2)==true)
{
alert("Invalid Value")
}
else
{
document.getElementById('answer').innerHTML="Invalid value"
}

{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, wala namang kayo";
}
if (isNaN(Value2))
{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, wala namang kayo";
}
	}
	function multiply()
	{
		var Value1=document.getElementById('Value1').value;
		var Value2=document.getElementById('Value2').value;
		 Value1= Number(Value1);
		 Value2= Number(Value2);
		 var total= Value1*Value2;
		 document.getElementById('answer').innerHTML=total;
		if(isNaN(Value1)==true || isNaN(value2)==true)
{
alert("Invalid Value")
}
else
{
document.getElementById('answer').innerHTML="Invalid value"
}

{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, hindi pwede kasi walang kayo";
}
if (isNaN(Value2))
{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, hindi pwede kasi walang kayo";
}
	}
	function divide()
	{
		var Value1=document.getElementById('Value1').value;
		var Value2=document.getElementById('Value2').value;
		 Value1= Number(Value1);
		 Value2= Number(Value2);
		 var total= Value1/Value2;
		 document.getElementById('answer').innerHTML=total;
		if(isNaN(Value1)==true || isNaN(value2)==true)
{
alert("Invalid Value")
}
else
{
document.getElementById('answer').innerHTML="Invalid value"
}

{
  document.getElementById("answer").innerHTML = "HINDI PWEDE,  dapat lng na hindi nanging kayo";
}
if (isNaN(Value2))
{
  document.getElementById("answer").innerHTML = "HINDI PWEDE, dapat lng na hindi nanging kayo";
}
	}
	
</script>
</body>
</html>

