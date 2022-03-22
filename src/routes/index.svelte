<body>
	<!-- header-start   -->
	<header id="header">
		<div class="container">
			<div class="logo">
				<a href="/">Place Holder</a>
			</div>
			<div class="nav-toggle" id="toggle">
				<i class="fas fa-bars" />
			</div>
		</div>
	</header>
	<!-- header-end   -->
	<!--  intro-start  -->
	<section id="intro">
		<div class="container">
			<div class="intro-text">
				<h1>Welcome to <em>Southampton Dental</em></h1>
				<p>
					Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem nemo, incidunt saepe
					quos nulla id officiis repudiandae natus, consequuntur officia.
				</p>
				<div class="call-to-action">
					<a href="/" class="btn-bg">Get started</a>
				</div>
			</div>
		</div>
	</section>
</body>

<style>
	body {
		line-height: 1.41;
		font-family: 'Roboto', sans-serif;
		background-color: #f4f4f4;
	}
	/*header start*/
	header {
		background-color: #fff;
		box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
		position: fixed;
		width: 100%;
		z-index: 99;
	}
	header a {
		display: block;
		padding: 10px;
		text-decoration: none;
		color: #010611;
		text-transform: uppercase;
		transition: color 0.4s, background-color 0.4s;
	}
	header nav a:hover {
		color: #5e7ce2;
		background-color: rgba(0, 0, 0, 0.1);
	}
	header .logo a {
		font-weight: bold;
		color: #5e7ce2;
	}
	.logo {
		width: 90%;
		display: inline-block;
		font-size: 1.5em;
	}
	.logo a {
		display: inline-block;
		padding: 20px 10px;
		padding-left: 0px;
	}
	.nav-toggle {
		font-size: 1.5em;
		display: inline-block;
		text-align: right;
		cursor: pointer;
		transition: color 0.4s;
	}
	.nav-toggle:hover {
		color: #5e7ce2;
	}
	/*header-end*/
	.container {
		max-width: 1100px;
		margin: auto;
		padding: 10px;
	}
	/*intro start*/
	/* intro{
   padding-top: 80px;
   min-height: 500px;
   background-image:linear-gradient(rgba(255,255,255,1), rgba(255,255,255,0.6)), url(../img/intro.jpg);
   background-size: cover;
   background-position: 40%;
   background-attachment: fixed;
   text-align: center;
   position: relative;
} */

	.intro-text {
		position: absolute;
		top: 200px;
	}
	.intro-text h1 {
		padding: 10px 0px;
		font-size: 1.7em;
	}
	.intro-text h1 em {
		color: #5e7ce2;
	}
	.intro-text p {
		padding: 10px;
	}
	.intro-text .call-to-action {
		width: 60%;
		margin: auto;
		margin-top: 20px;
	}
	.intro-text .call-to-action a {
		display: block;
	}
	.btn-bg {
		padding: 10px;
		text-decoration: none;
		border: none;
		background-color: #5e7ce2;
		color: #fff;
		margin: 10px;
		border-radius: 10px;
		font-weight: bold;
		box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
		transition: all 0.4s;
	}
	.btn-bg:hover {
		color: #5e7ce2;
		background-color: #fff;
		cursor: pointer;
		box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
	}
	.container {
		max-width: 1100px;
		margin: auto;
		padding: 10px;
	}

	/*intro end*/
</style>
