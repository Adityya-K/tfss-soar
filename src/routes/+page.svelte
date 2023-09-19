<script>
	import '/src/styles/home.css';
	import Card from '$lib/Card.svelte';
</script>

<div class="home-video">
	<video playsinline autoplay muted loop>
		<source
			src="https://drive.google.com/uc?export=download&id=1ahVqgMlBXWLPQU_4E7GiDWA9lY5FvNlw"
			type="video/mp4"
		/>
		Your browser doesn't support the video toDateString();
	</video>
	<div class="home-title">
		<h1 class="soar-text">SOAR</h1>
		<h1 class="year-text">2023</h1>
	</div>
</div>
<div class="grid-section">
	<div class="grid">
		<div class="grid-item-1">
			<Card>Hallo</Card>
		</div>
	</div>
</div>
