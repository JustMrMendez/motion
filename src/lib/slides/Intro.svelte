<script>
	import DonePostcard from './DonePostcard.svelte'

	import Csslogo from './Csslogo.svelte'

	import { Code, Slide } from '@components'
	import Cssawesome from '@lib/slides/Cssawesome.svelte'
	import Htmllogo from '@lib/slides/Htmllogo.svelte'
</script>

<Slide animate>
	<div data-id="1" class="w-60 mx-auto">
		<Htmllogo />
	</div>
</Slide>

<Slide animate>
	<div class="flex w-full justify-between items-center">
		<div data-id="1" class="w-60">
			<Htmllogo />
		</div>
		<Code data-id="1" lang="html" class="w-fit" lines="2,11|3-7|8-10">
			{`
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Postcard</title>
		<link rel="stylesheet"
		href="styles.css" />
	</head>
	<body>
		...content
	</body>
</html>
			  `}
		</Code>
	</div>
</Slide>

<Slide>
	<div class="flex w-full justify-between items-center">
		<Code data-id="1" lang="html" class="w-fit" lines="9">
			{`
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Postcard</title>
		<link rel="stylesheet"
		href="styles.css" />
	</head>
	<body>
		...content
	</body>
</html>
			  `}
		</Code>
		<Code data-id="1" lang="html" class="w-fit" lines="1,9|2,8|3-7">
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
	</div>
</Slide>

<Slide animate>
	<div class="flex w-full justify-between items-center">
		<Code data-id="5" lang="html" class="w-fit" lines="4">
			{`
<div class="postcard">
    <div class="postcard-header"/>
    <div class="postcard-body">
		    <div class="body-left">
		    <div class="body-right">
    </div>
</div>
			  `}
		</Code>
		<Code data-id="5" lang="html" class="w-fit" lines="1-4">
			{`
<div class="body-left">
    <p>Look how awesome!</p>
    <p>This is so cool!</p>
</div>
<div class="body-right">
    <input type="text" placeholder="" />
    <input type="text" placeholder="" />
    <input type="text" placeholder="" />
</div>
			  `}
		</Code>
	</div>
</Slide>
<Slide animate>
	<div class="flex w-full justify-between items-center">
		<Code data-id="5" lang="html" class="w-fit" lines="5">
			{`
<div class="postcard">
    <div class="postcard-header"/>
    <div class="postcard-body">
		    <div class="body-left">
		    <div class="body-right">
    </div>
</div>
			  `}
		</Code>
		<Code data-id="5" lang="html" class="w-fit" lines="5-9">
			{`
<div class="body-left">
    <p>Look how awesome!</p>
    <p>This is so cool!</p>
</div>
<div class="body-right">
    <input type="text" placeholder="" />
    <input type="text" placeholder="" />
    <input type="text" placeholder="" />
</div>
			  `}
		</Code>
	</div>
</Slide>

<Slide animate>
	<div class="flex w-full justify-center items-center">
		<div data-id="1" class="w-60">
			<Htmllogo />
		</div>
		<p class="text-9xl font-black opacity-0">+</p>
	</div>
</Slide>
<Slide animate>
	<div class="flex w-full justify-around items-center">
		<div data-id="1" class="w-60">
			<Htmllogo />
		</div>
		<p class="text-9xl font-black opacity-80">+</p>
		<div data-id="2" class="w-44">
			<Csslogo />
		</div>
	</div>
</Slide>
<Slide animate>
	<div class="flex w-full justify-around items-center">
		<div data-id="1" class="w-60">
			<Htmllogo />
		</div>
		<p class="text-9xl font-black opacity-80">+</p>
		<div data-id="2" class="w-44">
			<Csslogo />
		</div>
	</div>
	<Cssawesome />
</Slide>
<Slide animate>
	<div class="flex gap-10">
		<Cssawesome />

		<div class="window w-fit grid place-content-center !text-base">
			<div>
				<div>
					<h1>My Postcard</h1>
					<img
						src="https://raw.githubusercontent.com/breatheco-de/exercise-postcard/e63a7916530cc850bd92aa1c2e19191837fb5c80/.learn/assets/4geeks.png"
						alt="4Geeks Academy Logo"
					/>
				</div>
				<div>
					<div>
						<div>
							<p>
								Look how awesome! I created this by using HTML5 and CSS3 during
								my 4Geeks Academy Course!
							</p>
							<p>This is so cool! I can't wait to start doing more stuff!</p>
						</div>
						<div>
							<input type="text" placeholder="To: Jr. and Lani" />
							<input type="text" placeholder="example@x.com" />
							<input type="text" placeholder="Mommy loves you!" />
						</div>
					</div>
				</div>
				<div>
					<button>Send My Postcard</button>
				</div>
			</div>
		</div>
	</div>
</Slide>

<Slide animate>
	<div class="flex gap-10 justify-around">
		<div class="w-fit">
			<Cssawesome />
		</div>

		<div data-id="3">
			<DonePostcard />
		</div>
	</div>
</Slide>
<Slide animate>
	<div data-id="3" class="mx-auto w-fit">
		<DonePostcard />
	</div>
</Slide>
<Slide animate>
	<Code data-id="3" lang="html" class="w-fit" lines="1,18|2,5|6,16">
		{`
<div class="postcard">
    <header>
        <h1>My Postcard</h1>
        <img src="4geeks.png" alt="4Geeks Logo"/>
    </header>
    <main>
        <div class="left">
            <p>Look how awesome!</p>
            <p>This is so cool!</p>
        </div>
        <form class="right" action="/" method="POST">
            <input type="text" placeholder="To: Jr. and Lani" />
            <input type="text" placeholder="example@x.com" />
            <input type="text" placeholder="Mommy loves you!" />
        </form>
    </main>
    <button type="submit" form="form1">Send My Postcard</button>
</div>
                `}
	</Code>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="3" lang="html" class="w-fit" lines="1">
			{`
    <div class="postcard">
        <header>
            <h1>My Postcard</h1>
            <img src="4geeks.png"/>
        </header>
    </div>
                    `}
		</Code>
		<Code data-id="4" lang="css" class="w-fit" lines="1|4-6|10">
			{`
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
                    `}
		</Code>
	</div>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="3" lang="html" class="w-fit" lines="2-5">
			{`
    <div class="postcard">
        <header>
            <h1>My Postcard</h1>
            <img src="4geeks.png"/>
        </header>
    </div>
                    `}
		</Code>
		<Code data-id="4" lang="css" class="w-fit" lines="1-5|6-10|11-15">
			{`
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
                    `}
		</Code>
	</div>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="3" lang="html" class="w-fit" lines="3-13">
			{`
    <div class="postcard">
        <header />
        <main>
            <div class="left">
                <p>Look how awesome!</p>
                <p>This is so cool!</p>
            </div>
            <form class="right" >
                <input type="text"  />
                <input type="text" />
                <input type="text"  />
            </form>
        </main>
    </div>
                    `}
		</Code>
		<Code data-id="4" lang="css" class="w-fit" lines="1-4|5-10|11-15|16-18">
			{`
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
                    `}
		</Code>
	</div>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="3" lang="html" class="w-fit" lines="5-6,8-12">
			{`
    <div class="postcard">
        <header />
        <main>
            <div class="left">
                <p>Look how awesome!</p>
                <p>This is so cool!</p>
            </div>
            <form class="right" >
                <input type="text"  />
                <input type="text" />
                <input type="text"  />
            </form>
        </main>
    </div>
                    `}
		</Code>
		<Code data-id="4" lang="css" class="w-fit" lines="1-3|4-9|1-14">
			{`
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
                    `}
		</Code>
	</div>
</Slide>
<Slide animate>
	<div class="flex">
		<Code data-id="3" lang="html" class="w-fit" lines="9-14">
			{`
    <div class="postcard">
        <header />
        <main>
            <div class="left" />
                <p />
            <form class="right" />
                <inputs  />
        </main>
         <button
            type="submit"
            form="form1"
            >
             Send My Postcard
         </button>
        
    </div>
                    `}
		</Code>
		<Code data-id="4" lang="css" class="w-fit" lines="1-10|11-14|15-17">
			{`
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
                    `}
		</Code>
	</div>
</Slide>
<Slide animate>
    <div class="w-fit mr-auto flex justify-around">
    <DonePostcard />
    </div>
    <div class="w-fit ml-auto mr-32">
        <Cssawesome />
    </div>
</Slide>
<Slide animate>
    <h1 class="font-black text-7xl">Questions?</h1>
</Slide>
