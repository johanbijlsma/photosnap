<script>
	import logo from '$lib/assets/shared/desktop/logo.svg';
	import logoDarkBg from '$lib/assets/shared/desktop/logo-darkbg.svg';
	import facebook from '$lib/assets/shared/desktop/facebook-darkbg.svg';
	import instagram from '$lib/assets/shared/desktop/instagram-darkbg.svg';
	import twitter from '$lib/assets/shared/desktop/twitter-darkbg.svg';
	import youtube from '$lib/assets/shared/desktop/youtube-darkbg.svg';
	import pinterest from '$lib/assets/shared/desktop/pinterest-darkbg.svg';
	import fullMoonS from '$lib/assets/stories/moon-of-appalacia-S.jpg';
	import fullMoonM from '$lib/assets/stories/moon-of-appalacia-M.jpg';
	import fullMoonL from '$lib/assets/stories/moon-of-appalacia-L.jpg';
</script>

<nav>
	<ul>
		<li>
			<a href="/">
				<img src={logo} alt="Photosnap" width="100%" loading="lazy" />
			</a>
		</li>
		<li class="mobile-hidden"><a href="/stories">Stories</a></li>
		<li class="mobile-hidden"><a href="/features">Features</a></li>
		<li class="mobile-hidden"><a href="/pricing" class="current">Pricing</a></li>
		<li class="mobile-hidden"><a href="/" class="button-link">Get an invite</a></li>
	</ul>
</nav>
<div class="wrapper">
	Stories Features Pricing Get an invite Pricing Create a your stories, Photosnap is a platform for
	photographers and visual storytellers. It’s the simple way to create and share your photos.
	Monthly Yearly Basic Includes basic usage of our platform. Recommended for new and aspiring
	photographers. $19.00 per month $190.00 per year Pick Plan Pro More advanced features available.
	Recommended for photography veterans and professionals. $39.00 per month $390.00 per year Pick
	Plan Business Additional features available such as more detailed metrics. Recommended for
	business owners. $99.00 per month $990.00 per year Pick Plan Compare The Features Basic Pro
	Business Unlimited Story Posting Unlimited Photo Upload Embedding Custom Content Customize
	Metadata Advanced Metrics Photo Downloads Search Engine Indexing Custom Analytics We're in Beta.
	Get your invite today! Get an invite Home Stories Features Pricing Get an invite Copyright 2019.
	All Rights Reserved

	<footer>
		<div class="footer--inner">
			<img src={logoDarkBg} alt="Photosnap" loading="lazy" class="logo" />
			<ul class="social-links">
				<li><a href="/"><img src={facebook} alt="Facebook" /></a></li>
				<li><a href="/"><img src={youtube} alt="YouTube" /></a></li>
				<li><a href="/"><img src={twitter} alt="Twitter" /></a></li>
				<li><a href="/"><img src={pinterest} alt="Pinterest" /></a></li>
				<li><a href="/"><img src={instagram} alt="Instagram" /></a></li>
			</ul>
			<ul class="footer-links">
				<li><a href="/">Home</a></li>
				<li><a href="/stories">Stories</a></li>
				<li><a href="/features">Features</a></li>
				<li><a href="/pricing">Pricing</a></li>
			</ul>
			<a href="/" class="dark button-arrow">Get an invite</a>
			<p class="footer-copyright">Copyright 2023. All Rights Reserved</p>
		</div>
	</footer>
</div>
