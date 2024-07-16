<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, DarkMode } from 'flowbite-svelte';

	export let openSection="hhv";
	
	function openAbout(){
		openSection="about";
	}
	function openEduction(){
		openSection="education";
	}
	function openExperience(){
		openSection="experience";
	}
	function openProjects(){
		openSection="projects";
	}
	function openSkills(){
		openSection="skills";
	}
</script>

<header
	class="left-0 top-0 z-30 mx-auto w-full flex-none border-b-2 border-gray-300 bg-gray-200 dark:border-gray-700 dark:bg-gray-900"
>
	<div class="max-w-8xl mx-auto w-full px-0 py-3 lg:flex lg:justify-between lg:px-3">
		<Navbar class="bg-gray-200 dark:bg-gray-900">
			<NavBrand class="" href="/">
				<span class="self-center whitespace-nowrap text-3xl font-semibold">
					Abdur Rehman Shaikh
				</span>
			</NavBrand>
			<NavHamburger />
			<NavUl class="text-xl font-bold">
                <NavLi on:click={openAbout}><a href="#about">About</a></NavLi>
                <NavLi on:click={openEduction}><a href="#education">Education</a></NavLi>
                <NavLi on:click={openExperience}><a href="#experience">Experience</a></NavLi>
                <NavLi on:click={openProjects}><a href="#projects">Projects</a></NavLi>
                <NavLi on:click={openSkills}><a href="#skills">Skills</a></NavLi>
			</NavUl>
			<DarkMode />
		</Navbar>
	</div>
</header>
