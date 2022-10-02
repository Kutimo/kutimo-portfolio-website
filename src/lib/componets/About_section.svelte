<section>
	<h2>About me</h2>
	<div class="about_me_section">
		<div class="about_me_text">
			<p>
				Aspiring Front-End Developer located in Norway. With a serious passion for design,
				and creating intuitive, dynamic and of course responsive projects.
			</p>
			<p>
				Interested in the entire frontend spectrum and working on ambitious projects with like
				minded people.
			</p>
			<p class="tech_header">Here are a few technologies I've been working with recently:</p>
           <div class="tech">
            <ul>
                <li>JavaScript  (ES6+)</li>
                <li>Svelte</li>
                <li>Vite.js</li>
            </ul>
                <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Figma</li>
            </ul>
        </div>
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
		margin: 10% auto;
	}
	h2 {
		display: flex;
		align-items: center;
		padding-left: 10px;
	}
	h2::after {
		content: '';
		width: 500px;
		height: 1px;
		margin-left: 20px;
		background-color: var(--light_color);
	}
	p {
		padding: 15px;
		width: 40ch;
		line-height: calc(1ex / 0.32);
	}
	.about_me_section {
		display: flex;
		justify-content: space-between;
		padding: 10px;
        margin-top: 2%;
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
    .tech_header {
        font-size: 1rem;
        width: 100%;
    }
    .tech {
        width: 70%;
        display: flex;
        justify-content: space-around;
        margin: auto;
        gap: 20px;
    }
    ul {
        list-style: none;
        width: 100%;
    }
    li {
        padding: 2%;
    }
    li::before {
      content: url(../images/libracket.svg);
     padding: 5px;
     margin-top: 5px;
    }

</style>
