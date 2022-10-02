<script>
	import Globalcss from '../lib/componets/globalcss.svelte';
	import Header from '../lib/componets/Header.svelte';
	import Side_nav_left from '../lib/componets/Side_nav_left.svelte';
	import Side_nav_right from '../lib/componets/Side_nav_right.svelte';
	import Main from '../lib/componets/Main.svelte';
</script>

<Header />
<Side_nav_left />
<Side_nav_right />
<Main />

<section>
	<h2>About me</h2>
	<div class="about_me_section">
		<div class="about_me_text">
			<p>
				I'm an aspiring Front-End Developer located in Norway.I have a serious passion for design,
				and for creating intuitive, dynamic and of course responsive.
			</p>
			<p>
				After almost 10 years in the hospitality industry (specialising in wine, bar and fine dining
				). I decided to take my talents into a different industry where I strongly believe my
				problem solving skills, an eye for detail and interpersonal skills that are very much
				transferrable.
			</p>
			<p>
				Interested in the entire frontend spectrum and working on ambitious projects with like
				minded people.
			</p>
			<p>Let's make something exceptional together!</p>
		</div>
		<div class="photo_section">
		<div class="img_shadow">
			<img src="/images/photo_me2.jpg" alt="" height="282" width="125"/>
		</div>
		
	</div>
	</div>
</section>

<style>
	section {
		width: 70%;
		color: var(--light_color);
		display: flex;
		align-items: flex-start;
		flex-direction: column;
		width: 70%;
		margin: 5% auto;
	}
	h2 {
		display: flex;
		align-items: center;
		padding-left: 10px;
	}
	h2::after {
		content: '';
		width: 300px;
		height: 1px;
		margin-left: 20px;
		background-color: var(--light_color);
	}
	p {
		padding: 15px;
		width: 40ch;
	}
	.about_me_section {
		display: flex;
		justify-content: space-between;
		padding: 5px;
	}
	.photo_section{
		display: flex;
		justify-content: center;
		flex-direction: column;
	}
	.img_shadow {
		
		display: flex;
		justify-content: center;
		align-items: flex-start;
		filter: drop-shadow(14px 13px 0px var(--light_color, 0.5));
	}
	img {
		object-fit: cover;
		height: 90%;
		width: 60%;
		transition: height 1.5s;
	}

	img:hover {
		filter: grayscale(80%);
		transition-delay: 150ms;
		height: 100%;
		
	}
</style>
