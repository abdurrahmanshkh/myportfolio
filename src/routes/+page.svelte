<script>
	import About from './about.svelte';
	import Education from './education.svelte';
	import Experience from './experience.svelte';
	import Projects from './projects.svelte';
	import Skills from './skills.svelte';
	import Contact from './contact.svelte';
	import { Accordion, Card } from 'flowbite-svelte';
</script>

<main class="container mx-auto py-10">
	
	<div class="gap-10 lg:grid lg:grid-cols-7 md:grid md:grid-cols-1">
		<div class="lg:col-span-5 md:col-span-1">
			<Card class="border-2 border-gray-300 dark:border-gray-700" size="" padding="xl">
				<Accordion flush>
					<About/>
					<Education />
					<Experience />
					<Projects />
					<Skills />
				</Accordion>
			</Card>
		</div>
		<div class="lg:col-span-2 md:col-span-1">
			<Contact />
		</div>
	</div>
</main>