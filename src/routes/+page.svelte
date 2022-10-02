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
	<p>
		I'm an aspiring Front-End Developer located in Norway.I have a serious passion for design, and
		for creating intuitive, dynamic and of course responsive.
	</p>
	<p>
		After almost 10 years in the hospitality industry (specialising in wine, bar and fine dining ).
		I decided to take my talents into a different industry where I strongly believe my problem
		solving skills, an eye for detail and interpersonal skills that are very much transferrable.
	</p>
	<p>
		Interested in the entire frontend spectrum and working on ambitious projects with like minded
		people.
	</p>
	<p>Let's make something exceptional together!</p>
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
</style>
