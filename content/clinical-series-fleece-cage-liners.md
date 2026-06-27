+++
title = "Clinical Series Fleece Liners — All-in-One & Antimicrobial"
shortTitle = "Clinical Series Fleece Liners"
description = "The only all-in-one, washable guinea pig fleece liner for 2x4 C&C cages — entirely medical-grade, antimicrobial fabric with silver ion technology throughout. Pre-activated, no prep washes. $400 for two liners that last 6+ years. Handmade in SF."
type = "product"
layout = "landing"
weight = 3
[params]
  og_image = "clinical-series-brand.jpg"
[sitemap]
  priority = 0.9
+++

<style>
/* ==========================================================================
   Clinical Series — landing page (scoped under .cs-landing)
   Uses the site design tokens defined in assets/css/custom.css
   ========================================================================== */
.cs-landing { color: var(--color-text); }
.cs-landing p { color: var(--color-text); }
.cs-section { padding: 56px 0; }
.cs-section--alt { background: var(--color-bg-alt); }
.cs-section--grey { background: #DEDCD3; }
.cs-container { max-width: 1080px; margin: 0 auto; padding: 0 20px; }
.cs-eyebrow { text-transform: uppercase; letter-spacing: 1.2px; font-size: 13px; font-weight: 700; color: var(--color-primary); margin: 0 0 10px; }
.cs-h2 { font-family: var(--font-heading); font-weight: 600; font-size: 30px; text-align: center; margin: 0 0 14px; color: var(--color-text); }
.cs-lead { text-align: center; max-width: 760px; margin: 0 auto 28px; color: var(--color-text-light); font-size: 16px; }
.cs-center { text-align: center; }

/* CTA */
.cs-cta { text-align: center; margin: 30px 0 4px; }
.cs-shop-note { font-size: 13px; color: var(--color-text-light); margin-top: 8px !important; }

/* Hero */
.cs-hero { background: linear-gradient(180deg, var(--color-bg) 0%, var(--color-bg-alt) 100%); padding: 60px 0; }
.cs-hero__grid { display: grid; grid-template-columns: 1fr 1fr; gap: 44px; align-items: center; }
.cs-hero__title { font-family: var(--font-heading); font-size: 40px; line-height: 1.15; margin: 0 0 14px; color: var(--color-text); }
.cs-hero__sub { font-family: var(--font-heading); font-size: 20px; color: var(--color-primary-dark); margin: 0 0 16px; }
.cs-hero__text { font-size: 16px; color: var(--color-text-light); margin-bottom: 22px; }
.cs-hero__media { display: grid; grid-template-columns: 2fr 1fr; gap: 12px; }
.cs-hero__media img { width: 100%; height: 100%; object-fit: cover; border-radius: var(--radius); box-shadow: var(--shadow); }
.cs-hero__main { grid-row: span 2; }
.cs-hero__thumbs { display: grid; gap: 12px; }

/* Trust badges */
.cs-badges { background: var(--color-card); border-top: 1px solid var(--color-border); border-bottom: 1px solid var(--color-border); }
.cs-badges__row { display: grid; grid-template-columns: repeat(6, 1fr); gap: 18px; padding: 30px 0; }
.cs-badge { text-align: center; }
.cs-badge i { font-size: 26px; color: var(--color-primary); margin-bottom: 10px; display: block; }
.cs-badge span { display: block; font-size: 13px; font-weight: 700; color: var(--color-text); line-height: 1.35; }

/* Generic two-column text/media */
.cs-split { display: grid; grid-template-columns: 1fr 1fr; gap: 44px; align-items: center; }
.cs-split img { width: 100%; border-radius: var(--radius); box-shadow: var(--shadow); }
.cs-prose p { font-size: 16px; color: var(--color-text-light); }
.cs-prose h3 { font-family: var(--font-heading); font-size: 22px; margin: 0 0 14px; }

/* VS comparison */
.cs-vs { display: grid; grid-template-columns: 1fr auto 1fr; gap: 18px; align-items: stretch; max-width: 920px; margin: 0 auto; }
.cs-vs__panel { background: var(--color-card); border-radius: var(--radius); box-shadow: var(--shadow); overflow: hidden; }
.cs-vs__img { height: 170px; background-size: cover; background-position: center; }
.cs-vs__panel--bad .cs-vs__img { background: linear-gradient(135deg, #cbb89e, #b59f82); }
.cs-vs__cols { display: grid; grid-template-columns: repeat(3, 1fr); gap: 6px; padding: 16px 12px; }
.cs-vs__cell { text-align: center; font-size: 12px; line-height: 1.35; color: var(--color-text-light); }
.cs-vs__cell i { display: block; font-size: 18px; margin-bottom: 6px; }
.cs-vs__panel--bad .cs-vs__cell i { color: #b08968; }
.cs-vs__panel--good .cs-vs__cell i { color: var(--color-primary); }
.cs-vs__badge { align-self: center; font-family: var(--font-heading); font-weight: 700; color: #fff; background: var(--color-primary); width: 54px; height: 54px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 16px; }

/* Steps */
.cs-steps { display: grid; grid-template-columns: repeat(3, 1fr); gap: 22px; margin-top: 10px; }
.cs-step { background: var(--color-card); border-radius: var(--radius); box-shadow: var(--shadow); padding: 30px 22px; text-align: center; position: relative; }
.cs-step__num { width: 40px; height: 40px; border-radius: 50%; background: var(--color-primary); color: #fff; font-family: var(--font-heading); font-weight: 700; display: flex; align-items: center; justify-content: center; margin: 0 auto 14px; }
.cs-step i { font-size: 30px; color: var(--color-primary); margin-bottom: 12px; display: block; }
.cs-step strong { display: block; font-size: 17px; margin-bottom: 6px; }
.cs-step p { font-size: 14px; color: var(--color-text-light); margin: 0; }

/* Cost table */
.cs-table { width: 100%; border-collapse: collapse; background: var(--color-card); border-radius: var(--radius); overflow: hidden; box-shadow: var(--shadow); margin: 0 auto; }
.cs-table th, .cs-table td { padding: 14px 16px; border-bottom: 1px solid var(--color-border); text-align: center; font-size: 15px; }
.cs-table thead th { background: var(--color-text); color: #fff; font-family: var(--font-body); font-weight: 700; }
.cs-table td:first-child, .cs-table th:first-child { text-align: left; }
.cs-table .cs-sub { display: block; font-size: 12px; color: var(--color-text-light); font-weight: 400; }
.cs-table .cs-bad { color: var(--color-accent-dark); font-weight: 700; }
.cs-table tr.cs-row-feature td { background: #EFF3EC; font-weight: 700; }
.cs-callouts { display: grid; grid-template-columns: 1fr 1fr; gap: 22px; margin-top: 28px; max-width: 760px; margin-left: auto; margin-right: auto; }
.cs-callout { border-radius: var(--radius); padding: 26px; text-align: center; border: 1px solid var(--color-border); }
.cs-callout--bad { background: #FBEFEA; border-color: #E7C9BC; }
.cs-callout--good { background: #EEF4EA; border-color: #CADEC0; }
.cs-callout small { text-transform: uppercase; letter-spacing: 0.6px; font-size: 12px; font-weight: 700; color: var(--color-text-light); }
.cs-callout__amt { font-family: var(--font-heading); font-weight: 700; font-size: 40px; margin: 6px 0; }
.cs-callout--bad .cs-callout__amt { color: var(--color-accent-dark); }
.cs-callout--good .cs-callout__amt { color: var(--color-primary-dark); }
.cs-callout p { font-size: 13px; color: var(--color-text-light); margin: 0; }

/* How it works */
.cs-how { display: grid; grid-template-columns: 0.9fr 1.1fr; gap: 40px; align-items: center; }
.cs-stack { display: flex; flex-direction: column; gap: 14px; padding: 10px 0; }
.cs-layer { height: 26px; border-radius: 8px; box-shadow: var(--shadow); }
.cs-layer--top { background: linear-gradient(135deg, #9DBB91, #80A276); height: 30px; }
.cs-layer--core { background: #FBFAF7; border: 1px solid #ECE6DC; }
.cs-layer--base { background: linear-gradient(135deg, #4A4036, #2F2820); height: 30px; }
.cs-howcards { display: flex; flex-direction: column; gap: 16px; }
.cs-howcard { display: flex; gap: 16px; background: var(--color-card); border-radius: var(--radius); box-shadow: var(--shadow); padding: 18px 20px; }
.cs-howcard i { font-size: 22px; color: var(--color-primary); flex-shrink: 0; margin-top: 4px; width: 26px; text-align: center; }
.cs-howcard strong { display: block; font-size: 16px; margin-bottom: 4px; }
.cs-howcard p { font-size: 14px; color: var(--color-text-light); margin: 0; }

/* Prevent cards */
.cs-prevent { display: grid; grid-template-columns: repeat(3, 1fr); gap: 22px; }
.cs-pcard { background: var(--color-card); border-radius: var(--radius); box-shadow: var(--shadow); padding: 26px 22px; text-align: center; }
.cs-pcard i { font-size: 30px; color: var(--color-primary); margin-bottom: 12px; display: block; }
.cs-pcard h3 { font-family: var(--font-heading); font-size: 19px; margin: 0 0 8px; }
.cs-pcard p { font-size: 14px; color: var(--color-text-light); }
.cs-pcard__list { list-style: none; padding: 14px 0 0; margin: 14px 0 0; border-top: 1px solid var(--color-border); text-align: left; }
.cs-pcard__list li { position: relative; padding-left: 26px; margin-bottom: 8px; font-size: 14px; }
.cs-pcard__list li::before { content: "\f00c"; font-family: "Font Awesome 6 Free"; font-weight: 900; position: absolute; left: 0; top: 1px; color: var(--color-primary); font-size: 12px; }
.cs-pcard__label { display: block; text-transform: uppercase; letter-spacing: 0.5px; font-size: 11px; font-weight: 700; color: var(--color-text-light); margin-bottom: 6px; }

/* Comparison table (vs GuineaDad) */
.cs-compare { width: 100%; border-collapse: collapse; background: var(--color-card); border-radius: var(--radius); overflow: hidden; box-shadow: var(--shadow); }
.cs-compare th, .cs-compare td { padding: 14px 18px; border-bottom: 1px solid var(--color-border); font-size: 14px; vertical-align: top; }
.cs-compare thead th { background: var(--color-bg-alt); font-family: var(--font-body); }
.cs-compare th:first-child, .cs-compare td:first-child { font-weight: 700; }
.cs-compare thead th:nth-child(2) { color: var(--color-primary-dark); }

/* FAQ */
.cs-faq { max-width: 800px; margin: 0 auto; }
.cs-faq details { background: var(--color-card); border-radius: var(--radius-sm); box-shadow: var(--shadow); padding: 4px 22px; margin-bottom: 12px; }
.cs-faq summary { font-weight: 700; padding: 14px 0; }
.cs-faq details > div { padding-bottom: 14px; }
.cs-faq details > div p { font-size: 15px; color: var(--color-text-light); margin: 0; }

/* Learn more */
.cs-learn-cards { display: grid; grid-template-columns: repeat(3, 1fr); gap: 22px; margin-bottom: 30px; }
.cs-learn-card { display: block; background: var(--color-card); border-radius: var(--radius); box-shadow: var(--shadow); padding: 26px; text-decoration: none !important; transition: box-shadow .2s ease, transform .2s ease; }
.cs-learn-card:hover { box-shadow: var(--shadow-hover); transform: translateY(-2px); }
.cs-learn-card i { font-size: 24px; color: var(--color-primary); margin-bottom: 12px; display: block; }
.cs-learn-card strong { display: block; font-family: var(--font-heading); font-size: 17px; color: var(--color-text); margin-bottom: 6px; }
.cs-learn-card span { font-size: 14px; color: var(--color-text-light); }

@media (max-width: 860px) {
  .cs-hero__grid, .cs-split, .cs-how { grid-template-columns: 1fr; }
  .cs-badges__row { grid-template-columns: repeat(3, 1fr); }
  .cs-steps, .cs-prevent, .cs-learn-cards, .cs-callouts { grid-template-columns: 1fr; }
  .cs-vs { grid-template-columns: 1fr; }
  .cs-vs__badge { margin: 0 auto; }
  .cs-hero__title { font-size: 30px; }
  .cs-h2 { font-size: 24px; }
  .cs-table, .cs-compare { display: block; overflow-x: auto; white-space: nowrap; }
}
</style>

<section class="cs-hero">
<div class="cs-container">
<div class="cs-hero__grid">
<div class="cs-hero__copy">
<p class="cs-eyebrow">Clinical Series Guinea Pig Fleece Cage Liners</p>
<h1 class="cs-hero__title">An All-In-One Solution for Messy, Complicated Cage Setups</h1>
<p class="cs-hero__text">Our all-in-one, reusable, antimicrobial fleece liner replaces paper bedding, wood shavings, pee pads, and complicated fleece setups. Spend less, waste less, and keep your piggies happier and healthier.</p>
<div class="cs-cta" style="text-align:left;">
<a href="https://www.etsy.com/listing/4447649326/house-of-guineas-clinical-series-liners" class="btn btn-lg btn-primary" target="_blank" rel="noopener noreferrer">Shop Now</a>
<p class="cs-shop-note">$400 for two liners · Ships from our Etsy shop</p>
</div>
</div>
<div class="cs-hero__media">
<img class="cs-hero__main" src="/clinical-series-inuse.jpg" alt="Guinea pig resting on a Clinical Series fleece cage liner in a 2x4 C&C cage" loading="eager" />
<div class="cs-hero__thumbs">
<img src="/clinical-series-liner.jpg" alt="Clinical Series all-in-one fleece liner construction" loading="lazy" />
<img src="/clinical-series-brand.jpg" alt="House of Guineas — SF engineered, silver-ion technology" loading="lazy" />
</div>
</div>
</div>
</div>
</section>

<section class="cs-badges">
<div class="cs-container">
<div class="cs-badges__row">
<div class="cs-badge"><i class="fa-solid fa-stethoscope"></i><span>Trusted by Veterinary Hospitals</span></div>
<div class="cs-badge"><i class="fa-solid fa-arrows-rotate"></i><span>Reusable</span></div>
<div class="cs-badge"><i class="fa-solid fa-shield-virus"></i><span>Silver-Ion Antimicrobial Technology</span></div>
<div class="cs-badge"><i class="fa-solid fa-hand-holding-heart"></i><span>Hypoallergenic</span></div>
<div class="cs-badge"><i class="fa-solid fa-location-dot"></i><span>Handmade in SF</span></div>
<div class="cs-badge"><i class="fa-solid fa-seedling"></i><span>Vegan Materials</span></div>
</div>
</div>
</section>

<section class="cs-section">
<div class="cs-container">
<h2 class="cs-h2">Built to Support Guinea Pig Health</h2>
<p class="cs-lead">Guinea pigs live close to the ground, so their bedding affects more than just cage cleanup. It impacts their paws, breathing, comfort, and overall cage hygiene every day.</p>
<div class="cs-prose" style="max-width:820px;margin:0 auto;">
<p>Clinical Series Liners are designed to help reduce common cage stressors like dust, damp bedding, ammonia odor, bacteria buildup, and rough or wet surfaces. Each liner combines a soft medical-grade fleece top, an absorbent antimicrobial core, and a waterproof yet breathable base to create a cleaner, drier, more comfortable environment for sensitive little bodies.</p>
<p>By wicking moisture away from your guinea pig's skin and keeping the cage surface soft and dry, Clinical Series Liners help support paw health and may help reduce the risk of two common guinea pig concerns: bumblefoot, also known as pododermatitis, and upper respiratory irritation.</p>
</div>
</div>
</section>

<section class="cs-section cs-section--alt">
<div class="cs-container">
<div class="cs-vs">
<div class="cs-vs__panel cs-vs__panel--bad">
<div class="cs-vs__img"></div>
<div class="cs-vs__cols">
<div class="cs-vs__cell"><i class="fa-solid fa-cloud"></i>More dust in the air</div>
<div class="cs-vs__cell"><i class="fa-solid fa-shower"></i>Mess spreads easily</div>
<div class="cs-vs__cell"><i class="fa-solid fa-wind"></i>May trigger sneezes</div>
</div>
</div>
<div class="cs-vs__badge">VS</div>
<div class="cs-vs__panel cs-vs__panel--good">
<div class="cs-vs__img" style="background-image:url('/clinical-series-inuse.jpg');"></div>
<div class="cs-vs__cols">
<div class="cs-vs__cell"><i class="fa-solid fa-wind"></i>Helps reduce airborne dust</div>
<div class="cs-vs__cell"><i class="fa-solid fa-shield-heart"></i>Cleaner, more comfortable space</div>
<div class="cs-vs__cell"><i class="fa-solid fa-lungs"></i>Supports easier breathing</div>
</div>
</div>
</div>
<p class="cs-center" style="margin-top:26px;color:var(--color-text-light);">Cleaner cage conditions mean happier guinea pigs — and a simpler routine for the humans who love them.</p>
</div>
</section>

<section class="cs-section">
<div class="cs-container">
<h2 class="cs-h2">Less Cleaning, More Cuddles</h2>
<p class="cs-lead">Clinical Series Liners are designed to make cage care simpler. Instead of dumping dusty bedding, replacing pee pads, and rebuilding layers, just spot-clean daily and machine wash when needed. Less time managing mess means more time cuddling, bonding, and playing with your guinea pigs.</p>
<div class="cs-steps">
<div class="cs-step"><div class="cs-step__num">1</div><i class="fa-solid fa-broom"></i><strong>Spot Clean Daily</strong><p>Sweep off hay and remove droppings to keep the surface fresh.</p></div>
<div class="cs-step"><div class="cs-step__num">2</div><i class="fa-solid fa-soap"></i><strong>Wash Every 1–2 Weeks</strong><p>Machine wash warm with gentle, fragrance-free detergent. No fabric softener.</p></div>
<div class="cs-step"><div class="cs-step__num">3</div><i class="fa-solid fa-wind"></i><strong>Tumble Dry on Low</strong><p>Dry on low heat and swap in your second liner while the first is in the wash.</p></div>
</div>
<p class="cs-center" style="margin-top:24px;color:var(--color-text-light);">Each pack comes with two liners so you can use one while the other is in the wash!</p>
</div>
</section>

<section class="cs-section cs-section--alt">
<div class="cs-container">
<h2 class="cs-h2">Understand the Real Cost of Your Current Setup</h2>
<p class="cs-lead">Disposable bedding and DIY fleece setups may seem cheaper at first, but the costs add up fast. The Clinical Series replaces paper bedding, wood shavings, pee pads, towels, and waterproof layers with one reusable liner system built to last for years.</p>
<table class="cs-table">
<thead><tr><th>Bedding Type</th><th>Year 1</th><th>Year 2</th><th>Year 5</th></tr></thead>
<tbody>
<tr><td>Paper Bedding<span class="cs-sub">est. $40/mo</span></td><td>$480</td><td>$960</td><td class="cs-bad">$2,400</td></tr>
<tr><td>Wood Shavings<span class="cs-sub">est. $25/mo</span></td><td>$300</td><td>$600</td><td class="cs-bad">$1,500</td></tr>
<tr><td>Fleece Liners (Basic)<span class="cs-sub">est. $80/yr, replaced</span></td><td>$80</td><td>$160</td><td>$400</td></tr>
<tr class="cs-row-feature"><td>Clinical Series Liners<span class="cs-sub" style="font-weight:400;">two liners, 6+ year lifespan</span></td><td>$400</td><td>$400</td><td>$400</td></tr>
</tbody>
</table>
<div class="cs-callouts">
<div class="cs-callout cs-callout--bad"><small>Disposable Bedding Adds Up</small><div class="cs-callout__amt">$2,400+</div><p>Estimated paper bedding cost over 5 years — $40/month, replaced again and again.</p></div>
<div class="cs-callout cs-callout--good"><small>Clinical Series Liners Cost</small><div class="cs-callout__amt">$400</div><p>Two complete reusable liners. Designed for 6+ years of cage care.</p></div>
</div>
</div>
</section>

<section class="cs-section">
<div class="cs-container">
<h2 class="cs-h2">How It Works</h2>
<p class="cs-lead">We've engineered 6 high-performance layers into an all-in-one design so thin and sleek, it deceptively looks like 2! No extra pee pads, towels, or plastic layers needed.</p>
<div class="cs-how">
<div class="cs-stack">
<div class="cs-layer cs-layer--top"></div>
<div class="cs-layer cs-layer--core"></div>
<div class="cs-layer cs-layer--core"></div>
<div class="cs-layer cs-layer--core"></div>
<div class="cs-layer cs-layer--core"></div>
<div class="cs-layer cs-layer--base"></div>
</div>
<div class="cs-howcards">
<div class="cs-howcard"><i class="fa-solid fa-droplet"></i><div><strong>Ultra-Soft Antimicrobial Fleece Top</strong><p>Wicks moisture away in under 2 seconds to keep sensitive little paws 100% dry. Infused with antimicrobial silver ions to stop odor and bacteria right at the surface.</p></div></div>
<div class="cs-howcard"><i class="fa-solid fa-layer-group"></i><div><strong>4-Layer Medical Absorption Core</strong><p>Absorbs up to 10x its weight, while trapping and neutralizing urine and respiratory-damaging ammonia on contact.</p></div></div>
<div class="cs-howcard"><i class="fa-solid fa-shield-halved"></i><div><strong>Integrated Waterproof &amp; Breathable Base</strong><p>100% leakproof protection for your cage floor, while remaining breathable to help keep the cage cooler and cleaner.</p></div></div>
</div>
</div>
<div class="cs-cta">
<a href="https://www.etsy.com/listing/4447649326/house-of-guineas-clinical-series-liners" class="btn btn-lg btn-primary" target="_blank" rel="noopener noreferrer">Shop Now</a>
<p class="cs-shop-note">$400 for two liners · Ships from our Etsy shop</p>
</div>
</div>
</section>

<section class="cs-section cs-section--alt">
<div class="cs-container">
<div class="cs-split">
<div><img src="/engineer.jpg" alt="Alexandria Brown, founder of House of Guineas and exotic veterinary assistant" loading="lazy" /></div>
<div class="cs-prose">
<h3>Engineered with Clinical Care in Mind</h3>
<p>Clinical Series Liners were thoughtfully engineered by Alexandria Brown, who combines a background in engineering with hands-on experience as an exotic veterinary assistant. Every fabric was chosen with purpose — not just for softness, but for safety, performance, and everyday cage hygiene.</p>
<p>These are not basic fleece liners. Each material was selected for a specific role: fast moisture wicking, high-capacity absorption, odor control, leak protection, breathability, and comfort for sensitive little bodies.</p>
<p>The liner's technical fabrics are manufactured under strict medical-grade guidelines and selected to be hypoallergenic, eco-friendly, and made from 100% vegan materials. They are engineered without nanoparticles, harsh chemical finishes, or toxic coatings, and are free from PFAS, PFOA, phthalates, lead, heavy metals, and BPA.</p>
</div>
</div>
</div>
</section>

<section class="cs-section">
<div class="cs-container">
<h2 class="cs-h2">Help Prevent the Bedding Problems That Lead to Vet Bills</h2>
<p class="cs-lead">Damp, dusty, or dirty guinea pig bedding can contribute to problems like bumblefoot, respiratory irritation, skin irritation, odor buildup, and bacteria growth. Clinical Series Liners help reduce those risks by keeping your cage cleaner, drier, softer, and lower-irritant between washes.</p>
<div class="cs-prevent">
<div class="cs-pcard"><i class="fa-solid fa-paw"></i><h3>Bumblefoot / Pododermatitis</h3><p>Damp, soiled, or rough bedding can irritate sensitive paws.</p><span class="cs-pcard__label">Care may include</span><ul class="cs-pcard__list"><li>Exam</li><li>Medication</li><li>Wound care</li><li>Bandaging</li><li>Follow-up visits</li></ul></div>
<div class="cs-pcard"><i class="fa-solid fa-lungs"></i><h3>Respiratory Irritation</h3><p>Dust, ammonia odor, and damp cages can stress sensitive lungs.</p><span class="cs-pcard__label">Care may include</span><ul class="cs-pcard__list"><li>Exam</li><li>Medication</li><li>X-rays</li><li>Nebulization</li><li>Follow-up care</li></ul></div>
<div class="cs-pcard"><i class="fa-solid fa-shield-virus"></i><h3>Skin Irritation / Bacteria Buildup</h3><p>Moisture and dirty cage surfaces can make skin more vulnerable to irritation.</p><span class="cs-pcard__label">Care may include</span><ul class="cs-pcard__list"><li>Exam</li><li>Topical treatment</li><li>Cultures</li><li>Medication</li><li>Rechecks</li></ul></div>
</div>
<p class="cs-center" style="margin-top:24px;color:var(--color-text-light);">An upfront investment in better bedding may help you avoid recurring bedding costs and the stress of preventable cage-related vet visits.</p>
<div class="cs-cta">
<a href="https://www.etsy.com/listing/4447649326/house-of-guineas-clinical-series-liners" class="btn btn-lg btn-primary" target="_blank" rel="noopener noreferrer">Shop Now</a>
<p class="cs-shop-note">$400 for two liners · Ships from our Etsy shop</p>
</div>
</div>
</section>

<section class="cs-section cs-section--alt">
<div class="cs-container">
<h2 class="cs-h2">Clinical Series vs. GuineaDad</h2>
<p class="cs-lead">Looking for a GuineaDad liner alternative or comparing reusable guinea pig bedding options? Both are designed to replace disposable bedding, but they are built very differently. Here's how they compare across absorbency, antimicrobial technology, prep, lifespan, and construction.</p>
<table class="cs-compare">
<thead><tr><th>Feature</th><th>Clinical Series</th><th>GuineaDad Liner</th></tr></thead>
<tbody>
<tr><td>Antimicrobial</td><td>Medical-grade silver ion, woven through every layer</td><td>Naturally antibacterial bamboo fiber</td></tr>
<tr><td>Absorption</td><td>Up to 10x its weight</td><td>Up to 3x its weight</td></tr>
<tr><td>Prep before first use</td><td>None — pre-activated, absorbs from day one</td><td>Prewashing recommended; liner shrinks to fit over the first few washes</td></tr>
<tr><td>Lifespan</td><td>6+ years</td><td>Varies with use</td></tr>
<tr><td>Made</td><td>Handmade in San Francisco by an exotic veterinary assistant</td><td>Brand-manufactured</td></tr>
</tbody>
</table>
<p class="cs-center" style="margin-top:14px;font-size:13px;color:var(--color-text-light);">Comparison based on publicly available brand information and each brand's stated product features.</p>
</div>
</section>

<section class="cs-section">
<div class="cs-container">
<h2 class="cs-h2">Frequently Asked Questions</h2>
<div class="cs-faq">
<details><summary>Do I need to prep the liners before first use?</summary><div><p>No. Unlike most guinea pig fleece liners that require 3–5 wash cycles before they start wicking properly, our Clinical Series liners come pre-activated and are ready to absorb right out of the box.</p></div></details>
<details><summary>What size C&amp;C cage do they fit?</summary><div><p>Our liners are sized for a standard 2x4 C&amp;C cage (56 by 24 inches) — the most popular guinea pig housing recommended by rescue organizations. If you have a custom setup, <a href="mailto:petcare@houseofguineas.com">contact us</a> and we can discuss options.</p></div></details>
<details><summary>How often should I wash the liners?</summary><div><p>We recommend washing every 1–2 weeks. Spot clean daily by removing hay and droppings. When it's wash day, simply swap to your second liner while the first goes through the machine. Warm wash, gentle detergent, tumble dry low. No fabric softener.</p></div></details>
<details><summary>Are fleece liners safe for baby guinea pigs?</summary><div><p>Yes — fleece is actually safer for baby guinea pigs than loose bedding, which young pigs may accidentally ingest. Our medical-grade fleece provides a soft, warm surface that's gentle on tiny feet.</p></div></details>
<details><summary>What is silver ion antimicrobial technology?</summary><div><p>Silver ions (Ag+) have natural antimicrobial properties that disrupt bacterial cell membranes. In our liners, silver ion technology is integrated throughout the entire fabric — not just a single layer — to actively neutralize ammonia and inhibit bacterial growth between washes. This keeps your guinea pig's enclosure cleaner and healthier for longer.</p></div></details>
<details><summary>Can I use these liners for rabbits or chinchillas?</summary><div><p>While designed for guinea pigs, the Clinical Series liners work well for rabbits and chinchillas too. The antimicrobial properties and absorption capacity benefit any small mammal. Just ensure the sizing works for your enclosure.</p></div></details>
<details><summary>Do I need to buy separate pee pads or waterproof bases?</summary><div><p>No. Unlike most fleece liner setups where you need to buy a fleece liner, separate absorbent pads, and a waterproof base layer — often from different brands — the Clinical Series is an all-in-one design. The waterproof base, absorption core, and fleece top are all built into a single product, and the entire liner is antimicrobial with silver ion technology throughout. Just place it in your cage and you're done.</p></div></details>
<details><summary>How are these different from GuineaDad liners?</summary><div><p>The Clinical Series is a complete all-in-one liner — you don't need to buy separate pee pads or accessories. The entire fabric is medical-grade, with silver ion antimicrobial technology built into every layer that actively neutralizes ammonia. GuineaDad's antimicrobial protection comes from bamboo in its top fleece layer only; our silver-ion technology runs through the whole liner — base, core, and top. Our liners also come pre-activated (no 3–5 prep washes), last 6+ years, and are handmade in San Francisco by an exotic veterinary assistant with an engineering background.</p></div></details>
</div>
</div>
</section>

<section class="cs-section cs-section--grey">
<div class="cs-container">
<h2 class="cs-h2">Learn More</h2>
<p class="cs-lead">A better cage starts with a better surface. Read our guides to learn how Clinical Series Liners support cleaner, drier cage conditions, help reduce common bedding stressors, and make daily care simpler for guinea pig parents.</p>
<div class="cs-learn-cards">
<a class="cs-learn-card" href="/post/guinea-pig-fleece-liners-vs-disposable-bedding/"><i class="fa-solid fa-scale-balanced"></i><strong>Fleece Liners vs Disposable Bedding</strong><span>An honest cost and health comparison for guinea pig parents.</span></a>
<a class="cs-learn-card" href="/post/guinea-pig-cage-setup/"><i class="fa-solid fa-house-chimney"></i><strong>Guinea Pig Cage Setup</strong><span>C&amp;C cages, sizing, and what goes inside a healthy enclosure.</span></a>
<a class="cs-learn-card" href="/post/signs-your-guinea-pig-needs-a-vet/"><i class="fa-solid fa-stethoscope"></i><strong>Signs Your Guinea Pig Needs a Vet</strong><span>Spot the early warning signs of common guinea pig health issues.</span></a>
</div>
<div class="cs-center"><a href="/post/" class="btn btn-lg btn-primary">View All Resources</a></div>
</div>
</section>
