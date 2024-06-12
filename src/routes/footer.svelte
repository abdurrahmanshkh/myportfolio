<script>
	import { Footer, FooterCopyright, Navbar, A } from 'flowbite-svelte';
</script>

<footer
	class="mx-auto w-full flex-none border-t-2 border-gray-300 bg-white dark:border-gray-700 dark:bg-gray-900"
>
	<div class="max-w-8xl mx-auto w-full px-0 py-2 lg:flex lg:justify-between lg:px-3">
		<Navbar>
			<Footer rounded color="form" class="flex w-full items-center justify-center py-3 text-center">
				Created by
				<A class="ml-1 text-gray-700 dark:text-gray-300" href="/">
					Abdur Rehman Shaikh
				</A>
			</Footer>
		</Navbar>
	</div>
</footer>
