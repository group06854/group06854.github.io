<script>
	import github from './../../img/github (2).png';
	import tg from './../../img/tg.png';
	import email from './../../img/gmail.png';
	import Heade from './../__layout.svelte';
</script>

<Heade />
<div class="container">
	<div class="footer">
		<hr />
		<h3 id="head_end">Contact us</h3>
		<ul>
			<li>
				<a id="tg-link" href="https://t.me/arhitc"
					><img alt="" src={tg} />
					<p id="tg">tg-link</p></a
				>
			</li>
			<li>
				<a id="gh-link" href="https://github.com/group06854/portfolio-web.github.io"
					><img alt="" src={github} />
					<p id="gh">gh-link</p></a
				>
			</li>
			<li>
				<a id="email" href="mailto:leo2004201441@gmail.com"
					><img alt="" src={email} />
					<p>email</p></a
				>
			</li>
		</ul>
	</div>
</div>

<style>
	.container {
		margin-top: 1px;
		width: 98%;
		margin-left: 0.5%;
		margin-right: 0.5%;
	}
	.footer ul {
		text-align: center;
		list-style: none;
		display: flex;
		margin-left: 36%;
		margin-right: 40%;
		justify-content: space-between;
	}
	.footer {
		height: 100px;
	}
	#head_end {
		color: white;
		text-align: center;
		font-weight: 800;
		margin-bottom: 40px;
	}
	a {
		text-decoration: none;
		color: aliceblue;
	}
	#tg {
		text-align: center;
	}
	#gh {
		text-align: center;
		margin-left: 4px;
	}
	#gh-link img {
		margin-left: 7px;
		margin-top: 4px;
		margin-bottom: 4px;
	}
</style>
