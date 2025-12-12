<script lang="ts">
	import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-20 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 lg:gap-12">
			<!-- Stat 1 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Series B startup implements structured one-on-ones across engineering
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">87%</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-primary-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Team Alignment Score</span>
					</div>
				</div>
			</div>

			<!-- Stat 2 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Fast-growing tech company adopts reflection frameworks for managers
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">3x</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-primary-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Feedback Quality Increase</span>
					</div>
				</div>
			</div>

			<!-- Stat 3 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Engineering team uses collaborative rituals to reduce turnover
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">45%</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-primary-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Retention Improvement</span>
					</div>
				</div>
			</div>

			<!-- Stat 4 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Startup scales from 10 to 50 engineers with cohesive development practices
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">5x</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-primary-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Team Growth</span>
					</div>
				</div>
			</div>
		</div>

        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mt-12">
            <button class="w-10 h-10 rounded-full bg-white/5 hover:bg-white/10 flex items-center justify-center transition-colors">
                <ArrowLeft size={16} />
            </button>
            <button class="w-10 h-10 rounded-full bg-white/5 hover:bg-white/10 flex items-center justify-center transition-colors">
                <ArrowRight size={16} />
            </button>
        </div>
	</div>
</section>
