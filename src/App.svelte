<script>
	export let name;
	let github_img = 'assets/github_btn.svg';
	let portfolio_img = 'assets/portfolio_btn.svg';
</script>

<main>
	<div class="title">
		<h1>Andrew Yurlov</h1>
		<h3>Full Stack Software Engineer</h3>
	</div>
	<div class="buttons">
		<button class="github">
			<img src={github_img} alt="github button image" />
			<p>Github</p>
		</button>
		<button class="portfolio">
			<img src={portfolio_img} alt="portfolio button image" />
			<p>Portfolio</p>
		</button>
	</div>
</main>

<style type="text/scss">
	@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap');

	main {
		max-width: 1000px;
		width: 100%;
		height: 100%;
		display: flex;
		justify-content: space-between;
		align-items: center;

		.title {
			h1 {
				font-family: 'Lato', sans-serif;
				font-size: 64px;
				color: #fefefe;
				font-weight: 900;
				text-shadow: 0px 0px 15px 0px rgba(0,0,0,0.15);
			}

			h3 {
				font-family: 'Lato', sans-serif;
				font-size: 24px;
				color: #ACACAC;
				font-weight: 300;
			}
		}

		.buttons {
			display: flex;
			justify-content: space-between;
			align-items: center;

			.github { margin-right: 10px; }
			.portfolio { margin-left: 10px; }

			button {
				border-radius: 8px;
				padding: 18px 32px;
				background-color: #15161B;
				border: none;
				box-shadow: 0px 0px 15px 0px rgba(0,0,0,0.15);
				display: flex;
				justify-content: space-between;
				align-items: center;

				&:hover {
					background-color: #1E76BD;
				}
				
				img {
					height: 40px;
					width: 40px;
					padding-right: 10px;
				}
				
				p {
					padding-left: 10px;
					font-family: 'Lato', sans-serif;
					font-size: 22px;
					font-weight: 900;
					color: #F0F0F0;
				}
				
			}
			
			

		}
	}
</style>