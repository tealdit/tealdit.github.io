---
layout: page
title: Shared tweets via tealdit
permalink: /timeline/
---

<script type="text/javascript">
function getUtmSource () {
	var utm_source = window.top.location.search.substr(window.top.location.search.indexOf("utm_source=")).split('&')[0].split('=')[1];
	if(utm_source == 'undefined'){
		utm_source = 'https://twitter.com/search?q=tealdit';
	}else{
		utm_source = 'https://twitter.com/search?q=' + utm_source;
	}

	document.write('<a class="twitter-timeline" data-dnt="true" href="'+utm_source+'" data-widget-id="669483545673515008">Tweets Timeline</a>');

}
</script>


<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>