# Summary #
This plugin "jquery-scrollview" enables the content wrapping is disabled (ex. huge image) to grab-and-drag scrolling like Google Map.

# Functions #
  * grab and drag scrolling.
  * drawing the position to the center by double-click.

# Code Sample #

## HTML Body ##
```
<body>
<div id="map">
 <div>
   <img src="largepicture.jpg" width="1024" height="768" />
 </div>
</div>
</body>
```

## JavaScript ##
import jQuery libraries and attachment.
```
<script src="jquery-1.3.1.min.js" type="text/javascript"></script>
<script src="jquery.scrollview.js" type="text/javascript"></script>
<script type="text/javascript">
$(document).ready(function(){
  $("#map").scrollview({
    grab:"images/openhand.cur",
    grabbing:"images/closedhand.cur"
  });
});
</script>
```