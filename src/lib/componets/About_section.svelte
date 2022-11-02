<section>
	<h2>About me</h2>
	<div class="about">
		<div class="about_me_text">
			<p>
				Aspiring Front-End Developer located in Norway. With a serious passion for design, and
				creating intuitive, dynamic and of course responsive projects.
			</p>
			<p>
				Interested in the entire frontend spectrum and working on ambitious projects with like
				minded people.
			</p>
			<p class="tech_header">Here are a few technologies I've been working with recently:</p>
			<div class="tech">
				<ul>
					<li>JavaScript (ES6+)</li>
					<li>Svelte kit</li>
				</ul>
				<ul>
					<li>Node.js</li>
					<li>HTML</li>
				</ul>
				<ul>
					<li>CSS</li>
					<li>Figma</li>
				</ul>
			</div>
		</div>
		<div class="photo_section">
			<div class="img_shadow">
				<img src="/images/photo_me2.jpg" alt="Kutimo" />
			</div>
		</div>
	</div>
</section>

<style>
	@media (max-width: 1023px) {
		.about {
			flex-direction: column;
		}
		img {
			height: 45%;
			width: 30%;
			padding: 0.8rem;
		}
		.img_shadow {
			filter: drop-shadow(14px 13px 0px var(--light_color, 0.5));
		}
	}
	@media (min-width: 1024px) {
		img {
			height: 65%;
			width: 60%;
		}
		img:hover {
			filter: grayscale(80%);
			transition-delay: 150ms;
			height: 100%;
		}
		.img_shadow {
			display: flex;
			justify-content: center;
			align-items: flex-start;
			filter: drop-shadow(14px 13px 0px var(--light_color, 0.5));
		}
	}
	section {
		width: 70%;
		color: var(--light_color);
		display: flex;
		align-items: flex-start;
		flex-direction: column;
		width: 70%;
		margin: 10% auto;
	}
	h2 {
		display: flex;
		align-items: center;
		padding: 0.5rem;
	}
	h2::after {
		content: '';
		width: 10rem;
		height: 1px;
		margin-left: 20px;
		background-color: var(--light_color);
	}
	p {
		padding: 0.5rem;
		width: 40ch;
		line-height: calc(1ex / 0.32);
	}
	.about {
		display: flex;
		justify-content: space-between;
		margin-top: 2%;
	}
	.photo_section {
		display: flex;
		justify-content: center;
		flex-direction: column;
	}

	img {
		object-fit: cover;
		transition: height 1.5s;
	}

	.tech_header {
		width: 100%;
	}
	.tech {
		width: 100%;
		display: flex;
		justify-content: space-around;
		margin: auto;
		gap: 20px;
		color: var(--light_75_color);
	}
	ul {
		list-style: none;
		width: 100%;
	}
	li {
		padding: 0.5rem;
	}
	li::before {
		content: url(../images/libracket.svg);
		padding: 5px;
		margin-top: 5px;
	}
</style>
