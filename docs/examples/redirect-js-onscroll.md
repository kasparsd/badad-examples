---
title: On Scroll Redirect
description: Redirect as soon as the user scrolls the page.
---

<script>
	window.onscroll = function() {
		document.location = 'https://www.google.com?onscroll';
	};
</script>

<div style="min-height:9876px;">
	<!-- Ensure we have something to scroll. -->
</div>
