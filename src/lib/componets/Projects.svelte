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
	</div>
	<button>More projects</button>
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
	}
	.card {
		display: flex;
		align-items: center;
		flex-direction: column;
		background-color: var(--light_color) ;
		border-radius: 135px 135px 18px 18px;
		height: 430px;
		width: 270px;
	}
   .card:hover {
		filter: grayscale(80%);
		transition-delay: 150ms;
		height: 100%;
		
    }
	img {
		border-radius: 50%;
		height: 226px;
		width: 226px;
		object-fit: cover;
		padding: 15px;
	}
	p {
        color: var(--light_color);
		background: var(--main_75_color);
		border-radius: 21px;
		padding: 10px;
		margin: 15px;
        text-align: center;
	}
</style>
