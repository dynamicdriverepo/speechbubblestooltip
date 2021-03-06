# Speech Bubbles Tooltip #

*Description:*  Speech Bubbles Tooltip lets you add tooltips to links using either the value of the link's title attribute, or rich HTML defined all inside a single HTML file and fetched using Ajax instead. The style of the tooltip is modelled after the iconic speech bubble and uses NO images, thanks to the CSS triangle technique.

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.4 or above (served via Google CDN)
+ speechbubbles.js
+ speechbubbles.css
+ speechdata.txt (sample external file containing the markup for the tooltips)

*Step 2:* Add the below code to the HEAD section of your page:

	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.min.js"></script>
	
	<link rel="stylesheet" type="text/css" href="speechbubbles.css" />
	
	<script src="speechbubbles.js">
	
	/***********************************************
	* Speech Bubbles Tooltip- (c) Dynamic Drive (www.dynamicdrive.com)
	* This notice MUST stay intact for legal use
	* Visit http://www.dynamicdrive.com/ for this script and 100s more.
	***********************************************/
	
	</script>
	
	<script type="text/javascript">
	
	jQuery(function($){ //on document.ready
	 	//Apply tooltip to links with class="addspeech", plus look inside 'speechdata.txt' for the tooltip markups
		$('a.addspeech').speechbubble({url:'speechdata.txt'})
	})
	
	</script>


*Step 3:* Then, add the below sample markup to your page:

	<p><a href="http://tools.dynamicdrive.com/imageoptimizer/" class="addspeech" rel="#speechbubble1">Image 
	Optimizer</a> lets you easily optimize regular gifs, animated gifs, jpgs, and pngs, so they load as fast as possible. A fan of ribbons? Create alternating colored horizontal rules quickly using the <a href="http://tools.dynamicdrive.com/ribbon/" class="addspeech" rel="#speechbubble2">Ribbon Rules Generator</a>. Or, generate a gradient image using <a href="http://tools.dynamicdrive.com/gradient/" class="addspeech" rel="#speechbubble3">Gradient Image Maker</a>. And last but not least, if your site is missing a favourite icon- a 16x16 icon of your site shown in the user's location bar- generate one now using <a href="http://tools.dynamicdrive.com/favicon/" class="addspeech" rel="#speechbubble4">FavIcon Generator</a>.</p>
	
	<p>While all of the above tooltips have their contents defined inside a <a href="speechdata.txt">single external file</a>, the following simply use the <b>title attribute</b> of their respective links to make up the tooltip: Visit
	<a href="http://www.javascriptkit.com/" class="addspeech" title="Comprehensive JavaScript tutorials and over 400+ free scripts!">JavaScript Kit</a> for JavaScript tutorials! <a target="_partner" href="http://www.cssdrive.com/" class="addspeech" title="Categorized CSS gallery and examples!">CSS Drive</a> showcases some of the most attractive, CSS driven sites on the net.</p>

## Speech Bubbles Tooltip ##

See script project page for additional details on setup and documentation: <http://www.dynamicdrive.com/dynamicindex5/speechbubblestooltip.htm>
