## JAVA SCRIPT

> JavaScript is an object orient programming language designed to make web development easier and more attractive. In most cases, JavaScript is used to create responsive, interactive elements for web pages, enhancing the user experience.

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
## its Method
* fadeOut() is used to hide  a div (whose id is given in function ).
* slideToggle() is used to toggle div box.
* focus() to focus  on particular id and css() for applying style through Java Script.
* blur() to remove focus properties.

## AJAX
> AJAX = Asynchronous JavaScript And XML. AJAX is not a programming language. AJAX just uses a combination of: A browser built-in XMLHttpRequest object (to request data from a web server) JavaScript and HTML DOM (to display or use the data)


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
