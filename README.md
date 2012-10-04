test
====

###test rep

10/3/12
-------
i added this comment

<a href="#">Link Example</a>


How to use
----------

	<script>
		$(document).ready(function() {
			$('.fancybox').fancybox();
		});
	</script>
	
	<head>
		<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
		<link rel="stylesheet" href="/fancybox/jquery.fancybox.css" type="text/css" media="screen" />
		<script type="text/javascript" src="/fancybox/jquery.fancybox.pack.js"></script>
	</head>
	
CHANGE LOG
----------

* Fixed #357 - Converting values like 'auto' in getScalar()
* Fixed #358 - Updated overlay background image
* New "fancybox-href" and "fancybox-title" HTML5 data-attributes (#317)
* Improved helpers:
*     - now they can have a property 'defaults' that contains default settings
*     - updated vimeo and youtube parsers for media helper
* Content locking now can be turned off	