<section class="projects">
	<h2>Projects</h2>
	<div class="cards">
		<div class="card" id="color_run">
			<img src="./images/notTheColorRun.png" alt="Not the color run webiste" />
			<div class="card_text">
				<h3>Not the color run</h3>
				<p>
					A project to make a clone of the Color run, origninally a smaller task but i decided to
					implement JavaScript and a responsive layout
				</p>
			</div>
		</div>
		<div class="card" id="color_run">
			<img src="./images/notTheColorRun.png" alt="Not the color run webiste" />
			<div class="card_text">
				<h3>Not the color run</h3>
				<p>
					A project to make a clone of the Color run, origninally a smaller task but i decided to
					implement JavaScript and a responsive layout
				</p>
			</div>
		</div>
		<div class="card" id="color_run">
			<img src="./images/notTheColorRun.png" alt="Not the color run webiste" />
			<div class="card_text">
				<h3>Not the color run</h3>
				<p>
					A project to make a clone of the Color run, origninally a smaller task but i decided to
					implement JavaScript and a responsive layout
				</p>
			</div>
		</div>
		<div class="card" id="color_run">
			<img src="./images/notTheColorRun.png" alt="Not the color run webiste" />
			<div class="card_text">
				<h3>Not the color run</h3>
				<p>
					A project to make a clone of the Color run, origninally a smaller task but i decided to
					implement JavaScript and a responsive layout
				</p>
			</div>
		</div>

		<button>More projects</button>
	</div>
</section>

<style>
	/* @media (max-width: 1023px) {
		h2::after {
			display: none;
			width: 100px;
		}
	} */

	/* TODO: grid layout? */
	section {
		display: flex;
		justify-content: center;
		flex-direction: column;
		width: 70%;
		margin: 10% auto;
	}

	h2 {
		color: var(--light_color);
		display: flex;
		align-items: center;
		margin-top: 10%;
	}
	h2::after {
		content: '';
		width: 20rem;
		height: 1px;
		margin-left: 1.2rem;
		background-color: var(--light_color);
	}

	.cards {
		display: flex;
		justify-content: space-evenly;
		flex-wrap: wrap;
		gap: 30px;
		padding: 20px;
		margin-top: 5%;
	}
	.card {
		display: flex;
		align-items: center;
		flex-direction: column;
		background-color: var(--secondary_color);
		border-radius: 135px 135px 18px 18px;
		height: 430px;
		width: 270px;
	}
	.card:hover {
		filter: grayscale(80%);
		height: 100%;
		box-shadow: 6px 6px 0px 6px rgba(0, 0, 0, 0.5);
		transition: all 0.3s ease-in-out;
		/* transition-delay: 200ms; */
		cursor: pointer;
	}
	img {
		border-radius: 50%;
		height: 226px;
		width: 226px;
		object-fit: cover;
		padding: 15px;
		transition-delay: 500ms;
	}
	img:hover {
		border-radius: 0.4rem;
		height: 300px;
		width: 300px;
		background-size: cover;
		transition: all 0.3s ease-out;
		background-position: center;
	}
	img:hover,
	img {
		transition-delay: 300ms;
	}
	h3 {
		text-decoration: underline;
	}
	.card_text {
		color: var(--light_color);
		background: var(--main_75_color);
		border-radius: 21px;
		padding: 0.8rem;
		margin: 15px;
		text-align: center;
		height: 30vh;
		width: 20vw;
	}

	button {
		width: 50%;
		height: 35%;
		padding: 10px;
		background-color: transparent;
		color: var(--light_color);
		border: 1px solid var(--light_color);
	}
	button::after {
		position: absolute;
		content: '';
		background-image: url('/images/project_button.svg');
		height: 44px;
		width: 38px;
		background-repeat: no-repeat;
		background-position: center;
		margin-left: 10px;
	}
</style>
