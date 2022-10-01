<script>
	import Globalcss from './globalcss.svelte';
	import Header from '../lib/componets/Header.svelte';
	import Side_nav_left from '../lib/componets/Side_nav_left.svelte';
	import Side_nav_right from '../lib/componets/Side_nav_right.svelte';
	
</script>

<Header />
	<Side_nav_left />
	<Side_nav_right/>
	<main>
	<p>Hello, I am</p>
	<h1>
		Marius Kristiansen. <br />
		I design <span class="webthings">web things.</span>
	</h1>
	<p class="intro_text">
		Aspiring web developer that has a nose for details and the small things that make a big impact for your project and brand. 
	</p>
	<button type="button">Check out my <br> previous builds and <br> projects!</button>
</main>

<style>
	main {
	display: flex;
	align-items: flex-start;
	flex-direction: column;
	width: 70%;
	margin: 5% auto;
	
}
	p,
	h1 {
		color: var(--light_color);
		
	}
	.webthings {
		color: var(--secondary_color);
	}
    p{
        
        color: var(--light_color);
		width: 30ch;
    }

	.intro_text{
		padding: 15px;
	}

button {
	background-color: transparent;
	color: var(--light_color);
	border: 1px solid var(--light_color);
	padding: 10px;
	height: 30%;
	font-size: 1.5rem;
	margin-top: 1%;
	width: 30%;
}
button:hover {
	box-shadow: 8px 8px 0px 10px rgba(0, 0, 0, 0.25);
    transition: all 0.3s ease-out;
	cursor: pointer; 
}
</style>
