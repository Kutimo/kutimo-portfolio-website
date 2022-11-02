<script></script>

<div class="side_img">
	<img src="/images/ld.svg" alt="Linkedin link" />
	<img src="/images/git.svg" alt="Github link" />
	<img src="/images/account.svg" alt="Account link" />
	<img src="/images/line.svg" alt="n/a" />
</div>

<style>
	@media (max-width: 1023px) {
		.side_img {
			display: none;
		}
	}
	@media (min-width: 1024px) {
		.side_img {
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: flex-end;
		}
	}
	.side_img {
		width: 10%;
		height: 100vh;
		left: 0px;
		right: auto;
		position: fixed;
	}
	img {
		padding: 5px;
	}
</style>
