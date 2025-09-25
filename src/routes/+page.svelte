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
	title="Keep your best prompts close."
	subtitle="Stop searching, retyping, and wasting time."
	imageSrc="/generated/image-natural-light-editorial-photo-of-a-marke.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/slack.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo'
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
			name: "Maya Patel",
			position: "Marketing Director",
			company: "CloudScale SaaS",
			quote:
				"Prompt Quiver saved me 4 hours every day by organizing my 80+ prompts into searchable categories.\nMy content quality improved dramatically with consistent, proven templates at my fingertips.",
			image: "/generated/image-photorealistic-professional-headshot-of-.webp"
		},
		{
			name: "Marcus Rodriguez",
			position: "AI Strategy Consultant",
			company: "Neural Insights",
			quote:
				"Managing client prompts across 15 different projects used to be chaos.\nNow I deliver consistent results 3x faster and my clients see 67% better AI outputs.",
			image: "/generated/image-photorealistic-professional-headshot-of-.webp"
		},
		{
			name: "Elena Kowalski",
			position: "Content Operations Manager",
			company: "StreamlineTech",
			quote:
				"The snippet system transformed how our team scales content creation.\nWe reduced prompt revision cycles by 75% and increased our content output by 200%.",
			image: "/generated/image-photorealistic-professional-headshot-of-.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction 
	title="Stop wasting 3+ hours a day on repeat prompt work"
	subtitle="Install the extension and start reclaiming your time today"
	description="Prompt Quiver centralizes your AI prompts, streamlines workflows with intelligent snippets, and fits right into your browser—so you can finally stop searching, retyping, and switching tools. No onboarding. No workflow disruption. Just immediate time savings."
	imageSrc="/generated/image-happy-marketing-manager-celebrating-succ.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Get started for free",
			variant: "primary"
		},
		{
			href: "/demo",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
