<div class="side_nav">
	<a href="mailto:test@test.com"><p>blblabla@mail.com</p></a>
	<img src="/images/line.svg" alt="n/a" />
</div>

<style>
	@media (max-width: 1023px) {
		.side_nav,
		a,
		img {
			display: none;
		}
	}
	@media (min-width: 1024px) {
		.side_nav {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: flex-end;
		}
	}
	.side_nav {
		width: 10%;
		height: 100vh;
		right: 0px;
		left: auto;
		position: fixed;
		text-align: center;
	}
	p {
		transform: rotate(90deg);
		margin-bottom: 50%;
	}
	a {
		text-decoration: none;
		color: var(--light_75_color);
	}
	p:hover {
		color: var(--light_color);
		transition-delay: 300ms;
		transition: all 1.5s ease-out;
		font-size: 2rem;
		text-decoration: underline;
	}
</style>
