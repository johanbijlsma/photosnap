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
		<li class="mobile-hidden"><a href="/features" class="current">Features</a></li>
		<li class="mobile-hidden"><a href="/pricing">Pricing</a></li>
		<li class="mobile-hidden"><a href="/" class="button-link">Get an invite</a></li>
	</ul>
</nav>
<div class="wrapper">
	Stories Features Pricing Get an invite Features We make sure all of our features are designed to
	be loved by every aspiring and even professional photograpers who wanted to share their stories.
	100% Responsive No matter which the device you’re on, our site is fully responsive and stories
	look beautiful on any screen. No Photo Upload Limit Our tool has no limits on uploads or
	bandwidth. Freely upload in bulk and share all of your stories in one go. Available to Embed Embed
	Tweets, Facebook posts, Instagram media, Vimeo or YouTube videos, Google Maps, and more. Custom
	Domain With Photosnap subscriptions you can host your stories on your own domain. You can also
	remove our branding! Boost Your Exposure Users that viewed your story or gallery can easily get
	notifed of new and featured stories with our built in mailing list. Drag & Drop Image Easily drag
	and drop your image and get beautiful shots everytime. No over the top tooling to add friction to
	creating stories. We're in Beta. Get your invite today! Get an invite Home Stories Features
	Pricing Get an invite Copyright 2019. All Rights Reserved
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
