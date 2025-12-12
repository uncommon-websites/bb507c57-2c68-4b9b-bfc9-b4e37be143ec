<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-serif font-normal tracking-tight mb-8">
				Transform <span class="italic font-light font-serif">scattered feedback</span><br />
				into cohesive growth
			</h1>

			<p class="text-xl text-gray-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				Structured reflection frameworks and collaborative rituals that turn engineering teams into high-performing, intentional developers.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<button class="bg-primary-600 hover:bg-primary-700 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					Get started
				</button>
				<button class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					Join a community
				</button>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- One-on-One Framework Mockup -->
			<div class="rounded-xl overflow-hidden border border-white/10 shadow-2xl bg-[#0a0a0a] aspect-[16/10] relative">
				<img src="/generated/image-engineering-manager-having-a-thoughtful--1765515076314-0.webp" alt="Engineering manager in one-on-one" class="absolute inset-0 w-full h-full object-cover opacity-40" />
				
				<!-- Overlay Content -->
				<div class="relative h-full flex items-center justify-center p-8">
					<div class="max-w-2xl w-full bg-[#0f0f0f]/90 backdrop-blur-sm border border-white/10 rounded-xl p-8">
						<div class="text-xs font-bold text-primary-400 uppercase tracking-wider mb-4">Weekly One-on-One Framework</div>
						<div class="space-y-4">
							<div class="flex items-start gap-3">
								<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">1</div>
								<div>
									<div class="text-sm font-medium text-white mb-1">Reflection</div>
									<div class="text-xs text-gray-400">What went well? What could be better?</div>
								</div>
							</div>
							<div class="flex items-start gap-3">
								<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">2</div>
								<div>
									<div class="text-sm font-medium text-white mb-1">Growth Goals</div>
									<div class="text-xs text-gray-400">Progress on current objectives</div>
								</div>
							</div>
							<div class="flex items-start gap-3">
								<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">3</div>
								<div>
									<div class="text-sm font-medium text-white mb-1">Blockers & Support</div>
									<div class="text-xs text-gray-400">What help do you need?</div>
								</div>
							</div>
							<div class="flex items-start gap-3">
								<div class="w-6 h-6 rounded-full bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-primary-400 text-xs font-bold mt-0.5">4</div>
								<div>
									<div class="text-sm font-medium text-white mb-1">Action Items</div>
									<div class="text-xs text-gray-400">Clear next steps for both parties</div>
								</div>
							</div>
						</div>
					</div>
				</div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-black/40 pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Client Logos -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20">
        <div class="text-center mb-8">
            <p class="text-sm text-gray-500 uppercase tracking-wider">Trusted by engineering leaders at</p>
        </div>
        <div class="flex flex-wrap justify-center md:justify-between items-center gap-8 opacity-50 grayscale hover:grayscale-0 transition-all duration-500">
            <span class="text-xl font-bold font-sans">Stripe</span>
            <span class="text-xl font-bold font-sans">Vercel</span>
            <span class="text-xl font-bold font-sans tracking-wide">Linear</span>
            <span class="text-xl font-bold font-sans">Notion</span>
            <span class="text-xl font-bold font-sans">Figma</span>
            <span class="text-xl font-bold font-sans">Retool</span>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>
