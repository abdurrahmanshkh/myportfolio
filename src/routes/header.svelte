<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, DarkMode, Avatar, Button, Card } from 'flowbite-svelte';
</script>

<header
	class="left-0 top-0 z-30 mx-auto w-full flex-none border-b-2 border-gray-300 bg-white dark:border-gray-700 dark:bg-gray-900"
>
	<div class="max-w-8xl mx-auto w-full px-0 py-3 lg:flex lg:justify-between lg:px-3">
		<Navbar>
			<NavBrand class="" href="/">
				<span class="self-center whitespace-nowrap text-3xl font-semibold dark:text-white">
					Abdur Rehman Shaikh
				</span>
			</NavBrand>
			<NavHamburger />
			<NavUl>
                <NavLi><a href="#about">About</a></NavLi>
                <NavLi><a href="#education">Education</a></NavLi>
                <NavLi><a href="#experience">Experience</a></NavLi>
                <NavLi><a href="#projects">Projects</a></NavLi>
                <NavLi><a href="#skills">Skills</a></NavLi>
                <NavLi><a href="#contact">Contact</a></NavLi>
			</NavUl>
			<DarkMode />
		</Navbar>
	</div>
</header>
