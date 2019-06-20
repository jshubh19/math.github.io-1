## HTML

> Create a anyName.html file

> Use this code given below to create input boxes, submit and result button with  a box for storing result.   

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
