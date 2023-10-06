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
	import worldTourS from '$lib/assets/stories/world-tour-S.jpg';
	import worldTourL from '$lib/assets/stories/world-tour-L.jpg';
	import unforeseenS from '$lib/assets/stories/unforeseen-corners-S.jpg';
	import unforeseenL from '$lib/assets/stories/unforeseen-corners-L.jpg';
	import landofDreamsS from '$lib/assets/stories/land-of-dreams-S.jpg';
	import landofDreamsL from '$lib/assets/stories/land-of-dreams-L.jpg';
	import somwarpetS from '$lib/assets/stories/somwarpet-S.jpg';
	import somwarpetL from '$lib/assets/stories/somwarpet-L.jpg';
	import darkForestS from '$lib/assets/stories/dark-forest-S.jpg';
	import darkForestL from '$lib/assets/stories/dark-forest-L.jpg';
	import milkyWayS from '$lib/assets/stories/milky-way-S.jpg';
	import milkyWayL from '$lib/assets/stories/milky-way-L.jpg';
	import calmWatersS from '$lib/assets/stories/calm-waters-S.jpg';
	import calmWatersL from '$lib/assets/stories/calm-waters-L.jpg';
	import behindWavesS from '$lib/assets/stories/behind-the-waves-S.jpg';
	import behindWavesL from '$lib/assets/stories/behind-the-waves-L.jpg';
	import runningFreeS from '$lib/assets/stories/running-free-S.jpg';
	import runningFreeL from '$lib/assets/stories/running-free-L.jpg';
	import rageOfTheSeaS from '$lib/assets/stories/rage-of-the-sea-S.jpg';
	import rageOfTheSeaL from '$lib/assets/stories/rage-of-the-sea-L.jpg';
	import tripNowhereS from '$lib/assets/stories/trip-to-nowhere-S.jpg';
	import tripNowhereL from '$lib/assets/stories/trip-to-nowhere-L.jpg';
	import kingAfricaS from '$lib/assets/stories/king-on-africa-S.jpg';
	import kingAfricaL from '$lib/assets/stories/king-on-africa-L.jpg';
	import responsive from '$lib/assets/features/desktop/responsive.svg';
	import noLimit from '$lib/assets/features/desktop/no-limit.svg';
	import embed from '$lib/assets/features/desktop/embed.svg';
</script>

<nav>
	<ul>
		<li>
			<a href="/">
				<img src={logo} alt="Photosnap" width="100%" loading="lazy" />
			</a>
		</li>
		<li class="mobile-hidden"><a href="/stories" class="current">Stories</a></li>
		<li class="mobile-hidden"><a href="/features">Features</a></li>
		<li class="mobile-hidden"><a href="/pricing">Pricing</a></li>
		<li class="mobile-hidden"><a href="/" class="button-link">Get an invite</a></li>
	</ul>
</nav>
<div class="wrapper">
	<div class="card-wrapper">
		<div class="card createbg full-picture">
			<img
				src={fullMoonS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{fullMoonS} 400w, {fullMoonM} 800w, {fullMoonL} 1200w"
			/>
			<!-- <div class="card--inner"> -->
			<p class="card-extra-context">Last month's featured story</p>
			<h2 class="card-title">Hazy full moon of Appalachia.</h2>
			<p class="card-story-context">March 2nd 2020 <span class="author">by John Appleseed</span></p>

			<p>
				The dissected plateau area, while not actually made up of geological mountains, is popularly
				called "mountains," especially in eastern Kentucky and West Virginia, and while the ridges
				are not high, the terrain is extremely rugged.
			</p>
			<a href="/" class="dark button-arrow">Read the story</a>
			<!-- </div> -->
		</div>
	</div>
	<div class="photo-wrapper stories">
		<div class="photo-card">
			<img
				src={mountainsS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{mountainsS} 400w, {mountainsL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">April 11th 2020</p>
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
				<p class="photo-context">April 11th 2020</p>
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
				<p class="photo-context">April 9th 2020</p>
				<p class="photo-title">Architecturals</p>
				<p class="photo-author">by Samantha Brooke</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={worldTourS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{worldTourL} 400w, {worldTourL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">April 7th 2020</p>
				<p class="photo-title">World Tour 2019</p>
				<p class="photo-author">by Timothy Wagner</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={unforeseenS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{unforeseenL} 400w, {unforeseenL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">April 3rd 2020</p>
				<p class="photo-title">Unforeseen Corners</p>
				<p class="photo-author">by William Malcolm</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={kingAfricaS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{kingAfricaL} 400w, {kingAfricaL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 29th 2020</p>
				<p class="photo-title">King on Africa: Part II</p>
				<p class="photo-author">by Tim Hillenburg</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={tripNowhereS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{tripNowhereL} 400w, {tripNowhereL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 21st 2020</p>
				<p class="photo-title">The Trip to Nowhere</p>
				<p class="photo-author">by Felicia Rourke</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={rageOfTheSeaS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{rageOfTheSeaL} 400w, {rageOfTheSeaL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 19th 2020</p>
				<p class="photo-title">Rage of The Sea</p>
				<p class="photo-author">by Mohammed Abdul</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={runningFreeS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{runningFreeL} 400w, {runningFreeL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 16th 2020</p>
				<p class="photo-title">Running Free</p>
				<p class="photo-author">by Michelle</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={behindWavesS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{behindWavesL} 400w, {behindWavesL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 11th 2020</p>
				<p class="photo-title">Behind the Waves</p>
				<p class="photo-author">Lamarr Wilson</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={calmWatersS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{calmWatersL} 400w, {calmWatersL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 9th 2020</p>
				<p class="photo-title">Calm Waters</p>
				<p class="photo-author">by Samantha Brooke</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={milkyWayS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{milkyWayL} 400w, {milkyWayL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 5th 2020</p>
				<p class="photo-title">The Milky Way</p>
				<p class="photo-author">by Benjamin Cruz</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={darkForestS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{darkForestL} 400w, {darkForestL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 4th 2020</p>
				<p class="photo-title">Night at The Dark Forest</p>
				<p class="photo-author">by Mohammed Abdul</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={somwarpetS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{somwarpetL} 400w, {somwarpetL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">March 1st 2020</p>
				<p class="photo-title">Somwarpet’s Beauty</p>
				<p class="photo-author">by Michelle</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
		<div class="photo-card">
			<img
				src={landofDreamsS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{landofDreamsL} 400w, {landofDreamsL} 900w"
			/>
			<div class="photo-card--inner">
				<p class="photo-context">February 25th 2020</p>
				<p class="photo-title">Land of Dreams</p>
				<p class="photo-author">by William Malcolm</p>
				<a href="/stories" class="dark button-arrow photo-link">Read Story</a>
			</div>
		</div>
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
