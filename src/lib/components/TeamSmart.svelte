<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-12 leading-tight">
					Built for engineering<br />
					leaders who care
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 text-primary-400 font-medium">
						<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
						First-time managers
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Get the structure and frameworks you need to lead with confidence, even if you've never managed before.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Engineering managers
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Directors of engineering
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						VPs of engineering
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						CTOs at startups
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Technical founders
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative">
                     <img src="/generated/image-confident-engineering-leader-reviewing-n-1765515083143-2.webp" alt="Engineering leader planning" class="w-full h-full object-cover" />
                     
                     <!-- Framework Overlay -->
                     <div class="absolute bottom-8 left-8 right-8 bg-[#0f0f0f]/95 backdrop-blur-sm border border-white/10 rounded-xl p-4 shadow-2xl">
                         <div class="text-xs font-bold text-primary-400 uppercase tracking-wider mb-3">This Week's Focus</div>
                         <div class="space-y-2">
                             <div class="flex items-center gap-2 text-xs text-white">
                                 <div class="w-4 h-4 rounded bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-[8px] text-primary-400">✓</div>
                                 <span>3 one-on-ones completed</span>
                             </div>
                             <div class="flex items-center gap-2 text-xs text-white">
                                 <div class="w-4 h-4 rounded bg-primary-500/20 border border-primary-500/50 flex items-center justify-center text-[8px] text-primary-400">✓</div>
                                 <span>Q1 goals reviewed with team</span>
                             </div>
                             <div class="flex items-center gap-2 text-xs text-gray-400">
                                 <div class="w-4 h-4 rounded bg-white/10 border border-white/20"></div>
                                 <span>Friday retro scheduled</span>
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
