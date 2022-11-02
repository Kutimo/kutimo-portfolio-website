<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" />
<link
	href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&family=Poppins:ital,wght@0,500;0,700;1,300;1,400&display=swap"
	rel="stylesheet"
/>

<style>
	:root {
		--main_color: #101357;
		--main_75_color: #101457b4;
		--secondary_color: #626262;
		--light_color: #ffffff;
		--light_75_color: #ffffffe3;
		--dark_color: #000000;
	}

	:global(*) {
		margin: 0;
		padding: 0;
		--header_style: 'Montserrat, sans-serif';
	}
	:global(p, button) {
		font-family: poppins, sans-serif;
		font-weight: lighter;
		font-size: 1rem;
		line-height: calc(1ex / 0.32);
	}
	:global(li) {
		font-size: 1rem;
	}

	:global(h1) {
		font-family: 'montserrat, sans-serif';
		font-weight: bold;
		font-size: 4rem;
		line-height: 100%;
	}
	:global(h2) {
		font-family: 'montserrat, sans-serif';
		font-weight: bold;
		font-size: 2.5rem;
		line-height: 100%;
	}
	:global(h3) {
		font-family: 'montserrat, sans-serif';
		line-height: 100%;
		font-size: 1.3rem;
	}

	:global(body, html) {
		background-color: var(--main_color);
		width: 100%;
	}
</style>
