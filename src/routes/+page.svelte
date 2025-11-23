<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
	
	// Icons
	import IconZap from "~icons/lucide/zap";
	import IconHeart from "~icons/lucide/heart";
	import IconTarget from "~icons/lucide/target";
	import IconWand2 from "~icons/lucide/wand-2";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconShieldCheck from "~icons/lucide/shield-check";
</script>

<CenteredTextOnlyHero
	title="Emotion-aware voice agents that resolve enterprise support at scale"
	subtitle="Deploy AI voice agents in two weeks with 90% resolution accuracy. Handle millions of calls across 99+ languages while maintaining natural conversation and emotion detection."
	imageSrc="/generated/image-a-documentary-style-photograph-of-a-sale.webp"
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/doordash.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/airbnb.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/zendesk.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for enterprise support leaders"
	text="Giga deploys emotion-aware voice agents that resolve complex customer support tickets through natural conversation. We serve enterprise support teams who need to scale their operations without sacrificing quality, delivering 90% resolution accuracy across millions of calls in 99+ languages. Where traditional support systems break down under complexity, our agents understand context, detect emotion, and handle workflows from live delivery issues to compliance decisions—all deployed in just two weeks."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "VP Customer Experience",
			company: "Velocity Logistics",
			quote:
				"We went from 62% to 91% resolution accuracy in three weeks. Our team now handles 4x the volume with the same headcount, and customer satisfaction scores jumped 28 points. The ROI was immediate.",
			image: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		},
		{
			name: "Marcus Williams",
			position: "Head of Support Operations",
			company: "Nexus Financial",
			quote:
				"Giga cut our average handle time from 8 minutes to 2.5 minutes while maintaining compliance across all 47 states. We're saving $2.3M annually and our agents finally have time to focus on complex cases that actually need human judgment.",
			image: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		},
		{
			name: "Carmen Rodriguez",
			position: "Director of Customer Success",
			company: "Horizon Health",
			quote:
				"The emotion-aware capability was game-changing for healthcare support. We've reduced escalations by 67% because the AI knows when to adjust tone and when to route to specialists. Implementation took 11 days, not the 6 months our previous vendor quoted.",
			image: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		}
	]}
/>

<Features
	title="Why enterprise teams choose Giga"
	subtitle="Built for scale, designed for speed, optimized for results"
	features={[
		{
			title: "Deploy in two weeks, not months",
			description:
				"Launch production-ready voice agents in 14 days with our Agent Canvas builder. Skip months of development and start resolving tickets immediately.",
			icon: IconZap
		},
		{
			title: "Emotion-aware conversations",
			description:
				"Detect sentiment, pitch, and tone in real-time to deliver empathetic responses that feel genuinely human across 99+ languages.",
			icon: IconHeart
		},
		{
			title: "90% resolution accuracy in production",
			description:
				"Handle complex workflows from live delivery issues to compliance decisions with proven accuracy that eliminates escalations and reduces costs.",
			icon: IconTarget
		},
		{
			title: "Agent Canvas for effortless customization",
			description:
				"Build sophisticated AI agents through simple chat instructions. Atlas AI ingests your SOPs and auto-drafts policies tailored to your workflows.",
			icon: IconWand2
		},
		{
			title: "Smart Insights auto-improvement",
			description:
				"Continuously optimize performance with AI-generated suggestions that analyze thousands of calls to identify resolution rate improvements.",
			icon: IconTrendingUp
		},
		{
			title: "Enterprise-grade security & compliance",
			description:
				"Trust SOC 2, HIPAA, and GDPR-compliant infrastructure that protects sensitive data while scaling to millions of customer interactions.",
			icon: IconShieldCheck
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join enterprises scaling support without scaling costs"
	subtitle="Your competition is already implementing AI"
	description="DoorDash achieved 80% resolution across 40+ countries in weeks, not months. See how Giga deploys emotion-aware voice agents that handle millions of calls with 90% accuracy while you maintain full control and enterprise-grade security."
	imageSrc="/generated/image-a-confident-vp-of-customer-experience-in.webp"
	callsToAction={[
		{
			href: "/demo",
			label: "See a live demo",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
