## JAVA SCRIPT

Use java script code to make your webapp more dynamic and functional.

```javascript
<script type="text/javascript">

	$("document").ready(function(){
            $("#con").fadeOut()
            }); 

	$("Document").ready(function(){
		$("#btn1").click(function(){
			$("#con").slideToggle(3000)
		})
	}); 

	$("Document").ready(function(){
		$('input').focus(function(){
			$(this).css('background','pink')
		})
	});

	$("Document").ready(function(){
		$('input').blur(function(){
			$(this).css('background','white')
		})
	});
</script>
```
## Methods
* fadeOut() is used to hide  a div (whose id is given in function ).
* slideToggle() is used to toggle div box.
* focus() to focus  on particular id and css() for applying style through Java Script.
* blur() to remove focus properties.

## AJAX
AJAX = Asynchronous JavaScript And XML. AJAX is not a programming language. AJAX just uses a combination of: A browser built-in XMLHttpRequest object (to request data from a web server) JavaScript and HTML DOM (to display or use the data)


```AJAX
<script type="text/javascript">

	$("Document").ready(function(){
	$("#sub1").click(function(e) {
		e.preventDefault();
    var val1 = $("#input1").val();
    var val2 = $("#input2").val();
    var select1= $("#select").val();
    $.ajax({
        type: "GET",
        url: "Arithmetic.php",
        data: {
            input1: val1,
            input2: val2,
            select: select1
        },
        success: function(response) {
        	$("#result").val(response);
            //alert(data);
        }   
      
        
    })})}); 
    
</script> 
```

## AJAX Process
* $("Document").ready(function() 

The ready() method is used to make a function available after the document is loaded. Whatever code you write inside the $(document ).ready() method will run once the page DOM is ready to execute JavaScript code.

* e.preventDefault()

The event.preventDefault() method stops the default action of an element from happening. For example: Prevent a submit button from submitting a form. Prevent a link from following the URL.

* $("#id").click()

The click() is an inbuilt method in jQuery that starts the click event or attach a function to run when a click event occurs. Syntax: $(selector).click(function); Parameter: It accepts an optional parameter “function” which is used to run when a click event occurs.

* $.ajax()

$.ajax() method allows you to send asynchronous http requests to submit or retrieve data from the server without reloading the whole page. $.ajax() can be used to send http GET, POST, PUT, DELETE etc. request. It can retrieve any type of response from the server. Syntax: $.ajax(url,[options] 

* success: function()

A success callback that gets invoked upon successful completion of an Ajax request.

* $("#").val(response)

It will get the data that is fetched by the success function after successfull completion of an Ajax request