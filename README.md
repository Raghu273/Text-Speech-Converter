#html code

<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport"
		content="width=device-width, initial-scale=1.0">
	<title>Orati-Text to Speech Converter</title>
    <link rel="icon " href="/text.png">
	<link rel="stylesheet" href="speech.css">
    
</head>

<body>
    
 
	<div class="container">
        
		<div class="app-container">
			<div class="headings-container">
                <h4>RRK Corp©</h4>
               
                <h1><img src="/Black_and_Purple_Gradient_Modern_Studio_Logo-removebg-preview.png"></h1>
				<h1>
					Text to Speech<span>  Converter </span>
				</h1>
                
			</div>

			<div class="interaction-container">
				<textarea id="textToConvert"
						placeholder="Type here..."
			             cols="105"
						rows="18" class="text-control">
				</textarea>
				<p class="error-para"></p>
				<button class="btn" id="convertBtn">Play</button>
			</div>
		</div>
	</div>

	<script src="scp.js"></script>
</body>

</html>
