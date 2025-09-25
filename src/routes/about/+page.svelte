<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Privacy first",
			description: "Your prompts stay local. No cloud storage, no data collection, full user control."
		},
		{
			title: "Workflow focused",
			description: "Built for real AI power users who need efficiency, not complexity."
		},
		{
			title: "Universal compatibility",
			description: "Works across all major AI platforms with seamless browser integration."
		}
	];
</script>

<SecondaryHero
	title="Smarter prompts. Better work."
	subtitle="Finally, AI that fits your workflow"
	imageSrc="/generated/image-realistic-candid-photo-of-a-focused-prof.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"You shouldn't waste three hours a day digging through Notion, Docs, or Slack just to find the same prompts you used yesterday. For SaaS marketing teams and AI consultants juggling 50+ prompts daily, the chaos adds up fast. Prompt Quiver was born from that exact frustration—the need for a faster, cleaner way to manage proven prompts and produce consistent results at scale.",
		"We started by building a structured library that adapts to the way experts actually work. With a modular system of reusable snippets and a privacy-first design that keeps everything local, Prompt Quiver turns repetitive prompt workflows into time-saving systems. Whether you're refining copy across campaigns or keeping client results consistent, Prompt Quiver gives you browser-native access to your best prompts—right when and where you need them.",
		"Today, we're on a mission to transform disorganized AI interactions into powerful, repeatable workflows. From independent consultants to growing SaaS content teams, we help anyone working with AI daily save time, reduce errors, and scale their output. With over 100,000 installs and counting, Prompt Quiver is capturing a slice of the $50B productivity software market—one saved prompt at a time."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Building the future of AI productivity."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Former AI consultant who experienced prompt chaos firsthand and built Prompt Quiver to solve it.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "UX specialist focused on making complex prompt workflows simple and intuitive for daily use.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Browser extension expert building universal AI platform compatibility with privacy-first architecture.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by productivity experts."
	subtitle="Investors who understand AI workflow efficiency"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to streamline your prompts?"
	subtitle="Join thousands of AI power users"
	description="Transform your scattered prompts into organized, efficient workflows. Start building your prompt library today and reclaim hours of productive time."
/>
