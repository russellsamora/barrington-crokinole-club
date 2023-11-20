<script>
	import Store from "$components/Store.svelte";
</script>

<section>
	<h1>Barrington <br />Crokinole Club</h1>

	<p>A monthly meetup in South Berkshire County.</p>

	<p>All levels and ages are welcome!</p>

	<p><strong>Next meetup: TBD</strong></p>

	<p>
		<a
			class="btn"
			href="https://forms.gle/6GfKgu41sHh7gqc87"
			target="_blank"
			rel="noreferrer"
			>Stay updated
		</a>
	</p>

	<p>
		New to Crokinole? Watch this <a
			href="https://youtu.be/R-6hdqdYPpE"
			target="_blank"
			rel="noreferrer">YouTube video.</a
		>
	</p>

	<p>Support the club and buy a shirt!</p>

	<Store />

	<p>Get in touch: russellsamora@gmail.com</p>
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
		margin: 64px auto;
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
		margin-bottom: 64px;
	}
</style>
