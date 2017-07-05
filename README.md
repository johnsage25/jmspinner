## JmSpinner v1


JmSpinner is a light weight Jquery and Css preloader for your website. It adds Ajax loading or waiting animation to your website.

### Markdown

It is very light weight and easy to use!

```markdown
#Installation
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
	<script type="text/javascript" src="js/jm.spinner.js"></script>
	<link rel="stylesheet" type="text/css" href="css/jm.spinner.css">


# Default
$('#handler').jmspinner();

#Options

1. Small
2. Big
3. Default (You have to leave argument variable empty e.g $('#handler').jmspinner(argument)).

    <script type="text/javascript">	
		$(function(){
		
			$('#handler').jmspinner();
			$('#handler_small').jmspinner('small');
			$('#handler_big').jmspinner('big');

		

			
		})
	</script>
To remove Jm.Spinner just add false. Like this $('#handler_big').jmspinner(false);




```

