<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	centered={false}
	title="Create winning ads with AI actors in minutes"
	subtitle="Transform your ad creative production with 1,000+ photorealistic AI actors. Generate performance-ready video ads at 10% of traditional costs and scale to 720M monthly impressions."
	imageSrc="/generated/image-a-performance-marketer-with-a-joyful-exp.webp"
	callsToAction={[
		{
			href: "#",
			label: "Start creating ads"
		},
		{
			href: "#",
			label: "View AI actors"
		}
	]}
/>
<LogoScroller
	label="Trusted by leading brands"
	logoUrls={[
		'https://cdn.brandfetch.io/headway.io/w/400/h/400/logo',
		'https://cdn.brandfetch.io/asana.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/clickfunnels.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bendingspoons.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Head of Growth",
			company: "NutriFlow",
			quote:
				"We slashed our ad production costs by 87% while testing 3x more creative variations. What used to take us $2,400 and two weeks now costs $300 and happens in minutes. Our Meta ROAS improved by 42% because we can finally test at scale.",
			image: "/generated/image-confident-headshot-of-a-professional-asi.webp"
		},
		{
			name: "Marcus Washington",
			position: "Performance Marketing Lead",
			company: "FitTrack Studios",
			quote:
				"Before Arcads, hiring UGC creators was our biggest bottleneck. Now we generate 40+ ad variations weekly with their AI actors and our view rates jumped 68%. The multilingual support helped us expand into Spanish markets without additional production costs.",
			image: "/generated/image-confident-headshot-of-a-professional-bla.webp"
		},
		{
			name: "Carmen Rodriguez",
			position: "Acquisition Director",
			company: "LearnHub",
			quote:
				"The time savings are remarkable. We went from 5 days and $500 per video to 15 minutes and $50. Our TikTok campaigns now run with 25+ creative variants, and we've seen conversion rates increase by 31%. The AI actors genuinely outperform traditional creators.",
			image: "/generated/image-confident-headshot-of-a-professional-his.webp"
		}
	]}
/>

<Features
	title="Built for performance marketers who need results"
	subtitle="Everything you need to scale ad creative production and beat rising acquisition costs"
	features={[
		{
			title: "1,000+ photorealistic AI actors",
			description:
				"Choose from a massive library of hyper-realistic AI actors who can hold products, show apps, and wear clothing. No more waiting days for UGC creators or paying $300+ per video."
		},
		{
			title: "10% of traditional production costs",
			description:
				"Generate performance-ready video ads at a fraction of what you'd pay creators or production studios. Scale your testing budget to create dozens of variations instead of just a few."
		},
		{
			title: "Minutes instead of days",
			description:
				"Go from concept to finished ad in minutes, not the days or weeks traditional production requires. Launch campaigns faster and capitalize on trending opportunities immediately."
		},
		{
			title: "30+ languages for global reach",
			description:
				"Expand into new markets instantly with accurate translation and native-sounding voice synthesis. One creative becomes dozens of localized ads without hiring international creators."
		},
		{
			title: "Rapid testing at scale",
			description:
				"Test dozens of ad variations weekly to find winning combinations and beat your competitors. Full emotion control through text prompts means infinite creative possibilities."
		},
		{
			title: "Proven at 720M impressions monthly",
			description:
				"Join 100,000+ entrepreneurs generating real results with an average +70% view increase and +13% conversion lift. Our AI actors have already driven $4M in customer revenue."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start creating winning ads in minutes"
	subtitle="Join 100,000+ entrepreneurs"
	description="While your competitors wait days and pay $300+ per UGC video, you could be testing dozens of variations with photorealistic AI actors that have already generated 720M impressions. The marketers who scale fastest are the ones who test fastest."
	imageSrc="/generated/image-a-cheerful-performance-marketer-celebrat.webp"
	callsToAction={[
		{
			href: "#",
			label: "Start creating ads",
			variant: "primary"
		},
		{
			href: "#",
			label: "See AI actors in action",
			variant: "secondary"
		}
	]}
/>
