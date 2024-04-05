<script lang="ts">
	import './style.css';
	import Type from '$lib/components/type.svelte';
	import Logo from '$lib/images/logo.png';
</script>

<svelte:head>
	<title>Axis Lab</title>
	<meta name="description" content="Landing page of Axis Lab" />
</svelte:head>

<main>
	<section class="introduction">
		<div>
			<h1>Welcome to <span>Axis lab!</span></h1>
			<Type content="turning your imaginations into reality" />
		</div>

		<img src={Logo} alt="" />
	</section>
	<section class="about">
		<h1>What we Offer:</h1>
		<div class="container">
			<div>
				<h2>Customized Technological Solutions</h2>
				<p>
					At Axis Lab, we specialize in providing customized technological solutions tailored to
					meet the unique needs and challenges of your business. Our team of experts works closely
					with you to understand your requirements and develop innovative solutions that drive
					efficiency, productivity, and growth.
				</p>
			</div>
			<div>
				<h2>Software Development</h2>
				<p>
					Our software development services cover a wide range of solutions, including web
					applications, mobile apps, and enterprise software. Leveraging the latest technologies and
					methodologies, we create scalable and robust software solutions that streamline operations
					and enhance user experiences.
				</p>
			</div>

			<div>
				<h2>System Integration</h2>
				<p>
					Integration is key to maximizing the efficiency and effectiveness of your systems and
					processes. At Axis Lab, we offer comprehensive system integration services that connect
					disparate systems, applications, and data sources to create a seamless and unified
					ecosystem that supports your business goals.
				</p>
			</div>
			<div>
				<h2>Hardware Solutions</h2>
				<p>
					From designing custom hardware components to optimizing existing systems, our hardware
					solutions are engineered to deliver optimal performance, reliability, and scalability.
					Whether you need hardware for a specific project or a complete system overhaul, our team
					has the expertise to meet your requirements.
				</p>
			</div>
			<div>
				<h2>Consulting and Advisory Services</h2>
				<p>
					Navigating the ever-changing landscape of technology can be challenging. Our consulting
					and advisory services provide you with the insights, strategies, and guidance you need to
					make informed decisions, mitigate risks, and capitalize on opportunities in today's
					digital world.
				</p>
			</div>
			<div>
				<h2>Product Development and Innovation</h2>
				<p>
					Innovation is at the core of what we do. Our product development services encompass
					everything from ideation and conceptualization to design, prototyping, and market launch.
					Whether you're looking to create a new product or improve an existing one, our team is
					dedicated to turning your ideas into successful products that resonate with your target
					audience.
				</p>
			</div>
			<!-- <div>
			<h2>Managed Services and Support</h2>
			<p>
				Ensuring the smooth operation and maintenance of your technology infrastructure is essential
				for business continuity and success. Our managed services and support offerings provide
				proactive monitoring, maintenance, and support to keep your systems running at peak
				performance, minimize downtime, and maximize ROI.
			</p>
		</div> -->
		</div>
	</section>
	<section class="contact">
		<div class="info">
			<ul>
				<li>Address: Dhapasi, Kathmandu</li>
				<li>Phone: +977 9841780396</li>
				<li>Email: info@axislab.io</li>
			</ul>
		</div>
		<div class="connect">
			<h2>Connect with us!</h2>
			<div class="links">
				<a href="https://www.github.com/Prabesh-shrestha">Linkedin</a>
				<a href="https://www.github.com/Prabesh-shrestha">Instagram</a>
				<a href="https://www.github.com/Prabesh-shrestha">Facebook</a>
				<a href="https://www.github.com/Prabesh-shrestha">Github</a>
			</div>
		</div>
	</section>
	<footer>
		<p>© 2024 Axis Lab. All Rights Reserved.</p>
	</footer>
</main>

<style>
	.introduction {
		font-weight: bold;
		display: flex;
		/* text-align: center; */
		justify-content: space-between;
		align-items: center;
		font-size: 50px;
		margin: 0px;
		padding: 100px 150px;
	}
	.introduction img {
		height: 520px;
	}
	.introduction span {
		color: #31363f;
		font-size: 100px;
	}
	.about {
		background-color: #31363f;
		display: flex;
		flex-direction: column;
		align-items: center;
		padding: 70px 0px;
	}
	.about .container {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: space-around;
	}
	.about .container div {
		border: #76abae solid 4px;
		border-radius: 30px;
		padding: 30px;
		margin: 20px;
		width: 450px;
	}
	.about * {
		background-color: #31363f;
		color: #eeeeee;
	}
	.about h1 {
		font-weight: normal;
		font-size: 50px;
		padding-bottom: 30px;
	}
	.connect {
		background-color: #76abae;
		display: flex;
		flex-direction: column;
		align-items: center;
		padding: 100px 50px;
		width: 100%;
	}
	.info {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 35%;
	}
	.info ul {
		list-style-type: none;
		font-size: 23px;
	}

	.contact * {
		background-color: #76abae;
		color: #31363f;
	}
	.contact {
		display: flex;
	}
	.links {
		display: flex;
		flex-direction: row;
		justify-content: center;
	}
	.links a {
		padding: 10px;
	}
	footer {
		background-color: #31363f;
		padding: 6px;
		display: flex;
		flex-direction: columns;
		/* align-items: center; */
		justify-content: center;
	}
	footer p {
		background-color: #31363f;
		color: #eeeeee;
	}
</style>
