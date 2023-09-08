<div class="window w-fit grid place-content-center !text-base">
	<div class="postcard">
		<header>
			<h1>My Postcard</h1>
			<img
				src="https://raw.githubusercontent.com/breatheco-de/exercise-postcard/e63a7916530cc850bd92aa1c2e19191837fb5c80/.learn/assets/4geeks.png"
				alt="4Geeks Academy Logo"
			/>
		</header>
		<main>
			<div class="left">
				<p>
					Look how awesome! I created this by using HTML5 and CSS3 during my
					4Geeks Academy Course!
				</p>
				<p>This is so cool! I can't wait to start doing more stuff!</p>
			</div>
			<form class="right" action="/" method="POST">
				<input type="text" placeholder="To: Jr. and Lani" />
				<input type="text" placeholder="example@x.com" />
				<input type="text" placeholder="Mommy loves you!" />
			</form>
		</main>
		<button type="submit" form="form1">Send My Postcard</button>
	</div>
</div>

<style>
	.postcard {
		padding: 20px;
		border-radius: 0.5rem;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		width: 450px;
		height: fit-content;
		background: white;
		margin: auto;
		color: black;
	}

	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	header img {
		width: 55px;
		height: 55px;
		margin: 5px;
	}

	header h1 {
		font-size: 2.5rem;
		font-weight: bolder;
		color: rgb(255, 23, 62);
	}

	main {
		display: flex;
		justify-content: space-between;
	}

	main .left,
	main .right {
		padding: 10px;
		width: 50%;
		text-align: justify;
	}

	main .left {
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}

	main p:first-child {
		margin-bottom: 10px;
	}

	p {
		line-height: 1.5;
	}

	form.right input {
		font-size: 1rem;
		border: none;
		border-bottom: 1px rgb(255, 23, 62) solid;
		width: 100%;
	}

	form {
		display: flex;
		flex-direction: column;
		justify-content: space-around;
	}

	button {
		background-color: rgb(255, 23, 62);
		padding: 10px;
		border-radius: 5px;
		color: white;
		font-weight: bolder;
		width: 100%;
		font-size: 1rem;
		text-align: center;
	}

	button:hover {
		color: #148fcb;
		background-color: rgba(255, 0, 0, 0.521);
	}

	button:active {
		color: green;
	}
</style>
