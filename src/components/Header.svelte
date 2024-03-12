<script>
	import container2 from '$lib/Icon/Container2.svg?raw';
	import ContainerIcon from '$lib/Icon/ContainerIcon.svg?raw';
	import HomeIcon from '$lib/Icon/HomeIcon.svg?raw';
	import LogoIcon from '$lib/Icon/LogoIcon.svg?raw';
	import StoryIcon from '$lib/Icon/StoryIcon.svg?raw';
	import * as Avatar from '$lib/components/ui/avatar';
	import * as DropdownMenu from '$lib/components/ui/dropdown-menu';
</script>

<div
	class="mx-auto mt-2 flex w-10/12 justify-between border-b-2 border-dotted pb-2 pt-2 align-middle"
>
	<div class="flex items-center text-xl font-bold">
		{@html LogoIcon}
		<p class="pl-1">duggup</p>
	</div>
	<div class="flex">
		<div class="flex items-center px-4 text-slate-500">
			{@html HomeIcon}
			<p class="pl-1">Home</p>
		</div>
		<div class="flex items-center px-4 text-slate-500">
			{@html StoryIcon}
			<p class="pl-1">Explore</p>
		</div>
		<div class="flex items-center px-4 text-slate-500">
			{@html ContainerIcon}
			<p class="pl-1">Learn</p>
		</div>
		<div
			class="b-1 ml-4 flex items-center rounded-sm border border-b-4 border-black px-4 text-slate-500"
		>
			{@html container2}
			<p class="pl-1">Post</p>
		</div>
		<div class=" class flex items-center px-2 pl-24 text-slate-700">
			<Avatar.Root class="h-10 w-10">
				<Avatar.Image src="https://github.com/shadcn.png" alt="@shadcn" height="73px" />
				<Avatar.Fallback>CN</Avatar.Fallback>
			</Avatar.Root>
			<DropdownMenu.Root>
				<DropdownMenu.Trigger class="pl-1 text-black">Omkar Garde</DropdownMenu.Trigger>
				<DropdownMenu.Content>
					<DropdownMenu.Group>
						<DropdownMenu.Label>My Account</DropdownMenu.Label>
						<DropdownMenu.Separator />
						<DropdownMenu.Item>Profile</DropdownMenu.Item>
						<DropdownMenu.Item>Billing</DropdownMenu.Item>
						<DropdownMenu.Item>Team</DropdownMenu.Item>
						<DropdownMenu.Item>Subscription</DropdownMenu.Item>
					</DropdownMenu.Group>
				</DropdownMenu.Content>
			</DropdownMenu.Root>
		</div>
	</div>
</div>
