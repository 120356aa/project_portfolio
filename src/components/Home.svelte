<script>
	let github_img = 'assets/github_btn.svg';
	let portfolio_img = 'assets/portfolio_btn.svg';
</script>

<main>
	<div class="title">
		<h1>Andrew Yurlov</h1>
		<h3>Full Stack Software Engineer</h3>
	</div>
	<div class="buttons">
		<a href="#" class="github">
			<img src={github_img} alt="github button image" />
			<p>Github</p>
        </a>
		<a href="/#/portfolio" class="portfolio">
			<img src={portfolio_img} alt="portfolio button image" />
			<p>Portfolio</p>
        </a>
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

		@media screen and (max-width: 1400px) { max-width: 800px; }
		@media screen and (max-width: 1000px) {
			max-width: 100%;
			flex-direction: column;
			justify-content: center;
		}

		.title {
			@media screen and (max-width: 1000px) { padding: 30px 0; }
			@media screen and (max-width: 400px) {
				display: flex;
				flex-direction: column;
				justify-content: center;
				align-items: center;
			}

			h1 {
				font-family: 'Lato', sans-serif;
				font-size: 64px;
				color: #fefefe;
				font-weight: 900;
				text-shadow: 0px 0px 15px 0px rgba(0,0,0,0.15);

				@media screen and(max-width: 1400px) { font-size: 50px; }
				@media screen and (max-width: 500px) { font-size: 42px; }
				@media screen and (max-width: 400px) { font-size: 38px; }
				@media screen and (max-width: 360px) { font-size: 32px; }
				
			}

			h3 {
				font-family: 'Lato', sans-serif;
				font-size: 24px;
				color: #ACACAC;
				font-weight: 300;

				@media screen and(max-width: 1400px) { font-size: 20px; }
				@media screen and (max-width: 1000px) { font-size: 18px; }
				@media screen and (max-width: 500px) { font-size: 16px; }
				@media screen and (max-width: 400px) { font-size: 14px; }
			}
		}

		.buttons {
			display: flex;
			justify-content: space-between;
			align-items: center;

			@media screen and (max-width: 1000px) { padding: 30px 0; }
			@media screen and (max-width: 400px) {
				flex-direction: column;
				justify-content: center;
				align-items: center;
			}

			.github {
				margin-right: 10px;
				@media screen and (max-width: 400px) { margin: 0 0 4px 0; }
			}

			.portfolio {
				margin-left: 10px;
				@media screen and (max-width: 400px) { margin: 4px 0 0 0; }
			}

			a {
				border-radius: 8px;
				padding: 18px 32px;
				background-color: #15161B;
				border: none;
				box-shadow: 0px 0px 15px 0px rgba(0,0,0,0.15);
				display: flex;
				justify-content: space-between;
				align-items: center;
                text-decoration: none;

				&:hover {
					background-color: #1E76BD;
				}
				
				@media screen and (max-width: 1400px) { padding: 16px 28px; }
				@media screen and (max-width: 1000px) { padding: 14px 24px; }
				@media screen and (max-width: 500px) { padding: 12px 20px; }

				@media screen and (max-width: 400px) {
					padding: 10px 18px;
					width: 130px;
				}

				@media screen and (max-width: 360px) {
					justify-content: center;
					margin: 0 6px;
				}

				img {
					height: 40px;
					width: 40px;
					padding-right: 10px;

					@media screen and (max-width: 1400px) {
						height: 36px;
						width: 36px;
					}

					@media screen and (max-width: 1000px) {
						height: 32px;
						width: 32px;
					}

					@media screen and (max-width: 500px) {
						height: 28px;
						width: 28px;
					}

					@media screen and (max-width: 400px) {
						height: 24px;
						width: 24px;
					}

					@media screen and (max-width: 360px) {
						height: 20px;
						width: 20px;
					}
				}
				
				p {
					padding-left: 10px;
					font-family: 'Lato', sans-serif;
					font-size: 22px;
					font-weight: 900;
					color: #F0F0F0;

					@media screen and (max-width: 1400px) { font-size: 20px; }
					@media screen and (max-width: 1000px) { font-size: 18px; }
					@media screen and (max-width: 500px) { font-size: 16px; }
					@media screen and (max-width: 400px) { font-size: 14px; }
					@media screen and (max-width: 360px) { font-size: 12px; }
				}	
			}
		}
	}
</style>