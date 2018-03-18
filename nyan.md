---
layout: default
---
# Yay, this is nyan!
## What is nyan?
I dont't know yet XD

<button class="btn" onclick="let logObject = document.querySelector('#log');if (log.style.display === 'none') {log.style.display = 'block';} else {log.style.display = 'none';}">Show/Hide Log</button>
<div id="log" style="display: none">
	<script type="text/javascript" async>(function() {
		for (let i = 1; i <= 500; i++) {
			window.console.log('Repeated ' + i + ' time' + (i !== 1 ? 's' : ''));
			document.write('Repeated ' + i + ' time' + (i !== 1 ? 's' : '') + '<br>');
			window.alert('Repeated ' + i + ' time' + (i !== 1 ? 's' : ''));
		}
	})();</script>
</div>
