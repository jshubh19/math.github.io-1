## HTML

Create a anyName.html file

Use this code given below to create input boxes and for  submit button .   

```html
	<!-- anyName.html -->
	<div class="container">
			<div class="">
				<h3></h3>
			</div>
			<div class="row">
				<div class="col-sm-3 col-md-4">
				    <form class="" action="Arithmetic.php" method="get" id="form">
						<div class="form-group">
							<label for="input1">
								Input First: 
							</label>
							<input type="text" name="input1" placeholder="Enter First Input" required="" class="form-control" id="input1">
						</div>
						<br>
						<div class="form-group">
							<label for="input2">
								Input Second:
							</label>
							<input type="text" name="input2" id="input2" placeholder="Enter Second Input"required="" class="form-control" >
						</div>
						<br>
						<div class="form-group">
							<label>
								Operation:
							</label>
							<select class="form-control" id="select" name="select">
								<option>Choose A Option from Here </option>
								<option>Addition</option>
								<option>Subtraction</option>
								<option>Multiplication</option>
								<option>Division</option>
							</select>
						</div>
						<br>
						<button type="submit" name="submit" class="btn btn--default" value="submit" id="sub1">Submit</button>
					</form>
				</div>	
			</div>		
		</div>
		<br>
```

## Result Box

To create a result Box just import this code in your anyName.html file.

```html	
		<div class="container">
		<button type="button" name="button" id="btn1" class="btn btn-info" value="Result">Result</button>
	</div>
	<br>
	<div class="container" id="con">
		<div class="row">
			<div class="col-md-4 col-sm-6">
				<div class="form-group" >
				<input type="text" name="txt" id="result" placeholder="Result of Arithmetic Operation" class="form-control">
				</div>
			</div>
		</div>
	</div> 			

```
## Classes & Tag

A html tag is always enclosed between less than < and greated than > sign.   

div Tag The div tag is an empty container, which defines a division or a section. It has no effect on the content or layout and is used to group HTML elements to be styled with CSS or manipulated with scripts. ... To apply styles inside a paragraph use span tag, which is used with inline elements.

h1,h2,h3... is for headings.

input html tag is used for creating input boxes on webpages.

select html tag is used to create dropdown list .

button html tag is used to create buttons on html webpages.

br tag is for linebreak.

## Form & Its Method

form Tag. The form tag in HTML is used to create form for user input. There are many elements which are used within form tag. For example: input, textarea, button, select, option, optgroup, fieldset, label.	

action in form is use to call the file when submit button is clicked.

## GET & POST

Forms in HTML can use either method by specifying method="POST" or method="GET" (default) in the form element.
When the method is GET, all form data is encoded into the URL, appended to the action URL as query string parameters. With POST, form data appears within the message body of the HTTP request.


