---
title: Timeout Onclick Redirect
description: Redirect 1 second after the page load by triggering the `click` event on a link.
---

<a href="https://www.google.com?onclick" id="anchor">Link</a>

<script>
	setTimeout( function() {
		document.getElementById('anchor').click();
	}, 1000 );
</script>
