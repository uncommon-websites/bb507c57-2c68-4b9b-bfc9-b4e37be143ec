<script lang="ts">
    const integrations = [
        { name: 'Slack', color: 'bg-purple-500' },
        { name: 'Linear', color: 'bg-indigo-500' },
        { name: 'GitHub', color: 'bg-gray-700' },
        { name: 'Notion', color: 'bg-gray-600' },
        { name: 'Jira', color: 'bg-blue-500' },
        { name: 'Asana', color: 'bg-pink-500' },
        { name: 'Figma', color: 'bg-purple-400' },
        { name: 'Google Cal', color: 'bg-blue-400' },
        { name: 'Zoom', color: 'bg-blue-600' },
        { name: 'Loom', color: 'bg-purple-600' },
        { name: 'Confluence', color: 'bg-blue-300' },
        { name: 'GitLab', color: 'bg-orange-500' },
        { name: 'Trello', color: 'bg-blue-400' },
        { name: 'Monday', color: 'bg-red-500' },
        { name: 'ClickUp', color: 'bg-purple-500' },
        { name: 'Basecamp', color: 'bg-green-500' }
    ];

    const features = [
        'Goal tracking', 'Progress metrics', 'Team analytics', 'Custom frameworks', 
        'Peer feedback', 'Career ladders', 'Skill matrices', 'Growth plans', 
        'Meeting notes', 'Action items', 'Reflection prompts', 'Template library'
    ];
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
			Integrates with your<br />
			existing workflow
		</h2>
		<p class="text-gray-400 text-lg max-w-2xl mx-auto mb-20">
			Connect with the tools your team already uses. Track progress where work happens.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Integrations -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Connect your daily tools
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                    {#each integrations as tool}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-lg {tool.color} mb-3 flex items-center justify-center opacity-80 group-hover:opacity-100 transition-opacity">
                                <!-- Simple icon placeholder -->
                            </div> 
                            <span class="text-[10px] text-gray-400 font-medium">{tool.name}</span>
                        </div>
                    {/each}
                </div>
            </div>

            <!-- Features -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Powerful features included
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                     {#each features as item}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-full border border-primary-500/30 mb-3 flex items-center justify-center text-primary-400 group-hover:text-primary-300 transition-colors">
                                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                    <polyline points="20 6 9 17 4 12"/>
                                </svg>
                            </div> 
                            <span class="text-[10px] text-gray-400 text-center leading-tight font-medium">{item}</span>
                        </div>
                    {/each}
                </div>
            </div>
		</div>
	</div>
</section>
