<script>
	import circleBig from '$lib/Icon/CircleBig.svg?raw';
	import socialIcons from '$lib/Icon/SocialIconsBig.svg?raw';
	import arrowUp from '$lib/Icon/arrowUp.svg?raw';
	import circle from '$lib/Icon/circleSmall.svg?raw';
	import betterUp from '$lib/images/betterUp.png';
	import monitor from '$lib/images/monitor.png';
	import sam from '$lib/images/samAltman.png';
	import something from '$lib/images/something.png';
	import steve from '$lib/images/steveJobs.png';
</script>

<!-- 1st timeline -->
<div class="flex">
	<div class="flex w-[17rem] justify-end self-center pt-12 text-end">
		<span class="pr-2 text-gray-500">Dec 2023</span>
		<span class="relative left-[0.60rem] self-center">{@html circle}</span>
	</div>
	<div class=" flex border-l-[3px] border-dotted pl-12 pt-12">
		<div class=" mx-8 max-w-xs rounded-lg border border-gray-200 bg-white shadow-sm">
			<img class="rounded-t-lg" src={steve} alt="steve jobs" />
			<div class="p-5">
				<p class="mb-3 line-clamp-2 text-sm">
					No amount of technology can convert a bad story into a good story.
				</p>
			</div>
		</div>
		<div class="max-w-xs rounded-lg border border-gray-200 bg-white shadow-sm">
			<img class="rounded-t-lg" src={sam} alt="sam altman" />
			<div class="p-5">
				<p class="mb-3 line-clamp-2 text-sm">
					Most people don't have original ideas. Here is how Sam Altman pushes himself to have
					unpopular ideas.
				</p>
			</div>
		</div>
	</div>
</div>
<!-- 2 timeline -->
<div class="relative left-[0.55rem] flex w-[17rem] justify-end py-1">{@html arrowUp}</div>
<div class="flex">
	<div class="flex w-[17rem] justify-end self-center pt-2 text-end">
		<div class="">
			<div class="flex justify-end">{@html socialIcons}</div>
			<div class=" text-lg font-bold text-slate-700">Duggup</div>
			<div class="text-xs text-gray-500">San Francisco Bay Area</div>
			<div class="text-xs text-gray-500">Joined</div>
			<div class="text-xs text-gray-500">Nov 2023</div>
		</div>
		<span class="relative left-4 self-center">{@html circleBig}</span>
	</div>
	<div class=" self-center border-l-[3px] border-dotted pl-12 pt-12">
		<div class="mx-8 w-[42rem] rounded-lg border border-gray-200 bg-white shadow-sm">
			<div class="px-4 pt-4 text-2xl font-bold text-slate-700">Co-Founder and CEO</div>
			<div class="px-4 pb-4 text-xs text-gray-500">Full-time · Remote</div>
		</div>
	</div>
</div>
<!-- 3rd timeline -->
<div class="flex">
	<div class="flex w-[17rem] justify-end self-center pt-12 text-end">
		<span class="pr-2 text-gray-500">Dec 2023</span>
		<span class="relative left-[0.60rem] self-center">{@html circle}</span>
	</div>
	<div class=" flex border-l-[3px] border-dotted pl-12 pt-12">
		<div class=" mx-8 max-w-xs rounded-lg border border-gray-200 bg-white shadow-sm">
			<img class="rounded-t-lg" src={monitor} alt="steve jobs" />
			<div class="p-5">
				<p class="mb-3 line-clamp-2 text-sm">
					Startup Lesson I am reflecting. Don't build for the "average person".
				</p>
			</div>
		</div>
		<div class="max-w-xs rounded-lg border border-gray-200 bg-white shadow-sm">
			<img class="rounded-t-lg" src={something} alt="sam altman" />
			<div class="p-5">
				<p class="mb-3 line-clamp-2 text-sm">
					Your biggest regrets at 80 will be acts of omission.
				</p>
			</div>
		</div>
	</div>
</div>
<!-- 4th timeline -->
<div class="relative left-[0.55rem] flex w-[17rem] justify-end py-1">{@html arrowUp}</div>
<div class="flex">
	<div class="flex w-[17rem] justify-end self-center pt-2 text-end">
		<div class="">
			<div class="flex justify-end">
				<img class="rounded-t-lg" src={betterUp} alt="steve jobs" />
			</div>
			<div class=" text-lg font-bold text-slate-700">BetterUp</div>
			<div class="text-xs text-gray-500">San Francisco Bay Area</div>
			<div class="text-xs text-gray-500">Joined</div>
			<div class="text-xs text-gray-500">Sep 2022</div>
		</div>
		<span class="relative left-4 self-center">{@html circleBig}</span>
	</div>
	<div class=" self-center border-l-[3px] border-dotted pl-12 pt-12">
		<div class="mx-8 w-[42rem] rounded-lg border border-gray-200 bg-white shadow-sm">
			<div class="px-4 pt-4 text-2xl font-bold text-slate-700">VP Engineering</div>
			<div class="px-4 pb-4 text-xs text-gray-500">Full-time</div>
		</div>
	</div>
</div>
