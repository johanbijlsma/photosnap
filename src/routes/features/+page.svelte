<script>
	import logo from '$lib/assets/shared/desktop/logo.svg';
	import logoDarkBg from '$lib/assets/shared/desktop/logo-darkbg.svg';
	import facebook from '$lib/assets/shared/desktop/facebook-darkbg.svg';
	import instagram from '$lib/assets/shared/desktop/instagram-darkbg.svg';
	import twitter from '$lib/assets/shared/desktop/twitter-darkbg.svg';
	import youtube from '$lib/assets/shared/desktop/youtube-darkbg.svg';
	import pinterest from '$lib/assets/shared/desktop/pinterest-darkbg.svg';
	import heroS from '$lib/assets/features/hero-S.jpg';
	import heroM from '$lib/assets/features/hero-M.jpg';
	import heroL from '$lib/assets/features/hero-L.jpg';
	import responsive from '$lib/assets/features/responsive.svg';
	import noLimit from '$lib/assets/features/no-limit.svg';
	import embed from '$lib/assets/features/embed.svg';
	import boostExposure from '$lib/assets/features/boost-exposure.svg';
	import customDomain from '$lib/assets/features/custom-domain.svg';
	import dragDrop from '$lib/assets/features/drag-drop.svg';
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
	<div class="card-wrapper">
		<div class="card createbg picture-right picture-wide">
			<img
				src={heroS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{heroS} 400w, {heroM} 760w, {heroL} 900w"
			/>
			<!-- <div class="card--inner"> -->
			<h2 class="card-title">Features.</h2>

			<p>
				We make sure all of our features are designed to be loved by every aspiring and even
				professional photograpers who wanted to share their stories.
			</p>

			<!-- </div> -->
		</div>
	</div>
	<div class="about">
		<ul>
			<li class="about-card">
				<img src={responsive} alt="" />
				<h3>100% Responsive</h3>
				<p>
					No matter which the device you’re on, our site is fully responsive and stories look
					beautiful on any screen.
				</p>
			</li>
			<li class="about-card">
				<img src={noLimit} alt="" />
				<h3>No Photo Upload Limit</h3>
				<p>
					Our tool has no limits on uploads or bandwidth. Freely upload in bulk and share all of
					your stories in one go.
				</p>
			</li>
			<li class="about-card">
				<img src={embed} alt="" />
				<h3>Available to Embed</h3>
				<p>
					Embed Tweets, Facebook posts, Instagram media, Vimeo or YouTube videos, Google Maps, and
					more.
				</p>
			</li>
			<li class="about-card">
				<img src={customDomain} alt="" />
				<h3>Custom Domain</h3>
				<p>
					With Photosnap subscriptions you can host your stories on your own domain. You can also
					remove our branding!
				</p>
			</li>
			<li class="about-card">
				<img src={boostExposure} alt="" />
				<h3>Boost Your Exposure</h3>
				<p>
					Users that viewed your story or gallery can easily get notifed of new and featured stories
					with our built in mailing list.
				</p>
			</li>
			<li class="about-card">
				<img src={dragDrop} alt="" />
				<h3>Drag & Drop Image</h3>
				<p>
					Easily drag and drop your image and get beautiful shots everytime. No over the top tooling
					to add friction to creating stories.
				</p>
			</li>
		</ul>
	</div>
	<div class="banner">
		<h3>We're in Beta.<br /> Get your invite today!</h3>
		<a href="/" class="dark button-arrow">Get an invite</a>
	</div>
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
