<script>
	import logo from '$lib/assets/shared/desktop/logo.svg';
	import logoDarkBg from '$lib/assets/shared/desktop/logo-darkbg.svg';
	import facebook from '$lib/assets/shared/desktop/facebook-darkbg.svg';
	import instagram from '$lib/assets/shared/desktop/instagram-darkbg.svg';
	import twitter from '$lib/assets/shared/desktop/twitter-darkbg.svg';
	import youtube from '$lib/assets/shared/desktop/youtube-darkbg.svg';
	import pinterest from '$lib/assets/shared/desktop/pinterest-darkbg.svg';
	import heroS from '$lib/assets/pricing/hero-S.jpg';
	import heroM from '$lib/assets/pricing/hero-M.jpg';
	import heroL from '$lib/assets/pricing/hero-L.jpg';
	import check from '$lib/assets/pricing/check.svg';
	import slider from '$lib/assets/pricing/slider.svg';
	import sliderActive from '$lib/assets/pricing/slider-active.svg';

	let periodOptions = ['monthly', 'yearly'];
	let selectedPeriod = 'monthly';

	const changeOption = () => {
		if (selectedPeriod === 'monthly') {
			selectedPeriod = 'yearly';
		} else {
			selectedPeriod = 'monthly';
		}
	};
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
	<div class="card-wrapper">
		<div class="card createbg picture-right picture-wide">
			<img
				src={heroS}
				alt=""
				width="100%"
				loading="lazy"
				srcset="{heroS} 400w, {heroM} 760w, {heroL} 900w"
			/>
			<h2 class="card-title">Features.</h2>

			<p>
				We make sure all of our features are designed to be loved by every aspiring and even
				professional photograpers who wanted to share their stories.
			</p>
		</div>
	</div>
	<div class="select-plan">
		<div class="select-plan--inner">
			<div class="timeperiod-toggle">
				<label for="period-monthly" class:selected={selectedPeriod === 'monthly'}
					>{periodOptions[0]}</label
				>
				<button on:click={changeOption}>
					<img
						src={slider}
						alt="toggle pricing per month"
						class:selected={selectedPeriod === 'monthly'}
					/>
					<img
						src={sliderActive}
						alt="toggle pricing per year"
						class:selected={selectedPeriod === 'yearly'}
					/>
				</button>

				<input
					type="radio"
					bind:group={selectedPeriod}
					name="period"
					id="period-monthly"
					checked
					value={periodOptions[0]}
				/>
				<input
					type="radio"
					bind:group={selectedPeriod}
					name="period"
					id="period-yearly"
					value={periodOptions[1]}
				/>
				<label for="period-yearly" class:selected={selectedPeriod === 'yearly'}
					>{periodOptions[1]}</label
				>
			</div>
			<div class="select-card-wrapper">
				<div class="select-card basic">
					<h3>Basic</h3>
					<p class="card-content">
						Includes basic usage of our platform. Recommended for new and aspiring photographers.
					</p>
					{#if selectedPeriod === 'monthly'}
						<p class="select-card-prize monthly">
							<span class="prize textalign-right">$19.00</span>
							<span class="prize-period">per month</span>
						</p>
					{:else}
						<p class="select-card-prize yearly">
							<span class="prize textalign-right">$190.00</span>
							<span class="prize-period textalign-right"> per year </span>
						</p>
					{/if}
					<button>Pick Plan</button>
				</div>
				<div class="select-card pro">
					<h3>Pro</h3>
					<p class="card-content">
						More advanced features available. Recommended for photography veterans and
						professionals.
					</p>
					{#if selectedPeriod === 'monthly'}
						<p class="select-card-prize monthly">
							<span class="prize textalign-right">$39.00</span>
							<span class="prize-period textalign-right">per month</span>
						</p>
					{:else}
						<p class="select-card-prize yearly">
							<span class="prize textalign-right">$390.00</span>
							<span class="prize-period textalign-right"> per year </span>
						</p>
					{/if}

					<button>Pick Plan</button>
				</div>
				<div class="select-card business">
					<h3>Business</h3>
					<p class="card-content">
						Additional features available such as more detailed metrics. Recommended for business
						owners.
					</p>
					{#if selectedPeriod === 'monthly'}
						<p class="select-card-prize monthly">
							<span class="prize textalign-right">$99.00</span>
							<span class="prize-period">per month</span>
						</p>
					{:else}
						<p class="select-card-prize yearly">
							<span class="prize textalign-right">$990.00</span>
							<span class="prize-period"> per year </span>
						</p>
					{/if}
					<button>Pick Plan</button>
				</div>
			</div>
		</div>
	</div>
	<div class="comparisson-block tablet-hidden desktop-hidden">
		<h2>The features</h2>
		<ul>
			<li>Unlimited Story Posting</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Unlimited Photo Upload</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Embedding Custom Content</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Customize Metadata</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Advanced Metrics</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Photo Downloads</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Search Engine Indexing</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
			<li>Custom Analytics</li>
			<ul class="inner-list">
				<li>
					<div class="feature-plan">
						<span>Basic</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Pro</span>
						&nbsp;
					</div>
				</li>
				<li>
					<div class="feature-plan">
						<span>Business</span>
						<img src={check} alt="feature included in plan" loading="lazy" />
					</div>
				</li>
			</ul>
		</ul>
	</div>
	<div class="comparisson-table mobile-hidden">
		<h2>Compare</h2>
		<br />
		<table>
			<thead>
				<tr>
					<th>The features</th>
					<th>Basic</th>
					<th>Pro</th>
					<th>Business</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td class="row-title">Unlimited Story Posting</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Unlimited Photo Upload</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Embedding Custom Content</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Customize Metadata</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Advanced Metrics</td>
					<td>&nbsp;</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Photo Downloads</td>
					<td>&nbsp;</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Search Engine Indexing</td>
					<td>&nbsp;</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
				<tr>
					<td class="row-title">Custom Analytics </td>
					<td>&nbsp;</td>
					<td>&nbsp;</td>
					<td><img src={check} alt="feature included in plan" loading="lazy" /></td>
				</tr>
			</tbody>
		</table>
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
