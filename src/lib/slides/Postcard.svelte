<script>
	import { Code, Slide } from '@components'
</script>

<Slide animate>
	<div class="flex">
		<Code data-id="1" lang="html" class="w-1/2" lines="1,9|2,8|3-7">
			{`
<div class="postcard">
	<div class="postcard-header">
		<h1>My Postcard</h1>
		<img
			src="4geeks.png"
			alt="4Geeks Logo"
			/>
	</div>
</div>
			  `}
		</Code>

		<div class="window w-fit grid place-content-center">
			<div class="postcard">
				<div class="postcard-header">
					<h1>My Postcard</h1>
					<img
						src="https://raw.githubusercontent.com/breatheco-de/exercise-postcard/e63a7916530cc850bd92aa1c2e19191837fb5c80/.learn/assets/4geeks.png"
						alt="4Geeks Academy Logo"
					/>
				</div>
			</div>
		</div>
	</div>
</Slide>
<!-- .postcard -->
<Slide animate>
	<div class="flex">
		<div class="w-full">
			<Code lang="html" class="w-full">
				{`
            <div class="postcard" />
                          `}
			</Code>
			<Code data-id="1" lang="css" class="w-full" lines="2-3|5">
				{`
.postcard {
    width: 450px;
    height: 340px;
    background: white;
    margin: auto;
}
`}
			</Code>
		</div>

		<div class="window w-fit grid place-content-center">
			<div class="postcard">
			</div>
		</div>
	</div>
</Slide>

<!-- postcard body -->
<Slide animate>
	<div class="flex">
		<div class="w-full">
			<!-- <Code lang="html" class="w-full">
				{`
<div class="postcard" />
	<div class="postcard-header" />
                          `}
			</Code> -->
			<Code data-id="1" lang="css" class="w-full" lines="2-3|5">
				{`
<div class="postcard" />
	<div class="postcard-header" />
`}
			</Code>
		</div>

		<div class="window w-fit grid place-content-center">
			<div class="postcard">
				<div class="postcard-header">
					<h1>My Postcard</h1>
					<img
						src="https://raw.githubusercontent.com/breatheco-de/exercise-postcard/e63a7916530cc850bd92aa1c2e19191837fb5c80/.learn/assets/4geeks.png"
						alt="4Geeks Academy Logo"
					/>
				</div>
			</div>
		</div>
	</div>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="1" lang="html" class="w-1/2" lines="1,9|2,8|3-7">
			{`
<div class="postcard" />
	<div class="postcard-header">
		<h1>My Postcard</h1>
		<img
			src="4geeks.png"
			alt="4Geeks Logo"
			/>
	</div>
</div>
			  `}
		</Code>

		<div class="window w-fit grid place-content-center">
			<div class="postcard">
				<div class="postcard-header">
					<h1>My Postcard</h1>
					<img
						src="https://raw.githubusercontent.com/breatheco-de/exercise-postcard/e63a7916530cc850bd92aa1c2e19191837fb5c80/.learn/assets/4geeks.png"
						alt="4Geeks Academy Logo"
					/>
				</div>
				<div class="postcard-body">
					<div class="postcard-body">
						<div class="body-left">
							<p>
								Look how awesome! I created this by using HTML5 and CSS3 during
								my 4Geeks Academy Course!
							</p>
							<p>This is so cool! I can't wait to start doing more stuff!</p>
						</div>
						<div class="body-right">
							<input type="text" placeholder="To: Jr. and Lani" />
							<input type="text" placeholder="example@x.com" />
							<input type="text" placeholder="Mommy loves you!" />
						</div>
					</div>
				</div>
				<div class="postcard-footer">
					<button>Send My Postcard</button>
				</div>
			</div>
		</div>
	</div>
</Slide>
<Slide animate></Slide>

<style>
	.window {
		font-size: 14px !important;
	}
	.postcard {
		padding: 20px;
		border-radius: 0.5rem;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		width: 450px;
		height: 340px;
		background: white;
		margin: auto;
		color: black;
	}
	.postcard-header {
		display: flex;
		justify-content: space-between;
		align-items: center;
	}
	.postcard-header img {
		width: 55px;
		height: 55px;
		margin: 5px;
	}
	h1 {
		font-size: 2.5rem;
		font-weight: bolder;
		color: rgb(255, 23, 62);
	}
	.postcard-body {
		display: flex;
		justify-content: space-between;
	}
	.body-left p:first-child {
		margin-bottom: 10px;
	}
	p {
		line-height: 1.5;
	}
	.body-left,
	.body-right {
		padding: 10px;
		width: 50%;
		text-align: justify;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}
	input {
		font-size: 1rem;
		border: none;
		border-bottom: 1px rgb(255, 23, 62) solid;
		width: 100%;
	}
	.postcard-footer {
		text-align: center;
	}
	button {
		background-color: rgb(255, 23, 62);
		padding: 5px 10px;
		border-radius: 5px;
		color: white;
		font-weight: bolder;
		padding: 10px;
		width: 100%;
		font-size: 1rem;
	}
	.body-right {
		font-size: 20px;
	}
	button:hover {
		color: #148fcb;
		background-color: rgba(255, 0, 0, 0.521);
	}
	button:active {
		color: green;
	}
</style>
