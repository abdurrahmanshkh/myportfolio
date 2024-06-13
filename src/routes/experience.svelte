<script>
	import { Timeline, TimelineItem } from 'flowbite-svelte';
	import { AccordionItem } from 'flowbite-svelte';
	import { List, Li } from 'flowbite-svelte';

	const space="   ";
</script>

<div class="border-b-2 border-gray-400 dark:border-gray-700" id="experience">
<AccordionItem>
	<span slot="header" class="text-2xl font-semibold text-gray-900 dark:text-white">Work Experience</span>
	<Timeline>
		<TimelineItem title="Bioriidl – Biotechnology Lab" date="Feb 2024 – April 2024">
			<p class="mb-2 text-base font-bold text-gray-500 dark:text-gray-400">
                Research Fellow Intern
            </p>
			<List>
				<Li class="mb-1">
					Contributed to research on prion diseases, focusing on alpha-synuclein aggregation and its role
					in Parkinson's and Alzheimer's.
				</Li>
				<Li class="mb-1">
					Enhanced algorithms predicting protein structures, contributing to biotechnology advancements.
				</Li>
				<Li class="mb-0">
					Utilized Python for data analysis and algorithm enhancement.
				</Li>
			</List>			
		</TimelineItem>

		<TimelineItem title="AY International Pvt. Ltd." date="Dec 2023 – Jan 2024">
			<p class="mb-2 text-base font-bold text-gray-500 dark:text-gray-400">
                Web Developer Intern
            </p>
			<List>
				<Li class="mb-1">
					Led the development of “MapMyProject,” a dynamic project management system.
				</Li>
				<Li class="mb-1">
					Supervised the entire development lifecycle and a talented team, ensuring successful deployment.
				</Li>
				<Li class="mb-0">
					Utilized HTML, CSS, JavaScript for the frontend; Node.js and Svelte for the backend.
				</Li>
			</List>
		</TimelineItem>

		<TimelineItem title="IEEE Bombay – Al Hansat Solutions" date="Sep 2023 – Nov 2023">
			<p class="mb-2 text-base font-bold text-gray-500 dark:text-gray-400">
				Full Stack Developer Intern
			</p>
			<List>
				<Li class="mb-1">
					Co-led the development of 'DevStar,' a comprehensive developer toolkit website.
				</Li>
				<Li class="mb-1">
					Managed and assigned tasks to team members, fostering collaboration and ensuring timely project
					delivery.
				</Li>
				<Li class="mb-1">
					Conducted performance evaluations, demonstrating strong leadership and project management
					skills.
				</Li>
				<Li class="mb-0">
					Utilized HTML, CSS, and JavaScript for the frontend; Node.js and Svelte for the backend.
				</Li>
			</List>
		</TimelineItem>
	</Timeline>

</AccordionItem>
</div>