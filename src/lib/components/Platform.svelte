<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
				Complete framework for<br />
				intentional development
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				Everything you need to transform scattered feedback into structured growth for your engineering team.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: One-on-Ones -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Structured One-on-Ones</h3>
					<p class="text-gray-400 text-sm">Transform meetings into growth conversations</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex flex-col gap-3 p-4">
                         <div class="bg-[#1a1a1a] border border-white/5 rounded-lg p-4">
                             <div class="text-xs text-primary-400 font-bold mb-2">WEEKLY CHECK-IN</div>
                             <div class="text-sm text-white mb-3">Sarah Chen · Senior Engineer</div>
                             <div class="space-y-2">
                                 <div class="flex items-center gap-2 text-xs text-gray-400">
                                     <div class="w-4 h-4 rounded bg-primary-500/20 border border-primary-500/50"></div>
                                     <span>Wins & Learnings</span>
                                 </div>
                                 <div class="flex items-center gap-2 text-xs text-gray-400">
                                     <div class="w-4 h-4 rounded bg-primary-500/20 border border-primary-500/50"></div>
                                     <span>Career Goals Progress</span>
                                 </div>
                                 <div class="flex items-center gap-2 text-xs text-gray-400">
                                     <div class="w-4 h-4 rounded bg-white/10"></div>
                                     <span>Blockers & Support Needed</span>
                                 </div>
                             </div>
                         </div>
                         
                         <div class="bg-[#1a1a1a] border border-white/5 rounded-lg p-4 opacity-60">
                             <div class="text-xs text-gray-500 font-bold mb-2">NEXT UP</div>
                             <div class="text-sm text-gray-400">Marcus Rodriguez · Lead Engineer</div>
                         </div>
                         
                         <div class="bg-[#1a1a1a] border border-white/5 rounded-lg p-4 opacity-40">
                             <div class="text-xs text-gray-500 font-bold mb-2">SCHEDULED</div>
                             <div class="text-sm text-gray-400">Alex Kim · Mid-level Engineer</div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Progress Tracking -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Progress Tracking</h3>
					<p class="text-gray-400 text-sm">Visualize growth over time</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-primary-500/10 p-4 rounded w-1/3 border border-primary-500/20">
                            <div class="text-xs text-primary-300 mb-1">Team Health</div>
                            <div class="text-xl font-bold text-primary-400">92% ↗</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Engagement</div>
                            <div class="text-xl font-bold text-white">87%</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Goals Met</div>
                            <div class="text-xl font-bold text-white">78%</div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4">
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Lines -->
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="oklch(0.765 0.177 163.223)" stroke-width="2" />
                             
                             <!-- Area under curve -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="oklch(0.696 0.17 162.48)" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Reflection Frameworks -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Reflection Frameworks</h3>
					<p class="text-gray-400 text-sm">Structured templates for meaningful conversations</p>
				</div>
                
                 <!-- Mockup Content - Framework List -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 text-xs">
                    <div class="space-y-3">
                        <div class="bg-primary-500/10 border border-primary-500/30 rounded-lg p-3">
                            <div class="font-semibold text-white mb-1">Weekly One-on-One</div>
                            <div class="text-gray-400 text-[10px]">4 sections · 15 min</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-lg p-3 opacity-80">
                            <div class="font-semibold text-white mb-1">Quarterly Review</div>
                            <div class="text-gray-400 text-[10px]">6 sections · 45 min</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-lg p-3 opacity-60">
                            <div class="font-semibold text-white mb-1">Career Development</div>
                            <div class="text-gray-400 text-[10px]">5 sections · 30 min</div>
                        </div>
                        <div class="bg-white/5 border border-white/10 rounded-lg p-3 opacity-40">
                            <div class="font-semibold text-white mb-1">Project Retrospective</div>
                            <div class="text-gray-400 text-[10px]">3 sections · 20 min</div>
                        </div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Team Rituals -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Team Rituals</h3>
					<p class="text-gray-400 text-sm">Build consistent development practices</p>
				</div>
                
                 <!-- Mockup Content - Calendar View -->
                <div class="flex-1 relative flex flex-col gap-3">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-4 relative">
                        <div class="absolute -inset-0.5 bg-gradient-to-r from-primary-500/20 to-primary-600/20 blur opacity-50"></div>
                        
                        <div class="relative bg-[#1a1a1a] rounded-xl">
                            <div class="flex items-center gap-3 mb-3">
                                <div class="w-8 h-8 rounded bg-primary-500/20 flex items-center justify-center shrink-0 text-primary-400 font-bold text-xs">
                                    M
                                </div>
                                <div>
                                    <div class="font-medium text-xs text-white">Monday Team Sync</div>
                                    <div class="text-[10px] text-gray-500">Weekly alignment · 30 min</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] border border-white/5 rounded-lg p-4">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded bg-white/10 flex items-center justify-center shrink-0 text-gray-400 font-bold text-xs">
                                W
                            </div>
                            <div>
                                <div class="font-medium text-xs text-white">Mid-week Check-ins</div>
                                <div class="text-[10px] text-gray-500">Individual progress · 15 min</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] border border-white/5 rounded-lg p-4 opacity-60">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded bg-white/10 flex items-center justify-center shrink-0 text-gray-400 font-bold text-xs">
                                F
                            </div>
                            <div>
                                <div class="font-medium text-xs text-white">Friday Retros</div>
                                <div class="text-[10px] text-gray-500">Week reflection · 20 min</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Goal Alignment -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Goal Alignment</h3>
					<p class="text-gray-400 text-sm">Connect individual growth to team objectives</p>
				</div>
                
                 <!-- Mockup Content - Goal Hierarchy -->
                <div class="flex-1 relative flex flex-col gap-4">
                    <div class="bg-[#1a1a1a] rounded-lg p-4 text-xs text-gray-300 border border-primary-500/30">
                        <div class="text-[10px] text-primary-400 font-bold mb-2">TEAM GOAL</div>
                        <div class="text-sm text-white font-medium">Ship v2.0 by Q2</div>
                    </div>
                    
                    <div class="flex-1 bg-[#1a1a1a] border border-white/10 rounded-lg overflow-hidden flex flex-col p-4 gap-3">
                         <div class="text-[10px] text-gray-500 font-bold">INDIVIDUAL GOALS</div>
                         
                         <div class="bg-white/5 rounded p-3 border-l-2 border-primary-500">
                             <div class="text-xs text-white mb-1">Master GraphQL</div>
                             <div class="flex items-center gap-2 mt-2">
                                 <div class="flex-1 h-1.5 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full bg-primary-500 w-3/4"></div>
                                 </div>
                                 <span class="text-[10px] text-gray-400">75%</span>
                             </div>
                         </div>
                         
                         <div class="bg-white/5 rounded p-3 border-l-2 border-primary-500/50">
                             <div class="text-xs text-white mb-1">Lead architecture review</div>
                             <div class="flex items-center gap-2 mt-2">
                                 <div class="flex-1 h-1.5 bg-white/10 rounded-full overflow-hidden">
                                     <div class="h-full bg-primary-500 w-1/2"></div>
                                 </div>
                                 <span class="text-[10px] text-gray-400">50%</span>
                             </div>
                         </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
