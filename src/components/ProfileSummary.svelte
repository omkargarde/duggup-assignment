<script>
	import EllipsisIcon from '$lib/Icon/EllipsisIcon.svg?raw';
	import RedirectIcon from '$lib/Icon/RedirectIcon.svg?raw';
	import socialIcons from '$lib/Icon/socialIcons.svg?raw';
	import * as Avatar from '$lib/components/ui/avatar';
</script>

<div class="mx-auto mt-12 w-9/12">
	<div class="flex">
		<div class="grid justify-items-center">
			<Avatar.Root class="h-24 w-24">
				<Avatar.Image src="https://github.com/shadcn.png" alt="@shadcn" height="73px" />
				<Avatar.Fallback>CN</Avatar.Fallback>
			</Avatar.Root>
			<span class="pt-2 text-center text-2xl text-slate-700">Omkar Garde</span>
		</div>
		<div class="w-3/5 text-balance pl-8 pt-4 text-sm">
			<span class="">
				Co-Founder and CEO at Duggup - Social network for people in tech. Ex-Amazon Head of
				Engineering. I write hot-takes on building a business, shipping delightful products and
				accelerating product and career growth.
			</span>
			<span
				class="b-1 mt-8 flex max-w-24 items-center rounded-sm border border-b-4 border-black p-2 px-4 text-slate-500"
			>
				<p class="pl-1">Follow</p>
			</span>
		</div>
		<div class="pt-4">
			<span class="mb-4 flex flex-col items-end">
				{@html socialIcons}
				<p class="pt-1 text-center font-extrabold">Duggup</p>
				<p class="text-sm text-slate-500">Co-Founder and CEO</p>
			</span>
			<span class="mt-4">
				<a href="/" class="flex items-center justify-start"
					>My website <p class="pl-2">
						{@html RedirectIcon}
					</p>
					<p class="pl-2">{@html EllipsisIcon}</p>
				</a>
			</span>
		</div>
	</div>
</div>
