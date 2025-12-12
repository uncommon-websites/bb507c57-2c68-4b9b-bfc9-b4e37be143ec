<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-16">Pricing</h2>

		<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
			<!-- Enterprise -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Enterprise</h3>
				<p class="text-gray-400 text-sm mb-6">Custom pricing</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Contact sales
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN PROFESSIONAL +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom framework development</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Dedicated success manager</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Private coaching sessions</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom analytics & reporting</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>On-site workshops</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>API access for custom integrations</span>
					</li>
				</ul>
			</div>

			<!-- Professional -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Professional</h3>
				<p class="text-primary-400 text-sm mb-6">$99 / manager per month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Start free trial
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">EVERYTHING IN STARTER +</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Advanced analytics dashboard</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>All integrations (Slack, Linear, GitHub, etc.)</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom framework templates</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Weekly peer coaching calls</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Monthly expert workshops</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Priority support</span>
					</li>
				</ul>
			</div>

			<!-- Starter -->
			<div>
				<h3 class="text-xl font-bold mb-2">Starter</h3>
				<p class="text-primary-400 text-sm mb-6">$49 / manager per month</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Get started
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">PERFECT FOR NEW MANAGERS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 10 team members</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Private Slack community access</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Core framework templates</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>One-on-one meeting guides</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Basic progress tracking</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Goal setting templates</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Email support</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
