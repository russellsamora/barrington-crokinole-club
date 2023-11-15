<ul>
	<li>
		<a
			href="https://barrington-crokinole-club.printify.me/product/3553437/barrington-crokinole-club-bear"
			target="_blank"
			rel="noreferrer"
		>
			<img src="assets/shirt-bear.jpg" alt="bear t-shirt" />
		</a>
	</li>
	<li>
		<a
			href="https://barrington-crokinole-club.printify.me/product/3553435/barrington-crokinole-club-hanger"
			target="_blank"
			rel="noreferrer"
		>
			<img src="assets/shirt-hanger.jpg" alt="hanger t-shirt" />
		</a>
	</li>
	<li>
		<a
			href="https://barrington-crokinole-club.printify.me/product/3556082/barrington-crokinole-club-say-anything"
			target="_blank"
			rel="noreferrer"
		>
			<img src="assets/shirt-say-anything.jpg" alt="say anything t-shirt" />
		</a>
	</li>
</ul>

<style>
	ul {
		list-style-type: none;
		display: flex;
		flex-direction: column;
		max-width: 640px;
		margin: 32px auto;
		padding: 0;
	}

	li {
		text-align: center;
		margin: 16px 0;
		background: var(--color-bg);
	}

	img {
		outline: 4px solid var(--color-red);
		border-radius: 16px;
		padding: 16px;
	}

	a:hover img {
		outline: 8px solid var(--color-red);
	}

	@media (min-width: 600px) {
		ul {
			flex-direction: row;
		}

		li {
			margin: 0 16px;
		}

		li:first-of-type {
			margin-left: 0;
		}

		li:last-of-type {
			margin-right: 0;
		}
	}

	@media (hover: hover) and (pointer: fine) {
		li:hover {
			transform: scale(1.67);
			transform-origin: center 100%;
			transition: transform 0.1s;
		}
	}
</style>
