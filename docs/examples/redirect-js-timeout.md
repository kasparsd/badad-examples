---
title: Timeout Redirect
description: Redirect 2 seconds after the page load using `document.location`.
---

<script>
	setTimeout( function() {
		document.location = 'https://www.google.com/?timeout';
	}, 2000 );
</script>
