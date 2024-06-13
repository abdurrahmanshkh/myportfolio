<script>
	import About from './about.svelte';
	import Education from './education.svelte';
	import Experience from './experience.svelte';
	import Projects from './projects.svelte';
	import Skills from './skills.svelte';
	import Contact from './contact.svelte';
	import { Accordion, Card } from 'flowbite-svelte';
</script>

<main class="container mx-auto pt-10">
	
	<div class="gap-10 lg:grid lg:grid-cols-4 md:grid md:grid-cols-1">
		<div class="lg:col-span-3 md:col-span-1 pb-10">
			<Card class="border-2 bg-white dark:bg-gray-800 border-gray-300 dark:border-gray-700" size="" padding="xl">
				<Accordion flush>
					<About/>
					<Education />
					<Experience />
					<Projects />
					<Skills />
				</Accordion>
			</Card>
		</div>
		<div class="lg:col-span-1 md:col-span-1 pb-10">
			<Card class="border-2 bg-white dark:bg-gray-800 border-gray-300 dark:border-gray-700" size="" padding="xl">
				<Contact />
			</Card>		
		</div>
	</div>
</main>