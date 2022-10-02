<script>
	import Globalcss from '../lib/componets/globalcss.svelte';
</script>

<div class="error">
	<img src="/images/bracket_left.svg" alt="bracket" />
	<h1>
		40<span class="flick">4</span> <br />
		<span>page not found </span>
	</h1>
	<img class="swing" src="/images/bracket_right.svg" alt="bracket" />
</div>

<style>
	.error {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
		width: 100vw;
	}
	h1 {
		text-align: center;
	}
	span {
		color: var(--light_color);
	}
	img {
		height: 30%;
		margin-top: 40px;
		padding: 20px;
	}
	.flick {
        -webkit-animation: flicker-1 0.9s linear infinite backwards;
	        animation: flicker-1 1.9s linear infinite backwards;
	}
   
	.swing {
		margin-top: 24%;
		animation: swing ease-in-out 2s infinite alternate;
		transform-origin: left -20px;
	}

	.swing:after {
		transform: rotate(45deg);
	}

	@keyframes swing {
		0% {
			transform: rotate(6deg);
		}
		100% {
			transform: rotate(-6deg);
		}
	}



    @-webkit-keyframes flicker-1 {
  0%,
  100% {
    opacity: 1;
  }
  41.99% {
    opacity: 1;
  }
  42% {
    opacity: 0;
  }
  43% {
    opacity: 0;
  }
  43.01% {
    opacity: 1;
  }
  47.99% {
    opacity: 1;
  }
  48% {
    opacity: 0;
  }
  49% {
    opacity: 0;
  }
  49.01% {
    opacity: 1;
  }
}
@keyframes flicker-1 {
  0%,
  100% {
    opacity: 1;
  }
  41.99% {
    opacity: 1;
  }
  42% {
    opacity: 0;
  }
  43% {
    opacity: 0;
  }
  43.01% {
    opacity: 1;
  }
  47.99% {
    opacity: 1;
  }
  48% {
    opacity: 0;
  }
  49% {
    opacity: 0;
  }
  49.01% {
    opacity: 1;
  }
}
</style>
