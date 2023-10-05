<script>
	import './../styles.css';
	import createS from '$lib/assets/home/create-and-share-S.jpg';
	import createM from '$lib/assets/home/create-and-share-M.jpg';
	import createL from '$lib/assets/home/create-and-share-L.jpg';
	import beautifulS from '$lib/assets/home/beautiful-stories-S.jpg';
	import beautifulM from '$lib/assets/home/beautiful-stories-M.jpg';
	import beautifulL from '$lib/assets/home/beautiful-stories-L.jpg';
	import designedS from '$lib/assets/home/designed-for-everyone-S.jpg';
	import designedM from '$lib/assets/home/designed-for-everyone-M.jpg';
	import designedL from '$lib/assets/home/designed-for-everyone-L.jpg';
	import mountainsS from '$lib/assets/stories/mountains-S.jpg';
	import mountainsL from '$lib/assets/stories/mountains-L.jpg';
	import cityscapesS from '$lib/assets/stories/cityscapes-S.jpg';
	import cityscapesL from '$lib/assets/stories/cityscapes-L.jpg';
	import eighteenS from '$lib/assets/stories/18-days-voyage-S.jpg';
	import eighteenL from '$lib/assets/stories/18-days-voyage-L.jpg';
	import architecturalsS from '$lib/assets/stories/architecturals-S.jpg';
	import architecturalsL from '$lib/assets/stories/architecturals-L.jpg';
	import responsive from '$lib/assets/features/desktop/responsive.svg';
	import noLimit from '$lib/assets/features/desktop/no-limit.svg';
	import embed from '$lib/assets/features/desktop/embed.svg';
	import logo from '$lib/assets/shared/desktop/logo.svg';
	import logoDarkBg from '$lib/assets/shared/desktop/logo-darkbg.svg';
	import facebook from '$lib/assets/shared/desktop/facebook-darkbg.svg';
	import instagram from '$lib/assets/shared/desktop/instagram-darkbg.svg';
	import twitter from '$lib/assets/shared/desktop/twitter-darkbg.svg';
	import youtube from '$lib/assets/shared/desktop/youtube-darkbg.svg';
	import pinterest from '$lib/assets/shared/desktop/pinterest-darkbg.svg';
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
		<li class="mobile-hidden"><a href="/pricing">Pricing</a></li>
		<li class="mobile-hidden"><a href="/" class="button-link">Get an invite</a></li>
	</ul>
</nav>
<div class="wrapper">
	<div class="card-wrapper">
		<div class="card createbg picture-right">
			<img
				src={createS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{createS} 400w, {createM} 800w, {createL} 1200w"
			/>
			<!-- <div class="card--inner"> -->
			<h2 class="card-title">Create and share your photo Stories.</h2>

			<p>
				Photosnap is a platform for photographers and visual storytellers. We make it easy to share
				photos, tell stories and connect with others.
			</p>
			<a href="/" class="dark button-arrow">Get an invite</a>
			<!-- </div> -->
		</div>
		<div class="card picture-left">
			<img
				src={beautifulS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{beautifulS} 400w, {beautifulM} 800w, {beautifulL} 1200w"
			/>
			<!-- <div class="card--inner"> -->
			<h2 class="card-title">Beautiful stories every time</h2>
			<p>
				We provide design templates to ensure your stories look terrific. Easily add photos, text,
				embed maps and media from other networks. Then share your story with everyone.
			</p>
			<a href="/stories" class="button-arrow"> View the stories</a>
			<!-- </div> -->
		</div>

		<div class="card picture-right">
			<img
				src={designedS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{designedS} 400w, {designedM} 800w, {designedL} 1200w"
			/>
			<!-- <div class="card--inner"> -->
			<h2 class="card-title">Designed for everyone</h2>
			<p>
				Photosnap can help you create stories that resonate with your audience. Our tool is designed
				for photographers of all levels, brands, businesses you name it.
			</p>
			<a href="/stories" class="button-arrow"> View the stories</a>
			<!-- </div> -->
		</div>
	</div>
	<div class="photo-wrapper">
		<div class="photo-card">
			<img
				src={mountainsS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{mountainsS} 400w, {mountainsL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-title">The Mountains</p>
				<p class="photo-author">by John Appleseed</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={cityscapesS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{cityscapesS} 400w, {cityscapesL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-title">Sunset Cityscapes</p>
				<p class="photo-author">by Benjamin Cruz</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={eighteenS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{eighteenS} 400w, {eighteenL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-title">18 Days Voyage</p>
				<p class="photo-author">by Alexei Borodin</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={architecturalsS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{architecturalsL} 400w, {architecturalsL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-title">Architecturals</p>
				<p class="photo-author">by Samantha Brooke</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
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
		</ul>
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
			<ul>
				<li><a href="/">Home</a></li>
				<li><a href="/stories">Stories</a></li>
				<li><a href="/features">Features</a></li>
				<li><a href="/pricing">Pricing</a></li>
			</ul>
			<a href="/" class="dark button-arrow">Get an invite</a>
			<p>Copyright 2023. All Rights Reserved</p>
		</div>
	</footer>
</div>
