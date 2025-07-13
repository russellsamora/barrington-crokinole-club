<script>
	import Store from "$components/Store.svelte";
</script>

<section>
	<h1>Barrington <br />Crokinole Club</h1>

	<p class="description">
		<small
			>A regular meetup in South Berkshire County. All ages and levels are
			welcome!</small
		>
	</p>

	<p>
		<small>Next Event</small><br />
		<strong>Mondays @ 7:30 &mdash; Lucy’s Rendezvous</strong>
		<!-- <strong>TBD</strong> -->
	</p>

	<p class="top">Get notified about upcoming events:</p>

	<p>
		<a
			class="btn"
			href="https://barrington-crokinole-club.beehiiv.com/subscribe"
			target="_blank"
			rel="noreferrer"
			>Join the mailing list
		</a>
	</p>

	<p class="top">
		New to Crokinole? Watch this <a
			href="https://youtu.be/R-6hdqdYPpE"
			target="_blank"
			rel="noreferrer">YouTube video.</a
		>
	</p>

	<Store />

	<p class="top">Get in touch: russell@barringtoncrokinole.club</p>
</section>

<style>
	section {
		max-width: 60em;
		margin: 0 auto 96px auto;
		padding: 16px;
	}

	h1 {
		font-size: clamp(42px, 7vw, 96px);
		text-transform: uppercase;
		font-weight: 900;
		line-height: 1;
		text-align: center;
		margin: 32px auto;
	}

	p {
		font-size: clamp(16px, 4vw, 32px);
		line-height: 1.4;
		margin: 16px auto;
		text-align: center;
	}

	.btn {
		display: inline-block;
		background: var(--color-red);
		color: var(--color-fg);
		padding: 16px 32px;
		line-height: 1;
		font-weight: 900;
		text-decoration: none;
		border: none;
		text-align: center;
		text-transform: uppercase;
		border-radius: 16px;
	}

	p.description {
		line-height: 1.125;
	}
</style>
