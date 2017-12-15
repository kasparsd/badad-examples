---
title: Timeout Onclick Redirect
---

<a href="https://www.google.com?onclick" id="anchor">Link</a>

<script>
	setTimeout( function() {
		document.getElementById('anchor').click();
	}, 1000 );
</script>
