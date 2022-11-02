<header>
	<img src="/images/logo.svg" alt="Kutimo logo" id="logo" />

	<ul>
		<li>
			<a href="#About">About</a>
		</li>
		<li>projects</li>
		<li>Contact</li>
	</ul>
	<img src="/images/hamMenu.svg" alt="Menu button" id="HamMenu" />
</header>

<style>
	@media (max-width: 1023px) {
		ul {
			display: none;
		}
		#HamMenu {
			display: block;
		}
	}
	@media (min-width: 1024px) {
		#HamMenu {
			display: none;
		}
	}
	header {
		background: var(--dark_color);
		display: flex;
		border-bottom: 1px solid var(--light_color);
		align-items: center;
		justify-content: space-between;
		width: 100%;
		height: 15vh;
	}
	#logo {
		background-color: var(--dark_color);
		height: 2.5rem;
		width: auto;
		padding: 15px;
	}

	li {
		padding: 0.8rem;
		color: var(--light_color);
		list-style-type: none;
		display: inline;
		margin: 0.8rem;
	}
	a {
		color: var(--light_color);
		text-decoration: none;
	}
	a:hover {
		color: var(--main_color);
	}
	#HamMenu {
		height: 2rem;
		padding: 0.8rem;
	}
</style>
