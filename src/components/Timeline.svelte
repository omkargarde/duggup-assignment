<script>
	import sam from '$lib/images/samAltman.png';
	import steve from '$lib/images/steveJobs.png';
</script>

<div class="flex">
	<div class="w-[17rem] justify-end border-r-4 border-dotted pt-12 text-end">Dec 2023</div>
	<div class=" flex pl-12 pt-12">
		<div
			class=" mx-8 max-w-xs rounded-lg border border-gray-200 bg-white shadow dark:border-gray-700 dark:bg-gray-800"
		>
			<img class="rounded-t-lg" src={steve} alt="steve jobs" />
			<div class="p-5">
				<p class="mb-3 text-sm text-gray-700 dark:text-gray-400">
					No amount of technology can convert a bad story into a good story.
				</p>
			</div>
		</div>
		<div
			class="max-w-xs rounded-lg border border-gray-200 bg-white shadow dark:border-gray-700 dark:bg-gray-800"
		>
			<img class="rounded-t-lg" src={sam} alt="sam altman" />
			<div class="p-5">
				<p class="mb-3 text-sm text-gray-700 dark:text-gray-400">
					Most people don't have original ideas. Here is how Sam Altman pushes himself to have
					unpopular ideas.
				</p>
			</div>
		</div>
	</div>
</div>
<div></div>
