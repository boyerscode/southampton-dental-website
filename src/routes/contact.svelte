<body>
	<!--  contact-start  -->
	<section id="contact-us">
		<div class="container">
			<h2 class="section-title">Contact <span>Us</span></h2>
			<p class="section-desc">
				Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem odit architecto expedita,
				eum possimus delectus nulla similique? Illum animi perferendis excepturi repellat,
				voluptatum aliquid culpa unde praesentium, ipsam, odit repellendus.
			</p>
			<form action="">
				<label for="name">*Name</label>
				<input type="text" id="name" required />
				<label for="email">*Email</label>
				<input type="email" id="email" required />
				<label for="subject">*Subject</label>
				<input type="text" id="subject" required />
				<label for="msg">*Message</label>
				<textarea id="msg" required />
				<button type="submit" class="btn-bg">Send message</button>
			</form>
		</div>
	</section>
	<!--  contact-end  -->

	<!--  map-start -->
	<section id="map">
		<div class="mapouter">
			<div class="gmap_canvas">
				<iframe
					id="gmap_canvas"
					title="Southampton Dental Map"
					width="100%"
					height="500"
					src="https://maps.google.com/maps?q=1501%20Hampton%20Ave%2C%20St.%20Louis%2C%20MO%2063139&t=&z=13&ie=UTF8&iwloc=&output=embed"
					frameborder="0"
					scrolling="no"
					marginheight="0"
					marginwidth="0"
				/>
			</div>
			<style>
				.mapouter {
					overflow: hidden;
					height: 500px;
					width: 100%;
				}
				.gmap_canvas {
					background: none !important;
					height: 500px;
					width: 100%;
				}
			</style>
		</div>
	</section>
</body>

<!--  map-end -->
<style>
	.container {
		max-width: 1100px;
		margin: auto;
		padding: 10px;
	}
	form {
		background-color: #fff;
		padding: 10px;
	}
	form label {
		padding: 5px 0px;
		display: block;
	}
	form input,
	form textarea {
		width: 100%;
		border: 2px solid transparent;
		outline: none;
		padding: 10px;
		margin-bottom: 10px;
		background-color: #f4f4f4;
		transition: border 0.4s, background-color 0.4s;
	}
	form input:hover,
	form textarea:hover,
	form input:focus,
	form textarea:focus {
		border: 2px solid #f4f4f4;
		background-color: #fff;
	}
	form textarea {
		height: 80px;
	}
	form .btn-bg {
		margin: 10px 0px;
	}
	#map {
		padding-bottom: 0px;
	}
</style>
