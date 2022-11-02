<main>
	<p>Hello, I am</p>
	<h1>
		Marius Kristiansen. <br />
		I design <span class="greyText">web things.</span>
	</h1>
	<p>
		Aspiring web developer that has a nose for details and the small things that make a big impact
		for your project and brand.
	</p>
	<button type="button">Check out my builds and projects!</button>
</main>

<style>
	main {
		display: flex;
		align-items: flex-start;
		flex-direction: column;
		width: 70%;
		margin: 4% auto;
	}
	h1 {
		color: var(--light_color);
		padding: 0.2rem;
	}
	.greyText {
		color: var(--secondary_color);
	}
	p {
		color: var(--light_color);
		width: 30ch;
		padding: 0.2rem;
	}

	button {
		background-color: transparent;
		color: var(--light_color);
		border: 1px solid var(--light_color);
		padding: 0.5rem;
		height: 30%;
		margin-top: 1%;
		width: fit-content;
		height: 10vh;
	}
	button:hover {
		box-shadow: 4px 4px 0px 4px rgba(0, 0, 0, 0.5);
		transition: all 0.3s ease-out;
		cursor: pointer;
	}
</style>
