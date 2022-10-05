<section class="projects">
	<h2>Projects</h2>
	<div class="cards">
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui. lit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui. lit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui Elit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui Elit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui Elit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<div class="card">
			<img src="./images/placeholderimg.jpg" alt="textytext" />
			<p>Tempor nisi aliquip proident qui Elit eiusmod dolor eiusmod commodo laboris do culpa.</p>
		</div>
		<button>More projects</button>
	</div>
</section>

<style>
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
		width: 600px;
		height: 1px;
		margin-left: 20px;
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
		box-shadow: 8px 8px 0px 10px rgba(0, 0, 0, 0.5);
		transition: all 0.3s ease-out;
		transition-delay: 200ms;
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
		border-radius: 0%;
		height: 30 0px;
		width: 300px;
		object-fit: cover;
		padding: 0px;
		transition: all 0.3s ease-out;
		transition-delay: 0ms;
	}
	img:hover,
	img {
		transition-delay: 250ms;
	}
	p {
		color: var(--light_color);
		background: var(--main_75_color);
		border-radius: 21px;
		padding: 10px;
		margin: 15px;
		text-align: center;
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
		background-image: url("/images/project_button.svg");
        height: 10%;
        width: 5%;    
        background-repeat: no-repeat;
        margin-left: 10px;
	}
</style>
